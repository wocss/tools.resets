> ## This module is DEPRECATED
> This module has been moved to the monorepo [wocss](https://github.com/wocss/wocss/tree/master/packages/tools.resets#readme) (and renamed to `@wocss/tools-resets`)

# RESETS

> Tool

The `wocss-tools-resets` module contains `mixins` that allows reset styles.

Install using npm:

```sh
$ npm install wocss-tools-resets --save
```

## Usage

With a tool like [webpack](https://webpack.github.io/) you can import this module writing:

```scss
@import '~wocss-tools-resets';
```

### Mixins

Then you can use these mixins:

#### reset-list()

Removes any styles that were previously set on a list.

```scss
.items {
  @include reset-list();
}
```

Result:

```css
.items {
  list-style: none;
  padding-left: 0;
}
```
