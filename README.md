# PostCSS Keywords [<img src="https://postcss.github.io/postcss/logo.svg" alt="PostCSS" width="90" height="90" align="right">][postcss]

[![NPM Version][npm-img]][npm-url]
[![Build Status][cli-img]][cli-url]
[![Support Chat][git-img]][git-url]

[PostCSS Keywords] lets you create custom keywords which can be used in declarations.

```pcss
@keyword font-size-small: 12px;

.example {
  font-size: font-size-small;
}
```

Outputs:


```css
.example {
  font-size: 12px;
}
```

## Setup

Add it to your project:

```bash
npm install postcss-keywords --save-dev
```

[cli-img]: https://img.shields.io/travis/mindthetic/postcss-keywords.svg
[cli-url]: https://travis-ci.org/mindthetic/postcss-keywords
[git-img]: https://img.shields.io/badge/support-chat-blue.svg
[git-url]: https://gitter.im/postcss/postcss
[npm-img]: https://img.shields.io/npm/v/postcss-keywords.svg
[npm-url]: https://www.npmjs.com/package/postcss-keywords

[PostCSS]: https://github.com/postcss/postcss
[PostCSS Keywords]: https://github.com/mindthetic/postcss-keywords
