# colortest

A Leiningen plugin to work with [acolfut](https://github.com/zjhmale/acolfut).

[![Clojars Project](http://clojars.org/lein-colortest/latest-version.svg)](http://clojars.org/lein-colortest)

## Usage

* Use this for user-level plugins:

Put `[colortest "0.1.0"]` in `~/.lein/profiles.clj`.

```clojure
{:user {:plugins [[colortest "0.1.0"]]}}
```

* Use this for project-level plugins:

Put `[colortest "0.1.0"]` into the `:plugins` vector of your `project.clj`.

* And just run the cmd to use it

```
$ lein colortest
```

## License

Copyright © 2015 jihui

Distributed under the Eclipse Public License, the same as Clojure.
