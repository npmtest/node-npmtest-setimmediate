# npmtest-setimmediate

#### basic test coverage for  [setimmediate (v1.0.5)](https://github.com/yuzujs/setImmediate#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-setimmediate.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-setimmediate) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-setimmediate.svg)](https://travis-ci.org/npmtest/node-npmtest-setimmediate)

#### A shim for the setImmediate efficient script yielding API

[![NPM](https://nodei.co/npm/setimmediate.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/setimmediate)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-setimmediate/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-setimmediate/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-setimmediate/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-setimmediate/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-setimmediate/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-setimmediate/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-setimmediate/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-setimmediate/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-setimmediate/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-setimmediate/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-setimmediate/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-setimmediate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-setimmediate/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-setimmediate/build/test-report.html](https://npmtest.github.io/node-npmtest-setimmediate/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-setimmediate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-setimmediate/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-setimmediate/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-setimmediate/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-setimmediate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-setimmediate/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-setimmediate/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-setimmediate/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "YuzuJS"
    },
    "bugs": {
        "url": "https://github.com/yuzujs/setImmediate/issues"
    },
    "contributors": [
        {
            "name": "Domenic Denicola",
            "url": "https://domenic.me"
        },
        {
            "name": "Donavon West",
            "url": "http://donavon.com"
        },
        {
            "name": "Yaffle"
        }
    ],
    "dependencies": {},
    "description": "A shim for the setImmediate efficient script yielding API",
    "devDependencies": {
        "http-server": "~0.6.1",
        "jshint": "^2.5.0",
        "mocha": "~1.18.2",
        "opener": "^1.3",
        "zuul": "^1.6.4"
    },
    "directories": {},
    "dist": {
        "shasum": "290cbb232e306942d7d7ea9b83732ab7856f8285",
        "tarball": "https://registry.npmjs.org/setimmediate/-/setimmediate-1.0.5.tgz"
    },
    "files": [
        "setImmediate.js"
    ],
    "gitHead": "f1ccbfdf09cb93aadf77c4aa749ea554503b9234",
    "homepage": "https://github.com/yuzujs/setImmediate#readme",
    "license": "MIT",
    "main": "setImmediate.js",
    "maintainers": [
        {
            "name": "domenic"
        }
    ],
    "name": "setimmediate",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/yuzujs/setImmediate.git"
    },
    "scripts": {
        "lint": "jshint setImmediate.js",
        "test": "mocha test/tests.js",
        "test-browser": "opener http://localhost:9008/__zuul && zuul test/tests.js --ui mocha-bdd --local 9008",
        "test-browser-only": "opener http://localhost:9007/test/browserOnly/index.html && http-server . -p 9007"
    },
    "version": "1.0.5",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
