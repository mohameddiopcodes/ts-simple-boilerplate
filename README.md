## Typescript boilerplate

A simple typescript boilerplate to get started on your projects in an unopinionated manner. This sample repository only prints `"hello world"` to the console using `index.ts` as an entrypoint.

### install command

* `npm install`, `yarn install` or `pnpm install`

### dev command

use `npm run dev` to run the development server. 

* uses `nodemon`, `ts-node` and `tsconfig-paths`
* configuration can be found in the `package.json` file

### build command

use `npm run build`. The generated build can be found in the `./dist` folder.

* uses `tsc` (typescript compiler)
* configuration can be found in the `tsconfig.json` file

### start command

use `npm start`

* uses `node` to run the `./dist` folder through it's entrypoint `index.js` after it has been built.

