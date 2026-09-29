<p align="center">
    <img width="300" src="./logo.png" alt="logo of rspack-awesome repository"><br>
    A curated list of awesome things related to the Rstack toolchain
</p>

<h1>Awesome Rstack</h1>

- [Resources](#resources)
  - [Rstack](#rstack)
  - [Official Resources](#official-resources)
  - [Ecosystem](#ecosystem)
- [Starter](#starter)
  - [Rspack Starter](#rspack-starter)
  - [Rsbuild Starter](#rsbuild-starter)
  - [Rslib Starter](#rslib-starter)
- [Plugins](#plugins)
  - [Rspack Plugins](#rspack-plugins)
  - [Rspack Loaders](#rspack-loaders)
  - [Rsbuild Plugins](#rsbuild-plugins)
  - [Rspress Plugins](#rspress-plugins)
  - [Unplugin](#unplugin)
- [Rstest Adapters](#rstest-adapters)
- [Rstest Utilities](#rstest-utilities)
- [Deployment](#deployment)
- [Libraries](#libraries)
- [Blogs](#blogs)
- [License](#license)

## Resources

### Rstack

Rstack is a unified JavaScript toolchain built around Rspack, with high performance and consistent architecture.

| Name                                                  | Description              | Version                                                                                                                                                                          |
| ----------------------------------------------------- | ------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Rspack](https://github.com/web-infra-dev/rspack)     | Bundler                  | <a href="https://npmjs.com/package/@rspack/core"><img src="https://img.shields.io/npm/v/@rspack/core?style=flat-square&colorA=564341&colorB=EDED91" alt="npm version" /></a>     |
| [Rsbuild](https://github.com/web-infra-dev/rsbuild)   | Build tool               | <a href="https://npmjs.com/package/@rsbuild/core"><img src="https://img.shields.io/npm/v/@rsbuild/core?style=flat-square&colorA=564341&colorB=EDED91" alt="npm version" /></a>   |
| [Rslib](https://github.com/web-infra-dev/rslib)       | Library development tool | <a href="https://npmjs.com/package/@rslib/core"><img src="https://img.shields.io/npm/v/@rslib/core?style=flat-square&colorA=564341&colorB=EDED91" alt="npm version" /></a>       |
| [Rspress](https://github.com/web-infra-dev/rspress)   | Static site generator    | <a href="https://npmjs.com/package/@rspress/core"><img src="https://img.shields.io/npm/v/@rspress/core?style=flat-square&colorA=564341&colorB=EDED91" alt="npm version" /></a>   |
| [Rsdoctor](https://github.com/web-infra-dev/rsdoctor) | Build analyzer           | <a href="https://npmjs.com/package/@rsdoctor/core"><img src="https://img.shields.io/npm/v/@rsdoctor/core?style=flat-square&colorA=564341&colorB=EDED91" alt="npm version" /></a> |
| [Rstest](https://github.com/web-infra-dev/rstest)     | Testing framework        | <a href="https://npmjs.com/package/@rstest/core"><img src="https://img.shields.io/npm/v/@rstest/core?style=flat-square&colorA=564341&colorB=EDED91" alt="npm version" /></a>     |
| [Rslint](https://github.com/web-infra-dev/rslint)     | Linter                   | <a href="https://npmjs.com/package/@rslint/core"><img src="https://img.shields.io/npm/v/@rslint/core?style=flat-square&colorA=564341&colorB=EDED91" alt="npm version" /></a>     |
| [Rstack CLI](https://github.com/rstackjs/rstack-cli)  | Unified CLI              | <a href="https://npmjs.com/package/rstack"><img src="https://img.shields.io/npm/v/rstack?style=flat-square&colorA=564341&colorB=EDED91" alt="npm version" /></a>                 |

### Official Resources

- [rstack-examples](https://github.com/rstackjs/rstack-examples): Examples for Rstack.
- [rstack-design-resources](https://github.com/rstackjs/rstack-design-resources): Design resources for Rstack.
- [rstack-editor](https://github.com/rstackjs/rstack-editor): Unified VS Code extension for Rstack.
- [rsdoctor-action](https://github.com/web-infra-dev/rsdoctor-action): A GitHub Action for bundle size comparisons and pull request reports powered by Rsdoctor.
- [rspack-binding-template](https://github.com/rstackjs/rspack-binding-template): A template for creating custom Rspack bindings with plugins and loaders written in Rust.

### Ecosystem

Upper-level frameworks or libraries that are powered by Rspack or connected to Rspack:

- [Rspeedy](https://lynxjs.org/rspeedy/): The Rspack-based build tool designed specifically for [Lynx](https://lynxjs.org/) applications.
- [Modern.js](https://modernjs.dev/): A progressive React framework for web development.
- [storybook-rsbuild](https://github.com/rstackjs/storybook-rsbuild): Storybook builder powered by Rsbuild.
- [@nx/rspack](https://nx.dev/nx-api/rspack): The Nx plugin for Rspack.
- [@nx/rsbuild](https://nx.dev/nx-api/rsbuild): The Nx plugin for Rsbuild.
- [Docusaurus](https://docusaurus.io/blog/releases/3.6#docusaurus-faster): Help you ship a beautiful documentation site in no time.
- [TanStack Start](https://tanstack.com/start/latest): Full-stack Framework powered by TanStack Router for React and Solid.
- [next-rspack](https://rspack.rs/guide/tech/next): Use Rspack as the bundler for Next.js.
- [Nuxt](https://nuxt.com/): An intuitive Vue framework for creating web applications and websites with Vue.js. Install [@nuxt/rspack-builder](https://www.npmjs.com/package/@nuxt/rspack-builder) to use Rspack as the bundler for Nuxt.
- [Re.Pack](https://github.com/callstack/repack): A toolkit to build your React Native application with Rspack.
- [EMP 3.0](https://empjs.dev/): A high-performance enterprise-level front-end build system built on the Rust ecosystem.
- [pareto](https://github.com/childrentime/pareto): A lightweight SSR framework centered on stream rendering.
- [cypress-rspack-dev-server](https://www.npmjs.com/package/cypress-rspack-dev-server): Cypress Component-testing with Rust-based web bundler Rspack's dev server.
- [Extension.js](https://github.com/extension-js/extension.js): Create, develop, build, and preview browser extensions for Chrome, Firefox, and Edge with Rspack.
- [serverless-rspack](https://github.com/kitchenshelf/serverless-rspack): A Serverless framework plugin for zero-config JavaScript and TypeScript code bundling using the high performance Rust-based JavaScript bundler rspack.
- [AUmi](https://github.com/atom-yang/aumi): Use Rsbuild as Umi's bundler instead of Webpack, get high performance of Rsbuild and all Umi ecosystem.
- [electron-rsbuild](https://github.com/electron-rsbuild/electron-rsbuild): The Rsbuild-based electron build tool.
- [Rselectron](https://github.com/guangzan/rselectron): An Rsbuild-first Electron development and build tool.
- [Esmx](https://github.com/esmnext/esmx): Esmx is a next-generation micro-frontend framework based on native ESM, with no sandbox or runtime overhead, supporting multi-framework hybrid development and providing high-performance server-side rendering capabilities.
- [Angular Rspack](https://www.npmjs.com/package/@nx/angular-rspack): Rspack plugin, Rsbuild plugin and tooling for Angular applications.
- [PrevelteKit](https://github.com/tbocek/preveltekit): A lightweight, high-performance web application framework built on Svelte 5, featuring Server-Side Pre Rendering (SSPR) using Rsbuild as the build tool.
- [Kmi](https://github.com/kmijs/kmi): Based on Umi to provide Rspack support and other best practices.
- [xmcp](https://github.com/basementstudio/xmcp): A framework for building and shipping MCP servers with TypeScript and Rspack.
- [Meteor](https://github.com/meteor/meteor): An ultra-simple environment for building modern web applications with Rspack.
- [Addfox](https://github.com/addfox/addfox): A browser extension framework built on Rsbuild.
- [Shakapacker](https://github.com/shakacode/shakapacker): Make it easy to use the JavaScript pre-processor and Rspack to manage frontend JavaScript in Rails.
- [Symfony Reprise](https://github.com/symfony/reprise): Integrates Rsbuild with Symfony.
- [The Boring JavaScript Stack](https://github.com/sailscastshq/boring-stack): An opinionated full-stack JavaScript starter built with Sails.js, Inertia.js, and Rsbuild-powered frontend assets.
- [Rshono](https://github.com/rshono/rshono): Minimalist web framework based on Hono, Rspack and React Server Components.
- [effective-rsc](https://github.com/nikhilsnayak/effective-rsc): An Effect-native React Server Components framework for Bun, built on Rspack's native RSC support.

## Skills

- [agent-skills](https://github.com/rstackjs/agent-skills): A collection of Agent Skills for Rstack.

## Starter

### Rspack Starter

- [nuxt-rspack-starter](https://github.com/danielroe/nuxt-rspack-starter): Nuxt starter with Rspack.
- [rspack-react-router-starter](https://github.com/ulivz/rspack-react-router-starter)
- [rspack for create-react-app](https://github.com/yanhaijing/rspack-cra)
- [electron-forge-rspack-template](https://github.com/noshower/electron-forge-rspack-template)
- [shark](https://github.com/h7ml/shark): A React project with Rspack, Ant Design, Ant Design Pro Components, Antd@5 React@18 AntV G2Plot, ahooks, react-use, Axios, i18next, localforage, Mock.js, NProgress, and more.
- [electron-react-rspack](https://github.com/RyanProMax/electron-react-rspack): An Electron boilerplate including TypeScript, React, Rspack and ESLint.
- [ng-rspack](https://github.com/edbzn/ng-rspack): Angular + Rspack + Nx + Module Federation 2.0.
- [r2h](https://github.com/bdxygy/r2h): A blazing-fast SSR starter powered by React 19, Rspack, and Hono.
- [vue-admin-better](https://github.com/zxwk1998/vue-admin-better): A Vue 3 admin based on Rspack.
- [electron-react-rspack-boilerplate](https://github.com/Sovea/electron-react-rspack-boilerplate): A modern, unopinionated, pure boilerplate for developing electron app with Rspack, React, TypeScript.

### Rsbuild Starter

- [ding-dong](https://github.com/src-thk/ding-dong): A lightning-fast, modern React template supercharged with Rsbuild.
- [react-tailwind-rsbuild-boilerplate](https://github.com/alonronin/react-tailwind-rsbuild-boilerplate): React + React Router + Tailwind CSS with Rsbuild boilerplate.
- [TanStacked](https://github.com/mohmmedraad/TanStacked): React + Tanstack Router + Shadcn + Tailwind CSS v4 And Biome with Rsbuild boilerplate.
- [rsbuild_vue3_h5_template](https://github.com/DMaiGit/rsbuild_vue3_h5_template): A project template for Vue 3. It includes popular libraries such as Axios, Pinia, Vant, and Vue Router.
- [rsbuild-chrome-extension-boilerplate-react](https://github.com/filc-dev/rsbuild-chrome-extension-boilerplate-react): Chrome extension boilerplate for Rsbuild.
- [rsbuild-plugin-template](https://github.com/rstackjs/rsbuild-plugin-template): Use this template to create your own Rsbuild plugin.
- [react-antd-admin-pro](https://github.com/cl1107/react-antd-admin-pro): An admin project template for React. It's built with Rsbuild, React 18, TypeScript 5, antd 5, and React Router.
- [umi-rsbuild](https://github.com/atom-yang/aumi-example): `Umi` + `Rsbuild`, A `Umi` project integrated with `Rsbuild`, you can use `Umi` and its plugins with the same experiences as `Umi` + `Webpack` are.
- [rsbuild-react-chakra-starter](https://github.com/sozonome/rsbuild-react-chakra-starter): initialize react app with rsbuild, Chakra UI and TypeScript setup. Configured with awesome toolings: Biome, Husky + Lint-Staged, Commitlint, and Turbo.
- [template-rsbuild-react-ts-tailwind](https://github.com/RoyRao2333/template-rsbuild-react-ts-tailwind): Rsbuild starter template with React + Typescript + TailwindCSS + Biome.
- [rsbuild-turborepo-react-module-federation](https://github.com/nguyenbatranvan/rspack-turbo-module-federation): Rsbuild + Turborepo + Biome + Zustand + React for module federation.
- [@trapar-waves/react-tailwind](https://github.com/Trapar-waves/react-tailwind): A modern UI development template integrating React and Tailwind CSS, with Rsbuild, TypeScript, ESLint.
- [@trapar-waves/react-antd-pro](https://github.com/Trapar-waves/react-antd-pro): A React-based project leveraging Ant Design Pro, TanStack tools, and Rsbuild.
- [@trapar-waves/react-tanstack](https://github.com/Trapar-waves/react-tanstack): A React template leveraging TanStack tools, with TypeScript, Tailwind CSS, and Rsbuild integration.
- [@trapar-waves/react-mantine-tailwind](https://github.com/Trapar-waves/react-mantine-tailwind): A React template integrating Mantine UI and Tailwind CSS for modern web development.
- [@trapar-waves/vue-tailwind](https://github.com/Trapar-waves/vue-tailwind): A Vue 3 project with Tailwind CSS, Rsbuild and modern development tools.
- [vue-nestjs-ssr-starter](https://github.com/pikadun/vue-nestjs-ssr-starter): A lightweight full-stack SSR starter with Vue 3, NestJS, Fastify, PrimeVue, and Rsbuild.
- [react-nestjs-ssr-starter](https://github.com/pikadun/react-nestjs-ssr-starter): A lightweight full-stack starter for server-side rendering with NestJS and React.
- [rsbuild-vue-starter](https://github.com/logue/rsbuild-vue-starter): A simple starter template using the Vue + Vue-router + Pinia stack. Includes built-in formatting with rslint and testing with rstest.

### Rslib Starter

- [ts-lib-starter](https://github.com/ulivz/ts-lib-starter): A hassle-free TS library template, powered by Rslib.
- [rslib-npm-template](https://github.com/LLmoskk/rslib-npm-template): A starter template for developing React components with Rslib, featuring automated versioning and publishing using semantic-release.
- [web-component-starter](https://github.com/holyfata/web-component-starter): A starter for developing Web components with Rslib, featuring using stencil and useful both in React and Vue.
- [@trapar-waves/llm-template](https://github.com/Trapar-waves/llm-template): A template for LLM development integrating AI tools, TypeScript, Zod, and Rslib.
- [rstack-library-starter](https://github.com/logue/rstack-library-starter): Production-ready starter for Rsbuild/Rslib library development. Built on Rstack (Rspack, Rslib, Rstest, Rslint), with structured documentation patterns (AGENTS.md, PLAN.md), comprehensive testing, and a minimal Pico.css demo site. Validated across multiple libraries.

## Plugins

### Rspack Plugins

- [@rspack/plugin-react-refresh](https://github.com/rstackjs/rspack-plugin-react-refresh): Support React Fast Refresh.
- [@rspack/plugin-preact-refresh](https://github.com/rstackjs/rspack-plugin-preact-refresh): Support Preact Refresh.
- [rspack-manifest-plugin](https://github.com/rstackjs/rspack-manifest-plugin): An Rspack plugin for generating an asset manifest.
- [rspack-plugin-virtual-module](https://github.com/rstackjs/rspack-plugin-virtual-module): An Rspack plugin that allows you to create virtual modules.
- [html-rspack-plugin](https://github.com/rstackjs/html-rspack-plugin): Generate files to serve your Rspack bundles.
- [@aaroon/workbox-rspack-plugin](https://github.com/Clarkkkk/workbox-rspack-plugin): A plugin to use workbox in Rspack.
- [inject-manifest-plugin](https://github.com/tobua/inject-manifest-plugin): Injects a Workbox PWA manifest into a Service Worker.
- [code-inspector-plugin](https://github.com/zh-lx/code-inspector): Click an element on the page, it can automatically open the editor and position the cursor to the source code of the element.
- [rspack-plugin-mock](https://github.com/pengzhanbo/rspack-plugin-mock): Rspack and Rsbuild plugin for API mock dev server.
- [react-cosmos-plugin-rspack](https://github.com/birchill/react-cosmos-plugin-rspack/): Allows building / running React Cosmos using Rspack.
- [rspack-plugin-cli-copy](https://github.com/rstackjs/rspack-plugin-cli-copy): Start the project and automatically copy the network URL of the terminal.
- [rtlcss-rspack-plugin](https://github.com/cbbfcd/rtlcss-rspack-plugin): Rspack plugin to create a second css bundle, processed to be rtl.
- [html-inline-css-rspack-plugin](https://github.com/cbbfcd/html-inline-css-rspack-plugin) A Rspack plugin to convert external stylesheets into embedded stylesheets.
- [html-rspack-skip-assets-plugin](https://github.com/cbbfcd/html-rspack-skip-assets-plugin) Adapt `html-webpack-skip-assets-plugin` to Rspack.
- [rspack-plugin-retry-chunk-load](https://github.com/khodorammar/rspack-plugin-retry-chunk-load) Retry loading of chunks that failed to load.
- [rspack-plugin-svg-sprite](https://github.com/yichenzhu1337/rspack-plugin-svg-sprite): SVG sprite plugin for Rspack — drop-in replacement for svg-sprite-loader.
- [typia-rspack-plugin](https://github.com/colinaaa/typia-rspack-plugin): A Rspack plugin for `typia` - TypeScript transformer for runtime type checking and validation.
- [sonda](https://github.com/filipsobol/sonda): Visualizer and analyzer for JavaScript and CSS bundles.
- [@rsdoctor/rspack-plugin](https://github.com/web-infra-dev/rsdoctor/tree/main/packages/rspack-plugin): An Rspack plugin for integrating Rsdoctor.
- [rspack-deno-plugin](https://github.com/LonelySnowman/rspack-deno-plugin): Make Rspack run correctly in the deno environment.
- [rspack-circular-dependency-plugin](https://github.com/Sunny-117/rspack-circular-dependency-plugin): Detect circular dependencies in modules compiled with Rspack.
- [@nx/module-federation](https://nx.dev/nx-api/module-federation/documents/nx-module-federation-plugin): Includes several Rspack plugins for Nx and Module Federation.
- [@module-federation/enhanced](https://github.com/module-federation/core/tree/main/packages/enhanced): Provides enhanced features for Module Federation.
- [zephyr-rspack-plugin](https://www.npmjs.com/package/zephyr-rspack-plugin): An Rspack plugin for deploying applications with Zephyr Cloud.
- [rspack-s3-plugin](https://github.com/ts-codeworks/rspack-s3-plugin): A Rspack plugin for uploading compiled assets to Amazon S3 after build.
- [compression-rspack-plugin](https://github.com/ramon-villain/compression-rspack-plugin): Rust-native parallel compression plugin for Rspack. Drop-in replacement for compression-webpack-plugin with gzip, brotli, deflate, and deflateRaw — all parallelized across CPU cores via Rust + rayon.
- [rspack-plugin-solid-svg](https://github.com/solarlime/rspack-plugin-solid-svg): Rspack plugin for transforming SVG files into SolidJS components.
- [case-sensitive-paths-webpack-plugin](https://github.com/Urthen/case-sensitive-paths-webpack-plugin): Enforces case sensitive paths of all required modules.
- [clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin): Remove your build folder before building.
- [compression-webpack-plugin](https://github.com/webpack-contrib/compression-webpack-plugin): Prepare compressed versions of assets to serve them with Content-Encoding.
- [css-minimizer-webpack-plugin](https://github.com/webpack-contrib/css-minimizer-webpack-plugin): Uses cssnano to optimize and minify your CSS.
- [dotenv-webpack](https://github.com/mrsteele/dotenv-webpack): A secure plugin that supports dotenv and other environment variables.
- [eslint-rspack-plugin](https://github.com/rstackjs/eslint-rspack-plugin): Rspack plugin to run ESLint checks during the compilation.
- [ts-checker-rspack-plugin](https://github.com/rstackjs/ts-checker-rspack-plugin): Runs TypeScript type checker on a separate process.
- [node-polyfill-webpack-plugin](https://github.com/Richienb/node-polyfill-webpack-plugin): Polyfill Node.js core modules.
- [webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer): Visualize size of webpack output files with an interactive zoomable treemap.
- [webpackbar](https://github.com/unjs/webpackbar): Elegant ProgressBar and Profiler for Rspack.
- [rspack-unocss-plugin](https://github.com/umbrella22/rspack-unocss-plugin): Native UnoCSS integration for Rspack with virtual CSS modules and native CSS processing.
- [@unocss/webpack](https://github.com/unocss/unocss/tree/main/packages-integrations/webpack): Plugin for UnoCSS.
- [@vanilla-extract/webpack-plugin](https://github.com/vanilla-extract-css/vanilla-extract): Integrating vanilla-extract with webpack / Rspack.
- [@datadog/rspack-plugin](https://github.com/DataDog/build-plugins): A Rspack plugin to interact with Datadog from your builds.
- [@sentry/webpack-plugin](https://github.com/getsentry/sentry-javascript-bundler-plugins): Provides source map and release management support for Sentry.
- [@serwist/webpack-plugin](https://github.com/serwist/serwist): generate a manifest of local files for progressive web apps.
- [@vue-devtools-rstack/rspack](https://github.com/OskarLebuda/vue-devtools-rstack/tree/main/packages/rspack): Integrates Vue DevTools with raw Rspack setups, with feature parity with `vite-plugin-vue-devtools`.
- [@octanejs/rspack-plugin](https://octanejs.dev/docs/build-tools#rspack): Rspack loader and compiler plugin for Octane TSRX source.
- [@golar-rstack/rspack](https://github.com/OskarLebuda/golar-rstack-plugin/tree/main/packages/rspack): Runs golar type checking and type-aware linting in a separate process as an Rspack plugin.
- [@lunora/rspack](https://github.com/anolilab/lunora/tree/alpha/packages/rspack): Rspack and Rsbuild integration for the Lunora realtime backend framework on Cloudflare Workers.

### Rspack Loaders

Rspack and Rsbuild support most of the webpack loaders, such as:

- [babel-loader](https://github.com/babel/babel-loader): Transpiling JavaScript files using Babel.
- [css-loader](https://github.com/webpack-contrib/css-loader): Interprets @import and url() in CSS files and resolve them.
- [sass-loader](https://github.com/webpack-contrib/sass-loader): Compiles Sass/SCSS files to CSS.
- [less-loader](https://github.com/webpack-contrib/less-loader): Compiles Less to CSS.
- [stylus-loader](https://github.com/webpack-contrib/stylus-loader): Compiles Stylus to CSS.
- [postcss-loader](https://github.com/webpack-contrib/postcss-loader): Loader to process CSS with PostCSS.
- [style-loader](https://github.com/webpack-contrib/style-loader): Inject CSS into the DOM.
- [html-loader](https://www.npmjs.com/package/html-loader): Exports HTML as string.
- [rspack-vue-loader](https://github.com/rstackjs/rspack-vue-loader): Vue loader for Rspack.
- [svelte-loader](https://github.com/sveltejs/svelte-loader): Loader for svelte components.
- [imports-loader](https://www.npmjs.com/package/imports-loader): Use modules that depend on specific global variables.
- [source-map-loader](https://github.com/webpack-contrib/source-map-loader): Extracts source maps from existing source files.
- [svg-react-loader](https://github.com/jhamlet/svg-react-loader): Turn SVGs into React Components.
- [svgo-loader](https://github.com/svg/svgo-loader): Loader for SVGO.
- [coffee-loader](https://www.npmjs.com/package/coffee-loader): Compile CoffeeScript to JavaScript.
- [node-loader](https://www.npmjs.com/package/node-loader): Allows to connect native node modules with .node extension.
- [@mdx-js/loader](https://github.com/mdx-js/mdx/tree/main/packages/loader): Loader for MDX.
- [@svgr/webpack](https://github.com/gregberge/svgr/tree/main/packages/webpack): Loader for SVGR.
- [yaml-loader](https://github.com/eemeli/yaml-loader): Allows importing YAML files as JS objects.
- [react-compiler-webpack](https://github.com/SukkaW/react-compiler-webpack): The webpack / Rspack loader for React Compiler.
- [worker-rspack-loader](https://github.com/rstackjs/worker-rspack-loader): An Rspack loader that registers a script as a Web Worker.
- [rsbuild-plugin-markdown-loader](https://github.com/aliezzahn/rsbuild-plugin-markdown-loader): Importing and rendering Markdown files as React components or pure HTML.
- [@vue-vine/rspack-loader](https://github.com/vue-vine/vue-vine): Rspack loader for Vue Vine.
- [@tailwindcss/webpack](https://github.com/tailwindlabs/tailwindcss/tree/main/packages/%40tailwindcss-webpack): A webpack loader for Tailwind CSS v4.
- [oxc-webpack-loader](https://github.com/oxc-project/oxc-webpack-loader): Uses Oxc for fast JavaScript and TypeScript transformation.

### Rsbuild Plugins

#### For React

- [@rsbuild/plugin-react](https://rsbuild.rs/plugins/list/plugin-react): Provides support for React.
- [rsbuild-plugin-react-router](https://github.com/rstackjs/rsbuild-plugin-react-router): Provides seamless integration with React Router.
- [@rsbuild/plugin-svgr](https://rsbuild.rs/plugins/list/plugin-svgr): Support convert SVG to React components.
- [@rsbuild/plugin-styled-components](https://github.com/rstackjs/rsbuild-plugin-styled-components): Provides compile-time support for styled-components.
- [rsbuild-plugin-rsc](https://github.com/rstackjs/rsbuild-plugin-rsc): React Server Components (RSC) support for Rsbuild.
- [rsbuild-plugin-react-inspector](https://github.com/hunghg255/rsbuild-plugin-react-inspector): Allows automatic jumping to the local IDE when clicking on a browser element.
- [rsbuild-react-generate-pages](https://github.com/hunghg255/rsbuild-react-generate-pages): Generate pages for React app based on the directory structure and `react-router-dom` configuration.

#### For Vue

- [@rsbuild/plugin-vue](https://rsbuild.rs/plugins/list/plugin-vue): Provides support for Vue 3 SFC (Single File Components).
- [@rsbuild/plugin-vue-jsx](https://github.com/rstackjs/rsbuild-plugin-vue-jsx): Provides support for Vue 3 JSX / TSX syntax.
- [@rsbuild/plugin-vue2](https://github.com/rstackjs/rsbuild-plugin-vue2): Provides support for Vue 2 SFC (Single File Components).
- [@rsbuild/plugin-vue2-jsx](https://github.com/rstackjs/rsbuild-plugin-vue2-jsx): Provides support for Vue 2 JSX / TSX syntax.
- [@vue-devtools-rstack/rsbuild](https://github.com/OskarLebuda/vue-devtools-rstack/tree/main/packages/rsbuild): Integrates Vue DevTools with Rsbuild, with feature parity with `vite-plugin-vue-devtools`.
- [rsbuild-plugin-unplugin-vue](https://github.com/rstackjs/rsbuild-plugin-unplugin-vue): Integrates `unplugin-vue` for Vue SFC compilation.
- [rsbuild-plugin-vue-inspector](https://github.com/hunghg255/rsbuild-plugin-vue-inspector): Allows automatic jumping to the local IDE when clicking on a browser element.
- [rsbuild-plugin-vue-legacy](https://github.com/skymoonya/rsbuild-plugin-vue-legacy): Support for Vue versions below 2.7 by setting an alias for `vue`.
- [rspack-plugin-svg](https://github.com/fuxichen/rspack-plugin-svg): Rsbuild plugin to load SVG files as Vue components, using SVGO for optimization.
- [@mutsuntsai/rsbuild-plugin-vue-ssg](https://github.com/mutsuntsai/rsbuild-plugin-vue-ssg): Generate Vue SSG contents and inject those into HTML for Rsbuild.
- [@vue-vine/rsbuild-plugin](https://github.com/vue-vine/vue-vine): Rsbuild plugin for Vue Vine.
- [@vizejs/rspack-plugin](https://github.com/ubugeeei/vize): High-Performance Vue.js Toolchain in Rust.
- [rsbuild-plugin-vue-mcp](https://github.com/BrightX/rsbuild-plugin-vue-mcp): Integrates Vue DevTools with MCP to expose Vue component trees, component state, and Pinia stores to AI tools.

#### For Preact

- [@rsbuild/plugin-preact](https://rsbuild.rs/plugins/list/plugin-preact): Provides support for Preact.

#### For Svelte

- [@rsbuild/plugin-svelte](https://rsbuild.rs/plugins/list/plugin-svelte): Provides support for Svelte components (`.svelte` files).
- [rsbuild-plugin-svelte-inspector](https://github.com/hunghg255/rsbuild-plugin-svelte-inspector): Allows automatic jumping to the local IDE when clicking on a browser element.

#### For Solid

- [@rsbuild/plugin-solid](https://rsbuild.rs/plugins/list/plugin-solid): Provides support for Solid.

#### For Lynx

- [relog-rsbuild-plugin](https://github.com/nanofuxion/relog-rsbuild-plugin): Allows you to intercept `console.log()` calls from your LynxJS app running on a device or emulator and send them back to the Rsbuild dev server.
- [ngrok-rsbuild-plugin](https://github.com/nanofuxion/ngrok-rsbuild-plugin): Expose your Rsbuild dev server over the internet via ngrok — built for use with the LynxJS app.
- [lynxjs-app-config-plugin](https://github.com/HimanshuKumarDutt094/lynxjs-app-config-plugin): Rsbuild plugin to inject application icons, permissions and minimal app config changes into Android / iOS project folders.

#### Common

- [@rsbuild/plugin-assets-retry](https://github.com/rstackjs/rsbuild-plugin-assets-retry): Used to automatically resend requests when static assets fail to load.
- [@rsbuild/plugin-babel](https://rsbuild.rs/plugins/list/plugin-babel): Provides support for Babel transpilation capabilities.
- [@rsbuild/plugin-basic-ssl](https://github.com/rstackjs/rsbuild-plugin-basic-ssl): Generate an untrusted, self-signed certificate for the HTTPS server.
- [@rsbuild/plugin-eslint](https://github.com/rstackjs/rsbuild-plugin-eslint): Used to run ESLint checks during the compilation.
- [@rsbuild/plugin-type-check](https://github.com/rstackjs/rsbuild-plugin-type-check): Used to run TypeScript type checker on a separate process.
- [@rsbuild/plugin-image-compress](https://github.com/rstackjs/rsbuild-plugin-image-compress): Compress the image assets.
- [@rsbuild/plugin-mdx](https://github.com/rstackjs/rsbuild-plugin-mdx): Provide support for MDX.
- [@rsbuild/plugin-node-polyfill](https://github.com/rstackjs/rsbuild-plugin-node-polyfill): Used to inject polyfills of Node core modules in the browser side.
- [@rsbuild/plugin-source-build](https://github.com/rstackjs/rsbuild-plugin-source-build): This plugin is designed for the monorepo scenario. It supports referencing source code from other subdirectories and performs build and hot update.
- [@rsbuild/plugin-sass](https://rsbuild.rs/plugins/list/plugin-sass): Sass plugin for Rsbuild.
- [@rsbuild/plugin-less](https://rsbuild.rs/plugins/list/plugin-less): Less plugin for Rsbuild.
- [@rsbuild/plugin-stylus](https://rsbuild.rs/plugins/list/plugin-stylus): Use Stylus as the CSS preprocessor.
- [@rsbuild/plugin-tailwindcss](https://rsbuild.rs/plugins/list/plugin-tailwindcss): Integrates Tailwind CSS v4 in Rsbuild.
- [@rsbuild/plugin-check-syntax](https://github.com/rstackjs/rsbuild-plugin-check-syntax): Used to analyze the syntax compatibility of artifacts, to see if there are any advanced syntaxes that may cause compatibility issues.
- [@rsbuild/plugin-css-minimizer](https://github.com/rstackjs/rsbuild-plugin-css-minimizer): Used to customize CSS minimizer, switch to [cssnano](https://cssnano.co/) or other tools for CSS compression.
- [@rsbuild/plugin-typed-css-modules](https://github.com/rstackjs/rsbuild-plugin-typed-css-modules): Generate TypeScript declaration files for CSS Modules.
- [@rsbuild/plugin-pug](https://github.com/rstackjs/rsbuild-plugin-pug): Provides support for the Pug template engine.
- [@rsbuild/plugin-rem](https://github.com/rstackjs/rsbuild-plugin-rem): Implements the rem adaptive layout for mobile pages.
- [@rsbuild/plugin-umd](https://github.com/rstackjs/rsbuild-plugin-umd): Used to build outputs in UMD format.
- [@rsbuild/plugin-yaml](https://github.com/rstackjs/rsbuild-plugin-yaml): Used to import YAML files and convert them into JavaScript objects.
- [@rsbuild/plugin-toml](https://github.com/rstackjs/rsbuild-plugin-toml): Used to import TOML files and convert them into JavaScript objects.
- [rsbuild-plugin-virtual-module](https://github.com/rstackjs/rsbuild-plugin-virtual-module): Used to create virtual modules with loader API.
- [rsbuild-plugin-dts](https://github.com/web-infra-dev/rslib/tree/main/packages/plugin-dts): Generate TypeScript declaration files.
- [rsbuild-plugin-ejs](https://github.com/rstackjs/rsbuild-plugin-ejs): Provide support for the EJS template engine.
- [rsbuild-plugin-print](https://github.com/hunghg255/rsbuild-plugin-print): Print text, show host with qrcode.
- [rsbuild-plugin-console-debug](https://github.com/hunghg255/rsbuild-plugin-console-debug): Output debug information in the console.
- [rsbuild-plugin-generate-file](https://github.com/sumy7/rsbuild-plugin-generate-file): Generate static file and write them to dist folder after packaging.
- [rsbuild-plugin-google-analytics](https://github.com/rstackjs/rsbuild-plugin-google-analytics): Setup Google Analytics in your website.
- [rsbuild-plugin-web-extension](https://github.com/filc-dev/rsbuild-plugin-web-extension): Rsbuild plugin for Chrome/web extension.
- [rsbuild-plugin-web-ext](https://github.com/xbzhang2020/rsbuild-plugin-web-ext/tree/main/packages/rsbuild): A Rsbuild plugin for developing and building browser extensions.
- [rsbuild-plugin-open-graph](https://github.com/rstackjs/rsbuild-plugin-open-graph): Generate Open Graph meta tags.
- [rsbuild-plugin-posthog](https://github.com/m1911star/rsbuild-plugin-posthog): Rsbuild plugin for PostHog.
- [@webx-kit/rsbuild-plugin](https://github.com/tmkx/webx-kit): Rsbuild plugin for Web eXtension development.
- [plugin-sails-content](https://github.com/sailscastshq/sails-content/packages/plugin-sails-content): Rsbuild plugin for [Sails Content](https://docs.sailscasts.com/content/).
- [rsbuild-plugin-html-minifier-terser](https://github.com/rstackjs/rsbuild-plugin-html-minifier-terser): An Rsbuild plugin to use `html-minifier-terser` to minify the HTML outputs.
- [rsbuild-plugin-glsl](https://github.com/sakitam-fdd/rsbuild-plugin-glsl): An Rsbuild plugin to import inline (and compress) GLSL shader.
- [rsbuild-plugin-marko](https://github.com/ipseonet/rsbuild-plugin-marko): An Rsbuild plugin to provide support for the Marko template engine.
- [rsbuild-plugin-monaco-editor-nls](https://github.com/zackshen/rsbuild-plugin-monaco-editor-nls): An Rsbuild plugin to localize monaco-editor.
- [rsbuild-plugin-auto-alias](https://github.com/jwyGithub/rsbuild-plugin-auto-alias): Automatically generate alias based on path.
- [rsbuild-plugin-svg-sprite](https://github.com/yichenzhu1337/rspack-plugin-svg-sprite): SVG sprite plugin for Rsbuild — drop-in replacement for svg-sprite-loader.
- [rsbuild-plugin-tailwindcss](https://github.com/rstackjs/rsbuild-plugin-tailwindcss): An Rsbuild plugin to integrate with Tailwind CSS.
- [rsbuild-plugin-i18next-extractor](https://github.com/rstackjs/rsbuild-plugin-i18next-extractor): An Rsbuild plugin using [i18next-cli](https://github.com/i18next/i18next-cli) to extract i18n translations.
- [rsbuild-auto-i18n-plugin](https://github.com/auto-i18n/auto-i18n-translation-plugins): An Rsbuild plugin for automatic translation with support for multiple translation services and custom translators.
- [@module-federation/rsbuild-plugin](https://module-federation.io/guide/basic/rsbuild): An Rsbuild plugin for integrating Module Federation v2.
- [rsbuild-plugin-fusion](https://github.com/mpaynesecurity/rsbuild-plugin-fusion): Run server code directly from any Rsbuild supported UI framework.
- [rsbuild-plugin-hydra](https://github.com/mpaynesecurity/rsbuild-plugin-hydra): Turn any Rsbuild app into a lightweight fullstack framework.
- [rsbuild-plugin-wasmpack](https://github.com/im-neiru/rsbuild-plugin-wasmpack): compile Rust crates to WebAssembly using wasm-pack.
- [rsbuild-plugin-publint](https://github.com/rstackjs/rsbuild-plugin-publint): Run `publint` to lint npm packages after the build.
- [rsbuild-plugin-aws-lambda](https://github.com/wxiaoyun/rsbuild-plugin-aws-lambda): An Rsbuild plugin to configure rsbuild to bundle js assets suitable for AWS Lambda.
- [@devjskit/rsbuild-plugin-langs](https://github.com/devjskit/rsbuild-plugin-langs): Extract content from JSON files and merge into a multi-language file.
- [@seed-design/rsbuild-plugin](https://github.com/daangn/seed-design): An Rsbuild plugin for the Seed design system.
- [rsbuild-plugin-arco](https://github.com/zhmushan/rsbuild-plugin-arco): Rsbuild plugins for Arco Design.
- [rsbuild-plugin-css-optimizer](https://github.com/aliezzahn/rsbuild-plugin-css-optimizer): Customize CSS minification, allowing you to choose between cssnano (JavaScript-based) or Lightning CSS (Rust-based) for high-performance CSS compression.
- [rsbuild-plugin-devtools-json](https://github.com/rstackjs/rsbuild-plugin-devtools-json): Generating `com.chrome.devtools.json` on the fly in the dev server.
- [rsbuild-plugin-rempa](https://github.com/sumy7/rsbuild-plugin-rempa): A Rsbuild plugin designed to collect pages and generate a Multi-Page Application (MPA).
- [rsbuild-plugin-iconify](https://github.com/pathscale/iconify-preload): A Rsbuild plugin that automatically generates optimized CSS with embedded SVG icons from Iconify.
- [rsbuild-plugin-arethetypeswrong](https://github.com/rstackjs/rsbuild-plugin-arethetypeswrong): Checking TypeScript type definitions with `arethetypeswrong`.
- [zephyr-rsbuild-plugin](https://www.npmjs.com/package/zephyr-rsbuild-plugin): An Rsbuild plugin for deploying applications with Zephyr Cloud.
- [rsbuild-plugin-protobufjs](https://github.com/baranwang/rsbuild-plugin-protobufjs): An Rsbuild plugin that integrates `protobufjs`.
- [rsbuild-plugin-cdn-import](https://github.com/fuxichen/rsbuild-plugin-cdn-import): Import modules from CDN with Rsbuild plugin.
- [rsbuild-plugin-mcp](https://github.com/colinaaa/rsbuild-plugin-mcp): Rsbuild plugin that enables a MCP server for your Rsbuild app to provide information about your setup and modules graphs.
- [rsbuild-plugin-workspace-dev](https://github.com/rstackjs/rsbuild-plugin-workspace-dev): Start monorepo sub-projects in topological order.
- [rsbuild-plugin-stylelint](https://github.com/zalishchuk/rsbuild-plugin-stylelint): Used to run Stylelint checks during the compilation.
- [rsbuild-plugin-block-imports](https://github.com/malekabdelkader/rsbuild-plugin-block-imports): Rsbuild plugin to detect and block forbidden imports in Module Federation builds.
- [rsbuild-plugin-compression](https://github.com/s-r-x/rsbuild-plugin-compression): Compress the assets using gzip, brotli or zstd.
- [rsbuild-plugin-pwa](https://github.com/s-r-x/rsbuild-plugin-pwa): Zero-config PWA support for rsbuild
- [@plugin-cra-proxy/rsbuild](https://github.com/robertpanvip/plugin-cra-proxy/tree/main/packages/rsbuild): A development proxy plugin for Rsbuild, mimicking Create React App proxy behavior.
- [rsbuild-plugin-oxlint](https://github.com/robertpanvip/rsbuild-plugin-lint/tree/main/packages/oxlint): Plugin for Integrating Oxlint into the Rsbuild Build Process.
- [rsbuild-plugin-rslint](https://github.com/robertpanvip/rsbuild-plugin-lint/tree/main/packages/rslint): Plugin for Integrating Rslint into the Rsbuild Build Process.
- [rsbuild-plugin-biome](https://github.com/robertpanvip/rsbuild-plugin-lint/tree/main/packages/biome): Plugin for Integrating Biome into the Rsbuild Build Process.
- [@octanejs/rsbuild-plugin](https://octanejs.dev/docs/build-tools#rsbuild): Rsbuild metaframework plugin for Octane, including routing, SSR, hydration, and production builds.
- [@golar-rstack/rsbuild](https://github.com/OskarLebuda/golar-rstack-plugin/tree/main/packages/rsbuild): Runs golar type checking and type-aware linting in a separate process as an Rsbuild plugin.
- [rsbuild-plugin-ssg](https://github.com/jhanca-vm/rsbuild-plugin-ssg): Prerender pages at build time with zero-JS by default and Islands Architecture support.

### Rspress Plugins

- [@rspress/plugin-llms](https://rspress.rs/plugin/official-plugins/llms): Generates `llms.txt` and `llms-full.txt` files for your docs site.
- [@rspress/plugin-sitemap](https://rspress.rs/plugin/official-plugins/sitemap): Generates `sitemap.xml` for your website.
- [@rspress/plugin-client-redirects](https://rspress.rs/plugin/official-plugins/client-redirects): Supports client-side redirects for moved routes.
- [@rspress/plugin-typedoc](https://rspress.rs/plugin/official-plugins/typedoc): Integrate [TypeDoc](https://github.com/TypeStrong/typedoc), used to generate API documentation of TS module automatically.
- [@rspress/plugin-api-docgen](https://rspress.rs/plugin/official-plugins/api-docgen): Generates API documentation from TypeScript declarations.
- [@rspress/plugin-preview](https://rspress.rs/plugin/official-plugins/preview): Support preview of code blocks in Markdown/MDX.
- [@rspress/plugin-playground](https://rspress.rs/plugin/official-plugins/playground): Provide a real-time playground to preview the code blocks in Markdown/MDX files.
- [@rspress/plugin-rss](https://rspress.rs/plugin/official-plugins/rss): Generates RSS files for specific document pages with [feed](https://github.com/jpmonette/feed).
- [@rspress/plugin-algolia](https://rspress.rs/plugin/official-plugins/algolia): Integrates Algolia DocSearch for site search.
- [@rspress/plugin-twoslash](https://rspress.rs/plugin/official-plugins/twoslash): Adds TypeScript Twoslash support for code blocks.
- [rspress-plugin-typesense](https://github.com/typesense/rspress-plugin-typesense): Integrates Typesense for typo-tolerant search.
- [@seshuk/rspress-plugin-scalar](https://github.com/maximseshuk/rspress-plugin-scalar): Renders interactive Scalar API reference pages from OpenAPI specifications.
- [rspress-plugin-translate](https://github.com/byteHulk/rspress-plugin-translate): Automatically translate your content behind the scenes using GPT's.
- [rspress-plugin-shiki](https://github.com/hunghg255/rspress-plugin-shiki): Rspress plugin shiki with transformer.
- [rspress-plugin-remote-page](https://github.com/ulivz/rspress-plugin-remote-page): Load remote markdown file (e.g. README.md) onto your website.
- [rspress-plugin-font-open-sans](https://github.com/rstackjs/rspress-plugin-font-open-sans): Use Open Sans as the default font in your Rspress website.
- [rspress-plugin-align-image](https://github.com/rstackjs/rspress-plugins/tree/main/packages/rspress-plugin-align-image): Rspress plugin to align images in markdown.
- [rspress-plugin-directives](https://github.com/rstackjs/rspress-plugins/tree/main/packages/rspress-plugin-directives): Rspress plugin for custom directives support.
- [rspress-plugin-file-tree](https://github.com/rstackjs/rspress-plugins/tree/main/packages/rspress-plugin-file-tree): Rspress plugin that add tree view for file structure display.
- [rspress-plugin-gh-pages](https://github.com/rstackjs/rspress-plugins/tree/main/packages/rspress-plugin-gh-pages): Rspress plugin to add support for automatic deployment to GitHub Pages.
- [rspress-plugin-google-analytics](https://github.com/rstackjs/rspress-plugins/tree/main/packages/rspress-plugin-google-analytics): Rspress plugin for Google Analytics integration.
- [rspress-plugin-vercel-analytics](https://github.com/rstackjs/rspress-plugins/tree/main/packages/rspress-plugin-vercel-analytics): Rspress plugin for Vercel Analytics integration.
- [rspress-plugin-katex](https://github.com/rstackjs/rspress-plugins/tree/main/packages/rspress-plugin-katex): Rspress plugin to add support for rendering math equations using [KaTeX](https://katex.org/).
- [rspress-plugin-live2d](https://github.com/rstackjs/rspress-plugins/tree/main/packages/rspress-plugin-live2d): Rspress plugin for live2d, powered by [on-my-live2d](https://oml2d.com/).
- [rspress-plugin-mermaid](https://github.com/rstackjs/rspress-plugins/tree/main/packages/rspress-plugin-mermaid): Rspress plugin to render [Mermaid](https://mermaid.js.org/#/) diagrams in markdown files.
- [rspress-plugin-reading-time](https://github.com/rstackjs/rspress-plugins/tree/main/packages/rspress-plugin-reading-time): Rspress plugin to display reading time for your document pages.
- [rspress-plugin-supersub](https://github.com/rstackjs/rspress-plugins/tree/main/packages/rspress-plugin-supersub): Rspress plugin to add superscript(`<super></super>`) and subscript(`<sub></sub>`) support.
- [rspress-plugin-toc](https://github.com/rstackjs/rspress-plugins/tree/main/packages/rspress-plugin-toc): Rspress plugin that injects a table of contents into the page.
- [rspress-plugin-clarity](https://github.com/jl917/rspress-plugin-clarity): Rspress plugin for [Clarity](https://clarity.microsoft.com/) integration.
- [rspress-plugin-sitemap](https://github.com/jl917/rspress-plugin-sitemap): Automatically generate SEO-related sitemaps.
- [rspress-plugin-mention-github](https://github.com/hunghg255/rspress-plugin-mention-github): Rspress plugin mention github user, or any link.
- [rspress-plugin-changelog](https://github.com/baranwang/rspress-plugin-changelog): Generates changelog pages, fetching release information from GitHub and GitLab repositories.
- [rspress-plugin-annotation-words](https://github.com/2heal1/rspress-plugin-annotation-words): An Rspress plugin to support annotation words.
- [rspress-plugin-font-figtree](https://github.com/maccuaa/rspress-plugin-font-figtree): Use Figtree as the default font in your Rspress website.
- [zephyr-rspress-plugin](https://www.npmjs.com/package/zephyr-rspress-plugin): An Rspress plugin for deploying applications with Zephyr Cloud.
- [rspress-language-tabs](https://github.com/maccuaa/rspress-language-tabs): An Rspress component for creating tabbed code examples with programming language icons.
- [rspress-plugin-auto-sidebar](https://github.com/buyfakett/rspress-plugin-auto-sidebar): Automatically generate the sidebar from the navbar configuration.
- [rspress-plugin-giscus](https://github.com/buyfakett/rspress-plugin-giscus): Integrate [giscus](https://github.com/giscus/giscus) into Rspress, a comment system powered by GitHub Discussions.
- [rspress-plugin-blog-list](https://github.com/buyfakett/rspress-plugin-blog-list): Integrate blog list into Rspress.
- [rspress-plugin-pdf-generator](https://github.com/MaxtuneLee/rspress-plugin-pdf-generator): Generates multi-language single-page or multi-page PDF documents from Rspress site during build process.
- [rspress-plugin-viz](https://github.com/elecmonkey/rspress-plugin-viz): Add Graphviz support for Rspress using `@viz-js/viz`.

### Unplugin

Rspack and Rsbuild support most of the [unplugin](https://github.com/unplugin), such as:

- [unplugin-vue](https://www.npmjs.com/package/unplugin-vue): Transform Vue 3 SFC to JavaScript.
- [unplugin-vue-components](https://github.com/unplugin/unplugin-vue-components): On-demand components auto importing for Vue.
- [unplugin-element-plus](https://github.com/element-plus/unplugin-element-plus): Import Element Plus on demand.
- [unplugin-auto-import](https://github.com/unplugin/unplugin-auto-import): Auto import APIs on-demand.
- [@stylexjs/unplugin](https://www.npmjs.com/package/@stylexjs/unplugin): Universal bundler plugin for StyleX.
- [@arco-plugins/unplugin-react](https://www.npmjs.com/package/@arco-plugins/unplugin-react): A plugin to help you use Arco Design React.
- [@tanstack/router-plugin](https://www.npmjs.com/package/@tanstack/router-plugin): Automatically generate configuration for TanStack Router.
- [unplugin-build-info](https://github.com/renzp94/unplugin-build-info): Print the build information on the console.
- [unplugin-info](https://github.com/yjl9903/unplugin-info): Export build information as a virtual module.
- [unplugin-turbo-console](https://github.com/unplugin/unplugin-turbo-console): Improve the Developer Experience of console.
- [unplugin-vue-macros](https://github.com/vue-macros/vue-macros): Explore more macros and syntax sugar to Vue.
- [unplugin-inject-preload](https://github.com/Applelo/unplugin-inject-preload): Inject `<link rel="preload">` to your index.html based on your build assets. Need to be used with HTMLWebpackPlugin or HTMLRspackPlugin.
- [@intlify/unplugin-vue-i18n](https://github.com/intlify/bundle-tools/tree/main/packages/unplugin-vue-i18n): unplugin for Vue I18n.
- [@formatjs/unplugin](https://www.npmjs.com/package/@formatjs/unplugin): Universal build plugin for FormatJS.
- [unplugin-ast](https://github.com/unplugin/unplugin-ast): Manipulate the AST to transform your code.
- [unplugin-build-meta](https://github.com/luxass/unplugin-build-meta): Import build metadata into your JavaScript/TypeScript projects.
- [unplugin-dts](https://github.com/qmhc/unplugin-dts): An unplugin that generates declaration files (\*.d.ts).
- [unplugin-icons](https://github.com/unplugin/unplugin-icons): Access thousands of icons as components on-demand universally.
- [@iconify/unplugin](https://github.com/iconify/iconify-unplugin): Generate icon components on demand from Iconify.
- [unplugin-favicons](https://github.com/anolilab/unplugin-favicons): Generate favicons for your project with caching for blazing fast rebuilds.
- [unplugin-macros](https://github.com/unplugin/unplugin-macros): Macros plugin for bundlers.
- [zod-compiler](https://github.com/gajus/zod-compiler): Compile Zod schemas into zero-overhead validation functions at build time.
- [unplugin-ata](https://github.com/ata-core/unplugin-ata): Compile JSON Schema files into standalone ata-validator modules with TypeScript declarations at build time.
- [unplugin-oxc](https://github.com/unplugin/unplugin-oxc): Transform and minify JavaScript and TypeScript with Oxc.

## Rstest Adapters

- [@rstest/adapter-rspack](https://github.com/web-infra-dev/rstest/tree/main/packages/adapter-rspack): Rstest adapter for Rspack configuration.
- [@rstest/adapter-rsbuild](https://github.com/web-infra-dev/rstest/tree/main/packages/adapter-rsbuild): Rstest adapter for Rsbuild configuration.
- [@rstest/adapter-rslib](https://github.com/web-infra-dev/rstest/tree/main/packages/adapter-rslib): Rstest adapter for Rslib configuration.
- [@modern-js/adapter-rstest](https://github.com/web-infra-dev/modern.js/tree/main/packages/cli/adapter-rstest): Rstest adapter for Modern.js configuration.

## Rstest Utilities

- [rstest-fetch-mock](https://github.com/rstackjs/rstest-fetch-mock): Mock the global fetch API in Rstest tests.
- [rstest-canvas-mock](https://github.com/rstackjs/rstest-canvas-mock): Mock the Canvas API in Rstest tests.
- [rstest-sonar-reporter](https://github.com/onigoetz/rstest-sonar-reporter): A Rstest reporter that outputs test results in SonarQube's Generic Test Execution XML format.
- [path-serializer](https://github.com/rstackjs/path-serializer): A snapshot serializer that normalizes system-specific paths for stable snapshots.
- [effect-rstest](https://github.com/Nsttt/effect-rstest): Effect test helpers for Rstest, with shared layers, test services, and property testing.

## Deployment

- [Zephyr Cloud](https://zephyr-cloud.io): A cloud-agnostic deployment platform offering sub-seconds `deploy from one command` experience.

## Libraries

- [@rspack/dev-server](https://github.com/rstackjs/rspack-dev-server): Dev server for Rspack, provides the same API as webpack-dev-server.
- [@rspack/dev-middleware](https://github.com/rstackjs/rspack-dev-middleware): A development middleware for Rspack.
- [@rspack/resolver](https://github.com/rstackjs/rspack-resolver): A Rust port of enhanced-resolve.
- [@rspack/lite-tapable](https://github.com/rstackjs/rspack-lite-tapable): Lite weight tapable for Rspack.
- [rspack-chain](https://github.com/rstackjs/rspack-chain): A chaining API to generate and simplify the modification of Rspack configurations.
- [rspack-merge](https://github.com/rstackjs/rspack-merge): Smart configuration merging for Rspack.
- [Sails Shipwright](https://github.com/sailshq/sails-hook-shipwright) - The modern asset pipeline for [Sails](https://sailsjs.com) powered by Rsbuild.
- [rspackify](https://github.com/SyMind/rspackify): Experience lightning-fast builds by instantly switching from webpack to Rspack.
- [Spinpack](https://github.com/denniscual/spinpack): A CLI tool that turbocharges the developer server experience for CRA projects with Rspack.
- [Jetpack](https://github.com/KidkArolis/jetpack): Jetpack wraps Rspack to create a smoother developer experience.

## Blogs

### Rspack Team

Blogs from the Rspack team:

- [rspack.rs/blogs](https://rspack.rs/blog/)
- [web-infra-dev/blogs](https://github.com/web-infra-dev/blogs)

### Community

English blogs:

- [2026-06] [TanStack Start Adds First-Class Rsbuild Support](https://tanstack.com/blog/start-adds-rsbuild-support)
- [2026-05] [Yelp Engineering: Optimizing Our Build Times by Migrating from Webpack to Rspack](https://engineeringblog.yelp.com/2026/05/optimizing-our-build-times-by-migrating-from-webpack-to-rspack.html)
- [2026-03] [Rspress 2.0: AI-Native Documentation, Faster Startup and a Redesigned Theme](https://www.infoq.com/news/2026/03/rspress-docs-2-release)
- [2026-01] [Transforming SVGs to Vue and Svelte Components: The SVGR Alternative for Rsbuild](https://hackernoon.com/transforming-svgs-to-vue-and-svelte-components-the-svgr-alternative-for-rsbuild)
- [2025-12] [Goodbye Webpack, Hello Rspack (and 80% Faster Builds)](https://developers.mews.com/goodbye-webpack-hello-rspack-and-80-faster-builds/)
- [2025-12] [The JavaScript Bundler Grand Prix](https://redmonk.com/kholterhoff/2025/12/16/javascript-bundler-grand-prix/)
- [2025-08] [Rspack Introduces Rslint, a TypeScript-First Linter Written in Go](https://socket.dev/blog/rspack-introduces-rslint-a-typescript-first-linter-written-in-go)
- [2025-08] [Question-based web performance analysis using rsdoctor/mcp-server](https://dev.to/husdev/question-based-web-performance-analysis-using-rsdoctormcp-server-325a)
- [2025-08] [Rust Tools That Made Our Dev Team Productive Again](https://dev.to/programmerraja/rust-tools-that-made-our-dev-team-productive-again-479)
- [2025-07] [Webpack to Rspack: A Deep Dive Into Our Build Time Breakthrough](https://dev.to/diwakersurya/webpack-to-rspack-a-deep-dive-into-our-build-time-breakthrough-3ih)
- [2025-04] [My journey from Webpack to Vite and finally Rsbuild](https://www.ginkonote.com/users/flo/articles/my-journey-from-webpack-to-vite-and-finally-rsbuild@javascript)
- [2025-04] [An Introduction to JavaScript Bundler Rspack](https://blog.appsignal.com/2025/04/16/an-introduction-to-javascript-bundler-rspack.html)
- [2025-04] [Scaffolding New Apps With Angular Rspack](https://nx.dev/blog/scaffold-angular-rspack-applications):
- [2025-03] [Using Rspack with Angular](https://nx.dev/blog/using-rspack-with-angular)
- [2025-02] [Rspack: An Engineer’s Approach to Build System Innovation](https://medium.com/ekino-france/rspack-an-engineers-approach-to-build-system-innovation-924e57c596a0)
- [2025-01] [State of Rspack in Angular](https://edbzn.dev/state-of-rspack-in-angular/)
- [2025-01] [Nx and Angular with Rspack and Module Federation](https://www.angulararchitects.io/en/blog/nx-with-rspack-and-module-federation/)
- [2024-12] [Rspack with Module federation V2 is the future](https://dev.to/ibrahimshamma99/rspack-with-module-federation-v2-is-the-future-3g89)
- [2024-09] [A bundler story: migrating from Webpack to Rspack](https://medium.com/alan/a-bundler-story-migrating-from-webpack-to-rspack-f548c62f757d)
- [2024-09] [Custom chunk optimization, how code splitting works in Rspack/Webpack](https://scriptedalchemy.medium.com/custom-chunk-optimization-how-code-splitting-works-in-rspack-webpack-146a3fa3a39a)
- [2024-08] [Lessons learned switching to Rspack](https://birtles.blog/2024/08/14/lessons-learned-switching-to-rspack/)
- [2024-08] [Why Moving to Rspack and How to Use It with Bazel](https://medium.com/@yanirmanor/why-moving-to-rspack-and-how-to-use-it-with-bazel-9f66139fe493)
- [2024-08] [Module Federation users now have a clear upgrade path](https://medium.com/@gfox1984/module-federation-users-now-have-a-clear-upgrade-path-1701de23f58e)
- [2024-08] [Optimizing SPA load times with async chunks preloading (use Rsbuild)](https://mmazzarolo.com/blog/2024-08-13-async-chunk-preloading-on-load/)
- [2024-06] [Micro Frontend Setup with Nx, Rspack, Module Federation 2.0 and React](https://medium.com/@soumyanildas/micro-frontend-setup-with-nx-rspack-module-federation-2-0-and-react-698674edb09f)
- [2024-06] [From Webpack to Rspack: Slashing Build Times Effectively](https://medium.com/panorays-r-d-blog/from-webpack-to-rspack-slashing-build-times-effectively-0674fd3cc284)
- [2024-02] [Why I'm Bullish on Rspack](https://www.raygesualdo.com/posts/bullish-on-rspack/)
- [2024-02] [Rsdoctor: A Bundle Analysis Solution](https://scriptedalchemy.medium.com/rsdoctor-a-bundle-analysis-solution-ee3f720e0347)
- [2024-02] [Microfrontends with Module Federation and Rspack — Simple example](https://medium.com/@alexefimenko/microfrontends-with-module-federation-and-rspack-simple-example-730f4e6308a7)
- [2024-02] [Bun, Biome/OXC, AI Tools and Rsbuild](https://onwebfocus.com/bun)
- [2024-01] [How I migrated from CRA to Rsbuild](https://dev.to/verthon/how-i-migrated-from-cra-to-rsbuild-4ia8)
- [2024-01] [Module Federation gets upgraded, and Rspack supports it](https://scriptedalchemy.medium.com/emodule-federation-gets-upgraded-and-rspack-supports-it-5ddb0d1e9546)
- [2023-10] [Why you should migrate to Rspack from webpack](https://blog.logrocket.com/migrate-rspack-webpack/)
- [2023-08] [Rust Port of Webpack? Rspack, the New Kid on the Block](https://blog.stackademic.com/rust-port-of-webpack-rspack-the-new-kid-on-the-block-c3a3de569bfb)
- [2023-04] [What is Rspack? And how does it compare to Webpack in under 5 minutes?](https://www.hamzak.xyz/blog-posts/what-is-rspack-and-how-does-it-compare-to-webpack)
- [2023-03] [Rspack — Getting up to speed with Nx](https://blog.nrwl.io/rspack-getting-up-to-speed-with-nx-4c34540bccf2)

Chinese blogs (中文):

- [2025-04] [从 Vite 到 Rsbuild：一次意想不到的构建性能飞跃](https://juejin.cn/post/7496345478658637865)
- [2024-10] [我把大型团队项目从 Vite 前端迁移到了 Rsbuild，收益如何？](https://juejin.cn/post/7425804396292325414)
- [2024-09] [[译] 一个关于打包工具的故事：从 webpack 迁移到 Rspack](https://juejin.cn/post/7425598941859676170)
- [2024-08] [开发体验的彻底提升，从 Vite 迁移到 Rspack](https://moonvy.com/blog/post/2024/migrate-vite-to-rsbuild/)
- [2024-08] [译：前 Firefox 工程师迁移到 Rspack 的经验教训](https://juejin.cn/post/7402554147276980224)
- [2024-07] [基于 Rspack 实现大仓应用构建提效实践](https://juejin.cn/post/7389925302020014118)

Japanese blogs (日本語):

- [2025-11] [KARTEの分析システムのレガシーな開発環境を高速にする。pnpm, Rspackの導入で改善できたこと。](https://tech.plaid.co.jp/speedup-pnpm-rspack)
- [2025-08] [Rails アプリケーションのフロントエンドを webpack から Rspack に移行しました](https://tech.synchro-food.co.jp/entry/2025/08/18/180000)
- [2025-04] [Rspack に移行したらフロントエンドのビルドがめっちゃ速くなりました](https://buildersbox.corp-sansan.com/entry/2025/04/14/110000)
- [2026-05] [Rsbuildで組むVueのVRMコンポーネント。ライセンスと配信の安全性を追求したライブラリ設計](https://qiita.com/logue/items/21bb239fed2c4f4a3b2f)
- [2026-05] [なぜRsbuildスタックなのか？](https://qiita.com/logue/items/e191ed56e922b33e4c8f)

French blogs (Français):

- [2025-04] [Mon voyage depuis Webpack vers Vite et finalement Rsbuild](https://www.ginkonote.com/fr/utilisateurs/flo/articles/mon-voyage-depuis-webpack-vers-vite-et-finalement-rsbuild@javascript)

## Videos

- [2025-04]: [Zack Jackson - ByteDance, rspack, and the Future of Web Development](https://www.youtube.com/watch?v=Uo1Gf_32MK0)
- [2025-04]: [It’s Not Out Yet… But Rstest Has Me HYPED](https://www.youtube.com/watch?v=nhSCmYJew-M)
- [2025-01]: [Let’s Learn Rsbuild and Rspack](https://www.youtube.com/watch?v=wJ3abFp701k)
- [2025-01]: [Micro-Frontends in React-Native! Game Changer for Mobile Apps](https://www.youtube.com/watch?v=Lp-5wSsd5Do)
- [2024-11]: [Everything You Ever Wanted To Know About Web Bundlers (and Rspack!)](https://www.youtube.com/watch?v=ma_c6UNHddI)
- [2024-07]: [The First Real Webpack Alternative (Written in Rust!)](https://www.youtube.com/watch?v=Vn2Rq2uktLE&t=37s)
- [2024-07]: [Microfrontends with Module Federation, Rspack, React and Bit](https://www.youtube.com/watch?v=4CQEPBLxU_g&t=13s)
- [2024-06]: [Rsbuild is 3x faster than Vite](https://www.youtube.com/watch?v=w8mL_HiN9Qo&t=3s)
- [2024-02]: [Mastering Micro-Frontends With Rspack and Module Federation](https://www.youtube.com/watch?v=32_EikGKESk)
- [2024-01]: [Micro Frontends - Rspack and Module Federation v1.5](https://www.youtube.com/watch?v=_HWWaPk1vRE&t=4s)
- [2023-03]: [Rspack! The Successor of Webpack?](https://www.youtube.com/watch?v=jGTE7xAcg24)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Web Infra](https://github.com/web-infra-dev) has waived all copyright and related or neighboring rights to this work.
