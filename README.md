# npmdoc-react-chartjs

#### api documentation for  [react-chartjs (v0.8.0)](https://github.com/jhudson8/react-chartjs)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-chartjs.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-chartjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-chartjs.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-chartjs)

#### react charting components using the chartjs lib

[![NPM](https://nodei.co/npm/react-chartjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-chartjs)

- [https://npmdoc.github.io/node-npmdoc-react-chartjs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-chartjs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-chartjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-chartjs/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-chartjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-chartjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-chartjs",
    "version": "0.8.0",
    "description": "react charting components using the chartjs lib",
    "main": "index.js",
    "scripts": {
        "test": "mocha",
        "build": "webpack index.js dist/react-chartjs.js",
        "dist": "COMPRESS=1 webpack index.js dist/react-chartjs.min.js"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/jhudson8/react-chartjs"
    },
    "keywords": [
        "react",
        "react-component",
        "chart",
        "charts",
        "graph",
        "chartjs"
    ],
    "author": "Joe Hudson",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/jhudson8/react-chartjs/issues"
    },
    "homepage": "https://github.com/jhudson8/react-chartjs",
    "peerDependencies": {
        "react": "*",
        "react-dom": "*",
        "chart.js": "^1.1.1"
    },
    "devDependencies": {
        "uglify-js": "^2.4.16",
        "webpack": "^1.4.14"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
