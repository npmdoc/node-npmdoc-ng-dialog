# npmdoc-ng-dialog

#### api documentation for  [ng-dialog (v1.0.1)](https://github.com/likeastore/ngDialog)  [![npm package](https://img.shields.io/npm/v/npmdoc-ng-dialog.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-ng-dialog) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-ng-dialog.svg)](https://travis-ci.org/npmdoc/node-npmdoc-ng-dialog)

#### Modal dialogs and popups provider for Angular.js applications

[![NPM](https://nodei.co/npm/ng-dialog.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ng-dialog)

- [https://npmdoc.github.io/node-npmdoc-ng-dialog/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ng-dialog/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ng-dialog/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ng-dialog/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-ng-dialog/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-ng-dialog/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "ng-dialog",
    "version": "1.0.1",
    "homepage": "https://github.com/likeastore/ngDialog",
    "description": "Modal dialogs and popups provider for Angular.js applications",
    "main": "./js/ngDialog.js",
    "style": "./css/ngDialog.css",
    "scripts": {
        "pretest": "npm install && bower install --allow-root",
        "test": "./node_modules/karma/bin/karma start --single-run --browsers PhantomJS",
        "test-min": "./node_modules/karma/bin/karma start --single-run --browsers PhantomJS --min",
        "test-watch": "./node_modules/karma/bin/karma start --auto-watch --browsers PhantomJS",
        "serve": "node server",
        "webdriver-update": "node_modules/.bin/webdriver-manager update --standalone",
        "webdriver": "node_modules/.bin/webdriver-manager start",
        "preprotractor": "npm install && bower install --allow-root",
        "protractor": "node_modules/.bin/protractor protractor.conf.js",
        "protractor-a11y": "node_modules/.bin/protractor protractor.conf.js --a11y",
        "protractor-console": "node_modules/.bin/protractor protractor.conf.js --console-error",
        "build": "grunt build"
    },
    "directories": {
        "test": "tests"
    },
    "keywords": [
        "angular.js",
        "modals",
        "popups",
        "dialog",
        "ng",
        "provider",
        "factory",
        "directive"
    ],
    "author": {
        "name": "Dmitri Voronianski",
        "web": "http://pixelhunter.me",
        "twitter": "voronianski"
    },
    "bugs": "https://github.com/likeastore/ngDialog/issues",
    "repository": {
        "type": "git",
        "url": "https://github.com/likeastore/ngDialog"
    },
    "readmeFilename": "README.md",
    "license": "MIT",
    "devDependencies": {
        "express": "^4.13.3",
        "grunt": "^0.4.5",
        "grunt-cli": "^0.1.13",
        "grunt-contrib-cssmin": "^0.14.0",
        "grunt-contrib-jshint": "^0.11.3",
        "grunt-contrib-uglify": "^0.9.2",
        "grunt-myth": "^1.0.1",
        "jasmine-core": "^2.3.4",
        "karma": "^1.3.0",
        "karma-coverage": "^1.1.1",
        "karma-jasmine": "^1.1.0",
        "karma-phantomjs-launcher": "^1.0.2",
        "myth": "^1.5.0",
        "phantomjs": "^2.1.7",
        "protractor": "^2.2.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
