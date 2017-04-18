# npmdoc-docopt

#### api documentation for  [docopt (v0.6.2)](https://github.com/scarnie/docopt.coffee)  [![npm package](https://img.shields.io/npm/v/npmdoc-docopt.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-docopt) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-docopt.svg)](https://travis-ci.org/npmdoc/node-npmdoc-docopt)

#### a command line option parser that will make you smile

[![NPM](https://nodei.co/npm/docopt.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/docopt)

- [https://npmdoc.github.io/node-npmdoc-docopt/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-docopt/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-docopt/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-docopt/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-docopt/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-docopt/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Vladimir Keleshev"
    },
    "bugs": {
        "url": "https://github.com/scarnie/docopt.coffee/issues"
    },
    "contributors": [
        {
            "name": "Andrew Kassen"
        },
        {
            "name": "Vladimir Keleshev"
        },
        {
            "name": "Stuart Carnie"
        },
        {
            "name": "Matthias Rolke"
        }
    ],
    "dependencies": {},
    "description": "a command line option parser that will make you smile",
    "devDependencies": {
        "chai": "^2.2.0",
        "coffee-script": "^1.9.1",
        "coffeelint": "^1.9.2",
        "mocha": "^2.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "b28e9e2220da5ec49f7ea5bb24a47787405eeb11",
        "tarball": "https://registry.npmjs.org/docopt/-/docopt-0.6.2.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "198e5c72baff8a6e10832c677eba67dc29068792",
    "homepage": "https://github.com/scarnie/docopt.coffee",
    "keywords": [
        "command",
        "options",
        "argument",
        "args",
        "cli",
        "commandline"
    ],
    "licenses": "MIT",
    "main": "docopt.js",
    "maintainers": [
        {
            "name": "stuartcarnie"
        }
    ],
    "name": "docopt",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/scarnie/docopt.coffee.git"
    },
    "scripts": {
        "lint": "coffeelint docopt.coffee test/*.coffee",
        "prepublish": "coffee -c docopt.coffee",
        "test": "mocha --compilers coffee:coffee-script/register"
    },
    "version": "0.6.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
