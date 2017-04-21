# npmdoc-redux-auth

#### api documentation for  [redux-auth (v0.0.5-beta5)](https://github.com/lynndylanhurley/redux-auth)  [![npm package](https://img.shields.io/npm/v/npmdoc-redux-auth.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-redux-auth) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-redux-auth.svg)](https://travis-ci.org/npmdoc/node-npmdoc-redux-auth)

#### Complete token authentication system for react + redux.

[![NPM](https://nodei.co/npm/redux-auth.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/redux-auth)

- [https://npmdoc.github.io/node-npmdoc-redux-auth/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-redux-auth/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-redux-auth/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-redux-auth/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-redux-auth/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-redux-auth/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "redux-auth",
    "description": "Complete token authentication system for react + redux.",
    "version": "0.0.5-beta5",
    "license": "WTFPL",
    "repository": {
        "type": "git",
        "url": "https://github.com/lynndylanhurley/redux-auth.git"
    },
    "homepage": "https://github.com/lynndylanhurley/redux-auth",
    "keywords": [
        "react",
        "isomorphic",
        "universal",
        "starter",
        "boilerplate",
        "template",
        "webpack",
        "koa",
        "transmit"
    ],
    "main": "index.js",
    "scripts": {
        "release": "node ./node_modules/webpack/bin/webpack.js --verbose --colors --display-error-details --config webpack.release.js",
        "test": "node_modules/.bin/_mocha --timeout 5000 --compilers .:test/compiler.js test/runner.js",
        "test-coverage": "node_modules/.bin/babel-node node_modules/.bin/isparta cover --root ./src node_modules/.bin/_mocha -- --timeout 5000 test/runner.js && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js"
    },
    "files": [
        "src",
        "default-theme.js",
        "bootstrap-theme.js",
        "material-ui-theme.js",
        "index.js",
        "LICENSE.md",
        "README.md"
    ],
    "dependencies": {
        "browser-cookies": "^1.0.8",
        "classnames": "^2.1.5",
        "cookie": "^0.2.3",
        "extend": "^3.0.0",
        "immutable": "^3.7.5",
        "isomorphic-fetch": "^2.1.1",
        "query-string": "^2.4.2",
        "rc-dialog": "^6.1.1",
        "react-bootstrap": "^0.29.5",
        "react-loader": "^2.4.0",
        "redux-immutablejs": "0.0.8"
    },
    "devDependencies": {
        "babel-cli": "6.3.13",
        "babel-core": "6.3.13",
        "babel-loader": "6.1.0",
        "babel-polyfill": "6.3.13",
        "babel-preset-es2015": "6.3.13",
        "babel-preset-react": "6.3.13",
        "babel-preset-stage-0": "6.3.13",
        "babel-register": "6.3.13",
        "bootstrap": "^3.3.5",
        "bootstrap-sass": "^3.3.5",
        "bootstrap-webpack": "0.0.5",
        "chai": "^3.3.0",
        "chai-as-promised": "^5.1.0",
        "concurrently": "0.1.1",
        "coveralls": "^2.11.4",
        "css-loader": "^0.19.0",
        "exports-loader": "^0.6.2",
        "extract-text-webpack-plugin": "0.9.1",
        "fetch-mock": "^2.1.0",
        "file-loader": "0.8.5",
        "h2o2": "4.0.1",
        "hapi": "9.3.1",
        "highlight.js": "^8.8.0",
        "imports-loader": "^0.6.4",
        "inert": "3.0.1",
        "install": "^0.3.0",
        "invariant": "^2.2.0",
        "isparta": "^4.0.0",
        "istanbul": "^0.3.22",
        "istanbul-instrumenter-loader": "^0.1.3",
        "jquery": "^2.1.4",
        "jquery-deparam": "^0.4.2",
        "jsdom": "^9.4.1",
        "jsdomify": "^2.1.0",
        "json-loader": "0.5.4",
        "material-ui": "0.15.2",
        "mocha": "^2.3.4",
        "mockery": "^1.4.0",
        "nock": "^3.3.2",
        "node-sass": "^3.3.3",
        "nodemon": "^1.7.2",
        "piping": "0.2.0",
        "react": "^15.2.1",
        "react-addons-test-utils": "^0.14.3",
        "react-dom": "^15.2.1",
        "react-hot-loader": "1.3.0",
        "react-redux": "^3.1.2",
        "react-router": "^2.5.2",
        "react-router-bootstrap": "^0.19.0",
        "react-router-redux": "^4.0.5",
        "react-select": "^1.0.0-beta13",
        "react-tap-event-plugin": "^0.2.1",
        "react-transmit": "3.0.6",
        "redux": "^3.3.1",
        "redux-thunk": "^1.0.0",
        "require-subvert": "^0.1.0",
        "rewire": "^2.5.1",
        "sass-loader": "^3.0.0",
        "serialize-javascript": "^1.1.2",
        "sinon": "1.17.0",
        "style-loader": "^0.12.4",
        "thunk": "^0.0.1",
        "url-loader": "^0.5.6",
        "warning": "^2.1.0",
        "webpack": "1.12.9",
        "webpack-dev-server": "1.14.0"
    },
    "peerDependencies": {
        "react-router-bootstrap": "*"
    },
    "engines": {
        "node": ">=0.10.32"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
