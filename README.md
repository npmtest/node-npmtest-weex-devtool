# npmtest-weex-devtool

#### basic test coverage for  weex-devtool (v0.2.80)  [![npm package](https://img.shields.io/npm/v/npmtest-weex-devtool.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-weex-devtool) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-weex-devtool.svg)](https://travis-ci.org/npmtest/node-npmtest-weex-devtool)

#### weex developer tool for debugging weex app with chrome devtool

[![NPM](https://nodei.co/npm/weex-devtool.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/weex-devtool)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-weex-devtool/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-weex-devtool/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-weex-devtool/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-weex-devtool/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-weex-devtool/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-weex-devtool/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-weex-devtool/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-weex-devtool/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-weex-devtool/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-weex-devtool/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-weex-devtool/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-weex-devtool/build/test-report.html](https://npmtest.github.io/node-npmtest-weex-devtool/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-weex-devtool/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-weex-devtool/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-weex-devtool/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-weex-devtool/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-weex-devtool/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-weex-devtool/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-weex-devtool/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-weex-devtool/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "weex-devtool",
    "description": "weex developer tool for debugging weex app with chrome devtool",
    "version": "0.2.80",
    "author": "exolution <exolution@163.com>",
    "license": "GPL-3.0",
    "main": "index.js",
    "keywords": [
        "weex",
        "debugger",
        "inspector",
        "devtool"
    ],
    "scripts": {
        "prepublish": "node_modules/babel-cli/bin/babel.js src --out-dir lib"
    },
    "devDependencies": {
        "babel-cli": "^6.10.1",
        "babel-core": "^6.10.4",
        "babel-loader": "^6.2.4",
        "babel-preset-es2015": "^6.9.0",
        "babel-plugin-transform-runtime": "^6.7.5",
        "eslint": "^2.13.1"
    },
    "dependencies": {
        "babel-core": "^6.10.4",
        "babel-loader": "^6.2.4",
        "babel-preset-es2015": "^6.9.0",
        "babel-runtime": "^6.6.1",
        "commander": "^2.9.0",
        "del": "^2.2.1",
        "exit": "^0.1.2",
        "ip": "^1.1.3",
        "javascript-obfuscator": "^0.8.6",
        "koa": "^1.2.0",
        "koa-bodyparser": "^2.3.0",
        "koa-router": "~5.2.3",
        "koa-serve": "~0.1.6",
        "koa-serve-static": "0.0.1",
        "koa-websocket": "^2.0.0",
        "mkdirp": "^0.5.1",
        "node-watch": "^0.3.5",
        "opn": "^4.0.2",
        "parse-hosts": "^1.0.1",
        "source-map": "^0.5.6",
        "webpack": "^1.13.1",
        "weex-components": "^0.2.0",
        "weex-loader": "^0.4.2-beta",
        "weex-transformer": "^0.3.1"
    },
    "bin": {
        "weex-devtool": "bin/weex-devtool.js"
    },
    "babel": {
        "presets": [
            "es2015"
        ],
        "plugins": [
            [
                "transform-runtime",
                {
                    "polyfill": false,
                    "regenerator": true
                }
            ]
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
