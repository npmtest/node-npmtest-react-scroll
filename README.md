# npmtest-react-scroll

#### test coverage for  [react-scroll (v1.5.2)](https://github.com/fisshy/react-scroll)  [![npm package](https://img.shields.io/npm/v/npmtest-react-scroll.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-scroll) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-scroll.svg)](https://travis-ci.org/npmtest/node-npmtest-react-scroll)

#### A scroll component for React.js

[![NPM](https://nodei.co/npm/react-scroll.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-scroll)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-scroll/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-scroll/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-scroll/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-scroll/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-scroll/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-scroll/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-scroll/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-scroll/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-scroll/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-scroll/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-scroll/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-scroll/build/test-report.html](https://npmtest.github.io/node-npmtest-react-scroll/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-scroll/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-scroll/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-scroll/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-scroll/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-scroll/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-scroll/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-scroll/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-scroll/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "authors": [
        "Joachim Karlsson"
    ],
    "babel": {
        "presets": [
            "es2015",
            "react"
        ]
    },
    "bugs": {
        "url": "https://github.com/fisshy/react-scroll/issues"
    },
    "dependencies": {
        "object-assign": "^4.1.1",
        "prop-types": "^15.5.8"
    },
    "description": "A scroll component for React.js",
    "devDependencies": {
        "babel-cli": "^6.24.1",
        "babel-core": "^6.24.1",
        "babel-loader": "^6.4.1",
        "babel-preset-es2015": "^6.24.1",
        "babel-preset-react": "^6.24.1",
        "expect": "^1.20.2",
        "gulp": "^3.9.1",
        "gulp-concat": "^2.6.1",
        "karma": "^1.6.0",
        "karma-chrome-launcher": "^2.0.0",
        "karma-mocha": "^1.3.0",
        "karma-mocha-reporter": "^2.2.3",
        "karma-sourcemap-loader": "^0.3.7",
        "karma-webpack": "^2.0.3",
        "mocha": "^3.2.0",
        "react": "^15.5.4",
        "react-addons-test-utils": "^15.5.1",
        "react-dom": "^15.5.4",
        "webpack": "^2.4.1",
        "webpack-dev-server": "^2.4.2"
    },
    "directories": {},
    "dist": {
        "shasum": "f10f14840d3138a121d2c0f04933bbfee4193975",
        "tarball": "https://registry.npmjs.org/react-scroll/-/react-scroll-1.5.2.tgz"
    },
    "homepage": "https://github.com/fisshy/react-scroll",
    "keywords": [
        "react",
        "react-component",
        "scroll",
        "scroller",
        "scrolls"
    ],
    "license": "MIT",
    "main": "modules",
    "maintainers": [
        {
            "name": "fisshy"
        }
    ],
    "name": "react-scroll",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^15.5.4",
        "react-dom": "^15.5.4"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/fisshy/react-scroll.git"
    },
    "scripts": {
        "build": "babel modules -d build/npm/modules --ignore '**/__tests__/**' && gulp",
        "clean": "rm -rf build/npm/modules",
        "examples": "webpack-dev-server --config examples/webpack.config.js --no-info --content-base examples",
        "test": "karma start"
    },
    "tags": [
        "react",
        "scroll"
    ],
    "version": "1.5.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
