# npmtest-api-benchmark

#### basic test coverage for  [api-benchmark (v0.4.2)](http://www.api-benchmark.com/)  [![npm package](https://img.shields.io/npm/v/npmtest-api-benchmark.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-api-benchmark) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-api-benchmark.svg)](https://travis-ci.org/npmtest/node-npmtest-api-benchmark)

#### A simple nodejs tool to measure and compare performances of api services

[![NPM](https://nodei.co/npm/api-benchmark.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/api-benchmark)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-api-benchmark/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-api-benchmark/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-api-benchmark/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-api-benchmark/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-api-benchmark/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-api-benchmark/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-api-benchmark/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-api-benchmark/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-api-benchmark/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-api-benchmark/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-api-benchmark/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-api-benchmark/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-api-benchmark/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-api-benchmark/build/test-report.html](https://npmtest.github.io/node-npmtest-api-benchmark/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-api-benchmark/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-api-benchmark/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-api-benchmark/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-api-benchmark/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-api-benchmark/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-api-benchmark/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-api-benchmark/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-api-benchmark/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Matteo Figus"
    },
    "bugs": {
        "url": "https://github.com/matteofigus/api-benchmark/issues"
    },
    "contributors": [
        {
            "name": "Michael Sanford"
        },
        {
            "name": "Derek Myers"
        }
    ],
    "dependencies": {
        "give-me": "0.1.0",
        "superagent": "2.0.0",
        "underscore": "1.8.3"
    },
    "description": "A simple nodejs tool to measure and compare performances of api services",
    "devDependencies": {
        "http-test-servers": "1.0.0",
        "injectr": "^0.5.1",
        "jshint": "^2.9.2",
        "mocha": "2.5.3",
        "should": "8.4.0"
    },
    "directories": {},
    "dist": {
        "shasum": "15598bb5e8d534372a7dccdd8ac4a525b4518076",
        "tarball": "https://registry.npmjs.org/api-benchmark/-/api-benchmark-0.4.2.tgz"
    },
    "engines": {
        "node": ">=0.8.x",
        "npm": ">=1.2.x"
    },
    "gitHead": "fbbc05308bad75a27c06f4c8e8407a963b828a00",
    "homepage": "http://www.api-benchmark.com/",
    "keywords": [
        "benchmark",
        "api",
        "performance",
        "test",
        "load balancer",
        "deployment",
        "continuous delivery"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "matteofigus"
        }
    ],
    "name": "api-benchmark",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/matteofigus/api-benchmark.git"
    },
    "scripts": {
        "pretest": "jshint lib test templates index.js",
        "test": "node test/index"
    },
    "version": "0.4.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
