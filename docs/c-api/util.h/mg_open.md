---
title: "mg_open()"
decl_name: "mg_open"
symbol_kind: "func"
signature: |
  int mg_open(const char *path, int flag, int mode);
---

Open the given file and return a file stream.

`path` should be UTF8 encoded.

Return value is the same as for the `open()` syscall. 

