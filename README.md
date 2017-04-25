# npmtest-twitter

#### basic test coverage for  [twitter (v1.7.0)](https://github.com/desmondmorris/node-twitter)  [![npm package](https://img.shields.io/npm/v/npmtest-twitter.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-twitter) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-twitter.svg)](https://travis-ci.org/npmtest/node-npmtest-twitter)

#### Twitter API client library for node.js

[![NPM](https://nodei.co/npm/twitter.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/twitter)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-twitter/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-twitter/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-twitter/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-twitter/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-twitter/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-twitter/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-twitter/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-twitter/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-twitter/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-twitter/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-twitter/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-twitter/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-twitter/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-twitter/build/test-report.html](https://npmtest.github.io/node-npmtest-twitter/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-twitter/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-twitter/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-twitter/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-twitter/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-twitter/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-twitter/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-twitter/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-twitter/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Desmond Morris"
    },
    "bugs": {
        "url": "https://github.com/desmondmorris/node-twitter/issues"
    },
    "dependencies": {
        "deep-extend": "^0.4.1",
        "request": "^2.72.0"
    },
    "description": "Twitter API client library for node.js",
    "devDependencies": {
        "eslint": "^2.10.0",
        "mocha": "^2.4.5",
        "nock": "^8.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "2882e208e0ad83bb226528613561f1dd233ac94b",
        "tarball": "https://registry.npmjs.org/twitter/-/twitter-1.7.0.tgz"
    },
    "gitHead": "87225a043db8f318fa1a05399638e8f106ea43a9",
    "homepage": "https://github.com/desmondmorris/node-twitter",
    "keywords": [
        "twitter",
        "streaming",
        "oauth"
    ],
    "license": "MIT",
    "main": "./lib/twitter",
    "maintainers": [
        {
            "name": "desmondmorris"
        }
    ],
    "name": "twitter",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/desmondmorris/node-twitter.git"
    },
    "scripts": {
        "lint": "eslint test/*.js lib/*.js",
        "test": "npm run lint && mocha"
    },
    "version": "1.7.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
