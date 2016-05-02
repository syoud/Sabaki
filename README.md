# Sabaki [![Build Status](https://travis-ci.org/yishn/Sabaki.svg?branch=master)](https://travis-ci.org/yishn/Sabaki)

<img src="logo.png" width="156" height="156">

An elegant Go/Baduk/Weiqi board and SGF editor for a more civilized age. [Download the latest release](https://github.com/yishn/Sabaki/releases) of Sabaki.

![Screenshot](screenshot.png)

## Features

- Fuzzy stone placement
- Read and save SGF games and collections
- Display formatted SGF comments using a [subset of Markdown](https://github.com/yishn/Sabaki/wiki/Markdown-in-Sabaki)
- SGF editing tools
- Lines & arrows markup
- Game graph
- Scoring tool
- Find move
- Position & move annotations
- GTP engines support
- Guess mode

For more information visit the [wiki](https://github.com/yishn/Sabaki/wiki).

## Building

Building Sabaki requires [Node.js](https://nodejs.org/en/download/) and npm. First, clone Sabaki:

~~~
git clone https://github.com/yishn/Sabaki
cd Sabaki
~~~

Install `electron-packager` globally and the dependencies of Sabaki using npm:

~~~
npm install electron-packager -g
npm install
~~~

You can build Sabaki by using one of the three build instructions depending on the target OS:

* `npm run build:win`
* `npm run build:linux`
* `npm run build:osx`

The binaries will be in `Sabaki/bin/`.

To run the (currently very limited) tests, you have to install `electron-prebuilt` and `electron-mocha` globally using npm:

~~~
npm install electron-prebuilt -g
npm install electron-mocha -g
npm test
~~~

## Web Version

Sabaki has a `web` branch. It's a trimmed-down version of Sabaki that runs in any modern browser. You can try a working demo at http://sabaki.yichuanshen.de/web/.

## Third Party Libraries

* [Electron](http://electron.atom.io/)
  ([MIT License](https://github.com/atom/electron/blob/master/LICENSE))
* [MooTools](http://mootools.net/)
  ([MIT License](https://github.com/mootools/mootools-core/blob/master/Source/license.txt))
* [sigma](http://sigmajs.org/)
  ([MIT License](https://github.com/jacomyal/sigma.js/blob/master/LICENSE.txt))
* [marked](https://github.com/chjj/marked)
  ([MIT License](https://github.com/chjj/marked/blob/master/LICENSE))
* [gemini-scrollbar](http://noeldelgado.github.io/gemini-scrollbar/)
  ([MIT License](https://github.com/noeldelgado/gemini-scrollbar/blob/master/LICENSE))
* [argv-split](https://github.com/kaelzhang/node-argv-split)
  ([MIT License](https://github.com/kaelzhang/node-argv-split/blob/master/LICENSE-MIT))
* [Octicons](https://octicons.github.com/)
  ([License](https://github.com/github/octicons/blob/master/LICENSE.txt))
