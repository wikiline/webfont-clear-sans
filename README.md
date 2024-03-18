# WebFont Clear Sans

Package for integrating `Clear Sans` fonts in a web environment.

![npm](https://img.shields.io/npm/v/@wikiline/webfont-clear-sans?style=for-the-badge)
![npm](https://img.shields.io/npm/dm/@wikiline/webfont-clear-sans?style=for-the-badge)
![npm](https://img.shields.io/npm/dt/@wikiline/webfont-clear-sans?style=for-the-badge)
___

## Installation

This package can be deployed automatically using NPM:

```
npm i @wikiline/webfont-clear-sans
```

## Usage (CSS)

Font files are located in the `fonts/` directory. To import all fonts, you can use:

```css
body {
  font-family: 'Clear Sans', sans-serif;
}
```

### Importing

```css
@import "~@wikiline/webfont-clear-sans/css/all.css";
@import "~@wikiline/webfont-clear-sans/css/all-normal.css";
@import "~@wikiline/webfont-clear-sans/css/all-italic.css";
```

To import specific fonts, you can use:

```css
@import "~@wikiline/webfont-clear-sans/css/weight-200.css";
@import "~@wikiline/webfont-clear-sans/css/weight-200-normal.css";
@import "~@wikiline/webfont-clear-sans/css/weight-300.css";
@import "~@wikiline/webfont-clear-sans/css/weight-300-normal.css";
@import "~@wikiline/webfont-clear-sans/css/weight-400.css";
@import "~@wikiline/webfont-clear-sans/css/weight-400-normal.css";
@import "~@wikiline/webfont-clear-sans/css/weight-400-italic.css";
@import "~@wikiline/webfont-clear-sans/css/weight-500.css";
@import "~@wikiline/webfont-clear-sans/css/weight-500-normal.css";
@import "~@wikiline/webfont-clear-sans/css/weight-500-italic.css";
@import "~@wikiline/webfont-clear-sans/css/weight-700.css";
@import "~@wikiline/webfont-clear-sans/css/weight-700-normal.css";
@import "~@wikiline/webfont-clear-sans/css/weight-700-italic.css";
```

Note: Also, each file is presented in a minimized form.

### Variables

Each font uses the following CSS variables to set the font display property with the default `swap` value if CSS
variables are not defined:

```css
:root {
  --font-display: swap;
  --font-display-clear-sans: swap;
}
```

## Usage (LESS)

Font files are located in the `fonts/` directory. To import all fonts, you can use:

```less
body {
  font-family: 'Clear Sans', sans-serif;
}
```

### Importing

```less
@import "~@wikiline/webfont-clear-sans/less/all";
@import "~@wikiline/webfont-clear-sans/less/all-normal";
@import "~@wikiline/webfont-clear-sans/less/all-italic";
```

To import specific fonts, you can use:

```less
@import "~@wikiline/webfont-clear-sans/less/_weight-200";
@import "~@wikiline/webfont-clear-sans/less/_weight-200-normal";
@import "~@wikiline/webfont-clear-sans/less/_weight-300";
@import "~@wikiline/webfont-clear-sans/less/_weight-300-normal";
@import "~@wikiline/webfont-clear-sans/less/_weight-400";
@import "~@wikiline/webfont-clear-sans/less/_weight-400-normal";
@import "~@wikiline/webfont-clear-sans/less/_weight-400-italic";
@import "~@wikiline/webfont-clear-sans/less/_weight-500";
@import "~@wikiline/webfont-clear-sans/less/_weight-500-normal";
@import "~@wikiline/webfont-clear-sans/less/_weight-500-italic";
@import "~@wikiline/webfont-clear-sans/less/_weight-700";
@import "~@wikiline/webfont-clear-sans/less/_weight-700-normal";
@import "~@wikiline/webfont-clear-sans/less/_weight-700-italic";
```

### Variables

Each font uses the following LESS variables to set the font display property with the default `swap` value if SCSS
variables are not defined:

```less
@font-display: swap;
@font-display-clear-sans: swap;
```

or

```less
@import "~@wikiline/webfont-clear-sans/less/config/_variables";
```

## Usage (SCSS)

Font files are located in the `fonts/` directory. To import all fonts, you can use:

```scss
body {
  font-family: 'Clear Sans', sans-serif;
}
```

### Importing

```scss
@import "~@wikiline/webfont-clear-sans/scss/all";
@import "~@wikiline/webfont-clear-sans/scss/all-normal";
@import "~@wikiline/webfont-clear-sans/scss/all-italic";
```

To import specific fonts, you can use:

```scss
@import "~@wikiline/webfont-clear-sans/scss/weight-200";
@import "~@wikiline/webfont-clear-sans/scss/weight-200-normal";
@import "~@wikiline/webfont-clear-sans/scss/weight-300";
@import "~@wikiline/webfont-clear-sans/scss/weight-300-normal";
@import "~@wikiline/webfont-clear-sans/scss/weight-400";
@import "~@wikiline/webfont-clear-sans/scss/weight-400-normal";
@import "~@wikiline/webfont-clear-sans/scss/weight-400-italic";
@import "~@wikiline/webfont-clear-sans/scss/weight-500";
@import "~@wikiline/webfont-clear-sans/scss/weight-500-normal";
@import "~@wikiline/webfont-clear-sans/scss/weight-500-italic";
@import "~@wikiline/webfont-clear-sans/scss/weight-700";
@import "~@wikiline/webfont-clear-sans/scss/weight-700-normal";
@import "~@wikiline/webfont-clear-sans/scss/weight-700-italic";
```

### Variables

Each font uses the following SCSS variables to set the font display property with the default `swap` value if SCSS
variables are not defined:

```scss
$font-display: swap;
$font-display-clear-sans: swap;
```

or

```scss
@import "~@wikiline/webfont-clear-sans/scss/config/_variables";
```

## Licensing

It is important to always read the license for every font that you use. Most of the fonts in the collection use the SIL
Open Font License, v1.1. Some fonts use the Apache 2 license. The Ubuntu fonts use the Ubuntu Font License v1.0.
