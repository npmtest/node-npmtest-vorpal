# npmtest-vorpal

#### basic test coverage for  [vorpal (v1.12.0)](https://github.com/dthree/vorpal#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-vorpal.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-vorpal) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-vorpal.svg)](https://travis-ci.org/npmtest/node-npmtest-vorpal)

#### Node's first framework for building immersive CLI apps.

[![NPM](https://nodei.co/npm/vorpal.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/vorpal)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-vorpal/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-vorpal/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-vorpal/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-vorpal/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-vorpal/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-vorpal/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-vorpal/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-vorpal/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-vorpal/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-vorpal/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-vorpal/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-vorpal/build/test-report.html](https://npmtest.github.io/node-npmtest-vorpal/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-vorpal/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-vorpal/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-vorpal/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-vorpal/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-vorpal/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-vorpal/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-vorpal/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-vorpal/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "dthree"
    },
    "bugs": {
        "url": "https://github.com/dthree/vorpal/issues"
    },
    "dependencies": {
        "babel-polyfill": "^6.3.14",
        "chalk": "^1.1.0",
        "in-publish": "^2.0.0",
        "inquirer": "0.11.0",
        "lodash": "^4.5.1",
        "log-update": "^1.0.2",
        "minimist": "^1.2.0",
        "node-localstorage": "^0.6.0",
        "strip-ansi": "^3.0.0",
        "wrap-ansi": "^2.0.0"
    },
    "description": "Node's first framework for building immersive CLI apps.",
    "devDependencies": {
        "babel": "^6.3.26",
        "babel-core": "^6.4.5",
        "babel-preset-es2015": "^6.3.13",
        "bluebird": "^3.1.1",
        "gulp": "^3.9.0",
        "gulp-babel": "^6.1.2",
        "gulp-changed": "^1.3.0",
        "gulp-eslint": "^1.1.1",
        "gulp-xo": "^0.7.0",
        "load-plugins": "^2.1.0",
        "mocha": "^2.2.5",
        "moment": "^2.10.3",
        "request": "^2.58.0",
        "should": "^6.0.3",
        "vorpal-less": "0.0.4",
        "vorpal-repl": "^1.1.8",
        "xo": "^0.9.0"
    },
    "directories": {},
    "dist": {
        "shasum": "4be7b2a4e48f8fcfc9cf3648c419d311c522159d",
        "tarball": "https://registry.npmjs.org/vorpal/-/vorpal-1.12.0.tgz"
    },
    "engines": {
        "iojs": ">= 1.0.0",
        "node": ">= 0.10.0"
    },
    "files": [
        "dist"
    ],
    "gitHead": "d3211623a172a694559063111dd9f7ee430c5be3",
    "homepage": "https://github.com/dthree/vorpal#readme",
    "keywords": [
        "api",
        "cli",
        "repl",
        "shell",
        "immersive",
        "framework",
        "app",
        "application",
        "command",
        "commander",
        "automated",
        "prompt",
        "inquirer"
    ],
    "license": "MIT",
    "main": "./dist/vorpal.js",
    "maintainers": [
        {
            "name": "dthree"
        },
        {
            "name": "scotthovestadt"
        }
    ],
    "name": "vorpal",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/dthree/vorpal.git"
    },
    "scripts": {
        "prepublish": "in-publish && gulp build || not-in-publish",
        "test": "gulp build; mocha;"
    },
    "version": "1.12.0",
    "xo": {
        "space": true,
        "rules": {
            "no-eval": 0,
            "no-unused-expressions": 0,
            "max-nested-callbacks": 0,
            "no-proto": 0,
            "wrap-iife": 0,
            "global-require": 0,
            "no-negated-condition": 0,
            "no-loop-func": 0,
            "no-implicit-coercion": 0,
            "no-use-extend-native/no-use-extend-native": 0,
            "no-undef": 0
        }
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
