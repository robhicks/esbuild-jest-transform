# esbuild-jest-transform
[![npm](https://img.shields.io/npm/v/esbuild-jest.svg)](https://www.npmjs.com/package/esbuild-jest)
esbuild jest plugin.
You can set the build option of esbuild by putting jest.esbuild.js.

[esbuild config](https://github.com/evanw/esbuild/blob/v0.7.6/lib/types.ts)

## Install
```bash
npm install --save-dev swc-jest @swc/core
```

## Setup
jest.config.js

```json
"transform": {
  "^.+\\.jsx?$": "swc-jest"
},
```

