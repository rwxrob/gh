# GitHub Utilities in Go 1.18+

🚧 *under construction* 🚧

[![Go Version](https://img.shields.io/github/go-mod/go-version/rwxrob/gh)](https://tip.golang.org/doc/go1.18)
[![GoDoc](https://godoc.org/github.com/rwxrob/gh?status.svg)](https://godoc.org/github.com/rwxrob/gh)
[![License](https://img.shields.io/badge/license-Apache2-brightgreen.svg)](LICENSE)
[![Go Report
Card](https://goreportcard.com/badge/github.com/rwxrob/gh)](https://goreportcard.com/report/github.com/rwxrob/gh)

## Design Considerations

* **Create high-level functions for stuff in the `gh` tool.** No need to
  re-invent anything here, just pulling out all that existing code into
  a usable Go 1.18 module.
