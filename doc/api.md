# API

In addition to `clojure.core`, `clojure.set`, `clojure.edn`, `clojure.string`,
`clojure.walk`, nbb exposes the following namespaces:

## Nbb

### nbb.core

- `*file*`: dynamic var representing the currently executing file.
- `(load-file f)`: reads contents of file f and then handles it using `load-string`.
- `(load-string s)`: parses and evaluates `s`, returns result as promise.
- `(slurp f)`: slurps contents of file to string, synchronously.

## Reagent

See [Reagent docs](http://reagent-project.github.io/docs/master/) for docstrings.

### reagent.core

- `atom`, `as-element`

### reagent.dom

- `render`