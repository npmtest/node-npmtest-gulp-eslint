# npmtest-gulp-eslint

#### test coverage for  [gulp-eslint (v3.0.1)](https://github.com/adametry/gulp-eslint#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-eslint.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-eslint) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-eslint.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-eslint)

#### A gulp plugin for processing files with ESLint

[![NPM](https://nodei.co/npm/gulp-eslint.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-eslint)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-eslint/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-eslint/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-eslint/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-eslint/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-eslint/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-eslint/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-eslint/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-eslint/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-eslint/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-eslint/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-eslint/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-eslint/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-eslint/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-eslint/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-eslint/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-eslint/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-eslint/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-eslint/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-eslint/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-eslint/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-eslint/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Adametry"
    },
    "bugs": {
        "url": "https://github.com/adametry/gulp-eslint/issues"
    },
    "contributors": [
        {
            "name": "Shinnosuke Watanabe",
            "url": "https://github.com/shinnn"
        }
    ],
    "dependencies": {
        "bufferstreams": "^1.1.1",
        "eslint": "^3.0.0",
        "gulp-util": "^3.0.6"
    },
    "description": "A gulp plugin for processing files with ESLint",
    "devDependencies": {
        "@shinnn/eslint-config-node": "^2.0.0",
        "babel-eslint": "^6.1.0",
        "from2-string": "^1.1.0",
        "gulp": "^3.9.0",
        "istanbul": "^0.4.4",
        "mocha": "^2.2.5",
        "should": "^9.0.2",
        "vinyl": "^1.0.0"
    },
    "directories": {
        "example": "example",
        "test": "test"
    },
    "dist": {
        "shasum": "04e57e3e18c6974267c12cf6855dc717d4a313bd",
        "tarball": "https://registry.npmjs.org/gulp-eslint/-/gulp-eslint-3.0.1.tgz"
    },
    "files": [
        "index.js",
        "util.js"
    ],
    "gitHead": "6059c2245c677a48add3ca4bbe5912f601732826",
    "homepage": "https://github.com/adametry/gulp-eslint#readme",
    "keywords": [
        "gulpplugin",
        "eslint",
        "gulp",
        "errors",
        "warnings",
        "check",
        "source",
        "code",
        "formatter",
        "js",
        "javascript",
        "task",
        "lint",
        "plugin"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "shinnn"
        },
        {
            "name": "adametry"
        }
    ],
    "name": "gulp-eslint",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/adametry/gulp-eslint.git"
    },
    "scripts": {
        "coverage": "istanbul cover _mocha",
        "gulp": "gulp",
        "gulp-example": "gulp --gulpfile=example/config.js",
        "pretest": "gulp test",
        "test": "mocha"
    },
    "version": "3.0.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
