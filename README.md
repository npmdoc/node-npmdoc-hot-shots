# npmdoc-hot-shots

#### api documentation for  hot-shots (v4.4.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-hot-shots.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-hot-shots) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-hot-shots.svg)](https://travis-ci.org/npmdoc/node-npmdoc-hot-shots)

#### Node.js client for StatsD, DogStatsD, and Telegraf

[![NPM](https://nodei.co/npm/hot-shots.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hot-shots)

- [https://npmdoc.github.io/node-npmdoc-hot-shots/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-hot-shots/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hot-shots/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hot-shots/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-hot-shots/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-hot-shots/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "hot-shots",
    "description": "Node.js client for StatsD, DogStatsD, and Telegraf",
    "version": "4.4.0",
    "author": "Steve Ivy",
    "contributors": [
        "Russ Bradberry <rbradberry@gmail.com>",
        "Brian Deitte <bdeitte@gmail.com>",
        "Mikhail Mazurskiy <mikhail.mazursky@gmail.com>"
    ],
    "keywords": [
        "statsd",
        "dogstatsd",
        "datadog",
        "metrics",
        "telegraf"
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/brightcove/hot-shots.git"
    },
    "bugs": {
        "url": "https://github.com/brightcove/hot-shots/issues"
    },
    "directories": {
        "lib": "./lib/"
    },
    "engines": {
        "node": ">=0.8.0"
    },
    "scripts": {
        "test": "mocha -R spec",
        "lint": "jshint lib/**.js test/**.js",
        "pretest": "npm run lint"
    },
    "dependencies": {},
    "devDependencies": {
        "jshint": "2.x",
        "mocha": "2.x"
    },
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
