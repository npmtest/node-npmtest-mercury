# npmtest-mercury

#### basic test coverage for  [mercury (v14.1.0)](https://github.com/Raynos/mercury)  [![npm package](https://img.shields.io/npm/v/npmtest-mercury.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mercury) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mercury.svg)](https://travis-ci.org/npmtest/node-npmtest-mercury)

#### A truly modular frontend framework

[![NPM](https://nodei.co/npm/mercury.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mercury)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mercury/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mercury/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mercury/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mercury/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mercury/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-mercury/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-mercury/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mercury/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mercury/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-mercury/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-mercury/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mercury/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-mercury/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-mercury/build/test-report.html](https://npmtest.github.io/node-npmtest-mercury/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-mercury/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mercury/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-mercury/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mercury/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mercury/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mercury/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mercury/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mercury/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Raynos"
    },
    "bugs": {
        "url": "https://github.com/Raynos/mercury/issues"
    },
    "contributors": [
        {
            "name": "Raynos"
        },
        {
            "name": "Matt-Esch"
        },
        {
            "name": "neonstalwart"
        },
        {
            "name": "parshap"
        },
        {
            "name": "nrw"
        }
    ],
    "dependencies": {
        "dom-delegator": "^13.0.1",
        "geval": "^2.1.1",
        "http-hash-router": "~1.1.0",
        "main-loop": "^3.1.0",
        "observ": "^0.2.0",
        "observ-array": "^3.1.0",
        "observ-struct": "^5.0.1",
        "observ-varhash": "^1.0.2",
        "value-event": "^5.0.0",
        "vdom-thunk": "^3.0.0",
        "virtual-dom": "^2.1.1",
        "xtend": "^4.0.0"
    },
    "description": "A truly modular frontend framework",
    "devDependencies": {
        "backbone": "^1.1.2",
        "browserify": "^3.38.0",
        "callify": "^0.2.0",
        "coveralls": "^2.11.1",
        "cuid": "^1.2.1",
        "disc": "^1.3.0",
        "function-bind": "^0.1.0",
        "global": "^4.2.1",
        "hash-router": "^0.4.0",
        "immutable": "^3.6.2",
        "indexhtmlify": "^1.2.0",
        "istanbul": "^0.2.16",
        "javascript-editor": "^0.2.1",
        "jquery": "^2.1.4",
        "json-globals": "^0.2.1",
        "lint-trap": "^1.0.1",
        "marked": "^0.3.2",
        "mercury-jsxify": "^0.14.0",
        "min-document": "^2.9.0",
        "next-tick": "^0.2.2",
        "node-hook": "^0.1.0",
        "opn": "^1.0.1",
        "pre-commit": "0.0.7",
        "process": "^0.7.0",
        "raf": "^2.0.1",
        "rcss": "^0.1.5",
        "require-modify": "^0.1.0",
        "rimraf": "^2.2.8",
        "route-map": "^0.1.0",
        "run-browser": "^1.3.1",
        "run-parallel": "^1.0.0",
        "run-series": "^1.0.2",
        "st": "^0.4.1",
        "synthetic-dom-events": "git://github.com/Raynos/synthetic-dom-events.git",
        "tap-spec": "^0.2.0",
        "tape": "^2.13.2",
        "valid-email": "0.0.1",
        "vdom-to-html": "~1.2.5",
        "vdom-virtualize": "0.0.5",
        "vtree-select": "^1.0.1",
        "weakmap-shim": "^1.1.0",
        "zuul": "^1.9.0"
    },
    "directories": {},
    "dist": {
        "shasum": "9789a5b59ac2faa98fe4e9a7d9f7207ff3814acb",
        "tarball": "https://registry.npmjs.org/mercury/-/mercury-14.1.0.tgz"
    },
    "gitHead": "15512903702a4b496a98c3526595ca91acac68db",
    "homepage": "https://github.com/Raynos/mercury",
    "keywords": [
        "framework",
        "frontend",
        "virtual",
        "react",
        "modular",
        "web"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "http://github.com/Raynos/mercury/raw/master/LICENSE"
        }
    ],
    "main": "index.js",
    "maintainers": [
        {
            "name": "raynos"
        },
        {
            "name": "mattesch"
        }
    ],
    "name": "mercury",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/Raynos/mercury.git"
    },
    "scripts": {
        "browser": "run-browser test/index.js",
        "build": "node bin/build.js",
        "cover": "istanbul cover --report html --print detail ./test/index.js",
        "disc": "browserify index.js --full-paths | discify > disc.html && opn disc.html",
        "dist": "node bin/dist.js",
        "dist-publish": "npm run dist && git add dist/mercury.js && git commit -m 'dist' && npm publish",
        "examples": "node bin/example-server.js",
        "lint": "lint-trap",
        "modules-docs": "node bin/modules-docs.js",
        "phantom": "run-browser test/index.js -b | tap-spec",
        "test": "npm run lint && node test/index.js | tap-spec",
        "travis-test": "npm run phantom && npm run cover && istanbul report lcov && ((cat coverage/lcov.info | coveralls) || exit 0) && zuul -- test/index.js",
        "view-cover": "istanbul report html && opn coverage/index.html"
    },
    "version": "14.1.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
