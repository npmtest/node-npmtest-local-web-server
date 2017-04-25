# npmtest-local-web-server

#### basic test coverage for  [local-web-server (v1.2.7)](https://github.com/75lb/local-web-server#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-local-web-server.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-local-web-server) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-local-web-server.svg)](https://travis-ci.org/npmtest/node-npmtest-local-web-server)

#### A simple web-server for productive front-end development

[![NPM](https://nodei.co/npm/local-web-server.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/local-web-server)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-local-web-server/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-local-web-server/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-local-web-server/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-local-web-server/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-local-web-server/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-local-web-server/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-local-web-server/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-local-web-server/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-local-web-server/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-local-web-server/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-local-web-server/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-local-web-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-local-web-server/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-local-web-server/build/test-report.html](https://npmtest.github.io/node-npmtest-local-web-server/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-local-web-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-local-web-server/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-local-web-server/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-local-web-server/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-local-web-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-local-web-server/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-local-web-server/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-local-web-server/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Lloyd Brookes"
    },
    "bin": {
        "ws": "./bin/cli.js"
    },
    "bugs": {
        "url": "https://github.com/75lb/local-web-server/issues"
    },
    "dependencies": {
        "ansi-escape-sequences": "^3.0.0",
        "array-back": "^1.0.4",
        "command-line-args": "^4.0.2",
        "command-line-usage": "^4.0.0",
        "config-master": "^3.0.0",
        "debug": "^2.2.0",
        "http-proxy": "^1.15.1",
        "kcors": "^1.3.0",
        "koa": "2.0.1",
        "koa-bodyparser": "^3.0.0",
        "koa-compress": "^1.0.9",
        "koa-conditional-get": "^1.0.3",
        "koa-connect-history-api-fallback": "^0.3.1",
        "koa-convert": "^1.2.0",
        "koa-etag": "^2.1.1",
        "koa-json": "^1.1.3",
        "koa-morgan": "^1.0.1",
        "koa-rewrite": "^2.1.0",
        "koa-route": "^3",
        "koa-send": "^3.2.0",
        "koa-serve-index": "^1.1.1",
        "koa-static": "^2.0.0",
        "path-to-regexp": "^1.6.0",
        "reduce-flatten": "^1.0.1",
        "stream-log-stats": "^1.1.7",
        "test-value": "^2.1.0",
        "typical": "^2.6.0"
    },
    "description": "A simple web-server for productive front-end development",
    "devDependencies": {
        "jsdoc-to-markdown": "^3.0.0",
        "req-then": "^0.2.4",
        "tape": "^4.6.2"
    },
    "directories": {},
    "dist": {
        "shasum": "c3b5079cc07059bd5efce369f16b1802d44a1929",
        "tarball": "https://registry.npmjs.org/local-web-server/-/local-web-server-1.2.7.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "185845c63017f2ddcce8911eeaa7b7366ed79a7e",
    "homepage": "https://github.com/75lb/local-web-server#readme",
    "keywords": [
        "dev",
        "server",
        "web",
        "tool",
        "front-end",
        "development",
        "cors",
        "mime",
        "rest"
    ],
    "license": "MIT",
    "main": "lib/local-web-server.js",
    "maintainers": [
        {
            "name": "75lb"
        }
    ],
    "name": "local-web-server",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/75lb/local-web-server.git"
    },
    "scripts": {
        "cover": "istanbul cover ./node_modules/.bin/tape test/*.js && cat coverage/lcov.info | coveralls && rm -rf coverage; echo",
        "docs": "jsdoc2md -t jsdoc2md/README.hbs -p list lib/*.js > README.md; echo",
        "test": "tape test/*.js"
    },
    "version": "1.2.7"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
