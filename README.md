# npmtest-gulp-wp-theme

#### basic test coverage for  gulp-wp-theme (v1.0.0)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-wp-theme.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-wp-theme) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-wp-theme.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-wp-theme)

#### WordPress Theme Project Templates for Gulp

[![NPM](https://nodei.co/npm/gulp-wp-theme.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-wp-theme)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-wp-theme/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-wp-theme/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-wp-theme/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-wp-theme/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-wp-theme/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-wp-theme/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-wp-theme/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-wp-theme/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-wp-theme/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-wp-theme/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-wp-theme/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-wp-theme/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-wp-theme/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-wp-theme/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-wp-theme/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-wp-theme/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-wp-theme/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-wp-theme/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-wp-theme/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-wp-theme/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-wp-theme/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "gulp-wp-theme",
    "version": "1.0.0",
    "description": "WordPress Theme Project Templates for Gulp ",
    "author": "whatwedo <welove@whatwedo.ch",
    "contributors": [
        {
            "name": "René Stalder"
        },
        {
            "name": "Ueli Banholzer"
        }
    ],
    "keywords": [
        "wordpress",
        "gulp",
        "themes",
        "browserify",
        "wp"
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/whatwedo/gulp-wp-theme.git"
    },
    "bugs": {
        "url": "https://github.com/whatwedo/gulp-wp-theme/issues"
    },
    "license": "MIT",
    "main": "index.js",
    "browser": {},
    "browserify": {
        "transform": [
            "browserify-shim"
        ]
    },
    "browserify-shim": {
        "jQuery": "global:jQuery"
    },
    "dependencies": {
        "browser-sync": "~2.7.1",
        "browserify": "~10.1.3",
        "browserify-shim": "~3.8.6",
        "debowerify": "1.2.1",
        "glob": "^5.0.12",
        "glob-stream": "^5.0.0",
        "gulp": "^3.8.11",
        "gulp-autoprefixer": "*",
        "gulp-bump": "^0.3.0",
        "gulp-changed": "^1.2.1",
        "gulp-if": "~1.2.5",
        "gulp-imagemin": "^2.2.1",
        "gulp-markdown": "^1.0.0",
        "gulp-minify-css": "^1.1.1",
        "gulp-notify": "^2.2.0",
        "gulp-plumber": "*",
        "gulp-prompt": "^0.1.2",
        "gulp-replace": "^0.5.3",
        "gulp-sourcemaps": "^1.5.2",
        "gulp-stylus": "^2.0.1",
        "gulp-svgmin": "^1.1.2",
        "gulp-util": "^3.0.4",
        "hbsfy": "~2.2.1",
        "lodash": "^3.8.0",
        "node.extend": "^1.1.3",
        "pretty-hrtime": "~1.0.0",
        "require-dir": "^0.3.0",
        "semver": "^4.3.4",
        "through2": "^0.6.5",
        "uglifyify": "^3.0.1",
        "vinyl-source-stream": "~1.1.0",
        "watchify": "~3.2.1",
        "yargs": "^3.8.0"
    },
    "devDependencies": {
        "bower": "^1.4.1"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
