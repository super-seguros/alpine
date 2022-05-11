# Alpine.js

This is a fork of https://github.com/alpinejs/alpine/tree/v2.8.2

It adds `readonly` attribute to `x-model`, for cases where we want a particular data
to always represent the current value `<input>`/`<select>`/etc

```sh
npm install && \
npm run build && \
cp packages/alpinejs/dist/cdn.js ~/super-pas/assets/js/vendor/alpine-readonly-fork.js
```
