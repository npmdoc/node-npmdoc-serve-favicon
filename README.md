# api documentation for  [serve-favicon (v2.4.2)](https://github.com/expressjs/serve-favicon#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-serve-favicon.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-serve-favicon) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-serve-favicon.svg)](https://travis-ci.org/npmdoc/node-npmdoc-serve-favicon)
#### favicon serving middleware with caching

[![NPM](https://nodei.co/npm/serve-favicon.png?downloads=true)](https://www.npmjs.com/package/serve-favicon)

[![apidoc](https://npmdoc.github.io/node-npmdoc-serve-favicon/build/screenCapture.buildNpmdoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-serve-favicon%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-serve-favicon/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-serve-favicon/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-serve-favicon/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Douglas Christopher Wilson",
        "email": "doug@somethingdoug.com"
    },
    "bugs": {
        "url": "https://github.com/expressjs/serve-favicon/issues"
    },
    "dependencies": {
        "etag": "~1.8.0",
        "fresh": "0.5.0",
        "ms": "1.0.0",
        "parseurl": "~1.3.1"
    },
    "description": "favicon serving middleware with caching",
    "devDependencies": {
        "eslint": "3.18.0",
        "eslint-config-standard": "7.1.0",
        "eslint-plugin-markdown": "1.0.0-beta.4",
        "eslint-plugin-promise": "3.5.0",
        "eslint-plugin-standard": "2.1.1",
        "istanbul": "0.4.5",
        "mocha": "2.5.3",
        "supertest": "1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "aed1d8de67d5b83192cf31fdf53d2ea29464363e",
        "tarball": "https://registry.npmjs.org/serve-favicon/-/serve-favicon-2.4.2.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "files": [
        "LICENSE",
        "HISTORY.md",
        "index.js"
    ],
    "gitHead": "b450452e5dc432d9019ee48e7b4702b7ed835c10",
    "homepage": "https://github.com/expressjs/serve-favicon#readme",
    "keywords": [
        "express",
        "favicon",
        "middleware"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "dougwilson",
            "email": "doug@somethingdoug.com"
        }
    ],
    "name": "serve-favicon",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/expressjs/serve-favicon.git"
    },
    "scripts": {
        "lint": "eslint --plugin markdown --ext js,md .",
        "test": "mocha --reporter spec --bail --check-leaks test/",
        "test-ci": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks test/"
    },
    "version": "2.4.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module serve-favicon](#apidoc.module.serve-favicon)



# <a name="apidoc.module.serve-favicon"></a>[module serve-favicon](#apidoc.module.serve-favicon)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
