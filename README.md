# Awesome Luau on npm

A handpicked list of quality [Luau](https://luau-lang.org) packages, hosted on [npm](https://www.npmjs.com). These packages follow the [Sea of Voices Luau Package Standard](https://github.com/seaofvoices/luau-package-standard).

*To submit a package, simply open an issue with a link to your repository.*

__Table of content__:
- [Data](#data): for data structures or data management packages
- [Resources](#resources): utilities to manage resources
- [Async](#async): asynchronous utilities
- [Roblox](#roblox): specific for Roblox development
- [Test](#test): test frameworks or utilities for testing
- [React](#react): libraries of components, hooks or other packages related to [React](https://github.com/jsdotlua/react-lua)
- [JavaScript](#javascript): packages inspired by JavaScript
- [Rust](#rust): packages inspired by Rust

## Data

| Package | Description | License |
| --- | --- | :---: |
| [`@aceworks-studio/random`](https://github.com/Aceworks-Studio/roblox-utils/tree/main/packages/random) | A utility library to work with randomness. | ![NPM License](https://img.shields.io/npm/l/@aceworks-studio/random?label=) |
| [`@aceworks-studio/state-machine`](https://github.com/Aceworks-Studio/roblox-utils/tree/main/packages/state-machine) | A utility to easily create simple state machines | ![NPM License](https://img.shields.io/npm/l/@aceworks-studio/state-machine?label=) |
| [`@jsdotlua/collections`](https://github.com/jsdotlua/luau-polyfill) | JavaScript like collections (Array, Map, Set, Object) | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/collections?label=) |
| [`@jsdotlua/diff-sequences`](https://github.com/jsdotlua/jest-lua) | Compare items in two sequences to find the longest common subsequence | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/diff-sequences?label=) |
| [`@jsdotlua/graphql`](https://github.com/jsdotlua/graphql-lua) | A reference implementation of GraphQL translated to Luau | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/graphql?label=) |
| [`@jsdotlua/otter`](https://github.com/jsdotlua/otter/tree/main/modules/otter) | Declarative animation library for Luau built around (but not limited to) springs | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/otter?label=) |
| [`@jsdotlua/react-otter`](https://github.com/jsdotlua/otter/tree/main/modules/react-otter) | A React interface to the declarative animation library named Otter | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/react-otter?label=) |
| [`@seaofvoices/easing-styles`](https://github.com/seaofvoices/easing-styles) | A library to interpolate values using common easing functions  | ![NPM License](https://img.shields.io/npm/l/@seaofvoices/easing-styles?label=) |
| [`@seaofvoices/heck-luau`](https://github.com/seaofvoices/heck-luau) | A case conversion library with Unicode support | ![NPM License](https://img.shields.io/npm/l/@seaofvoices/heck-luau?label=) |
| [`@sircfenner/png-luau`](https://github.com/sircfenner/png-luau) | Luau library for working with PNG files  | ![NPM License](https://img.shields.io/npm/l/@sircfenner/png-luau?label=) |
| [`chroma-luau`](https://github.com/seaofvoices/chroma-luau) | A library for color manipulation  | ![NPM License](https://img.shields.io/npm/l/chroma-luau?label=) |
| [`luau-character`](https://github.com/seaofvoices/luau-character) |  A library for Unicode character classification  | ![NPM License](https://img.shields.io/npm/l/luau-character?label=) |
| [`luau-disk`](https://github.com/seaofvoices/luau-disk) | Immutable table operations for Luau | ![NPM License](https://img.shields.io/npm/l/luau-disk?label=) |
| [`luau-grids`](https://github.com/seaofvoices/luau-grids) | A fully typed library to handle grids (2D or 3D) | ![NPM License](https://img.shields.io/npm/l/luau-grids?label=) |
| [`luau-path`](https://github.com/seaofvoices/luau-path) | A library to handle file paths (based on the Rust implementation)  | ![NPM License](https://img.shields.io/npm/l/luau-path?label=) |
| [`luau-unicode-width`](https://github.com/seaofvoices/luau-unicode-width) | A library for calculating displayed width of Unicode characters and strings  | ![NPM License](https://img.shields.io/npm/l/luau-unicode-width?label=) |
| [`luau-zlib`](https://github.com/seaofvoices/luau-zlib) | A library to compress and decompress strings using the deflate/zlib format | ![NPM License](https://img.shields.io/npm/l/luau-zlib?label=) |

## Resources

| Package | Description | License |
| --- | --- | :---: |
| [`luau-teardown`](https://github.com/seaofvoices/luau-teardown) | A utility to easily clean up resources | ![NPM License](https://img.shields.io/npm/l/luau-teardown?label=) |

## Async

| Package | Description | License |
| --- | --- | :---: |
| [`@jsdotlua/promise`](https://github.com/jsdotlua/roblox-lua-promise) | A JavaScript like Promise implementation | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/promise?label=) |
| [`@jsdotlua/scheduler`](https://github.com/jsdotlua/react-lua) | The scheduler implementation used by the React fiber reconciler | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/scheduler?label=) |
| [`@jsdotlua/zen-observable`](https://github.com/jsdotlua/zen-observable-lua) | Observables for Luau | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/zen-observable?label=) |
| [`luau-signal`](https://github.com/seaofvoices/luau-signal) | A simple signal (or event) utility | ![NPM License](https://img.shields.io/npm/l/luau-signal?label=) |

## Roblox

| Package | Description | License |
| --- | --- | :---: |
| [`@crosswalk-game/currency`](https://github.com/seaofvoices/crosswalk-currency) | A crosswalk module to handle in-game currencies | ![NPM License](https://img.shields.io/npm/l/@crosswalk-game/currency?label=) |
| [`@crosswalk-game/data-handler`](https://github.com/seaofvoices/crosswalk-data-handler) | A crosswalk module to handle player data | ![NPM License](https://img.shields.io/npm/l/@crosswalk-game/data-handler?label=) |
| [`@crosswalk-game/menu-handler`](https://github.com/seaofvoices/menu-handler) | A module to handle UI menus using tagged instances | ![NPM License](https://img.shields.io/npm/l/@crosswalk-game/menu-handler?label=) |
| [`@seaofvoices/react-lua-hooks`](https://github.com/seaofvoices/react-lua-hooks) | General-purpose collection of hooks for React-Lua | ![NPM License](https://img.shields.io/npm/l/@seaofvoices/react-lua-hooks?label=) |
| [`@seaofvoices/react-render-hook`](https://github.com/seaofvoices/react-lua-hooks) | Testing utility to easily test React-Lua hooks | ![NPM License](https://img.shields.io/npm/l/@seaofvoices/react-render-hook?label=) |
| [`@seaofvoices/react-roblox-hooks`](https://github.com/seaofvoices/react-lua-hooks) | Roblox specific collection of hooks for React-Lua | ![NPM License](https://img.shields.io/npm/l/@seaofvoices/react-roblox-hooks?label=) |
| [`@seaofvoices/react-roblox-studio-plugin`](https://github.com/seaofvoices/react-roblox-studio-plugin) | A React component library to create Roblox plugins | ![NPM License](https://img.shields.io/npm/l/@seaofvoices/react-roblox-studio-plugin?label=) |
| [`@seaofvoices/tag-effect`](https://github.com/seaofvoices/tag-effect) | A Luau library to apply effects to tagged Roblox instances | ![NPM License](https://img.shields.io/npm/l/@seaofvoices/tag-effect?label=) |
| [`@sircfenner/studiocomponents`](https://github.com/sircfenner/StudioComponents) | React implementation of Roblox Studio components | ![NPM License](https://img.shields.io/npm/l/@sircfenner/studiocomponents?label=) |
| [`crosswalk-channels`](https://github.com/seaofvoices/crosswalk-channels) | A crosswalk module to send data from server to clients | ![NPM License](https://img.shields.io/npm/l/crosswalk-channels?label=) |
| [`crosswalk-client`](https://github.com/seaofvoices/crosswalk) | A Roblox game framework (client logic) | ![NPM License](https://img.shields.io/npm/l/crosswalk-client?label=) |
| [`crosswalk-server`](https://github.com/seaofvoices/crosswalk) | A Roblox game framework (server logic)  | ![NPM License](https://img.shields.io/npm/l/crosswalk-server?label=) |

## Test

| Package | Description | License |
| --- | --- | :---: |
| [`@jsdotlua/dom-testing-library`](https://github.com/jsdotlua/dom-testing-library-lua) | Testing utilities for Roblox Luau | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/dom-testing-library?label=) |
| [`@jsdotlua/jest`](https://github.com/jsdotlua/jest-lua) | Delightful Luau testing library | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/jest?label=) |
| [`@jsdotlua/jest-globals`](https://github.com/jsdotlua/jest-lua) | Access all jest utilities like `it`, `describe` or `expect` | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/jest-globals?label=) |
| [`@jsdotlua/react-test-renderer`](https://github.com/jsdotlua/react-lua) | Roblox Luau port of the react-test-renderer for integration-level tests | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/react-test-renderer?label=) |
| [`@jsdotlua/react-testing-library`](https://github.com/jsdotlua/react-testing-library-lua) | Simple and complete testing utilities that encourage good testing practices.  | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/react-testing-library?label=) |
| [`@seaofvoices/react-render-hook`](https://github.com/seaofvoices/react-lua-hooks) | Testing utility to easily test React-Lua hooks | ![NPM License](https://img.shields.io/npm/l/@seaofvoices/react-render-hook?label=) |

## React

| Package | Description | License |
| --- | --- | :---: |
| [`@jsdotlua/react`](https://github.com/jsdotlua/react-lua) | A translation of React JS 17.x into Luau | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/react?label=) |
| [`@jsdotlua/react-is`](https://github.com/jsdotlua/react-lua) | Constants and runtime check functions for the various valid types of elements in React | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/react-is?label=) |
| [`@jsdotlua/react-otter`](https://github.com/jsdotlua/otter/tree/main/modules/react-otter) | A React interface to the declarative animation library named Otter | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/react-otter?label=) |
| [`@jsdotlua/react-roblox`](https://github.com/jsdotlua/react-lua) | Roblox opinionated renderer to stand for native renderers like react-dom | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/react-roblox?label=) |
| [`@jsdotlua/react-test-renderer`](https://github.com/jsdotlua/react-lua) | Roblox Luau port of the react-test-renderer for integration-level tests | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/react-test-renderer?label=) |
| [`@jsdotlua/react-testing-library`](https://github.com/jsdotlua/react-testing-library-lua) | Simple and complete testing utilities that encourage good testing practices.  | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/react-testing-library?label=) |
| [`@jsdotlua/roact-navigation`](https://github.com/jsdotlua/roact-navigation) | A declarative navigation system built on React-Lua, mostly translated from React Navigation v4 | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/roact-navigation?label=) |
| [`@jsdotlua/scheduler`](https://github.com/jsdotlua/react-lua) | The scheduler implementation used by the React fiber reconciler | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/scheduler?label=) |
| [`@seaofvoices/react-lua-hooks`](https://github.com/seaofvoices/react-lua-hooks) | General-purpose collection of hooks for React-Lua | ![NPM License](https://img.shields.io/npm/l/@seaofvoices/react-lua-hooks?label=) |
| [`@seaofvoices/react-render-hook`](https://github.com/seaofvoices/react-lua-hooks) | Testing utility to easily test React-Lua hooks | ![NPM License](https://img.shields.io/npm/l/@seaofvoices/react-render-hook?label=) |
| [`@seaofvoices/react-roblox-hooks`](https://github.com/seaofvoices/react-lua-hooks) | Roblox specific collection of hooks for React-Lua | ![NPM License](https://img.shields.io/npm/l/@seaofvoices/react-roblox-hooks?label=) |
| [`@seaofvoices/react-roblox-studio-plugin`](https://github.com/seaofvoices/react-roblox-studio-plugin) | A React component library to create Roblox plugins | ![NPM License](https://img.shields.io/npm/l/@seaofvoices/react-roblox-studio-plugin?label=) |
| [`@sircfenner/studiocomponents`](https://github.com/sircfenner/StudioComponents) | React implementation of Roblox Studio components | ![NPM License](https://img.shields.io/npm/l/@sircfenner/studiocomponents?label=) |

## JavaScript

A list of packages inspired by JavaScript concepts or even directly translated from the JavaScript ecosystem.

| Package | Description | License |
| --- | --- | :---: |
| [`@jsdotlua/chalk`](https://github.com/jsdotlua/chalk-lua) | Terminal string styling library | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/chalk?label=) |
| [`@jsdotlua/collections`](https://github.com/jsdotlua/luau-polyfill) | JavaScript like collections (Array, Map, Set, Object) | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/collections?label=) |
| [`@jsdotlua/diff-sequences`](https://github.com/jsdotlua/jest-lua) | Compare items in two sequences to find the longest common subsequence | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/diff-sequences?label=) |
| [`@jsdotlua/dom-testing-library`](https://github.com/jsdotlua/dom-testing-library-lua) | Testing utilities for Roblox Luau | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/dom-testing-library?label=) |
| [`@jsdotlua/graphql`](https://github.com/jsdotlua/graphql-lua) | A reference implementation of GraphQL translated to Luau | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/graphql?label=) |
| [`@jsdotlua/instance-of`](https://github.com/jsdotlua/luau-polyfill) | A utility function to check if a table-object is considered an Instance of another table-class | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/instance-of?label=) |
| [`@jsdotlua/jest`](https://github.com/jsdotlua/jest-lua) | Delightful Luau testing library | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/jest?label=) |
| [`@jsdotlua/jest-globals`](https://github.com/jsdotlua/jest-lua) | Access all jest utilities like `it`, `describe` or `expect` | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/jest-globals?label=) |
| [`@jsdotlua/luau-polyfill`](https://github.com/jsdotlua/luau-polyfill) | Utilities to mimic common JavaScript logic useful for translation to Luau  | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/luau-polyfill?label=) |
| [`@jsdotlua/picomatch`](https://github.com/jsdotlua/picomatch-lua) | Glob matcher library | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/picomatch?label=) |
| [`@jsdotlua/pretty-format`](https://github.com/jsdotlua/jest-lua) | Stringify Luau values | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/pretty-format?label=) |
| [`@jsdotlua/promise`](https://github.com/jsdotlua/roblox-lua-promise) | A JavaScript like Promise implementation | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/promise?label=) |
| [`@jsdotlua/react`](https://github.com/jsdotlua/react-lua) | A translation of React JS 17.x into Luau | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/react?label=) |
| [`@jsdotlua/react-is`](https://github.com/jsdotlua/react-lua) | Constants and runtime check functions for the various valid types of elements in React | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/react-is?label=) |
| [`@jsdotlua/react-roblox`](https://github.com/jsdotlua/react-lua) | Roblox opinionated renderer to stand for native renderers like react-dom | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/react-roblox?label=) |
| [`@jsdotlua/react-test-renderer`](https://github.com/jsdotlua/react-lua) | Roblox Luau port of the react-test-renderer for integration-level tests | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/react-test-renderer?label=) |
| [`@jsdotlua/react-testing-library`](https://github.com/jsdotlua/react-testing-library-lua) | Simple and complete testing utilities that encourage good testing practices.  | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/react-testing-library?label=) |
| [`@jsdotlua/roact-navigation`](https://github.com/jsdotlua/roact-navigation) | A declarative navigation system built on React-Lua, mostly translated from React Navigation v4 | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/roact-navigation?label=) |
| [`@jsdotlua/scheduler`](https://github.com/jsdotlua/react-lua) | The scheduler implementation used by the React fiber reconciler | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/scheduler?label=) |
| [`@jsdotlua/zen-observable`](https://github.com/jsdotlua/zen-observable-lua) | Observables for Luau | ![NPM License](https://img.shields.io/npm/l/@jsdotlua/zen-observable?label=) |
| [`@seaofvoices/easing-styles`](https://github.com/seaofvoices/easing-styles) | A library to interpolate values using common easing functions  | ![NPM License](https://img.shields.io/npm/l/@seaofvoices/easing-styles?label=) |
| [`chroma-luau`](https://github.com/seaofvoices/chroma-luau) | A library for color manipulation  | ![NPM License](https://img.shields.io/npm/l/chroma-luau?label=) |
| [`luau-regexp`](https://github.com/jsdotlua/regex-lua) | A regular expression library for Luau | ![NPM License](https://img.shields.io/npm/l/luau-regexp?label=) |
| [`symbol-luau`](https://github.com/jsdotlua/symbol-luau) | Simple object to mimic JavaScript Symbol type | ![NPM License](https://img.shields.io/npm/l/symbol-luau?label=) |

## Rust

A list of packages inspired by Rust concepts or even directly translated from Rust crates.

| Package | Description | License |
| --- | --- | :---: |
| [`@seaofvoices/heck-luau`](https://github.com/seaofvoices/heck-luau) | A case conversion library with Unicode support | ![NPM License](https://img.shields.io/npm/l/@seaofvoices/heck-luau?label=) |
| [`luau-character`](https://github.com/seaofvoices/luau-character) |  A library for Unicode character classification  | ![NPM License](https://img.shields.io/npm/l/luau-character?label=) |
| [`luau-unicode-width`](https://github.com/seaofvoices/luau-unicode-width) | A library for calculating displayed width of Unicode characters and strings  | ![NPM License](https://img.shields.io/npm/l/luau-unicode-width?label=) |
