---
layout: default
---

<h1 id="install">Install <a href="#install" title="Permalink">#</a></h1>


Math.js can be installed via various package managers:

<table>
  <thead>
    <tr>
      <th>Package Manager</th>
      <th>Installation</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="http://npmjs.org/">npm</a> (recommended)</td>
      <td><pre class="highlight">npm install mathjs</pre></td>
    </tr>
    <tr>
      <td><a href="http://bower.io/">bower</a> (deprecated)</td>
      <td><pre class="highlight">bower install mathjs</pre></td>
    </tr>
  </tbody>
</table>

When installed globally with [npm](https://npmjs.org/) (using the `-g` option), math.js is available as a command line application `mathjs`, see documentation on [Command Line Interface](docs/command_line_interface.html).


<h1 id="download">Download <a href="#download" title="Permalink">#</a></h1>

Math.js can be downloaded or linked from various content delivery networks:

<table>
  <thead>
    <tr>
      <th>CDN</th>
      <th>Url</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>unpkg</td>
      <td><a href="https://unpkg.com/mathjs@4.4.0/">https://unpkg.com/mathjs@4.4.0/</a></td>
    </tr>
    <tr>
      <td>cdnjs</td>
      <td><a href="https://cdnjs.com/libraries/mathjs">https://cdnjs.com/libraries/mathjs</a></td>
    </tr>
    <tr>
      <td>jsDelivr</td>
      <td><a href="https://www.jsdelivr.com/package/npm/mathjs">https://www.jsdelivr.com/package/npm/mathjs</a></td>
    </tr>
  </tbody>
</table>

Here some direct download links from [unpkg](https://unpkg.com):

<table class="download">
  <tr>
    <td>
      <a href="https://unpkg.com/mathjs@4.4.0/dist/math.js">
        Development (version 4.4.0)
      </a>
    </td>
    <td>
      <span id="development-size">1663 kB</span>, uncompressed with comments
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://unpkg.com/mathjs@4.4.0/dist/math.min.js">
        Production (version 4.4.0)
      </a>
    </td>
    <td>
      <span id="production-size">131 kB</span>, minified and gzipped
    </td>
  </tr>
</table>

Too large for you? Create your own [custom bundle](docs/custom_bundling.html).


<h1 id="webservice">Web Service <a href="#webservice" title="Permalink">#</a></h1>

Math.js is available as a RESTful web service: <a href="http://api.mathjs.org">http://api.mathjs.org</a>


<h1 id="extensions">Extensions <a href="#extensions" title="Permalink">#</a></h1>

Here some notable extensions for mathjs:

Extension | Description
--------- | -----------
[mathsteps](https://github.com/socraticorg/mathsteps) | A step-by-step math solver library that is focused on pedagogy (how best to teach). The math problems it focuses on are pre-algebra and algebra problems involving simplifying expressions.
[mathjs&#8209;expression&#8209;parser](https://github.com/josdejong/mathjs-expression-parser) | This custom build of mathjs contains just the expression parser and basic arithmetic functions for numbers. About four times as small as the full mathjs library.
[mathjs-simple-integral](https://github.com/joelhoover/mathjs-simple-integral) | Extends Math.js to be able to compute simple integrals.
[math.diff.js](https://github.com/hausen/math.diff.js) | Symbolic differentiation plugin for Math.js
[postcss-math](https://github.com/shauns/postcss-math) | PostCSS plugin for making calculations with math.js


<h1 id="extensions">Other math libraries <a href="#other-math-libraries" title="Permalink">#</a></h1>

Here some other interesting JavaScript math libraries. Some can be imported into math.js using `math.import`.

Extension | Description
--------- | -----------
[math&#8209;expression&#8209;evaluator](https://www.npmjs.com/package/math-expression-evaluator) | An extremely efficient, flexible and amazing evaluator for Math expression in Javascript.
[numbers.js](https://github.com/numbers/numbers.js) | Advanced Mathematics Library for Node.js and JavaScript
[numeric.js](https://github.com/sloisel/numeric) | Numerical analysis in Javascript
[decimal.js](https://github.com/MikeMcl/decimal.js/) | An arbitrary-precision Decimal type for JavaScript. Used by mathjs for BigNumber support.
[ndarray](https://github.com/scijs/ndarray) | Multidimensional arrays for JavaScript
[Algebrite](https://github.com/davidedc/Algebrite) | Computer Algebra System in Javascript (Coffeescript)
[algebra.js](https://github.com/nicolewhite/algebra.js) | Build, display, and solve algebraic equations.
[numeral-js](https://github.com/adamwdraper/Numeral-js) | A javascript library for formatting and manipulating numbers


<h1 id="history">History <a href="#history" title="Permalink">#</a></h1>

A changelog describing the changes with each release is available on the page [History](history.html).


<h1 id="browsersupport">Browser support <a href="#browsersupport" title="Permalink">#</a></h1>

Math.js works on any ES5 compatible JavaScript engine: node.js 4 and newer and IE11 and newer. If support for old browsers is required, the [es5-shim](https://github.com/kriskowal/es5-shim) library has to be loaded.


<h1 id="source-code">Source code <a href="#source-code" title="Permalink">#</a></h1>

The source code of math.js is available on GitHub: [https://github.com/josdejong/mathjs](https://github.com/josdejong/mathjs).


<h1 id="license">License <a href="#license" title="Permalink">#</a></h1>

Math.js is open source and licensed under the
[Apache 2.0 License](http://www.apache.org/licenses/LICENSE-2.0)