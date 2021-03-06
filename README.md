# npmdoc-stylint

#### api documentation for  [stylint (v1.5.9)](https://github.com/SimenB/stylint#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-stylint.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-stylint) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-stylint.svg)](https://travis-ci.org/npmdoc/node-npmdoc-stylint)

#### A linter for stylus

[![NPM](https://nodei.co/npm/stylint.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/stylint)

- [https://npmdoc.github.io/node-npmdoc-stylint/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-stylint/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-stylint/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-stylint/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-stylint/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-stylint/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ross Patton"
    },
    "bin": {
        "stylint": "./bin/stylint"
    },
    "bugs": {
        "url": "https://github.com/SimenB/stylint/issues"
    },
    "dependencies": {
        "async": "1.5.2",
        "chalk": "1.1.3",
        "chokidar": "1.5.2",
        "columnify": "1.5.4",
        "glob": "7.0.4",
        "lodash.defaults": "4.0.1",
        "path-is-absolute": "1.0.0",
        "stampit": "1.2.0",
        "strip-json-comments": "2.0.1",
        "user-home": "2.0.0",
        "yargs": "4.7.1"
    },
    "description": "A linter for stylus",
    "devDependencies": {
        "chai": "3.5.0",
        "eslint": "2.13.1",
        "istanbul": "0.4.3",
        "jsdoc": "3.4.2",
        "mocha": "2.5.3",
        "sinon": "1.17.4",
        "touch": "1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "29f4dc129fa1ca22150cd867223cee2bed5ff6a2",
        "tarball": "https://registry.npmjs.org/stylint/-/stylint-1.5.9.tgz"
    },
    "files": [
        "bin/",
        "index.js",
        "src/"
    ],
    "gitHead": "96b7db561090d355c31a8b2444cc7f00880f222e",
    "homepage": "https://github.com/SimenB/stylint#readme",
    "keywords": [
        "cli",
        "css",
        "hinter",
        "lint",
        "linter",
        "styl",
        "style",
        "stylint",
        "stylus",
        "stylus-hint",
        "stylus-lint"
    ],
    "license": "GPL-3.0",
    "main": "index.js",
    "maintainers": [
        {
            "name": "rpatton"
        },
        {
            "name": "simenb"
        },
        {
            "name": "wojciechczerniak"
        }
    ],
    "name": "stylint",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/SimenB/stylint.git"
    },
    "scripts": {
        "cover": "istanbul cover node_modules/.bin/_mocha -- -u exports -R spec test/test.js",
        "docs": "jsdoc src/ --recurse --destination docs/",
        "lint": "eslint .",
        "precover": "npm run lint",
        "pretest": "npm run lint",
        "start": "node --harmony index.js",
        "test": "mocha"
    },
    "version": "1.5.9"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
