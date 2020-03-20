# `linaria-css-grid`

[![Travis](https://img.shields.io/travis/azz/styled-css-grid.svg?style=flat-square)](https://travis-ci.org/azz/styled-css-grid)
[![Prettier](https://img.shields.io/badge/styled_with-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)
[![npm](https://img.shields.io/npm/v/styled-css-grid.svg?style=flat-square)](https://npmjs.org/styled-css-grid)
[![License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](LICENSE)

> A lightweight [CSS grid] layout for React, built with [linaria] 💅.

## demo

See the **[website]**.

## installation

Install React and [linaria``], then:

```bash
$ yarn add linaria-css-grid
```

## usage

```jsx
import React from "react";
import { Grid, Cell } from "linaria-css-grid";

const MyGrid = () => (
  <Grid columns={2} gap="2px">
    <Cell>foo</Cell>
    <Cell height={2}>bar</Cell>
    <Cell width={2}>baz</Cell>
  </Grid>
);
```

## api

### `Cell`

A cell. Not too much to say...

Props:

* `width`: Cell width in units, default is `1`.
* `height`: Cell height in units, default is `1`.

### `Grid`

Wrap your cells in `Grid`. Pretty simple.

Props:

* `columns`: Number of columns to draw, default is `3`.
* `gap`: Gap between cells. Default is `"8px"`.
* `minRowHeight`: Minimum height of each row. Default is `"20vh"`.

[website]: https://styled-css-grid.netlify.com/
[CSS grid]: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout
[linaria]: https://github.com/callstack/linaria
