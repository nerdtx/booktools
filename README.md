# book build tools

helpers for building textbook pdfs

## requirements

- pandoc (apt install works)
- https://github.com/lierdakil/pandoc-crossref
  this is written in haskell, suggest grabbing a prebuilt release.
  put this executable at booktools/bin/pandoc-crossref
- on debian, install texlive-xetex

## directory layout

This directory needs to be setup at the same level as the book contents
directory.

```
books/
├─ booktools/
├─ book01/
├─ book02
```

## to build

```
cd prog1
../booktools/bin/mkpdf
```

