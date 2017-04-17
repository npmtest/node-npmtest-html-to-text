# test coverage for  [html-to-text (v3.2.0)](https://github.com/werk85/node-html-to-text)  [![npm package](https://img.shields.io/npm/v/npmtest-html-to-text.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-html-to-text) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-html-to-text.svg)](https://travis-ci.org/npmtest/node-npmtest-html-to-text)
#### Advanced html to plain text converter

[![NPM](https://nodei.co/npm/html-to-text.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/html-to-text)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-html-to-text/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-html-to-text/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-html-to-text/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-html-to-text/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-html-to-text/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-html-to-text/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-html-to-text/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-html-to-text/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-html-to-text/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-html-to-text/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-html-to-text/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-html-to-text/build/test-report.html](https://npmtest.github.io/node-npmtest-html-to-text/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-html-to-text/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-html-to-text/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-html-to-text/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-html-to-text/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-html-to-text/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-html-to-text/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-html-to-text/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-html-to-text/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Malte Legenhausen"
    },
    "bin": {
        "html-to-text": "./bin/cli.js"
    },
    "bugs": {
        "url": "https://github.com/werk85/node-html-to-text/issues"
    },
    "dependencies": {
        "he": "^1.0.0",
        "htmlparser2": "^3.9.2",
        "optimist": "^0.6.1",
        "underscore": "^1.8.3",
        "underscore.string": "^3.2.3"
    },
    "description": "Advanced html to plain text converter",
    "devDependencies": {
        "chai": "^3.5.0",
        "eslint": "^3.14.1",
        "istanbul": "^0.4.5",
        "mocha": "^3.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "0dfa5d27ff816b07281c79eaf60d408744ac6d89",
        "tarball": "https://registry.npmjs.org/html-to-text/-/html-to-text-3.2.0.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "gitHead": "8782c3d4d6d2f41b276ce5562cb3d5f39fdd0079",
    "homepage": "https://github.com/werk85/node-html-to-text",
    "keywords": [
        "html",
        "node",
        "text",
        "mail",
        "plain",
        "converter"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "mlegenhausen"
        }
    ],
    "name": "html-to-text",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/werk85/node-html-to-text.git"
    },
    "scripts": {
        "example": "node ./example/html-to-text.js",
        "lint": "eslint .",
        "test": "istanbul cover _mocha && eslint ."
    },
    "version": "3.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
