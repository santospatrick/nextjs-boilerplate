# `@santospatrick/nextjs-boilerplate`

## Usage
```bash
yarn create next-app -e https://github.com/santospatrick/nextjs-boilerplate
```

## Features
- [x] [Next.js](https://nextjs.org/)
- [x] [Typescript](https://www.typescriptlang.org/)
- [x] [Styled Components](https://styled-components.com/)
- [x] [Next.js PWA](https://www.npmjs.com/package/next-pwa)
- [x] [React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)
- [x] [Jest](https://jestjs.io/)
- [x] [ESLint](https://github.com/santospatrick/eslint-config-react)/[Prettier](https://github.com/santospatrick/prettier-config)
- [x] [Husky (Git Hooks)](https://github.com/typicode/husky)/[Lint Staged](https://github.com/okonet/lint-staged)
- [x] [Storybook](https://storybook.js.org/)
- [x] [Plop (Template Generator)](https://plopjs.com/)
- [ ] [Stylelint](https://stylelint.io/)
- [ ] [SWR](https://swr.vercel.app/)

## Scripts

#### `yarn dev`
Runs development environment locally at `http://localhost:3000`

#### `yarn build`
Builds project to `.next` folder

#### `yarn start`
Runs production environment (make sure to run `yarn build` first)

#### `yarn lint`
Runs [ESLint](https://github.com/santospatrick/eslint-config-react)/[Prettier](https://github.com/santospatrick/prettier-config) for all files inside `src/`

#### `yarn test`
Runs [Jest](https://jestjs.io/) tests for all ts/tsx files inside `src`

#### `yarn test:watch`
Runs and keep watching Jest tests for all ts/tsx files inside `src` (You don't need this if you have [Jest extension installed in VSCode](https://marketplace.visualstudio.com/items?itemName=Orta.vscode-jest))

#### `yarn storybook`
Runs [Storybook](https://storybook.js.org/) server locally at `http://localhost:6006`

#### `yarn build-storybook`
Builds [Storybook](https://storybook.js.org/) static files to `storybook-static` folder
