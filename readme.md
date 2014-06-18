# tmpin [![Build Status](https://travis-ci.org/sindresorhus/tmpin.svg?branch=master)](https://travis-ci.org/sindresorhus/tmpin)

> Adds stdin support to any CLI app that accepts file input

It pipes stdin to a tempfile and spawns the chosen app with the tempfile path as the first argument.


## Install

```sh
$ npm install --global tmpin
```


## Usage

```sh
$ tmpin --help

Usage
  $ echo <string> | tmpin <app> [<args>]

Example
  $ git diff | tmpin atom

# Note that the first arg to <app> will be set to the tempfile
```


## License

MIT © [Sindre Sorhus](http://sindresorhus.com)
