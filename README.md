# api documentation for  [video.js (v5.19.1)](http://videojs.com)  [![npm package](https://img.shields.io/npm/v/npmdoc-video.js.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-video.js) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-video.js.svg)](https://travis-ci.org/npmdoc/node-npmdoc-video.js)
#### An HTML5 and Flash video player with a common API and skin for both.

[![NPM](https://nodei.co/npm/video.js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/video.js)

[![apidoc](https://npmdoc.github.io/node-npmdoc-video.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-video.js/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-video.js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-video.js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Steve Heffernan"
    },
    "bugs": {
        "url": "https://github.com/videojs/video.js/issues"
    },
    "config": {
        "ghooks": {
            "pre-push": "npm run lint -- --errors"
        }
    },
    "copyright": "Copyright Brightcove, Inc. <https://www.brightcove.com/>",
    "dependencies": {
        "babel-runtime": "^6.9.2",
        "global": "4.3.0",
        "safe-json-parse": "4.0.0",
        "tsml": "1.0.1",
        "videojs-font": "2.0.0",
        "videojs-ie8": "1.1.2",
        "videojs-swf": "5.3.0",
        "videojs-vtt.js": "0.12.3",
        "xhr": "2.2.2"
    },
    "description": "An HTML5 and Flash video player with a common API and skin for both.",
    "devDependencies": {
        "aliasify": "^2.1.0",
        "babel-cli": "^6.11.4",
        "babel-plugin-inline-json": "^1.1.1",
        "babel-plugin-transform-es3-member-expression-literals": "^6.8.0",
        "babel-plugin-transform-es3-property-literals": "^6.8.0",
        "babel-plugin-transform-runtime": "^6.9.0",
        "babel-preset-es2015": "^6.14.0",
        "babel-register": "^6.9.0",
        "babelify": "^7.3.0",
        "blanket": "^1.1.6",
        "browserify-derequire": "^0.9.4",
        "browserify-istanbul": "^2.0.0",
        "browserify-versionify": "^1.0.4",
        "bundle-collapser": "^1.2.1",
        "chg": "^0.3.2",
        "conventional-changelog-cli": "^1.2.0",
        "conventional-changelog-videojs": "^3.0.0",
        "es5-shim": "^4.1.3",
        "es6-shim": "^0.35.1",
        "ghooks": "^1.3.2",
        "grunt": "^0.4.5",
        "grunt-accessibility": "^5.0.0",
        "grunt-babel": "^6.0.0",
        "grunt-banner": "^0.6.0",
        "grunt-browserify": "5.0.0",
        "grunt-cli": "~1.2.0",
        "grunt-concurrent": "^2.3.1",
        "grunt-contrib-clean": "^1.0.0",
        "grunt-contrib-concat": "^1.0.1",
        "grunt-contrib-connect": "~1.0.2",
        "grunt-contrib-copy": "^1.0.0",
        "grunt-contrib-cssmin": "~1.0.2",
        "grunt-contrib-uglify": "^2.0.0",
        "grunt-contrib-watch": "~1.0.0",
        "grunt-coveralls": "^1.0.0",
        "grunt-fastly": "^0.1.3",
        "grunt-github-releaser": "^0.1.17",
        "grunt-karma": "^2.0.0",
        "grunt-sass": "^2.0.0",
        "grunt-shell": "^2.0.0",
        "grunt-version": "~1.1.1",
        "grunt-videojs-languages": "0.0.4",
        "grunt-zip": "0.17.1",
        "istanbul": "^0.4.5",
        "jsdoc": "^3.4.2",
        "karma": "^1.2.0",
        "karma-browserify": "^5.1.0",
        "karma-browserstack-launcher": "^1.0.1",
        "karma-chrome-launcher": "^2.0.0",
        "karma-coverage": "^1.1.1",
        "karma-detect-browsers": "~2.2.3",
        "karma-firefox-launcher": "^1.0.0",
        "karma-ie-launcher": "^1.0.0",
        "karma-opera-launcher": "^1.0.0",
        "karma-qunit": "^1.2.0",
        "karma-safari-launcher": "^1.0.0",
        "karma-sinon": "^1.0.5",
        "load-grunt-tasks": "^3.1.0",
        "lodash": "^4.16.6",
        "markdown-table": "^1.0.0",
        "npm-run": "^4.1.0",
        "proxyquireify": "^3.0.0",
        "qunitjs": "1.23.1",
        "remark-cli": "^2.1.0",
        "remark-lint": "^5.2.0",
        "remark-toc": "^3.1.0",
        "remark-validate-links": "^5.0.0",
        "shelljs": "^0.7.5",
        "sinon": "^1.16.1",
        "time-grunt": "^1.1.1",
        "uglify-js": "~2.7.3",
        "videojs-doc-generator": "0.0.1",
        "videojs-standard": "^6.0.1",
        "webpack": "^1.13.2"
    },
    "directories": {},
    "dist": {
        "shasum": "5d6407aebd078bf4c4f94183f840a53388c34f25",
        "tarball": "https://registry.npmjs.org/video.js/-/video.js-5.19.1.tgz"
    },
    "gitHead": "3c77005bec422cb08d5f436ae5f12ca4c7099ee3",
    "homepage": "http://videojs.com",
    "keywords": [
        "flash",
        "html5",
        "player",
        "video",
        "videojs"
    ],
    "license": "Apache-2.0",
    "main": "./es5/video.js",
    "maintainers": [
        {
            "name": "gkatsev"
        }
    ],
    "name": "video.js",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/videojs/video.js.git"
    },
    "scripts": {
        "babel": "babel src/js -d es5",
        "build": "grunt dist",
        "change": "grunt chg-add",
        "changelog": "conventional-changelog -p videojs -i CHANGELOG.md -s",
        "clean": "grunt clean",
        "docs": "npm run docs:lint && npm run docs:api",
        "docs:api": "jsdoc -r src/js -d docs/api -c .jsdoc.json",
        "docs:fix": "remark --output -- './**/*.md'",
        "docs:lint": "remark -- './**/*.md'",
        "grunt": "grunt",
        "lint": "vjsstandard",
        "start": "grunt dev",
        "test": "grunt test"
    },
    "style": "./dist/video-js.css",
    "version": "5.19.1",
    "vjsstandard": {
        "ignore": [
            "**/Gruntfile.js",
            "**/es5/**",
            "**/build/**",
            "**/dist/**",
            "**/docs/**",
            "**/lang/**",
            "**/sandbox/**",
            "**/test/api/**",
            "**/test/coverage/**",
            "**/test/karma.conf.js"
        ]
    }
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module video.js](#apidoc.module.video.js)
1.  boolean <span class="apidocSignatureSpan">video.js.</span>TOUCH_ENABLED
1.  [function <span class="apidocSignatureSpan">video.</span>js (id, options, ready)](#apidoc.element.video.js.js)
1.  [function <span class="apidocSignatureSpan">video.js.</span>AudioTrack ()](#apidoc.element.video.js.AudioTrack)
1.  [function <span class="apidocSignatureSpan">video.js.</span>EventTarget ()](#apidoc.element.video.js.EventTarget)
1.  [function <span class="apidocSignatureSpan">video.js.</span>TextTrack ()](#apidoc.element.video.js.TextTrack)
1.  [function <span class="apidocSignatureSpan">video.js.</span>VideoTrack ()](#apidoc.element.video.js.VideoTrack)
1.  [function <span class="apidocSignatureSpan">video.js.</span>addClass (element, classToAdd)](#apidoc.element.video.js.addClass)
1.  [function <span class="apidocSignatureSpan">video.js.</span>addLanguage (code, data)](#apidoc.element.video.js.addLanguage)
1.  [function <span class="apidocSignatureSpan">video.js.</span>appendContent (el, content)](#apidoc.element.video.js.appendContent)
1.  [function <span class="apidocSignatureSpan">video.js.</span>computedStyle (el, prop)](#apidoc.element.video.js.computedStyle)
1.  [function <span class="apidocSignatureSpan">video.js.</span>createEl ()](#apidoc.element.video.js.createEl)
1.  [function <span class="apidocSignatureSpan">video.js.</span>createTimeRange (start, end)](#apidoc.element.video.js.createTimeRange)
1.  [function <span class="apidocSignatureSpan">video.js.</span>createTimeRanges (start, end)](#apidoc.element.video.js.createTimeRanges)
1.  [function <span class="apidocSignatureSpan">video.js.</span>emptyEl (el)](#apidoc.element.video.js.emptyEl)
1.  [function <span class="apidocSignatureSpan">video.js.</span>extend (superClass)](#apidoc.element.video.js.extend)
1.  [function <span class="apidocSignatureSpan">video.js.</span>formatTime (seconds)](#apidoc.element.video.js.formatTime)
1.  [function <span class="apidocSignatureSpan">video.js.</span>getAttributes (tag)](#apidoc.element.video.js.getAttributes)
1.  [function <span class="apidocSignatureSpan">video.js.</span>getComponent (name)](#apidoc.element.video.js.getComponent)
1.  [function <span class="apidocSignatureSpan">video.js.</span>getPlayers ()](#apidoc.element.video.js.getPlayers)
1.  [function <span class="apidocSignatureSpan">video.js.</span>getTech (name)](#apidoc.element.video.js.getTech)
1.  [function <span class="apidocSignatureSpan">video.js.</span>hasClass (element, classToCheck)](#apidoc.element.video.js.hasClass)
1.  [function <span class="apidocSignatureSpan">video.js.</span>hook (type, fn)](#apidoc.element.video.js.hook)
1.  [function <span class="apidocSignatureSpan">video.js.</span>hooks (type, fn)](#apidoc.element.video.js.hooks)
1.  [function <span class="apidocSignatureSpan">video.js.</span>insertContent (el, content)](#apidoc.element.video.js.insertContent)
1.  [function <span class="apidocSignatureSpan">video.js.</span>isCrossOrigin (url)](#apidoc.element.video.js.isCrossOrigin)
1.  [function <span class="apidocSignatureSpan">video.js.</span>isEl (value)](#apidoc.element.video.js.isEl)
1.  [function <span class="apidocSignatureSpan">video.js.</span>isTextNode (value)](#apidoc.element.video.js.isTextNode)
1.  [function <span class="apidocSignatureSpan">video.js.</span>js.EventTarget ()](#apidoc.element.video.js.js.EventTarget)
1.  [function <span class="apidocSignatureSpan">video.js.</span>js.TextTrack ()](#apidoc.element.video.js.js.TextTrack)
1.  [function <span class="apidocSignatureSpan">video.js.</span>js.log ()](#apidoc.element.video.js.js.log)
1.  [function <span class="apidocSignatureSpan">video.js.</span>js.xhr (uri, options, callback)](#apidoc.element.video.js.js.xhr)
1.  [function <span class="apidocSignatureSpan">video.js.</span>log ()](#apidoc.element.video.js.log)
1.  [function <span class="apidocSignatureSpan">video.js.</span>mergeOptions ()](#apidoc.element.video.js.mergeOptions)
1.  [function <span class="apidocSignatureSpan">video.js.</span>off (elem, type, fn)](#apidoc.element.video.js.off)
1.  [function <span class="apidocSignatureSpan">video.js.</span>on (elem, type, fn)](#apidoc.element.video.js.on)
1.  [function <span class="apidocSignatureSpan">video.js.</span>one (elem, type, fn)](#apidoc.element.video.js.one)
1.  [function <span class="apidocSignatureSpan">video.js.</span>parseUrl (url)](#apidoc.element.video.js.parseUrl)
1.  [function <span class="apidocSignatureSpan">video.js.</span>plugin (name, init)](#apidoc.element.video.js.plugin)
1.  [function <span class="apidocSignatureSpan">video.js.</span>registerComponent (name, comp)](#apidoc.element.video.js.registerComponent)
1.  [function <span class="apidocSignatureSpan">video.js.</span>registerTech (name, tech)](#apidoc.element.video.js.registerTech)
1.  [function <span class="apidocSignatureSpan">video.js.</span>removeClass (element, classToRemove)](#apidoc.element.video.js.removeClass)
1.  [function <span class="apidocSignatureSpan">video.js.</span>removeHook (type, fn)](#apidoc.element.video.js.removeHook)
1.  [function <span class="apidocSignatureSpan">video.js.</span>setAttributes (el, attributes)](#apidoc.element.video.js.setAttributes)
1.  [function <span class="apidocSignatureSpan">video.js.</span>toString ()](#apidoc.element.video.js.toString)
1.  [function <span class="apidocSignatureSpan">video.js.</span>toggleClass (element, classToToggle, predicate)](#apidoc.element.video.js.toggleClass)
1.  [function <span class="apidocSignatureSpan">video.js.</span>trigger (elem, event, hash)](#apidoc.element.video.js.trigger)
1.  [function <span class="apidocSignatureSpan">video.js.</span>xhr (uri, options, callback)](#apidoc.element.video.js.xhr)
1.  object <span class="apidocSignatureSpan">video.js.</span>browser
1.  object <span class="apidocSignatureSpan">video.js.</span>hooks_
1.  object <span class="apidocSignatureSpan">video.js.</span>js.EventTarget.prototype
1.  object <span class="apidocSignatureSpan">video.js.</span>js.TextTrack.prototype
1.  object <span class="apidocSignatureSpan">video.js.</span>js.big_play_button
1.  object <span class="apidocSignatureSpan">video.js.</span>options
1.  object <span class="apidocSignatureSpan">video.js.</span>players
1.  string <span class="apidocSignatureSpan">video.js.</span>VERSION

#### [module video.js.EventTarget](#apidoc.module.video.js.EventTarget)
1.  [function <span class="apidocSignatureSpan">video.js.</span>EventTarget ()](#apidoc.element.video.js.EventTarget.EventTarget)

#### [module video.js.EventTarget.prototype](#apidoc.module.video.js.EventTarget.prototype)
1.  [function <span class="apidocSignatureSpan">video.js.EventTarget.prototype.</span>addEventListener (type, fn)](#apidoc.element.video.js.EventTarget.prototype.addEventListener)
1.  [function <span class="apidocSignatureSpan">video.js.EventTarget.prototype.</span>dispatchEvent (event)](#apidoc.element.video.js.EventTarget.prototype.dispatchEvent)
1.  [function <span class="apidocSignatureSpan">video.js.EventTarget.prototype.</span>off (type, fn)](#apidoc.element.video.js.EventTarget.prototype.off)
1.  [function <span class="apidocSignatureSpan">video.js.EventTarget.prototype.</span>on (type, fn)](#apidoc.element.video.js.EventTarget.prototype.on)
1.  [function <span class="apidocSignatureSpan">video.js.EventTarget.prototype.</span>one (type, fn)](#apidoc.element.video.js.EventTarget.prototype.one)
1.  [function <span class="apidocSignatureSpan">video.js.EventTarget.prototype.</span>removeEventListener (type, fn)](#apidoc.element.video.js.EventTarget.prototype.removeEventListener)
1.  [function <span class="apidocSignatureSpan">video.js.EventTarget.prototype.</span>trigger (event)](#apidoc.element.video.js.EventTarget.prototype.trigger)
1.  object <span class="apidocSignatureSpan">video.js.EventTarget.prototype.</span>allowedEvents_

#### [module video.js.TextTrack](#apidoc.module.video.js.TextTrack)
1.  [function <span class="apidocSignatureSpan">video.js.</span>TextTrack ()](#apidoc.element.video.js.TextTrack.TextTrack)

#### [module video.js.TextTrack.prototype](#apidoc.module.video.js.TextTrack.prototype)
1.  [function <span class="apidocSignatureSpan">video.js.TextTrack.prototype.</span>addCue (originalCue)](#apidoc.element.video.js.TextTrack.prototype.addCue)
1.  [function <span class="apidocSignatureSpan">video.js.TextTrack.prototype.</span>removeCue (_removeCue)](#apidoc.element.video.js.TextTrack.prototype.removeCue)
1.  object <span class="apidocSignatureSpan">video.js.TextTrack.prototype.</span>allowedEvents_

#### [module video.js.big_play_button](#apidoc.module.video.js.big_play_button)
1.  boolean <span class="apidocSignatureSpan">video.js.big_play_button.</span>__esModule
1.  [function <span class="apidocSignatureSpan">video.js.big_play_button.</span>default ()](#apidoc.element.video.js.big_play_button.default)

#### [module video.js.log](#apidoc.module.video.js.log)
1.  [function <span class="apidocSignatureSpan">video.js.</span>log ()](#apidoc.element.video.js.log.log)
1.  [function <span class="apidocSignatureSpan">video.js.log.</span>error ()](#apidoc.element.video.js.log.error)
1.  [function <span class="apidocSignatureSpan">video.js.log.</span>warn ()](#apidoc.element.video.js.log.warn)
1.  object <span class="apidocSignatureSpan">video.js.log.</span>history

#### [module video.js.xhr](#apidoc.module.video.js.xhr)
1.  [function <span class="apidocSignatureSpan">video.js.</span>xhr (uri, options, callback)](#apidoc.element.video.js.xhr.xhr)
1.  [function <span class="apidocSignatureSpan">video.js.xhr.</span>XMLHttpRequest ()](#apidoc.element.video.js.xhr.XMLHttpRequest)
1.  [function <span class="apidocSignatureSpan">video.js.xhr.</span>del (uri, options, callback)](#apidoc.element.video.js.xhr.del)
1.  [function <span class="apidocSignatureSpan">video.js.xhr.</span>get (uri, options, callback)](#apidoc.element.video.js.xhr.get)
1.  [function <span class="apidocSignatureSpan">video.js.xhr.</span>head (uri, options, callback)](#apidoc.element.video.js.xhr.head)
1.  [function <span class="apidocSignatureSpan">video.js.xhr.</span>patch (uri, options, callback)](#apidoc.element.video.js.xhr.patch)
1.  [function <span class="apidocSignatureSpan">video.js.xhr.</span>post (uri, options, callback)](#apidoc.element.video.js.xhr.post)
1.  [function <span class="apidocSignatureSpan">video.js.xhr.</span>put (uri, options, callback)](#apidoc.element.video.js.xhr.put)



# <a name="apidoc.module.video.js"></a>[module video.js](#apidoc.module.video.js)

#### <a name="apidoc.element.video.js.js"></a>[function <span class="apidocSignatureSpan">video.</span>js (id, options, ready)](#apidoc.element.video.js.js)
- description and source-code
```javascript
function videojs(id, options, ready) {
  var tag = void 0;

  // Allow for element or ID to be passed in
  // String ID
  if (typeof id === 'string') {

    // Adjust for jQuery ID syntax
    if (id.indexOf('#') === 0) {
      id = id.slice(1);
    }

    // If a player instance has already been created for this ID return it.
    if (videojs.getPlayers()[id]) {

      // If options or ready funtion are passed, warn
      if (options) {
        _log2['default'].warn('Player "' + id + '" is already initialised. Options will not be applied.');
      }

      if (ready) {
        videojs.getPlayers()[id].ready(ready);
      }

      return videojs.getPlayers()[id];
    }

    // Otherwise get element for ID
    tag = Dom.getEl(id);

    // ID is a media element
  } else {
    tag = id;
  }

  // Check for a useable element
  // re: nodeName, could be a box div also
  if (!tag || !tag.nodeName) {
    throw new TypeError('The element or ID supplied is not valid. (videojs)');
  }

  // Element may have a player attr referring to an already created player instance.
  // If so return that otherwise set up a new player below
  if (tag.player || _player2['default'].players[tag.playerId]) {
    return tag.player || _player2['default'].players[tag.playerId];
  }

  options = options || {};

  videojs.hooks('beforesetup').forEach(function (hookFunction) {
    var opts = hookFunction(tag, (0, _mergeOptions3['default'])(options));

    if (!(0, _obj.isObject)(opts) || Array.isArray(opts)) {
      _log2['default'].error('please return an object in beforesetup hooks');
      return;
    }

    options = (0, _mergeOptions3['default'])(options, opts);
  });

  var PlayerComponent = _component2['default'].getComponent('Player');
  // If not, set up a new player
  var player = new PlayerComponent(tag, options, ready);

  videojs.hooks('setup').forEach(function (hookFunction) {
    return hookFunction(player);
  });

  return player;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.AudioTrack"></a>[function <span class="apidocSignatureSpan">video.js.</span>AudioTrack ()](#apidoc.element.video.js.AudioTrack)
- description and source-code
```javascript
function AudioTrack() {
  var _this, _ret;

  var options = arguments.length > 0 && arguments[0] !== undefined ? arguments[0] : {};

  _classCallCheck(this, AudioTrack);

  var settings = (0, _mergeOptions2['default'])(options, {
    kind: _trackEnums.AudioTrackKind[options.kind] || ''
  });
  // on IE8 this will be a document element
  // for every other browser this will be a normal object
  var track = (_this = _possibleConstructorReturn(this, _Track.call(this, settings)), _this);
  var enabled = false;

  if (browser.IS_IE8) {
    for (var prop in AudioTrack.prototype) {
      if (prop !== 'constructor') {
        track[prop] = AudioTrack.prototype[prop];
      }
    }
  }
<span class="apidocCodeCommentSpan">  /**
   * @member {boolean} enabled
   *         If this 'AudioTrack' is enabled or not. When setting this will
   *         fire {@link AudioTrack#enabledchange} if the state of enabled is changed.
   *
   * @fires VideoTrack#selectedchange
   */
</span>  Object.defineProperty(track, 'enabled', {
    get: function get() {
      return enabled;
    },
    set: function set(newEnabled) {
      // an invalid or unchanged value
      if (typeof newEnabled !== 'boolean' || newEnabled === enabled) {
        return;
      }
      enabled = newEnabled;

      /**
       * An event that fires when enabled changes on this track. This allows
       * the AudioTrackList that holds this track to act accordingly.
       *
       * > Note: This is not part of the spec! Native tracks will do
       *         this internally without an event.
       *
       * @event AudioTrack#enabledchange
       * @type {EventTarget~Event}
       */
      this.trigger('enabledchange');
    }
  });

  // if the user sets this track to selected then
  // set selected to that true value otherwise
  // we keep it false
  if (settings.enabled) {
    track.enabled = settings.enabled;
  }
  track.loaded_ = true;

  return _ret = track, _possibleConstructorReturn(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.EventTarget"></a>[function <span class="apidocSignatureSpan">video.js.</span>EventTarget ()](#apidoc.element.video.js.EventTarget)
- description and source-code
```javascript
function EventTarget() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.TextTrack"></a>[function <span class="apidocSignatureSpan">video.js.</span>TextTrack ()](#apidoc.element.video.js.TextTrack)
- description and source-code
```javascript
function TextTrack() {
  var _this, _ret;

  var options = arguments.length > 0 && arguments[0] !== undefined ? arguments[0] : {};

  _classCallCheck(this, TextTrack);

  if (!options.tech) {
    throw new Error('A tech was not provided.');
  }

  var settings = (0, _mergeOptions2['default'])(options, {
    kind: _trackEnums.TextTrackKind[options.kind] || 'subtitles',
    language: options.language || options.srclang || ''
  });
  var mode = _trackEnums.TextTrackMode[settings.mode] || 'disabled';
  var default_ = settings['default'];

  if (settings.kind === 'metadata' || settings.kind === 'chapters') {
    mode = 'hidden';
  }
  // on IE8 this will be a document element
  // for every other browser this will be a normal object
  var tt = (_this = _possibleConstructorReturn(this, _Track.call(this, settings)), _this);

  tt.tech_ = settings.tech;

  if (browser.IS_IE8) {
    for (var prop in TextTrack.prototype) {
      if (prop !== 'constructor') {
        tt[prop] = TextTrack.prototype[prop];
      }
    }
  }

  tt.cues_ = [];
  tt.activeCues_ = [];

  var cues = new _textTrackCueList2['default'](tt.cues_);
  var activeCues = new _textTrackCueList2['default'](tt.activeCues_);
  var changed = false;
  var timeupdateHandler = Fn.bind(tt, function () {

    // Accessing this.activeCues for the side-effects of updating itself
    // due to it's nature as a getter function. Do not remove or cues will
    // stop updating!
<span class="apidocCodeCommentSpan">    /* eslint-disable no-unused-expressions */
</span>    this.activeCues;
    /* eslint-enable no-unused-expressions */
    if (changed) {
      this.trigger('cuechange');
      changed = false;
    }
  });

  if (mode !== 'disabled') {
    tt.tech_.ready(function () {
      tt.tech_.on('timeupdate', timeupdateHandler);
    }, true);
  }

  /**
   * @member {boolean} default
   *         If this track was set to be on or off by default. Cannot be changed after
   *         creation.
   *
   * @readonly
   */
  Object.defineProperty(tt, 'default', {
    get: function get() {
      return default_;
    },
    set: function set() {}
  });

  /**
   * @member {string} mode
   *         Set the mode of this TextTrack to a valid {@link TextTrack~Mode}. Will
   *         not be set if setting to an invalid mode.
   *
   * @fires TextTrack#modechange
   */
  Object.defineProperty(tt, 'mode', {
    get: function get() {
      return mode;
    },
    set: function set(newMode) {
      var _this2 = this;

      if (!_trackEnums.TextTrackMode[newMode]) {
        return;
      }
      mode = newMode;
      if (mode === 'showing') {
        this.tech_.ready(function () {
          _this2.tech_.on('timeupdate', timeupdateHandler);
        }, true);
      }
      /**
       * An event that fires when mode changes on this track. This allows
       * the TextTrackList that holds this track to act accordingly.
       *
       * > Note: This is not part of the spec!
       *
       * @event TextTrack#modechange
       * @type {EventTarget~Event}
       */
      this.trigger('modechange');
    }
  });

  /**
   * @member {TextTrackCueList} cues
   *         The text track cue list for this TextTrack.
   */
  Object.defineProperty(tt, 'cues', {
    get: function get() {
      if (!this.loaded_) {
        return null;
      }

      return cues;
    },
    set: function set() {}
  });

  /**
   * @member {TextTrackCueList} activeCues
   *         The list text track cues that are currently active for this TextTrack.
   */
  Object.defineProperty(tt, 'activeCues', {
    get: function get() {
      if (!this.loaded_) {
        return null;
      }

      // nothing to do
      if (this.cues.length === 0) {
        return activeCues;
      }

      var ct = this.tech_.currentTime();
      var active = [];

      for (var i = 0, l = this.cues.length; i < l; i++) {
        var cue = this.cues[i];

        if (cue.startTime <= ct && cue.endTime >= ct) {
          active.push(cue);
        } else if (cue.startTime === cue.endTime && cue.startTime <= ct && cue.startTime + 0.5 >= ct) {
          active.push(cue);
        }
      }

      chang ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.VideoTrack"></a>[function <span class="apidocSignatureSpan">video.js.</span>VideoTrack ()](#apidoc.element.video.js.VideoTrack)
- description and source-code
```javascript
function VideoTrack() {
  var _this, _ret;

  var options = arguments.length > 0 && arguments[0] !== undefined ? arguments[0] : {};

  _classCallCheck(this, VideoTrack);

  var settings = (0, _mergeOptions2['default'])(options, {
    kind: _trackEnums.VideoTrackKind[options.kind] || ''
  });

  // on IE8 this will be a document element
  // for every other browser this will be a normal object
  var track = (_this = _possibleConstructorReturn(this, _Track.call(this, settings)), _this);
  var selected = false;

  if (browser.IS_IE8) {
    for (var prop in VideoTrack.prototype) {
      if (prop !== 'constructor') {
        track[prop] = VideoTrack.prototype[prop];
      }
    }
  }

<span class="apidocCodeCommentSpan">  /**
   * @member {boolean} selected
   *         If this 'VideoTrack' is selected or not. When setting this will
   *         fire {@link VideoTrack#selectedchange} if the state of selected changed.
   *
   * @fires VideoTrack#selectedchange
   */
</span>  Object.defineProperty(track, 'selected', {
    get: function get() {
      return selected;
    },
    set: function set(newSelected) {
      // an invalid or unchanged value
      if (typeof newSelected !== 'boolean' || newSelected === selected) {
        return;
      }
      selected = newSelected;

      /**
       * An event that fires when selected changes on this track. This allows
       * the VideoTrackList that holds this track to act accordingly.
       *
       * > Note: This is not part of the spec! Native tracks will do
       *         this internally without an event.
       *
       * @event VideoTrack#selectedchange
       * @type {EventTarget~Event}
       */
      this.trigger('selectedchange');
    }
  });

  // if the user sets this track to selected then
  // set selected to that true value otherwise
  // we keep it false
  if (settings.selected) {
    track.selected = settings.selected;
  }

  return _ret = track, _possibleConstructorReturn(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.addClass"></a>[function <span class="apidocSignatureSpan">video.js.</span>addClass (element, classToAdd)](#apidoc.element.video.js.addClass)
- description and source-code
```javascript
function addElClass(element, classToAdd) {
  if (element.classList) {
    element.classList.add(classToAdd);

    // Don't need to 'throwIfWhitespace' here because 'hasElClass' will do it
    // in the case of classList not being supported.
  } else if (!hasElClass(element, classToAdd)) {
    element.className = (element.className + ' ' + classToAdd).trim();
  }

  return element;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.addLanguage"></a>[function <span class="apidocSignatureSpan">video.js.</span>addLanguage (code, data)](#apidoc.element.video.js.addLanguage)
- description and source-code
```javascript
addLanguage = function (code, data) {
  var _mergeOptions;

  code = ('' + code).toLowerCase();

  videojs.options.languages = (0, _mergeOptions3['default'])(videojs.options.languages, (_mergeOptions = {}, _mergeOptions[code] =
data, _mergeOptions));

  return videojs.options.languages[code];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.appendContent"></a>[function <span class="apidocSignatureSpan">video.js.</span>appendContent (el, content)](#apidoc.element.video.js.appendContent)
- description and source-code
```javascript
function appendContent(el, content) {
  normalizeContent(content).forEach(function (node) {
    return el.appendChild(node);
  });
  return el;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.computedStyle"></a>[function <span class="apidocSignatureSpan">video.js.</span>computedStyle (el, prop)](#apidoc.element.video.js.computedStyle)
- description and source-code
```javascript
function computedStyle(el, prop) {
  if (!el || !prop) {
    return '';
  }

  if (typeof _window2['default'].getComputedStyle === 'function') {
    var cs = _window2['default'].getComputedStyle(el);

    return cs ? cs[prop] : '';
  }

  return el.currentStyle[prop] || '';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.createEl"></a>[function <span class="apidocSignatureSpan">video.js.</span>createEl ()](#apidoc.element.video.js.createEl)
- description and source-code
```javascript
function createEl() {
  var tagName = arguments.length > 0 && arguments[0] !== undefined ? arguments[0] : 'div';
  var properties = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : {};
  var attributes = arguments.length > 2 && arguments[2] !== undefined ? arguments[2] : {};
  var content = arguments[3];

  var el = _document2['default'].createElement(tagName);

  Object.getOwnPropertyNames(properties).forEach(function (propName) {
    var val = properties[propName];

    // See #2176
    // We originally were accepting both properties and attributes in the
    // same object, but that doesn't work so well.
    if (propName.indexOf('aria-') !== -1 || propName === 'role' || propName === 'type') {
      _log2['default'].warn((0, _tsml2['default'])(_templateObject, propName, val));
      el.setAttribute(propName, val);

      // Handle textContent since it's not supported everywhere and we have a
      // method for it.
    } else if (propName === 'textContent') {
      textContent(el, val);
    } else {
      el[propName] = val;
    }
  });

  Object.getOwnPropertyNames(attributes).forEach(function (attrName) {
    el.setAttribute(attrName, attributes[attrName]);
  });

  if (content) {
    appendContent(el, content);
  }

  return el;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.createTimeRange"></a>[function <span class="apidocSignatureSpan">video.js.</span>createTimeRange (start, end)](#apidoc.element.video.js.createTimeRange)
- description and source-code
```javascript
function createTimeRanges(start, end) {
  if (Array.isArray(start)) {
    return createTimeRangesObj(start);
  } else if (start === undefined || end === undefined) {
    return createTimeRangesObj();
  }
  return createTimeRangesObj([[start, end]]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.createTimeRanges"></a>[function <span class="apidocSignatureSpan">video.js.</span>createTimeRanges (start, end)](#apidoc.element.video.js.createTimeRanges)
- description and source-code
```javascript
function createTimeRanges(start, end) {
  if (Array.isArray(start)) {
    return createTimeRangesObj(start);
  } else if (start === undefined || end === undefined) {
    return createTimeRangesObj();
  }
  return createTimeRangesObj([[start, end]]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.emptyEl"></a>[function <span class="apidocSignatureSpan">video.js.</span>emptyEl (el)](#apidoc.element.video.js.emptyEl)
- description and source-code
```javascript
function emptyEl(el) {
  while (el.firstChild) {
    el.removeChild(el.firstChild);
  }
  return el;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.extend"></a>[function <span class="apidocSignatureSpan">video.js.</span>extend (superClass)](#apidoc.element.video.js.extend)
- description and source-code
```javascript
function extendFn(superClass) {
  var subClassMethods = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : {};

  var subClass = function subClass() {
    superClass.apply(this, arguments);
  };

  var methods = {};

  if ((0, _obj.isObject)(subClassMethods)) {
    if (typeof subClassMethods.init === 'function') {
      _log2['default'].warn('Constructor logic via init() is deprecated; please use constructor() instead.');
      subClassMethods.constructor = subClassMethods.init;
    }
    if (subClassMethods.constructor !== Object.prototype.constructor) {
      subClass = subClassMethods.constructor;
    }
    methods = subClassMethods;
  } else if (typeof subClassMethods === 'function') {
    subClass = subClassMethods;
  }

  _inherits(subClass, superClass);

  // Extend subObj's prototype with functions and other properties from props
  for (var name in methods) {
    if (methods.hasOwnProperty(name)) {
      subClass.prototype[name] = methods[name];
    }
  }

  return subClass;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.formatTime"></a>[function <span class="apidocSignatureSpan">video.js.</span>formatTime (seconds)](#apidoc.element.video.js.formatTime)
- description and source-code
```javascript
function formatTime(seconds) {
  var guide = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : seconds;

  seconds = seconds < 0 ? 0 : seconds;
  var s = Math.floor(seconds % 60);
  var m = Math.floor(seconds / 60 % 60);
  var h = Math.floor(seconds / 3600);
  var gm = Math.floor(guide / 60 % 60);
  var gh = Math.floor(guide / 3600);

  // handle invalid times
  if (isNaN(seconds) || seconds === Infinity) {
    // '-' is false for all relational operators (e.g. <, >=) so this setting
    // will add the minimum number of fields specified by the guide
    h = m = s = '-';
  }

  // Check if we need to show hours
  h = h > 0 || gh > 0 ? h + ':' : '';

  // If hours are showing, we may need to add a leading zero.
  // Always show at least one digit of minutes.
  m = ((h || gm >= 10) && m < 10 ? '0' + m : m) + ':';

  // Check if leading zero is need for seconds
  s = s < 10 ? '0' + s : s;

  return h + m + s;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.getAttributes"></a>[function <span class="apidocSignatureSpan">video.js.</span>getAttributes (tag)](#apidoc.element.video.js.getAttributes)
- description and source-code
```javascript
function getElAttributes(tag) {
  var obj = {};

  // known boolean attributes
  // we can check for matching boolean properties, but older browsers
  // won't know about HTML5 boolean attributes that we still read from
  var knownBooleans = ',' + 'autoplay,controls,loop,muted,default' + ',';

  if (tag && tag.attributes && tag.attributes.length > 0) {
    var attrs = tag.attributes;

    for (var i = attrs.length - 1; i >= 0; i--) {
      var attrName = attrs[i].name;
      var attrVal = attrs[i].value;

      // check for known booleans
      // the matching element property will return a value for typeof
      if (typeof tag[attrName] === 'boolean' || knownBooleans.indexOf(',' + attrName + ',') !== -1) {
        // the value of an included boolean attribute is typically an empty
        // string ('') which would equal false if we just check for a false value.
        // we also don't want support bad code like autoplay='false'
        attrVal = attrVal !== null ? true : false;
      }

      obj[attrName] = attrVal;
    }
  }

  return obj;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.getComponent"></a>[function <span class="apidocSignatureSpan">video.js.</span>getComponent (name)](#apidoc.element.video.js.getComponent)
- description and source-code
```javascript
function getComponent(name) {
  if (!name) {
    return;
  }

  name = (0, _toTitleCase2['default'])(name);

  if (Component.components_ && Component.components_[name]) {
    return Component.components_[name];
  }

  if (_window2['default'] && _window2['default'].videojs && _window2['default'].videojs[name]) {
    _log2['default'].warn('The ' + name + ' component was added to the videojs object when it should be registered using videojs
.registerComponent(name, component)');

    return _window2['default'].videojs[name];
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.getPlayers"></a>[function <span class="apidocSignatureSpan">video.js.</span>getPlayers ()](#apidoc.element.video.js.getPlayers)
- description and source-code
```javascript
getPlayers = function () {
  return _player2['default'].players;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.getTech"></a>[function <span class="apidocSignatureSpan">video.js.</span>getTech (name)](#apidoc.element.video.js.getTech)
- description and source-code
```javascript
function getTech(name) {
  if (Tech.techs_ && Tech.techs_[name]) {
    return Tech.techs_[name];
  }

  if (_window2['default'] && _window2['default'].videojs && _window2['default'].videojs[name]) {
    _log2['default'].warn('The ' + name + ' tech was added to the videojs object when it should be registered using videojs.registerTech
(name, tech)');
    return _window2['default'].videojs[name];
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.hasClass"></a>[function <span class="apidocSignatureSpan">video.js.</span>hasClass (element, classToCheck)](#apidoc.element.video.js.hasClass)
- description and source-code
```javascript
function hasElClass(element, classToCheck) {
  throwIfWhitespace(classToCheck);
  if (element.classList) {
    return element.classList.contains(classToCheck);
  }
  return classRegExp(classToCheck).test(element.className);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.hook"></a>[function <span class="apidocSignatureSpan">video.js.</span>hook (type, fn)](#apidoc.element.video.js.hook)
- description and source-code
```javascript
hook = function (type, fn) {
  videojs.hooks(type, fn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.hooks"></a>[function <span class="apidocSignatureSpan">video.js.</span>hooks (type, fn)](#apidoc.element.video.js.hooks)
- description and source-code
```javascript
hooks = function (type, fn) {
  videojs.hooks_[type] = videojs.hooks_[type] || [];
  if (fn) {
    videojs.hooks_[type] = videojs.hooks_[type].concat(fn);
  }
  return videojs.hooks_[type];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.insertContent"></a>[function <span class="apidocSignatureSpan">video.js.</span>insertContent (el, content)](#apidoc.element.video.js.insertContent)
- description and source-code
```javascript
function insertContent(el, content) {
  return appendContent(emptyEl(el), content);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.isCrossOrigin"></a>[function <span class="apidocSignatureSpan">video.js.</span>isCrossOrigin (url)](#apidoc.element.video.js.isCrossOrigin)
- description and source-code
```javascript
function isCrossOrigin(url) {
  var winLoc = _window2['default'].location;
  var urlInfo = parseUrl(url);

  // IE8 protocol relative urls will return ':' for protocol
  var srcProtocol = urlInfo.protocol === ':' ? winLoc.protocol : urlInfo.protocol;

  // Check if url is for another domain/origin
  // IE8 doesn't know location.origin, so we won't rely on it here
  var crossOrigin = srcProtocol + urlInfo.host !== winLoc.protocol + winLoc.host;

  return crossOrigin;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.isEl"></a>[function <span class="apidocSignatureSpan">video.js.</span>isEl (value)](#apidoc.element.video.js.isEl)
- description and source-code
```javascript
function isEl(value) {
  return (0, _obj.isObject)(value) && value.nodeType === 1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.isTextNode"></a>[function <span class="apidocSignatureSpan">video.js.</span>isTextNode (value)](#apidoc.element.video.js.isTextNode)
- description and source-code
```javascript
function isTextNode(value) {
  return (0, _obj.isObject)(value) && value.nodeType === 3;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.js.EventTarget"></a>[function <span class="apidocSignatureSpan">video.js.</span>js.EventTarget ()](#apidoc.element.video.js.js.EventTarget)
- description and source-code
```javascript
function EventTarget() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.js.TextTrack"></a>[function <span class="apidocSignatureSpan">video.js.</span>js.TextTrack ()](#apidoc.element.video.js.js.TextTrack)
- description and source-code
```javascript
function TextTrack() {
  var _this, _ret;

  var options = arguments.length > 0 && arguments[0] !== undefined ? arguments[0] : {};

  _classCallCheck(this, TextTrack);

  if (!options.tech) {
    throw new Error('A tech was not provided.');
  }

  var settings = (0, _mergeOptions2['default'])(options, {
    kind: _trackEnums.TextTrackKind[options.kind] || 'subtitles',
    language: options.language || options.srclang || ''
  });
  var mode = _trackEnums.TextTrackMode[settings.mode] || 'disabled';
  var default_ = settings['default'];

  if (settings.kind === 'metadata' || settings.kind === 'chapters') {
    mode = 'hidden';
  }
  // on IE8 this will be a document element
  // for every other browser this will be a normal object
  var tt = (_this = _possibleConstructorReturn(this, _Track.call(this, settings)), _this);

  tt.tech_ = settings.tech;

  if (browser.IS_IE8) {
    for (var prop in TextTrack.prototype) {
      if (prop !== 'constructor') {
        tt[prop] = TextTrack.prototype[prop];
      }
    }
  }

  tt.cues_ = [];
  tt.activeCues_ = [];

  var cues = new _textTrackCueList2['default'](tt.cues_);
  var activeCues = new _textTrackCueList2['default'](tt.activeCues_);
  var changed = false;
  var timeupdateHandler = Fn.bind(tt, function () {

    // Accessing this.activeCues for the side-effects of updating itself
    // due to it's nature as a getter function. Do not remove or cues will
    // stop updating!
<span class="apidocCodeCommentSpan">    /* eslint-disable no-unused-expressions */
</span>    this.activeCues;
    /* eslint-enable no-unused-expressions */
    if (changed) {
      this.trigger('cuechange');
      changed = false;
    }
  });

  if (mode !== 'disabled') {
    tt.tech_.ready(function () {
      tt.tech_.on('timeupdate', timeupdateHandler);
    }, true);
  }

  /**
   * @member {boolean} default
   *         If this track was set to be on or off by default. Cannot be changed after
   *         creation.
   *
   * @readonly
   */
  Object.defineProperty(tt, 'default', {
    get: function get() {
      return default_;
    },
    set: function set() {}
  });

  /**
   * @member {string} mode
   *         Set the mode of this TextTrack to a valid {@link TextTrack~Mode}. Will
   *         not be set if setting to an invalid mode.
   *
   * @fires TextTrack#modechange
   */
  Object.defineProperty(tt, 'mode', {
    get: function get() {
      return mode;
    },
    set: function set(newMode) {
      var _this2 = this;

      if (!_trackEnums.TextTrackMode[newMode]) {
        return;
      }
      mode = newMode;
      if (mode === 'showing') {
        this.tech_.ready(function () {
          _this2.tech_.on('timeupdate', timeupdateHandler);
        }, true);
      }
      /**
       * An event that fires when mode changes on this track. This allows
       * the TextTrackList that holds this track to act accordingly.
       *
       * > Note: This is not part of the spec!
       *
       * @event TextTrack#modechange
       * @type {EventTarget~Event}
       */
      this.trigger('modechange');
    }
  });

  /**
   * @member {TextTrackCueList} cues
   *         The text track cue list for this TextTrack.
   */
  Object.defineProperty(tt, 'cues', {
    get: function get() {
      if (!this.loaded_) {
        return null;
      }

      return cues;
    },
    set: function set() {}
  });

  /**
   * @member {TextTrackCueList} activeCues
   *         The list text track cues that are currently active for this TextTrack.
   */
  Object.defineProperty(tt, 'activeCues', {
    get: function get() {
      if (!this.loaded_) {
        return null;
      }

      // nothing to do
      if (this.cues.length === 0) {
        return activeCues;
      }

      var ct = this.tech_.currentTime();
      var active = [];

      for (var i = 0, l = this.cues.length; i < l; i++) {
        var cue = this.cues[i];

        if (cue.startTime <= ct && cue.endTime >= ct) {
          active.push(cue);
        } else if (cue.startTime === cue.endTime && cue.startTime <= ct && cue.startTime + 0.5 >= ct) {
          active.push(cue);
        }
      }

      chang ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.js.log"></a>[function <span class="apidocSignatureSpan">video.js.</span>js.log ()](#apidoc.element.video.js.js.log)
- description and source-code
```javascript
function log() {
  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  logByType('log', args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.js.xhr"></a>[function <span class="apidocSignatureSpan">video.js.</span>js.xhr (uri, options, callback)](#apidoc.element.video.js.js.xhr)
- description and source-code
```javascript
function createXHR(uri, options, callback) {
    options = initParams(uri, options, callback)
    return _createXHR(options)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.log"></a>[function <span class="apidocSignatureSpan">video.js.</span>log ()](#apidoc.element.video.js.log)
- description and source-code
```javascript
function log() {
  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  logByType('log', args);
}
```
- example usage
```shell
...
The 'videojs' function also accepts an 'options' object and a callback to be invoked
 when the player is ready:

'''js
var options = {};

var player = videojs('my-player', options, function onPlayerReady() {
videojs.log('Your player is ready!');

// In this context, 'this' is the player that was created by Video.js.
this.play();

// How about an event listener?
this.on('ended', function() {
  videojs.log('Awww...over so soon?!');
...
```

#### <a name="apidoc.element.video.js.mergeOptions"></a>[function <span class="apidocSignatureSpan">video.js.</span>mergeOptions ()](#apidoc.element.video.js.mergeOptions)
- description and source-code
```javascript
function mergeOptions() {
  var result = {};

  for (var _len = arguments.length, sources = Array(_len), _key = 0; _key < _len; _key++) {
    sources[_key] = arguments[_key];
  }

  sources.forEach(function (source) {
    if (!source) {
      return;
    }

    (0, _obj.each)(source, function (value, key) {
      if (!(0, _obj.isPlain)(value)) {
        result[key] = value;
        return;
      }

      if (!(0, _obj.isPlain)(result[key])) {
        result[key] = {};
      }

      result[key] = mergeOptions(result[key], value);
    });
  });

  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.off"></a>[function <span class="apidocSignatureSpan">video.js.</span>off (elem, type, fn)](#apidoc.element.video.js.off)
- description and source-code
```javascript
function off(elem, type, fn) {
  // Don't want to add a cache object through getElData if not needed
  if (!Dom.hasElData(elem)) {
    return;
  }

  var data = Dom.getElData(elem);

  // If no events exist, nothing to unbind
  if (!data.handlers) {
    return;
  }

  if (Array.isArray(type)) {
    return _handleMultipleEvents(off, elem, type, fn);
  }

  // Utility function
  var removeType = function removeType(t) {
    data.handlers[t] = [];
    _cleanUpEvents(elem, t);
  };

  // Are we removing all bound events?
  if (!type) {
    for (var t in data.handlers) {
      removeType(t);
    }
    return;
  }

  var handlers = data.handlers[type];

  // If no handlers exist, nothing to unbind
  if (!handlers) {
    return;
  }

  // If no listener was provided, remove all listeners for type
  if (!fn) {
    removeType(type);
    return;
  }

  // We're only removing a single handler
  if (fn.guid) {
    for (var n = 0; n < handlers.length; n++) {
      if (handlers[n].guid === fn.guid) {
        handlers.splice(n--, 1);
      }
    }
  }

  _cleanUpEvents(elem, type);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.on"></a>[function <span class="apidocSignatureSpan">video.js.</span>on (elem, type, fn)](#apidoc.element.video.js.on)
- description and source-code
```javascript
function on(elem, type, fn) {
  if (Array.isArray(type)) {
    return _handleMultipleEvents(on, elem, type, fn);
  }

  var data = Dom.getElData(elem);

  // We need a place to store all our handler data
  if (!data.handlers) {
    data.handlers = {};
  }

  if (!data.handlers[type]) {
    data.handlers[type] = [];
  }

  if (!fn.guid) {
    fn.guid = Guid.newGUID();
  }

  data.handlers[type].push(fn);

  if (!data.dispatcher) {
    data.disabled = false;

    data.dispatcher = function (event, hash) {

      if (data.disabled) {
        return;
      }

      event = fixEvent(event);

      var handlers = data.handlers[event.type];

      if (handlers) {
        // Copy handlers so if handlers are added/removed during the process it doesn't throw everything off.
        var handlersCopy = handlers.slice(0);

        for (var m = 0, n = handlersCopy.length; m < n; m++) {
          if (event.isImmediatePropagationStopped()) {
            break;
          } else {
            try {
              handlersCopy[m].call(elem, event, hash);
            } catch (e) {
              _log2['default'].error(e);
            }
          }
        }
      }
    };
  }

  if (data.handlers[type].length === 1) {
    if (elem.addEventListener) {
      elem.addEventListener(type, data.dispatcher, false);
    } else if (elem.attachEvent) {
      elem.attachEvent('on' + type, data.dispatcher);
    }
  }
}
```
- example usage
```shell
...
var player = videojs('my-player', options, function onPlayerReady() {
  videojs.log('Your player is ready!');

  // In this context, 'this' is the player that was created by Video.js.
  this.play();

  // How about an event listener?
  this.on('ended', function() {
    videojs.log('Awww...over so soon?!');
  });
});
'''

If you're ready to dive in, the [Getting Started][getting-started] page and [documentation][docs] are the best places to go for
more information. If you get stuck, head over to our [Slack channel][slack-link]!
...
```

#### <a name="apidoc.element.video.js.one"></a>[function <span class="apidocSignatureSpan">video.js.</span>one (elem, type, fn)](#apidoc.element.video.js.one)
- description and source-code
```javascript
function one(elem, type, fn) {
  if (Array.isArray(type)) {
    return _handleMultipleEvents(one, elem, type, fn);
  }
  var func = function func() {
    off(elem, type, func);
    fn.apply(this, arguments);
  };

  // copy the guid to the new function so it can removed using the original function's ID
  func.guid = fn.guid = fn.guid || Guid.newGUID();
  on(elem, type, func);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.parseUrl"></a>[function <span class="apidocSignatureSpan">video.js.</span>parseUrl (url)](#apidoc.element.video.js.parseUrl)
- description and source-code
```javascript
function parseUrl(url) {
  var props = ['protocol', 'hostname', 'port', 'pathname', 'search', 'hash', 'host'];

  // add the url to an anchor and let the browser parse the URL
  var a = _document2['default'].createElement('a');

  a.href = url;

  // IE8 (and 9?) Fix
  // ie8 doesn't parse the URL correctly until the anchor is actually
  // added to the body, and an innerHTML is needed to trigger the parsing
  var addToBody = a.host === '' && a.protocol !== 'file:';
  var div = void 0;

  if (addToBody) {
    div = _document2['default'].createElement('div');
    div.innerHTML = '<a href="' + url + '"></a>';
    a = div.firstChild;
    // prevent the div from affecting layout
    div.setAttribute('style', 'display:none; position:absolute;');
    _document2['default'].body.appendChild(div);
  }

  // Copy the specific URL properties to a new object
  // This is also needed for IE8 because the anchor loses its
  // properties when it's removed from the dom
  var details = {};

  for (var i = 0; i < props.length; i++) {
    details[props[i]] = a[props[i]];
  }

  // IE9 adds the port to the host property unlike everyone else. If
  // a port identifier is added for standard ports, strip it.
  if (details.protocol === 'http:') {
    details.host = details.host.replace(/:80$/, '');
  }

  if (details.protocol === 'https:') {
    details.host = details.host.replace(/:443$/, '');
  }

  if (addToBody) {
    _document2['default'].body.removeChild(div);
  }

  return details;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.plugin"></a>[function <span class="apidocSignatureSpan">video.js.</span>plugin (name, init)](#apidoc.element.video.js.plugin)
- description and source-code
```javascript
function plugin(name, init) {
  _player2['default'].prototype[name] = init;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.registerComponent"></a>[function <span class="apidocSignatureSpan">video.js.</span>registerComponent (name, comp)](#apidoc.element.video.js.registerComponent)
- description and source-code
```javascript
registerComponent = function (name, comp) {
  if (_tech2['default'].isTech(comp)) {
    _log2['default'].warn('The ' + name + ' tech was registered as a component. It should instead be registered using videojs.registerTech
(name, tech)');
  }

  _component2['default'].registerComponent.call(_component2['default'], name, comp);
}
```
- example usage
```shell
...
 * @type {string}
 * @private
 */


BigPlayButton.prototype.controlText_ = 'Play Video';

_component2['default'].registerComponent('BigPlayButton', BigPlayButton);
exports['default'] = BigPlayButton;
...
```

#### <a name="apidoc.element.video.js.registerTech"></a>[function <span class="apidocSignatureSpan">video.js.</span>registerTech (name, tech)](#apidoc.element.video.js.registerTech)
- description and source-code
```javascript
function registerTech(name, tech) {
  if (!Tech.techs_) {
    Tech.techs_ = {};
  }

  if (!Tech.isTech(tech)) {
    throw new Error('Tech ' + name + ' must be a Tech');
  }

  Tech.techs_[name] = tech;
  return tech;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.removeClass"></a>[function <span class="apidocSignatureSpan">video.js.</span>removeClass (element, classToRemove)](#apidoc.element.video.js.removeClass)
- description and source-code
```javascript
function removeElClass(element, classToRemove) {
  if (element.classList) {
    element.classList.remove(classToRemove);
  } else {
    throwIfWhitespace(classToRemove);
    element.className = element.className.split(/\s+/).filter(function (c) {
      return c !== classToRemove;
    }).join(' ');
  }

  return element;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.removeHook"></a>[function <span class="apidocSignatureSpan">video.js.</span>removeHook (type, fn)](#apidoc.element.video.js.removeHook)
- description and source-code
```javascript
removeHook = function (type, fn) {
  var index = videojs.hooks(type).indexOf(fn);

  if (index <= -1) {
    return false;
  }

  videojs.hooks_[type] = videojs.hooks_[type].slice();
  videojs.hooks_[type].splice(index, 1);

  return true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.setAttributes"></a>[function <span class="apidocSignatureSpan">video.js.</span>setAttributes (el, attributes)](#apidoc.element.video.js.setAttributes)
- description and source-code
```javascript
function setElAttributes(el, attributes) {
  Object.getOwnPropertyNames(attributes).forEach(function (attrName) {
    var attrValue = attributes[attrName];

    if (attrValue === null || typeof attrValue === 'undefined' || attrValue === false) {
      el.removeAttribute(attrName);
    } else {
      el.setAttribute(attrName, attrValue === true ? '' : attrValue);
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.toString"></a>[function <span class="apidocSignatureSpan">video.js.</span>toString ()](#apidoc.element.video.js.toString)
- description and source-code
```javascript
toString = function () {
    return toString;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.toggleClass"></a>[function <span class="apidocSignatureSpan">video.js.</span>toggleClass (element, classToToggle, predicate)](#apidoc.element.video.js.toggleClass)
- description and source-code
```javascript
function toggleElClass(element, classToToggle, predicate) {

  // This CANNOT use 'classList' internally because IE does not support the
  // second parameter to the 'classList.toggle()' method! Which is fine because
  // 'classList' will be used by the add/remove functions.
  var has = hasElClass(element, classToToggle);

  if (typeof predicate === 'function') {
    predicate = predicate(element, classToToggle);
  }

  if (typeof predicate !== 'boolean') {
    predicate = !has;
  }

  // If the necessary class operation matches the current state of the
  // element, no action is required.
  if (predicate === has) {
    return;
  }

  if (predicate) {
    addElClass(element, classToToggle);
  } else {
    removeElClass(element, classToToggle);
  }

  return element;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.trigger"></a>[function <span class="apidocSignatureSpan">video.js.</span>trigger (elem, event, hash)](#apidoc.element.video.js.trigger)
- description and source-code
```javascript
function trigger(elem, event, hash) {
  // Fetches element data and a reference to the parent (for bubbling).
  // Don't want to add a data object to cache for every parent,
  // so checking hasElData first.
  var elemData = Dom.hasElData(elem) ? Dom.getElData(elem) : {};
  var parent = elem.parentNode || elem.ownerDocument;
  // type = event.type || event,
  // handler;

  // If an event name was passed as a string, creates an event out of it
  if (typeof event === 'string') {
    event = { type: event, target: elem };
  }
  // Normalizes the event properties.
  event = fixEvent(event);

  // If the passed element has a dispatcher, executes the established handlers.
  if (elemData.dispatcher) {
    elemData.dispatcher.call(elem, event, hash);
  }

  // Unless explicitly stopped or the event does not bubble (e.g. media events)
  // recursively calls this function to bubble the event up the DOM.
  if (parent && !event.isPropagationStopped() && event.bubbles === true) {
    trigger.call(null, parent, event, hash);

    // If at the top of the DOM, triggers the default action unless disabled.
  } else if (!parent && !event.defaultPrevented) {
    var targetData = Dom.getElData(event.target);

    // Checks if the target has a default action for this event.
    if (event.target[event.type]) {
      // Temporarily disables event dispatching on the target as we have already executed the handler.
      targetData.disabled = true;
      // Executes the default action.
      if (typeof event.target[event.type] === 'function') {
        event.target[event.type]();
      }
      // Re-enables event dispatching.
      targetData.disabled = false;
    }
  }

  // Inform the triggerer if the default was prevented by returning false
  return !event.defaultPrevented;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.xhr"></a>[function <span class="apidocSignatureSpan">video.js.</span>xhr (uri, options, callback)](#apidoc.element.video.js.xhr)
- description and source-code
```javascript
function createXHR(uri, options, callback) {
    options = initParams(uri, options, callback)
    return _createXHR(options)
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.video.js.EventTarget"></a>[module video.js.EventTarget](#apidoc.module.video.js.EventTarget)

#### <a name="apidoc.element.video.js.EventTarget.EventTarget"></a>[function <span class="apidocSignatureSpan">video.js.</span>EventTarget ()](#apidoc.element.video.js.EventTarget.EventTarget)
- description and source-code
```javascript
function EventTarget() {}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.video.js.EventTarget.prototype"></a>[module video.js.EventTarget.prototype](#apidoc.module.video.js.EventTarget.prototype)

#### <a name="apidoc.element.video.js.EventTarget.prototype.addEventListener"></a>[function <span class="apidocSignatureSpan">video.js.EventTarget.prototype.</span>addEventListener (type, fn)](#apidoc.element.video.js.EventTarget.prototype.addEventListener)
- description and source-code
```javascript
addEventListener = function (type, fn) {
  // Remove the addEventListener alias before calling Events.on
  // so we don't get into an infinite type loop
  var ael = this.addEventListener;

  this.addEventListener = function () {};
  Events.on(this, type, fn);
  this.addEventListener = ael;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.EventTarget.prototype.dispatchEvent"></a>[function <span class="apidocSignatureSpan">video.js.EventTarget.prototype.</span>dispatchEvent (event)](#apidoc.element.video.js.EventTarget.prototype.dispatchEvent)
- description and source-code
```javascript
dispatchEvent = function (event) {
  var type = event.type || event;

  if (typeof event === 'string') {
    event = { type: type };
  }
  event = Events.fixEvent(event);

  if (this.allowedEvents_[type] && this['on' + type]) {
    this['on' + type](event);
  }

  Events.trigger(this, event);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.EventTarget.prototype.off"></a>[function <span class="apidocSignatureSpan">video.js.EventTarget.prototype.</span>off (type, fn)](#apidoc.element.video.js.EventTarget.prototype.off)
- description and source-code
```javascript
off = function (type, fn) {
  Events.off(this, type, fn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.EventTarget.prototype.on"></a>[function <span class="apidocSignatureSpan">video.js.EventTarget.prototype.</span>on (type, fn)](#apidoc.element.video.js.EventTarget.prototype.on)
- description and source-code
```javascript
on = function (type, fn) {
  // Remove the addEventListener alias before calling Events.on
  // so we don't get into an infinite type loop
  var ael = this.addEventListener;

  this.addEventListener = function () {};
  Events.on(this, type, fn);
  this.addEventListener = ael;
}
```
- example usage
```shell
...
var player = videojs('my-player', options, function onPlayerReady() {
  videojs.log('Your player is ready!');

  // In this context, 'this' is the player that was created by Video.js.
  this.play();

  // How about an event listener?
  this.on('ended', function() {
    videojs.log('Awww...over so soon?!');
  });
});
'''

If you're ready to dive in, the [Getting Started][getting-started] page and [documentation][docs] are the best places to go for
more information. If you get stuck, head over to our [Slack channel][slack-link]!
...
```

#### <a name="apidoc.element.video.js.EventTarget.prototype.one"></a>[function <span class="apidocSignatureSpan">video.js.EventTarget.prototype.</span>one (type, fn)](#apidoc.element.video.js.EventTarget.prototype.one)
- description and source-code
```javascript
one = function (type, fn) {
  // Remove the addEventListener alialing Events.on
  // so we don't get into an infinite type loop
  var ael = this.addEventListener;

  this.addEventListener = function () {};
  Events.one(this, type, fn);
  this.addEventListener = ael;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.EventTarget.prototype.removeEventListener"></a>[function <span class="apidocSignatureSpan">video.js.EventTarget.prototype.</span>removeEventListener (type, fn)](#apidoc.element.video.js.EventTarget.prototype.removeEventListener)
- description and source-code
```javascript
removeEventListener = function (type, fn) {
  Events.off(this, type, fn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.EventTarget.prototype.trigger"></a>[function <span class="apidocSignatureSpan">video.js.EventTarget.prototype.</span>trigger (event)](#apidoc.element.video.js.EventTarget.prototype.trigger)
- description and source-code
```javascript
trigger = function (event) {
  var type = event.type || event;

  if (typeof event === 'string') {
    event = { type: type };
  }
  event = Events.fixEvent(event);

  if (this.allowedEvents_[type] && this['on' + type]) {
    this['on' + type](event);
  }

  Events.trigger(this, event);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.video.js.TextTrack"></a>[module video.js.TextTrack](#apidoc.module.video.js.TextTrack)

#### <a name="apidoc.element.video.js.TextTrack.TextTrack"></a>[function <span class="apidocSignatureSpan">video.js.</span>TextTrack ()](#apidoc.element.video.js.TextTrack.TextTrack)
- description and source-code
```javascript
function TextTrack() {
  var _this, _ret;

  var options = arguments.length > 0 && arguments[0] !== undefined ? arguments[0] : {};

  _classCallCheck(this, TextTrack);

  if (!options.tech) {
    throw new Error('A tech was not provided.');
  }

  var settings = (0, _mergeOptions2['default'])(options, {
    kind: _trackEnums.TextTrackKind[options.kind] || 'subtitles',
    language: options.language || options.srclang || ''
  });
  var mode = _trackEnums.TextTrackMode[settings.mode] || 'disabled';
  var default_ = settings['default'];

  if (settings.kind === 'metadata' || settings.kind === 'chapters') {
    mode = 'hidden';
  }
  // on IE8 this will be a document element
  // for every other browser this will be a normal object
  var tt = (_this = _possibleConstructorReturn(this, _Track.call(this, settings)), _this);

  tt.tech_ = settings.tech;

  if (browser.IS_IE8) {
    for (var prop in TextTrack.prototype) {
      if (prop !== 'constructor') {
        tt[prop] = TextTrack.prototype[prop];
      }
    }
  }

  tt.cues_ = [];
  tt.activeCues_ = [];

  var cues = new _textTrackCueList2['default'](tt.cues_);
  var activeCues = new _textTrackCueList2['default'](tt.activeCues_);
  var changed = false;
  var timeupdateHandler = Fn.bind(tt, function () {

    // Accessing this.activeCues for the side-effects of updating itself
    // due to it's nature as a getter function. Do not remove or cues will
    // stop updating!
<span class="apidocCodeCommentSpan">    /* eslint-disable no-unused-expressions */
</span>    this.activeCues;
    /* eslint-enable no-unused-expressions */
    if (changed) {
      this.trigger('cuechange');
      changed = false;
    }
  });

  if (mode !== 'disabled') {
    tt.tech_.ready(function () {
      tt.tech_.on('timeupdate', timeupdateHandler);
    }, true);
  }

  /**
   * @member {boolean} default
   *         If this track was set to be on or off by default. Cannot be changed after
   *         creation.
   *
   * @readonly
   */
  Object.defineProperty(tt, 'default', {
    get: function get() {
      return default_;
    },
    set: function set() {}
  });

  /**
   * @member {string} mode
   *         Set the mode of this TextTrack to a valid {@link TextTrack~Mode}. Will
   *         not be set if setting to an invalid mode.
   *
   * @fires TextTrack#modechange
   */
  Object.defineProperty(tt, 'mode', {
    get: function get() {
      return mode;
    },
    set: function set(newMode) {
      var _this2 = this;

      if (!_trackEnums.TextTrackMode[newMode]) {
        return;
      }
      mode = newMode;
      if (mode === 'showing') {
        this.tech_.ready(function () {
          _this2.tech_.on('timeupdate', timeupdateHandler);
        }, true);
      }
      /**
       * An event that fires when mode changes on this track. This allows
       * the TextTrackList that holds this track to act accordingly.
       *
       * > Note: This is not part of the spec!
       *
       * @event TextTrack#modechange
       * @type {EventTarget~Event}
       */
      this.trigger('modechange');
    }
  });

  /**
   * @member {TextTrackCueList} cues
   *         The text track cue list for this TextTrack.
   */
  Object.defineProperty(tt, 'cues', {
    get: function get() {
      if (!this.loaded_) {
        return null;
      }

      return cues;
    },
    set: function set() {}
  });

  /**
   * @member {TextTrackCueList} activeCues
   *         The list text track cues that are currently active for this TextTrack.
   */
  Object.defineProperty(tt, 'activeCues', {
    get: function get() {
      if (!this.loaded_) {
        return null;
      }

      // nothing to do
      if (this.cues.length === 0) {
        return activeCues;
      }

      var ct = this.tech_.currentTime();
      var active = [];

      for (var i = 0, l = this.cues.length; i < l; i++) {
        var cue = this.cues[i];

        if (cue.startTime <= ct && cue.endTime >= ct) {
          active.push(cue);
        } else if (cue.startTime === cue.endTime && cue.startTime <= ct && cue.startTime + 0.5 >= ct) {
          active.push(cue);
        }
      }

      chang ...
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.video.js.TextTrack.prototype"></a>[module video.js.TextTrack.prototype](#apidoc.module.video.js.TextTrack.prototype)

#### <a name="apidoc.element.video.js.TextTrack.prototype.addCue"></a>[function <span class="apidocSignatureSpan">video.js.TextTrack.prototype.</span>addCue (originalCue)](#apidoc.element.video.js.TextTrack.prototype.addCue)
- description and source-code
```javascript
function addCue(originalCue) {
  var cue = originalCue;

  if (_window2['default'].vttjs && !(originalCue instanceof _window2['default'].vttjs.VTTCue)) {
    cue = new _window2['default'].vttjs.VTTCue(originalCue.startTime, originalCue.endTime, originalCue.text);

    for (var prop in originalCue) {
      if (!(prop in cue)) {
        cue[prop] = originalCue[prop];
      }
    }

    // make sure that 'id' is copied over
    cue.id = originalCue.id;
    cue.originalCue_ = originalCue;
  }

  var tracks = this.tech_.textTracks();

  if (tracks) {
    for (var i = 0; i < tracks.length; i++) {
      if (tracks[i] !== this) {
        tracks[i].removeCue(cue);
      }
    }
  }

  this.cues_.push(cue);
  this.cues.setCues_(this.cues_);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.TextTrack.prototype.removeCue"></a>[function <span class="apidocSignatureSpan">video.js.TextTrack.prototype.</span>removeCue (_removeCue)](#apidoc.element.video.js.TextTrack.prototype.removeCue)
- description and source-code
```javascript
function removeCue(_removeCue) {
  var i = this.cues_.length;

  while (i--) {
    var cue = this.cues_[i];

    if (cue === _removeCue || cue.originalCue_ && cue.originalCue_ === _removeCue) {
      this.cues_.splice(i, 1);
      this.cues.setCues_(this.cues_);
      break;
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.video.js.big_play_button"></a>[module video.js.big_play_button](#apidoc.module.video.js.big_play_button)

#### <a name="apidoc.element.video.js.big_play_button.default"></a>[function <span class="apidocSignatureSpan">video.js.big_play_button.</span>default ()](#apidoc.element.video.js.big_play_button.default)
- description and source-code
```javascript
function BigPlayButton() {
  _classCallCheck(this, BigPlayButton);

  return _possibleConstructorReturn(this, _Button.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.video.js.log"></a>[module video.js.log](#apidoc.module.video.js.log)

#### <a name="apidoc.element.video.js.log.log"></a>[function <span class="apidocSignatureSpan">video.js.</span>log ()](#apidoc.element.video.js.log.log)
- description and source-code
```javascript
function log() {
  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  logByType('log', args);
}
```
- example usage
```shell
...
The 'videojs' function also accepts an 'options' object and a callback to be invoked
 when the player is ready:

'''js
var options = {};

var player = videojs('my-player', options, function onPlayerReady() {
videojs.log('Your player is ready!');

// In this context, 'this' is the player that was created by Video.js.
this.play();

// How about an event listener?
this.on('ended', function() {
  videojs.log('Awww...over so soon?!');
...
```

#### <a name="apidoc.element.video.js.log.error"></a>[function <span class="apidocSignatureSpan">video.js.log.</span>error ()](#apidoc.element.video.js.log.error)
- description and source-code
```javascript
error = function () {
  for (var _len2 = arguments.length, args = Array(_len2), _key2 = 0; _key2 < _len2; _key2++) {
    args[_key2] = arguments[_key2];
  }

  return logByType('error', args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.log.warn"></a>[function <span class="apidocSignatureSpan">video.js.log.</span>warn ()](#apidoc.element.video.js.log.warn)
- description and source-code
```javascript
warn = function () {
  for (var _len3 = arguments.length, args = Array(_len3), _key3 = 0; _key3 < _len3; _key3++) {
    args[_key3] = arguments[_key3];
  }

  return logByType('warn', args);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.video.js.xhr"></a>[module video.js.xhr](#apidoc.module.video.js.xhr)

#### <a name="apidoc.element.video.js.xhr.xhr"></a>[function <span class="apidocSignatureSpan">video.js.</span>xhr (uri, options, callback)](#apidoc.element.video.js.xhr.xhr)
- description and source-code
```javascript
function createXHR(uri, options, callback) {
    options = initParams(uri, options, callback)
    return _createXHR(options)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.xhr.XMLHttpRequest"></a>[function <span class="apidocSignatureSpan">video.js.xhr.</span>XMLHttpRequest ()](#apidoc.element.video.js.xhr.XMLHttpRequest)
- description and source-code
```javascript
function noop() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.xhr.del"></a>[function <span class="apidocSignatureSpan">video.js.xhr.</span>del (uri, options, callback)](#apidoc.element.video.js.xhr.del)
- description and source-code
```javascript
del = function (uri, options, callback) {
    options = initParams(uri, options, callback)
    options.method = method.toUpperCase()
    return _createXHR(options)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.xhr.get"></a>[function <span class="apidocSignatureSpan">video.js.xhr.</span>get (uri, options, callback)](#apidoc.element.video.js.xhr.get)
- description and source-code
```javascript
get = function (uri, options, callback) {
    options = initParams(uri, options, callback)
    options.method = method.toUpperCase()
    return _createXHR(options)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.xhr.head"></a>[function <span class="apidocSignatureSpan">video.js.xhr.</span>head (uri, options, callback)](#apidoc.element.video.js.xhr.head)
- description and source-code
```javascript
head = function (uri, options, callback) {
    options = initParams(uri, options, callback)
    options.method = method.toUpperCase()
    return _createXHR(options)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.xhr.patch"></a>[function <span class="apidocSignatureSpan">video.js.xhr.</span>patch (uri, options, callback)](#apidoc.element.video.js.xhr.patch)
- description and source-code
```javascript
patch = function (uri, options, callback) {
    options = initParams(uri, options, callback)
    options.method = method.toUpperCase()
    return _createXHR(options)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.xhr.post"></a>[function <span class="apidocSignatureSpan">video.js.xhr.</span>post (uri, options, callback)](#apidoc.element.video.js.xhr.post)
- description and source-code
```javascript
post = function (uri, options, callback) {
    options = initParams(uri, options, callback)
    options.method = method.toUpperCase()
    return _createXHR(options)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.video.js.xhr.put"></a>[function <span class="apidocSignatureSpan">video.js.xhr.</span>put (uri, options, callback)](#apidoc.element.video.js.xhr.put)
- description and source-code
```javascript
put = function (uri, options, callback) {
    options = initParams(uri, options, callback)
    options.method = method.toUpperCase()
    return _createXHR(options)
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
