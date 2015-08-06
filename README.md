docs
====

[![Chat at https://gitter.im/phaller/docs](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/phaller/docs)

scala-tutorial
--------------

Running this executable presentation requires:

- sbt 0.12.3 or higher
- a clone of https://github.com/phaller/replhtml (branch `topic/play-keydown`)

Assuming `docs` and `replhtml` are siblings within the same base directory,
the presentation can be run as follows (from within the base directory of
`replhtml`):

    sbt -Dkeydown.root=$PWD/../docs/scala-tutorial run

Then, point your browser to `http://localhost:8080/`.

Enjoy!
