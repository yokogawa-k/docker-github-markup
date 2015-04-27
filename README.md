Docker Image for [github/markup](https://github.com/github/markup/)
====

How to use.
----

```console
$ docker run -v ${PWD}:/work/ yokogawa/github-markup ./foo.md >./foo.html
```

If you use `./run` script.

```console
$ ./run ./foo.md >foo.html
```

### use bash

```console
$ ./run bash
```

TODO
----

- Support `.rst`
  - need python.


