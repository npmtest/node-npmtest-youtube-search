# npmtest-youtube-search

#### basic test coverage for  youtube-search (v1.0.9)  [![npm package](https://img.shields.io/npm/v/npmtest-youtube-search.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-youtube-search) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-youtube-search.svg)](https://travis-ci.org/npmtest/node-npmtest-youtube-search)

#### Search for youtube videos

[![NPM](https://nodei.co/npm/youtube-search.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/youtube-search)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-youtube-search/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-youtube-search/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-youtube-search/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-youtube-search/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-youtube-search/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-youtube-search/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-youtube-search/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-youtube-search/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-youtube-search/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-youtube-search/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-youtube-search/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-youtube-search/build/test-report.html](https://npmtest.github.io/node-npmtest-youtube-search/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-youtube-search/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-youtube-search/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-youtube-search/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-youtube-search/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-youtube-search/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-youtube-search/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-youtube-search/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-youtube-search/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "youtube-search",
    "version": "1.0.9",
    "description": "Search for youtube videos",
    "main": "index.js",
    "scripts": {
        "test": "standard && node tests/test-*.js"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/MaxGfeller/youtube-search"
    },
    "keywords": [
        "youtube",
        "search",
        "api"
    ],
    "author": "Max Gfeller <max.gfeller@gmail.com>",
    "license": "BSD",
    "dependencies": {
        "request": "^2.57.0",
        "xhr": "^2.0.1",
        "xml2js": "~0.2.8"
    },
    "devDependencies": {
        "browserify": "^10.2.1",
        "standard": "^4.3.3",
        "tape": "^4.0.0",
        "tape-run": "^1.0.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
