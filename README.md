# typographic-currency-db

[![NPM version][npm-image]][npm-url]

> Raw data about typographic currency

## Install

    npm install --save typographic-currency-db

## Usage

Use correct currency symbols. Just use name of currency in international format [ISO 4217](https://en.wikipedia.org/wiki/ISO_4217).

```js
import currencyDB from 'typographic-currency-db';

currencyDB['USD']; // $
currencyDB['KZT']; // ₸
currencyDB['JPY']; // ¥

```

## License

MIT © [talgautb](http://gtalk.kz)

[npm-url]: https://npmjs.org/package/typographic-currency-db
[npm-image]: https://img.shields.io/npm/v/typographic-currency-db.svg?style=flat-square

