# itk-wasm-ts-test

This repository is a basic reproduction of itk-wasm failing when used with TypeScript.

Tested package versions:

- `typescript@4.6.2`
- `itk-wasm@1.0.0-b.8` (and `itk-wasm@1.0.0-b.10` from @beta tag)

## Steps:

1. `npm install`
2. `npm start`
3. Error thrown:

   `Error [ERR_PACKAGE_PATH_NOT_EXPORTED]: No "exports" main defined in <...>/itk-wasm-ts-test/node_modules/itk-wasm/package.json`
