# longshadow-stylus

[![GitHub version](https://badge.fury.io/gh/sugarshin%2Fmodule-skeleton.svg)](http://badge.fury.io/gh/sugarshin%2Flongshadow-stylus) [![License](http://img.shields.io/:license-mit-blue.svg)](http://sugarshin.mit-license.org/)

Make Longshadow

[http://sugarshin.github.io/longshadow-stylus/](http://sugarshin.github.io/longshadow-stylus/)

## usage

```stylus
@import "dist/longshadow.styl"

h1
  text-longshadow(indianred)
```

box

```stylus
@import "dist/longshadow.styl"

h1
  box-longshadow(indianred)
```

## options

### `text-longshadow(color [, maxLength])`

```stylus
@import "dist/longshadow.styl"

h1
  text-longshadow(indianred, 32)
```

default `128`

## License

[MIT](http://sugarshin.mit-license.org/)

© sugarshin
