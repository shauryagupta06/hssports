# HS-Sports

index.html file path :
HSSports >> src >> src1 >> src2

# Vue Installation

# Compatibility Note
Vue does not support IE8 and below, because it uses ECMAScript 5 features that are un-shimmable in IE8. However it supports all ECMAScript 5 compliant browsers.

# Release Notes
Latest stable version: 2.6.10


# Vue Devtools
When using Vue, we recommend also installing the Vue Devtools in your browser, allowing you to inspect and debug your Vue applications in a more user-friendly interface.

# Direct <script> Include
Simply download and include with a script tag. Vue will be registered as a global variable.


# CDN
For prototyping or learning purposes, you can use the latest version with:

<script src="https://cdn.jsdelivr.net/npm/vue"></script>
For production, we recommend linking to a specific version number and build to avoid unexpected breakage from newer versions:

<script src="https://cdn.jsdelivr.net/npm/vue@2.6.10/dist/vue.js"></script>
If you are using native ES Modules, there is also an ES Modules compatible build:

<script type="module">
  import Vue from 'https://cdn.jsdelivr.net/npm/vue@2.6.10/dist/vue.esm.browser.js'
</script>

You can browse the source of the NPM package at cdn.jsdelivr.net/npm/vue.

Vue is also available on unpkg and cdnjs (cdnjs takes some time to sync so the latest release may not be available yet).

Make sure to read about the different builds of Vue and use the production
version in your published site, replacing vue.js with vue.min.js. This is a smaller build optimized for speed instead of development experience.

# NPM
NPM is the recommended installation method when building large scale applications with Vue. It pairs nicely with module bundlers such as Webpack or Browserify. Vue also provides accompanying tools for authoring Single File Components.

# latest stable
$ npm install vue


# CLI
Vue provides an official CLI for quickly scaffolding ambitious Single Page Applications. It provides batteries-included build setups for a modern frontend workflow. It takes only a few minutes to get up and running with hot-reload, lint-on-save, and production-ready builds. See the Vue CLI docs for more details.

The CLI assumes prior knowledge of Node.js and the associated build tools. If you are new to Vue or front-end build tools, we strongly suggest going through the guide without any build tools before using the CLI.


# Dev Build
Important: the built files in GitHub’s /dist folder are only checked-in during releases. To use Vue from the latest source code on GitHub, you will have to build it yourself!

git clone https://github.com/vuejs/vue.git node_modules/vue
cd node_modules/vue
npm install
npm run build
Bower
Only UMD builds are available from Bower.

# latest stable

$ bower install vue
AMD Module Loaders
All UMD builds can be used directly as an AMD module.
