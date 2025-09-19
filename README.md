# test-2

gitGraph
  commit id: "feat"
  branch sandbox
  commit id: "sandbox work"
  checkout main
  branch dev
  commit id: "dev harden"
  checkout sandbox
  merge dev tag: "promote→sandbox"
  checkout dev
  branch acpt
  commit id: "rc"
  merge dev tag: "promote→acpt"
  checkout acpt
  branch prod
  merge acpt tag: "promote→prod"
