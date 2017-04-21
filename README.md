# npmdoc-minimize

#### api documentation for  minimize (v2.1.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-minimize.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-minimize) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-minimize.svg)](https://travis-ci.org/npmdoc/node-npmdoc-minimize)

#### Minimize HTML

[![NPM](https://nodei.co/npm/minimize.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/minimize)

- [https://npmdoc.github.io/node-npmdoc-minimize/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-minimize/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-minimize/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-minimize/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-minimize/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-minimize/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "minimize",
    "version": "2.1.0",
    "description": "Minimize HTML",
    "main": "./lib/minimize",
    "bin": {
        "minimize": "./bin/minimize"
    },
    "scripts": {
        "test": "mocha $(find test -name '*.test.js')",
        "watch": "mocha --watch $(find test -name '*.test.js')",
        "coverage": "istanbul cover ./node_modules/.bin/_mocha -- $(find test -name '*.test.js')",
        "test-travis": "istanbul cover node_modules/.bin/_mocha --report lcovonly -- $(find test -name '*.test.js')"
    },
    "dependencies": {
        "argh": "^0.1.4",
        "async": "^2.1.5",
        "cli-color": "^1.2.0",
        "diagnostics": "^1.1.0",
        "emits": "^3.0.0",
        "htmlparser2": "^3.9.2",
        "uuid": "^3.0.0"
    },
    "devDependencies": {
        "chai": "^3.5.0",
        "istanbul": "^0.4.5",
        "mocha": "^3.2.0",
        "pre-commit": "^1.2.2",
        "sinon": "^1.17.7",
        "sinon-chai": "^2.8.0"
    },
    "repository": "git@github.com:Moveo/minimize.git",
    "keywords": [
        "minify",
        "minimize",
        "HTML"
    ],
    "author": "Martijn Swaagman",
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
