# slugcase

[![npm version](https://img.shields.io/npm/v/slugcase.svg)][npm-url]

[npm-url]: https://www.npmjs.com/package/slugcase

A library to convert a string to slug format

Demo on [Stackblitz](https://stackblitz.com/edit/vite-example-slug)

## Installation

```sh
npm install slugcase
```

## Usage

```js
import { slugcase } from 'slugcase';

const myString = 'Hola como estas?';

const mySlugString = slugcase(myString);

// mySlugString
// hola-como-estas
```

## Roadmap

- [ ] Add Typescript
- [ ] Add Unit tests
- [ ] Suport to ESM and CommonJS
- [ ] Whatever
