# XIP SCSS Library

Helper library of common SCSS mixins, functions and some utility classes.

## Usage

### Install

```sh
npm install --save-dev @xip-online-applications/scss
```

## Reset

Easily remove default user-agent styling from semantic elements. Include the following import statement somewhere in your global SCSS file:

```scss
@import '@xip-online-applications/scss/reset';
```

Additionally you can pass a platform to load additional reset styles:

```scss
@import '@xip-online-applications/scss/reset' with (
  $platform: 'angular'
);
```

## Utilities

Loads utility classes:

```scss
@import '@xip-online-applications/scss/utilities';
```

> TODO: Add more documentation on utility classes.