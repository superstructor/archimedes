# Archimedes, a Clojure Library For Tinkerpop Blueprints

Archimedes is a Clojure library for working with graphs that conform to the [Tinkerpop Blueprints](http://tinkerpop.com) interface.

## Project Goals

 * Provide an API that makes [Tinkerpop Blueprints](http://tinkerpop.com) really easy to use from Clojure
 * Be reasonably feature complete
 * Don't introduce any significant amount of performance overhead


## Community

Discussion about Archimedes takes place on the [Titanium mailing list](https://groups.google.com/forum/#!forum/clojure-titanium)
Feel free to join in and ask any questions you may have.

## Artifacts

Archimedes artifacts are
[released to Clojars](https://clojars.org/clojurewerkz/archimedes). If
you are using Maven, add the following repository definition to your
`pom.xml`:

``` xml
<repository>
  <id>clojars.org</id>
  <url>http://clojars.org/repo</url>
</repository>
```

### The Most Recent Release

With Leiningen:

    [clojurewerkz/archimedes "2.5.0.0"]


With Maven:

    <dependency>
      <groupId>clojurewerkz</groupId>
      <artifactId>archimedes</artifactId>
      <version>2.5.0.0</version>
    </dependency>

## Documentation & Examples

Archimedes documentation guides are not ready yet.

### Code Examples

Our [test suite](test/archimedes) has many code examples.

## Supported Clojure Versions

Archimedes is built from the ground up for Clojure 1.4 and up. The most recent stable release
is always recommended.


## Continuous Integration

[![Build Status](https://travis-ci.org/clojurewerkz/archimedes.svg?branch=master)](https://travis-ci.org/clojurewerkz/archimedes)

## Development

Archimedes uses
[Leiningen 2](https://github.com/technomancy/leiningen/blob/master/doc/TUTORIAL.md).
Make sure you have it installed and then run tests against supported
Clojure versions using

    lein all test

Then create a branch and make your changes on it. Once you are done
with your changes and all tests pass, submit a pull request on Github.



## License

Copyright (C) 2013-2016 Zack Maril and the ClojureWerkz Team

Licensed under the [Eclipse Public License](http://www.eclipse.org/legal/epl-v10.html) (the same as Clojure).
