# test coverage for  [noble (v1.8.1)](https://github.com/sandeepmistry/noble)  [![npm package](https://img.shields.io/npm/v/npmtest-noble.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-noble) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-noble.svg)](https://travis-ci.org/npmtest/node-npmtest-noble)
#### A Node.js BLE (Bluetooth Low Energy) central library.

[![NPM](https://nodei.co/npm/noble.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/noble)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-noble/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-noble/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-noble/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-noble/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-noble/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-noble/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-noble/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-noble/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-noble/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-noble/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-noble/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-noble/build/test-report.html](https://npmtest.github.io/node-npmtest-noble/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-noble/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-noble/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-noble/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-noble/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-noble/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-noble/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-noble/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-noble/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sandeep Mistry"
    },
    "browser": {
        "./lib/resolve-bindings.js": "./lib/resolve-bindings-web.js"
    },
    "bugs": {
        "url": "https://github.com/sandeepmistry/noble/issues"
    },
    "dependencies": {
        "bluetooth-hci-socket": "^0.5.1",
        "bplist-parser": "0.0.6",
        "debug": "~2.2.0",
        "xpc-connection": "~0.1.4"
    },
    "description": "A Node.js BLE (Bluetooth Low Energy) central library.",
    "devDependencies": {
        "async": "~0.2.9",
        "jshint": "latest",
        "mocha": "~1.8.2",
        "should": "~1.2.2",
        "sinon": "~1.6.0",
        "ws": "~0.4.31"
    },
    "directories": {},
    "dist": {
        "shasum": "efe880812b7251afaaadb4fe83753c1302a673f6",
        "tarball": "https://registry.npmjs.org/noble/-/noble-1.8.1.tgz"
    },
    "engines": {
        "node": ">=0.8"
    },
    "gitHead": "320e6198f22bcad2e193a3eda6efb0070e51c31f",
    "homepage": "https://github.com/sandeepmistry/noble",
    "keywords": [
        "bluetooth",
        "BLE",
        "bluetooth low energy",
        "bluetooth smart",
        "central"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "sandeepmistry"
        }
    ],
    "name": "noble",
    "optionalDependencies": {
        "bluetooth-hci-socket": "^0.5.1",
        "bplist-parser": "0.0.6",
        "xpc-connection": "~0.1.4"
    },
    "os": [
        "darwin",
        "linux",
        "freebsd",
        "win32"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/sandeepmistry/noble.git"
    },
    "scripts": {
        "pretest": "jshint *.js lib/. test/.",
        "test": "mocha -R spec test/*.js"
    },
    "version": "1.8.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
