<!--

@license Apache-2.0

Copyright (c) 2024 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->


<details>
  <summary>
    About stdlib...
  </summary>
  <p>We believe in a future in which the web is a preferred environment for numerical computation. To help realize this future, we've built stdlib. stdlib is a standard library, with an emphasis on numerical and scientific computation, written in JavaScript (and C) for execution in browsers and in Node.js.</p>
  <p>The library is fully decomposable, being architected in such a way that you can swap out and mix and match APIs and functionality to cater to your exact preferences and use cases.</p>
  <p>When you use stdlib, you can be absolutely certain that you are using the most thorough, rigorous, well-written, studied, documented, tested, measured, and high-quality code out there.</p>
  <p>To join us in bringing numerical computing to the web, get started by checking us out on <a href="https://github.com/stdlib-js/stdlib">GitHub</a>, and please consider <a href="https://opencollective.com/stdlib">financially supporting stdlib</a>. We greatly appreciate your continued support!</p>
</details>

# NAN

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Canonical double-precision complex floating-point `NaN`.



<section class="usage">

## Usage

```javascript
import COMPLEX128_NAN from 'https://cdn.jsdelivr.net/gh/stdlib-js/constants-complex128-nan@esm/index.mjs';
```

#### COMPLEX128_NAN

Canonical double-precision complex floating-point `NaN`.

```javascript
import real from 'https://cdn.jsdelivr.net/gh/stdlib-js/complex-real@esm/index.mjs';
import imag from 'https://cdn.jsdelivr.net/gh/stdlib-js/complex-imag@esm/index.mjs';

var re = real( COMPLEX128_NAN );
// returns NaN

var im = imag( COMPLEX128_NAN );
// returns NaN
```

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- eslint no-undef: "error" -->

```html
<!DOCTYPE html>
<html lang="en">
<body>
<script type="module">

import real from 'https://cdn.jsdelivr.net/gh/stdlib-js/complex-real@esm/index.mjs';
import imag from 'https://cdn.jsdelivr.net/gh/stdlib-js/complex-imag@esm/index.mjs';
import Complex128Array from 'https://cdn.jsdelivr.net/gh/stdlib-js/array-complex128@esm/index.mjs';
import COMPLEX128_NAN from 'https://cdn.jsdelivr.net/gh/stdlib-js/constants-complex128-nan@esm/index.mjs';

var x = new Complex128Array( [ 1.0, 2.0, 3.0, 4.0 ] );
// returns <Complex128Array>

var v = x.get( 0 );
// returns <Complex128>

var re = real( v );
// returns 1.0

var im = imag( v );
// returns 2.0

x.fill( COMPLEX128_NAN );

v = x.get( 0 );
// returns <Complex128>

re = real( v );
// returns NaN

im = imag( v );
// returns NaN

</script>
</body>
</html>
```

</section>

<!-- /.examples -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2024. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/constants-complex128-nan.svg
[npm-url]: https://npmjs.org/package/@stdlib/constants-complex128-nan

[test-image]: https://github.com/stdlib-js/constants-complex128-nan/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/constants-complex128-nan/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/constants-complex128-nan/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/constants-complex128-nan?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/constants-complex128-nan.svg
[dependencies-url]: https://david-dm.org/stdlib-js/constants-complex128-nan/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/constants-complex128-nan/tree/deno
[umd-url]: https://github.com/stdlib-js/constants-complex128-nan/tree/umd
[esm-url]: https://github.com/stdlib-js/constants-complex128-nan/tree/esm
[branches-url]: https://github.com/stdlib-js/constants-complex128-nan/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/constants-complex128-nan/main/LICENSE

</section>

<!-- /.links -->