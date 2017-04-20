# npmtest-oboe

#### basic test coverage for  [oboe (v2.1.3)](http://oboejs.com)  [![npm package](https://img.shields.io/npm/v/npmtest-oboe.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-oboe) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-oboe.svg)](https://travis-ci.org/npmtest/node-npmtest-oboe)

#### Oboe.js reads json, giving you the objects as they are found without waiting for the stream to finish

[![NPM](https://nodei.co/npm/oboe.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/oboe)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-oboe/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-oboe/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-oboe/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-oboe/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-oboe/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-oboe/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-oboe/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-oboe/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-oboe/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-oboe/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-oboe/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-oboe/build/test-report.html](https://npmtest.github.io/node-npmtest-oboe/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-oboe/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-oboe/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-oboe/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-oboe/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-oboe/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-oboe/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-oboe/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-oboe/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jim Higson"
    },
    "browser": "./dist/oboe-browser.js",
    "bugs": {
        "url": "https://github.com/jimhigson/oboe.js/issues"
    },
    "dependencies": {
        "http-https": "^1.0.0"
    },
    "description": "Oboe.js reads json, giving you the objects as they are found without waiting for the stream to finish",
    "devDependencies": {
        "color": "~0.4.4",
        "cors": "~2.1.1",
        "doctoc": "~0.4.3",
        "express": "~3.4.3",
        "get-json": "0.0.1",
        "grunt": "~0.4.1",
        "grunt-clear": "~0.2.1",
        "grunt-cli": "~0.1.9",
        "grunt-concurrent": "~0.3.1",
        "grunt-contrib-clean": "~0.5.0",
        "grunt-contrib-concat": "~0.1.3",
        "grunt-contrib-copy": "~0.4.1",
        "grunt-contrib-uglify": "~0.2.0",
        "grunt-contrib-watch": "~0.5.1",
        "grunt-exec": "~0.4.2",
        "grunt-karma": "~0.6.2",
        "grunt-micro": "~0.1.0",
        "grunt-wrap": "~0.2.0",
        "jasmine-node": "~1.11.0",
        "karma": "~0.10.0",
        "karma-coverage": "^0.2.4",
        "karma-firefox-launcher": "~0.1.0",
        "karma-jasmine": "~0.1.5",
        "karma-safari-launcher": "~0.1.1",
        "matchdep": "~0.1.2",
        "request": "^2.55.0"
    },
    "directories": {},
    "dist": {
        "shasum": "2b4865dbd46be81225713f4e9bfe4bcf4f680a4f",
        "tarball": "https://registry.npmjs.org/oboe/-/oboe-2.1.3.tgz"
    },
    "gitHead": "537e9e75b61f75d2d402632505ff3c9a12dd254f",
    "homepage": "http://oboejs.com",
    "jam": {
        "main": "dist/oboe-browser.js",
        "include": [
            "dist/oboe-browser.js",
            "LICENCE",
            "package.json",
            "README.md"
        ],
        "dependencies": {},
        "categories": [
            "AJAX & Websockets",
            "Parsers & Compilers"
        ]
    },
    "keywords": [
        "json",
        "parser",
        "stream",
        "progressive",
        "http",
        "sax",
        "event",
        "emitter",
        "async",
        "browser"
    ],
    "license": "BSD",
    "main": "./dist/oboe-node.js",
    "maintainers": [
        {
            "name": "jimhigson"
        },
        {
            "name": "joombar"
        },
        {
            "name": "juancaicedo"
        }
    ],
    "name": "oboe",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jimhigson/oboe.js.git"
    },
    "scripts": {
        "browser-test-auto-run": "node ./node_modules/grunt-cli/bin/grunt test-auto-run",
        "dist-sizes": "node ./node_modules/grunt-cli/bin/grunt dist-sizes",
        "node-test-auto-run": "node ./node_modules/grunt-cli/bin/grunt node-test-auto-run",
        "test": "node ./node_modules/grunt-cli/bin/grunt headless-mode default",
        "test-run": "node ./node_modules/grunt-cli/bin/grunt test-run",
        "test-start-server": "node ./node_modules/grunt-cli/bin/grunt test-start-server"
    },
    "title": "Oboe.js",
    "version": "2.1.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
