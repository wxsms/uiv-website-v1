# uiv-website-v1

> Documentation site of [uiv](https://github.com/wxsms/uiv) (Bootstrap 3 components implemented by Vue 2) — 1.x.

**Live site:** https://wxsms.github.io/uiv-website-v1/

Built with [VuePress](https://vuepress.vuejs.org/) v1.

## Build Setup

``` bash
# install dependencies
pnpm i

# serve with hot reload at localhost:8080
pnpm run docs:dev

# build for production
pnpm run docs:build
```

## Deployment

Pushing to `master` triggers the [publish doc](.github/workflows/publish_doc.yml) workflow, which builds the site and deploys it to the `gh-pages` branch.
