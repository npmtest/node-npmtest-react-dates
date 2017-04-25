# npmtest-react-dates

#### basic test coverage for  [react-dates (v10.1.1)](https://github.com/airbnb/react-dates#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-react-dates.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-dates) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-dates.svg)](https://travis-ci.org/npmtest/node-npmtest-react-dates)

#### A responsive and accessible date range picker component built with React

[![NPM](https://nodei.co/npm/react-dates.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-dates)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-dates/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-dates/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-dates/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-dates/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-dates/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-react-dates/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-react-dates/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-dates/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-dates/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-dates/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-dates/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-dates/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-dates/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-dates/build/test-report.html](https://npmtest.github.io/node-npmtest-react-dates/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-dates/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-dates/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-dates/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-dates/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-dates/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-dates/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-dates/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-dates/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Maja Wichrowska"
    },
    "bugs": {
        "url": "https://github.com/airbnb/react-dates/issues"
    },
    "dependencies": {
        "airbnb-prop-types": "^2.4.1",
        "array-includes": "^3.0.2",
        "classnames": "^2.2.5",
        "consolidated-events": "^1.0.1",
        "lodash.throttle": "^4.1.1",
        "prop-types": "^15.5.6",
        "react-moment-proptypes": "^1.3.0",
        "react-portal": "^3.0.0"
    },
    "description": "A responsive and accessible date range picker component built with React",
    "devDependencies": {
        "@kadira/react-storybook-addon-info": "^3.3.0",
        "@kadira/storybook": "^2.35.3",
        "@kadira/storybook-addon-options": "^1.0.2",
        "airbnb-js-shims": "^1.0.1",
        "babel-cli": "^6.22.2",
        "babel-core": "^6.22.1",
        "babel-loader": "^6.4.1",
        "babel-plugin-istanbul": "^4.1.1",
        "babel-plugin-syntax-jsx": "^6.18.0",
        "babel-preset-airbnb": "^2.2.0",
        "babel-register": "^6.22.0",
        "chai": "^3.5.0",
        "coveralls": "^2.12.0",
        "cross-env": "^4.0.0",
        "enzyme": "^2.8.1",
        "eslint": "^3.17.1",
        "eslint-config-airbnb": "^14.1.0",
        "eslint-plugin-import": "^2.2.0",
        "eslint-plugin-jsx-a11y": "^4.0.0",
        "eslint-plugin-react": "^6.10.3",
        "git-directory-deploy": "^1.5.1",
        "imports-loader": "^0.7.1",
        "in-publish": "^2.0.0",
        "json-loader": "^0.5.4",
        "karma": "^1.4.0",
        "karma-chai": "^0.1.0",
        "karma-firefox-launcher": "^1.0.0",
        "karma-mocha": "^1.3.0",
        "karma-sinon": "^1.0.5",
        "karma-webpack": "^2.0.3",
        "lodash.omit": "^4.5.0",
        "mocha": "^3.2.0",
        "mocha-wrap": "^2.1.0",
        "moment": "^2.17.1 && < 2.18.0",
        "node-sass": "^4.4.0",
        "nyc": "^10.1.2",
        "raw-loader": "^0.5.1",
        "react": "^15.5.0",
        "react-addons-shallow-compare": "^15.5.0",
        "react-addons-test-utils": "^15.5.0",
        "react-dom": "^15.5.0",
        "react-svg-loader": "^1.1.1",
        "react-test-renderer": "^15.5.4",
        "rimraf": "^2.5.4",
        "safe-publish-latest": "^1.1.1",
        "sass-loader": "^4.1.1",
        "sinon": "^2.0.0",
        "sinon-sandbox": "^1.0.2",
        "style-loader": "^0.16.1",
        "webpack": "^1.14.0"
    },
    "directories": {},
    "dist": {
        "shasum": "fbc6c57e575648908cfab1103449e8a3c66085de",
        "tarball": "https://registry.npmjs.org/react-dates/-/react-dates-10.1.1.tgz"
    },
    "gitHead": "782b5f3c8e3ebff91dbbc126c0503e1acba7c432",
    "greenkeeper": {
        "ignore": [
            "webpack"
        ]
    },
    "homepage": "https://github.com/airbnb/react-dates#readme",
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "ljharb"
        }
    ],
    "name": "react-dates",
    "optionalDependencies": {},
    "peerDependencies": {
        "moment": "(2.10 - 2.14 || ^2.15.1) && < 2.18.0",
        "react": ">=0.14",
        "react-dom": ">=0.14",
        "react-addons-shallow-compare": ">=0.14"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/airbnb/react-dates.git"
    },
    "scripts": {
        "build": "npm run clean && npm run build:js && npm run build:css && npm run build:svg",
        "build:css": "node-sass css/styles.scss lib/css/_datepicker.css",
        "build:js": "babel src/ -d lib/ --ignore src/components",
        "build:svg": "webpack",
        "check-changelog": "expr $(git status --porcelain 2>/dev/null| grep \"^\\s*M.*CHANGELOG.md\" | wc -l) >/dev/null || (echo 'Please edit CHANGELOG.md' && exit 1)",
        "check-only-changelog-changed": "(expr $(git status --porcelain 2>/dev/null| grep -v \"CHANGELOG.md\" | wc -l) >/dev/null && echo 'Only CHANGELOG.md may have uncommitted changes' && exit 1) || exit 0",
        "clean": "rimraf lib",
        "cover": "cross-env NODE_ENV=test node --max-old-space-size=2048 $(which nyc) npm run mocha test",
        "gh-pages": "npm run gh-pages:clean && npm run gh-pages:build && npm run gh-pages:copy-public && npm run gh-pages:publish",
        "gh-pages:build": "$(npm bin)/build-storybook -o _gh-pages",
        "gh-pages:clean": "rimraf _gh-pages",
        "gh-pages:copy-public": "cp public/* _gh-pages/$1",
        "gh-pages:publish": "$(npm bin)/git-directory-deploy --directory _gh-pages",
        "lint": "eslint --ext .js,.jsx src test",
        "mocha": "mocha ./test/_helpers",
        "postpublish": "npm run gh-pages",
        "postversion": "git commit package.json CHANGELOG.md -m \"Version $npm_package_version\" && npm run tag && git push && git push --tags && npm publish --registry=https://registry.npmjs.org/",
        "precover": "rimraf coverage",
        "prepublish": "in-publish && safe-publish-latest && npm run build || not-in-publish",
        "pretest": "npm run --silent lint",
        "preversion": "npm run test && npm run check-changelog && npm run check-only-changelog-changed",
        "react:14": "rimraf node_modules/.bin/npm && npm run react:clean && npm i react@0.14 react-dom@0.14 react-addons-test-utils@0.14",
        "react:15": "rimraf node_modules/.bin/npm && npm run react:clean && npm i react@15 react-dom@15 react-addons-test-utils@15",
        "react:clean": "rimraf node_modules/react node_modules/react-dom node_modules/react-addons-test-utils",
        "storybook": "start-storybook -p 9001 -s ./public",
        "tag": "git tag v$npm_package_version",
        "test": "npm run tests-only && npm run tests-karma",
        "tests-karma": "karma start",
        "tests-only": "npm run mocha --silent test",
        "version:major": "npm --no-git-tag-version version major",
        "version:minor": "npm --no-git-tag-version version minor",
        "version:patch": "npm --no-git-tag-version version patch"
    },
    "version": "10.1.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
