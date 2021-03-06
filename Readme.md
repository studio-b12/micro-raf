[![Coveralls – test coverage
](https://img.shields.io/coveralls/studio-b12/micro-raf.svg?style=flat-square)
](https://coveralls.io/r/studio-b12/micro-raf)
 [![Travis – build status
](https://img.shields.io/travis/studio-b12/micro-raf/master.svg?style=flat-square)
](https://travis-ci.org/studio-b12/micro-raf)
 [![David – status of dependencies
](https://img.shields.io/david/studio-b12/micro-raf.svg?style=flat-square)
](https://david-dm.org/studio-b12/micro-raf)
 [![Stability: stable
](https://img.shields.io/badge/stability-stable-brightgreen.svg?style=flat-square)
](https://nodejs.org/api/documentation.html#documentation_stability_index)
 [![Code style: airbnb
](https://img.shields.io/badge/code%20style-airbnb-777777.svg?style=flat-square)
](https://github.com/airbnb/javascript)




micro-raf
=========

**A tiny ponyfill for requestAnimationFrame.**

Makes your app testable for just 100 B.




<p align="center"><a
  title="Graphic by the great Justin Mezzell"
  href="http://justinmezzell.tumblr.com/post/64389350063"
  >
  <br/>
  <br/>
  <img
    src="https://cdn.rawgit.com/studio-b12/micro-raf/ea83e8f/Readme/Hourglass.gif"
    width="400"
    height="300"
  />
  <br/>
  <br/>
</a></p>




Installation
------------

```sh
$ npm install micro-raf
```




Usage
-----

```js
const raf = require('micro-raf');

raf(() => console.log('Next frame!'));
```

Works in node and [browsers](http://caniuse.com/#feat=requestanimationframe).




Credits
-------

Inspired by [ainojs-requestframe](https://github.com/aino/ainojs-requestframe) which is no longer maintained.




License
-------

[MIT][] © [Studio B12 GmbH][]

[MIT]:              ./License.md
[Studio B12 GmbH]:  http://www.studio-b12.de
