# nuxt-typescript

> for development

## Build Setup

```bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn run dev

# build for production and launch server
$ yarn run build
$ yarn start

# generate static project
$ yarn run generate
```

## Load Global SCSS

add scss file to assets/sass/xxx.scss

add path to nuxt.config.ts

```
  styleResources: {
    scss: ['~/assets/sass/xxx.scss']
  }
```

For detailed explanation on how things work, checkout [Nuxt.js docs](https://nuxtjs.org).
