
Jiff
====

Jiff is a small library for transforming diffs into Clojure sequences
of data structures.

Usage
-----

```clojure
(:use jiff.core)

(def files (jiff-seq {:vcs :svn
                      :from "svn://server/tags/1.1"
                      :to "svn://server/tags/1.2"}))
```
