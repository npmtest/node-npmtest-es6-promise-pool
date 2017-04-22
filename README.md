# npmtest-es6-promise-pool

#### basic test coverage for  [es6-promise-pool (v2.4.4)](https://github.com/timdp/es6-promise-pool#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-es6-promise-pool.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-es6-promise-pool) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-es6-promise-pool.svg)](https://travis-ci.org/npmtest/node-npmtest-es6-promise-pool)

#### Runs Promises in a pool that limits their concurrency.

[![NPM](https://nodei.co/npm/es6-promise-pool.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/es6-promise-pool)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-es6-promise-pool/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-es6-promise-pool/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-es6-promise-pool/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-es6-promise-pool/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-es6-promise-pool/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-es6-promise-pool/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-es6-promise-pool/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-es6-promise-pool/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-es6-promise-pool/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-es6-promise-pool/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-es6-promise-pool/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-es6-promise-pool/build/test-report.html](https://npmtest.github.io/node-npmtest-es6-promise-pool/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-es6-promise-pool/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-es6-promise-pool/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-es6-promise-pool/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-es6-promise-pool/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-es6-promise-pool/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-es6-promise-pool/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-es6-promise-pool/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-es6-promise-pool/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tim De Pauw",
        "url": "https://tmdpw.eu"
    },
    "bugs": {
        "url": "https://github.com/timdp/es6-promise-pool/issues"
    },
    "dependencies": {},
    "description": "Runs Promises in a pool that limits their concurrency.",
    "devDependencies": {
        "bluebird": "^3.4.0",
        "chai": "^3.2.0",
        "chai-as-promised": "^5.1.0",
        "console-stamp": "^0.2.2",
        "coveralls": "^2.11.4",
        "es6-promise": "^3.0.2",
        "istanbul": "^0.4.3",
        "mocha": "^2.2.5",
        "mocha-lcov-reporter": "^1.2.0",
        "mocha-phantomjs": "^4.0.2",
        "phantomjs-prebuilt": "^2.1.7",
        "standard": "^7.1.2"
    },
    "directories": {},
    "dist": {
        "shasum": "2e3c4859d52add51852a14d13584a047f03f3dba",
        "tarball": "https://registry.npmjs.org/es6-promise-pool/-/es6-promise-pool-2.4.4.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "es6-promise-pool.js"
    ],
    "gitHead": "d75e4abce154aeb69c193dd1d96653aeb4b95c98",
    "homepage": "https://github.com/timdp/es6-promise-pool#readme",
    "keywords": [
        "promise",
        "promises",
        "promises-a",
        "promises-aplus",
        "future",
        "futures",
        "deferred",
        "deferreds",
        "generator",
        "generators",
        "async",
        "await",
        "flow control",
        "pool",
        "queue",
        "throttle",
        "es6",
        "browser",
        "node"
    ],
    "license": "MIT",
    "main": "es6-promise-pool.js",
    "maintainers": [
        {
            "name": "timdp"
        }
    ],
    "name": "es6-promise-pool",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/timdp/es6-promise-pool.git"
    },
    "scripts": {
        "coverage": "node --harmony node_modules/istanbul/lib/cli.js cover node_modules/mocha/bin/_mocha -- -R spec && node node_modules/istanbul/lib/cli.js check-coverage",
        "coveralls": "node node_modules/coveralls/bin/coveralls.js <coverage/lcov.info",
        "standard": "node node_modules/standard/bin/cmd.js",
        "test": "npm run standard && npm run coverage"
    },
    "standard": {
        "ignore": [
            "bower_components/**"
        ],
        "globals": [
            "define",
            "describe",
            "it",
            "before",
            "after",
            "beforeEach",
            "afterEach"
        ]
    },
    "typings": "es6-promise-pool.d.ts",
    "version": "2.4.4",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
