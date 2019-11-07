# keystone-typeorm-adapter

An adapter to bring typeorm support for the awesome keystone.

## Motivation

The v5 of keystone is insane !! But it was designed to accomodate mongo databases first and only have support for knex (and only postgresql).

This project intends to fill the gap by providing a easy and straightforward to use typeorm with keystone, letting us then to support other rdbms and the awesome out of the box migration support of typeorm.

## Installation

`npm install --save keystone-typeorm-adapter`

or

`yarn add keystone-typeorm-adapter`

```ts
import { TypeORMAdapter } from "keystone-typeorm-adapter";
```
