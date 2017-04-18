# npmtest-strong-supervisor

#### test coverage for  [strong-supervisor (v6.1.1)](https://github.com/strongloop/strong-supervisor)  [![npm package](https://img.shields.io/npm/v/npmtest-strong-supervisor.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-strong-supervisor) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-strong-supervisor.svg)](https://travis-ci.org/npmtest/node-npmtest-strong-supervisor)

#### supervisor and monitor for node.js applications

[![NPM](https://nodei.co/npm/strong-supervisor.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/strong-supervisor)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-strong-supervisor/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-strong-supervisor/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-strong-supervisor/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-strong-supervisor/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-strong-supervisor/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-strong-supervisor/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-strong-supervisor/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-strong-supervisor/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-strong-supervisor/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-strong-supervisor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-strong-supervisor/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-strong-supervisor/build/test-report.html](https://npmtest.github.io/node-npmtest-strong-supervisor/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-strong-supervisor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-strong-supervisor/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-strong-supervisor/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-strong-supervisor/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-strong-supervisor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-strong-supervisor/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-strong-supervisor/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-strong-supervisor/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sam Roberts"
    },
    "bin": {
        "sl-run": "./bin/sl-run.js",
        "sl-runctl": "./bin/sl-runctl.js",
        "slr": "./bin/sl-run.js",
        "slrc": "./bin/sl-runctl.js"
    },
    "bugs": {
        "url": "https://github.com/strongloop/strong-supervisor/issues"
    },
    "dependencies": {
        "appmetrics": "^1.1.0",
        "appmetrics-dash": "^3.0.0",
        "async": "^2.0.0",
        "debug": "^2.0.0",
        "dotenv": "^1.0.0",
        "heapdump": "^0.3.5",
        "lodash": "^4.14.1",
        "modern-syslog": "^1.x",
        "posix-getopt": "^1.1.0",
        "strong-cluster-control": "^2.0.0",
        "strong-control-channel": "^2.0.0",
        "strong-log-transformer": "^1.0.0",
        "strong-npm-ls": "^1.0.0",
        "strong-statsd": "^2.0.0",
        "strong-trace": "^1.2.0",
        "strong-url-defaults": "^1.2.0"
    },
    "description": "supervisor and monitor for node.js applications",
    "devDependencies": {
        "byline": "^5.x",
        "eslint": "^2.x",
        "eslint-config-strongloop": "^2.x",
        "express": "^4.0.0",
        "mocha": "^2.2.4",
        "optimist": "~0.6.0",
        "semver": "^5.3.0",
        "strong-express-metrics": "^2.0.0",
        "tap": "^6.1.1"
    },
    "directories": {},
    "dist": {
        "shasum": "7a64583b182e5e91ff03d9bc91618fbfa07fd4af",
        "tarball": "https://registry.npmjs.org/strong-supervisor/-/strong-supervisor-6.1.1.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "gitHead": "c8202dcf9903613d234c6cda1ce8f87fa72e5852",
    "homepage": "https://github.com/strongloop/strong-supervisor",
    "keywords": [
        "agent",
        "cluster",
        "forever",
        "master",
        "pm",
        "process",
        "runner",
        "supervisor",
        "strongloop",
        "strongops",
        "supervisor"
    ],
    "license": "Artistic-2.0",
    "main": "index.js",
    "maintainers": [
        {
            "name": "0candy"
        },
        {
            "name": "amir-61"
        },
        {
            "name": "b-admike"
        },
        {
            "name": "bajtos"
        },
        {
            "name": "chandadharap"
        },
        {
            "name": "davidcheung"
        },
        {
            "name": "hacksparrow"
        },
        {
            "name": "ibmcloud-admin"
        },
        {
            "name": "jannyhou2016"
        },
        {
            "name": "kjdelisle"
        },
        {
            "name": "kraman"
        },
        {
            "name": "loay"
        },
        {
            "name": "octet"
        },
        {
            "name": "qpresley"
        },
        {
            "name": "rfeng"
        },
        {
            "name": "ritch"
        },
        {
            "name": "rmg"
        },
        {
            "name": "setogit"
        },
        {
            "name": "strongloop"
        },
        {
            "name": "superkhau"
        },
        {
            "name": "thegman"
        },
        {
            "name": "tonyf-ibm"
        }
    ],
    "name": "strong-supervisor",
    "optionalDependencies": {
        "heapdump": "^0.3.5",
        "modern-syslog": "^1.x"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/strongloop/strong-supervisor.git"
    },
    "scripts": {
        "pretest": "eslint ./",
        "test": "tap --timeout 300 test/test-*.js"
    },
    "version": "6.1.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
