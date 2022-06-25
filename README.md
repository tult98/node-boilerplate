# blog-api

This boilerplate contains the following tools are set 
1. TypeScript 
2. Esbuild
3. Nodemon
4. Eslint 
5. Prettier 
6. Husk

### Typescript, Esbuild and Nodemon
- I use Eslint to compile TypeScript code for speedup the compilation time. But because it do not does typechecking and create `d.ts` file. Therefore, I still have to use `tsc` by setting a script for it. 
- Nodemon is use for setup live reloading with Typescript and Esbuild 


### Eslint and Prettier
- I turn off all the rules might conflict between eslint and prettier by using `eslint-config-prettier` library. As well as run prettier as an eslint rule.
