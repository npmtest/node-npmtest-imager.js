# npmtest-imager.js

#### basic test coverage for  [imager.js (v0.5.0)](https://github.com/BBC-News/Imager.js)  [![npm package](https://img.shields.io/npm/v/npmtest-imager.js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-imager.js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-imager.js.svg)](https://travis-ci.org/npmtest/node-npmtest-imager.js)

#### Imager.js is an alternative solution to the issue of how to handle responsive image loading, created by developers at BBC News.

[![NPM](https://nodei.co/npm/imager.js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/imager.js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-imager.js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-imager.js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-imager.js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-imager.js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-imager.js/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-imager.js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-imager.js/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-imager.js/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-imager.js/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-imager.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-imager.js/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-imager.js/build/test-report.html](https://npmtest.github.io/node-npmtest-imager.js/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-imager.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-imager.js/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-imager.js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-imager.js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-imager.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-imager.js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-imager.js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-imager.js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/BBC-News/Imager.js/issues"
    },
    "contributors": [
        {
            "name": "Mark McDonnell",
            "url": "http://www.integralist.co.uk/"
        },
        {
            "name": "Addy Osmani",
            "url": "http://addyosmani.com/"
        },
        {
            "name": "Tom Maslen",
            "url": "http://tmaslen.com/"
        },
        {
            "name": "Thomas Parisot",
            "url": "https://oncletom.io/"
        }
    ],
    "dependencies": {},
    "description": "Imager.js is an alternative solution to the issue of how to handle responsive image loading, created by developers at BBC News.",
    "devDependencies": {
        "components-jquery": "git://github.com/components/jquery.git#1.10.2",
        "expect.js": "^0.2.0",
        "jshint": "^2.4.3",
        "karma": "^0.12.31",
        "karma-browserstack-launcher": "^0.1.1",
        "karma-chrome-launcher": "^0.1.0",
        "karma-expect": "^1.0.0",
        "karma-firefox-launcher": "^0.1.3",
        "karma-html2js-preprocessor": "^0.1.0",
        "karma-ievms": "^0.0.4",
        "karma-mocha": "^0.1.9",
        "karma-phantomjs-launcher": "^0.1.4",
        "karma-sauce-launcher": "^0.2.10",
        "karma-sinon": "^1.0.3",
        "mocha": "^1.17.1",
        "sinon": "^1.8.1",
        "uglify-js": "^2.4.3"
    },
    "directories": {},
    "dist": {
        "shasum": "ea8b454dda254b1b2999c9139322db63f511b9f9",
        "tarball": "https://registry.npmjs.org/imager.js/-/imager.js-0.5.0.tgz"
    },
    "gitHead": "77d79c6ae8a88eba5463dec6da02027573a7ae1f",
    "homepage": "https://github.com/BBC-News/Imager.js",
    "keywords": [
        "responsive",
        "srcset",
        "images",
        "resize",
        "polyfill",
        "shim",
        "img",
        "PictureFill"
    ],
    "license": "Apache-2.0",
    "main": "Imager.js",
    "maintainers": [
        {
            "name": "oncletom"
        }
    ],
    "name": "imager.js",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/BBC-News/Imager.js.git"
    },
    "scripts": {
        "build": "uglifyjs ./Imager.js -c -m -o ./Imager.min.js --source-map ./Imager.map.js && mv -f Imager.{map,min}.js ./dist",
        "test": "npm run test-pre && ./node_modules/karma/bin/karma start",
        "test-pre": "jshint Imager.js",
        "test-watch": "./node_modules/karma/bin/karma start --auto-watch --no-single-run"
    },
    "version": "0.5.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
