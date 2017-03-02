# three-orbit-controls-loader

> NodeJS wrapper for Three.js' OrbitalControls function

By default, [Three.js](https://www.npmjs.com/package/three) does not have [OrbitControls](https://github.com/mrdoob/three.js/blob/dev/examples/js/controls/OrbitControls.js) built in. This is a NodeJS wrapper for the OrbitControls library so that it can be used with npm in systems using browserify, webpack, etc.

## Install

```
$ npm install --save three-orbit-controls-loader
```

## Usage

```js
var THREE = require('three');
var OrbitControls = require('three-orbit-controls-loader');
OrbitControls(THREE);

console.log(typeof THREE.OrbitControls);
//=> 'function'
```

## License

MIT © [quitedensepoint](https://github.com/quitedensepoint)
