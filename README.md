# qrcode.react

A React component to generate [QR codes](http://en.wikipedia.org/wiki/QR_code).
forked from [zpao/qrcode.react](https://github.com/zpao/qrcode.react)

## Installation

```sh
npm i -S https://github.com/nicholaspsmith/qrcode.react
```

## Usage

```js
import React from 'react'
import QRCode from 'qr-code-react'

React.render(
  <QRCode value="http://facebook.github.io/react/" />,
  mountNode
);
```

## Available Props

prop      | type                 | default value
----------|----------------------|--------------
`value`   | `string`             |
`size`    | `number`             | `128`
`bgColor` | `string` (CSS color) | `"#FFFFFF"`
`fgColor` | `string` (CSS color) | `"#000000"`
`level`   | `string` (`'L' 'M' 'Q' 'H'`)            | `'L'`
`className`|`string`             | ``

<img src="qrcode.png" height="256" width="256">


## LICENSE [ISC](LICENSE)
