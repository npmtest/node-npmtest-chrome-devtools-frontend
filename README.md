# npmtest-chrome-devtools-frontend

#### basic test coverage for  [chrome-devtools-frontend (v1.0.465916)](https://devtools.chrome.com)  [![npm package](https://img.shields.io/npm/v/npmtest-chrome-devtools-frontend.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-chrome-devtools-frontend) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-chrome-devtools-frontend.svg)](https://travis-ci.org/npmtest/node-npmtest-chrome-devtools-frontend)

#### Chrome DevTools UI

[![NPM](https://nodei.co/npm/chrome-devtools-frontend.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/chrome-devtools-frontend)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-chrome-devtools-frontend/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-chrome-devtools-frontend/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-chrome-devtools-frontend/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-chrome-devtools-frontend/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-chrome-devtools-frontend/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-chrome-devtools-frontend/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-chrome-devtools-frontend/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-chrome-devtools-frontend/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-chrome-devtools-frontend/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-chrome-devtools-frontend/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-chrome-devtools-frontend/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-chrome-devtools-frontend/build/test-report.html](https://npmtest.github.io/node-npmtest-chrome-devtools-frontend/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-chrome-devtools-frontend/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-chrome-devtools-frontend/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-chrome-devtools-frontend/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-chrome-devtools-frontend/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-chrome-devtools-frontend/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-chrome-devtools-frontend/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-chrome-devtools-frontend/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-chrome-devtools-frontend/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "chrome-devtools-frontend",
    "description": "Chrome DevTools UI",
    "scripts": {
        "start": "node scripts/start_chrome_and_server.js",
        "chrome": "node scripts/chrome_debug_launcher/launch_chrome.js",
        "server": "node scripts/hosted_mode/server.js",
        "test": "node scripts/npm_test.js",
        "debug-test": "node scripts/npm_test.js --debug-devtools",
        "compat-test": "node scripts/npm_test.js --compat-protocol=1.2",
        "lint": "eslint front_end",
        "format": "git cl format --js .",
        "closure": "python scripts/compile_frontend.py",
        "setup-dtrun": "cd scripts/devtools_run && npm link",
        "format-py": "yapf --exclude scripts/build/rjsmin.py -i --recursive scripts PRESUBMIT.py"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ChromeDevTools/devtools-frontend.git"
    },
    "keywords": [
        "devtools",
        "chrome",
        "chromium",
        "blink",
        "debugger"
    ],
    "author": "The Chromium Authors",
    "license": "SEE LICENSE IN https://chromium.googlesource.com/chromium/src/+/master/LICENSE",
    "bugs": {
        "url": "https://bugs.chromium.org/p/chromium/issues/list?can=2&q=component:Platform%3EDevTools%20&sort=-opened&colspec=ID%20Stars%20Owner%20Summary%20Modified%20Opened"
    },
    "homepage": "https://devtools.chrome.com",
    "devDependencies": {
        "eslint": "3.10.0"
    },
    "version": "1.0.465916"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
