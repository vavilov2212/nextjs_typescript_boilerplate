# NextJS Typescript Boilerplate

##### Based on https://github.com/vercel/next.js/tree/master/examples/with-typescript-eslint-jest

[`ESLint`](https://www.eslint.org/) is replaced with [`TSLint`](https://palantir.github.io/tslint/). [`Stylelint`](https://stylelint.io/) added for css/scss linting.<br>
Config files were added:<br>
`.prettierrc`<br>
`.prettierignore`<br>
`.stylelintrc`<br>
`.gitignore`<br>
tslint.json

Package.json scripts and dependency tree are changed to reflect the above.

Configured with:

- [Typescript](https://www.typescriptlang.org/)
- Linting with [TSLint](https://palantir.github.io/tslint/)
- Formatting with [Prettier](https://prettier.io/)
- Linting, typechecking and formatting on by default using [`husky`](https://github.com/typicode/husky) for commit hooks
- Testing with [Jest](https://jestjs.io/) and [`react-testing-library`](https://testing-library.com/docs/react-testing-library/intro)

Created with this command:

```bash
npx create-next-app --ts -e https://github.com/vercel/next.js/tree/master/examples/with-typescript-eslint-jest --use-npm
```
