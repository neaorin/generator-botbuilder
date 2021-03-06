# generator-botbuilder [![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Dependency Status][daviddm-image]][daviddm-url]
> Yeoman generator for Microsoft Bot Framework

## Features

Scaffolds a bot using [Microsoft Bot Framework](https://dev.botframework.com).

### Dependencies

- [dotenv](https://github.com/motdotla/dotenv) for managing environmental variables
- [restify](http://restify.com/) for hosting the API

## Installation

First, install [Yeoman](http://yeoman.io) and generator-botbuilder using [npm](https://www.npmjs.com/) (we assume you have pre-installed [node.js](https://nodejs.org/)).

```bash
npm install -g yo
npm install -g generator-botbuilder
```

## Generating your bot

```bash
yo botbuilder
```

### Next Steps

- Update `.env` with your bot App ID and Password (if needed)
- Add your logic to `bot.js`

## Getting To Know Yeoman

 * Yeoman has a heart of gold.
 * Yeoman is a person with feelings and opinions, but is very easy to work with.
 * Yeoman can be too opinionated at times but is easily convinced not to be.
 * Feel free to [learn more about Yeoman](http://yeoman.io/).

## License

MIT © Microsoft


[npm-image]: https://badge.fury.io/js/generator-botbuilder.svg
[npm-url]: https://npmjs.org/package/generator-botbuilder
[travis-image]: https://travis-ci.org/geektrainer/generator-botbuilder.svg?branch=master
[travis-url]: https://travis-ci.org/geektrainer/generator-botbuilder
[daviddm-image]: https://david-dm.org/geektrainer/generator-botbuilder.svg?theme=shields.io
[daviddm-url]: https://david-dm.org/geektrainer/generator-botbuilder
