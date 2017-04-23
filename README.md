# npmtest-electron-windows-installer

#### basic test coverage for  [electron-windows-installer (v1.4.4)](https://github.com/Aluxian/electron-windows-installer#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-electron-windows-installer.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-electron-windows-installer) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-electron-windows-installer.svg)](https://travis-ci.org/npmtest/node-npmtest-electron-windows-installer)

#### Build Windows installers for Electron apps using Squirrel. Works with Gulp!

[![NPM](https://nodei.co/npm/electron-windows-installer.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/electron-windows-installer)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-electron-windows-installer/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-electron-windows-installer/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-electron-windows-installer/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-electron-windows-installer/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-electron-windows-installer/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-electron-windows-installer/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-electron-windows-installer/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-electron-windows-installer/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-electron-windows-installer/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-electron-windows-installer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-electron-windows-installer/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-electron-windows-installer/build/test-report.html](https://npmtest.github.io/node-npmtest-electron-windows-installer/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-electron-windows-installer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-electron-windows-installer/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-electron-windows-installer/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-electron-windows-installer/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-electron-windows-installer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-electron-windows-installer/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-electron-windows-installer/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-electron-windows-installer/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Alexandru Rosianu"
    },
    "bugs": {
        "url": "https://github.com/Aluxian/electron-windows-installer/issues"
    },
    "dependencies": {
        "asar": "0.11.0",
        "bluebird": "^3.1.1",
        "dot": "^1.0.3",
        "fs-extra": "^0.26.3",
        "temp": "^0.8.3"
    },
    "description": "Build Windows installers for Electron apps using Squirrel. Works with Gulp!",
    "devDependencies": {
        "coffee-script": "^1.10.0",
        "coffeelint": "^1.13.1",
        "mocha": "^2.3.4"
    },
    "directories": {},
    "dist": {
        "shasum": "1be229263530d27496e1a867d16cc91254ee488c",
        "tarball": "https://registry.npmjs.org/electron-windows-installer/-/electron-windows-installer-1.4.4.tgz"
    },
    "files": [
        "dist",
        "vendor",
        "resources"
    ],
    "gitHead": "bc04f9a784530fe2764517e10eab154a096a34ed",
    "homepage": "https://github.com/Aluxian/electron-windows-installer#readme",
    "keywords": [
        "electron",
        "atom-shell",
        "windows",
        "installer",
        "squirrel",
        "gulpplugin"
    ],
    "license": "MIT",
    "main": "./dist/index.js",
    "maintainers": [
        {
            "name": "aluxian"
        }
    ],
    "name": "electron-windows-installer",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/Aluxian/electron-windows-installer.git"
    },
    "scripts": {
        "build": "coffee -c -b -o dist src",
        "pretest": "npm run build",
        "test": "mocha -t 300000 --compilers coffee:coffee-script/register"
    },
    "version": "1.4.4",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
