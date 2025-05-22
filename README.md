# Markdown textual stages diffing

This repository holds some experimental diff viewers (implemented as simple HTML pages). They make use of common diff algorithms and are intended to facilitate insights into textual genesis over multiple stages.

## v20250522

*This is not optimised for performande and loading/processing of the files will require some patience and might trigger a browser warning.*

* Unified diff (base text with variants) in a single panel; for comparison of two files:  [/md-stages-diffing/v20250522/single-panel-unified.html](`single-panel-unified.html`)
* Unified diff (base texts with variants) in multiple panels; for comparison of several files, two at a time: [/md-stages-diffing/v20250522/multi-panel-unified.html](multi-panel-unified.html)

## Roadmap

* Restrict rendering to visible sections (plus some)
* Add more diffing algorithms and some diffing options
* Improved section and paragraph alignment
* (Virtual) TOC functionality
