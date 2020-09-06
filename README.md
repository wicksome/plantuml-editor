# PlantUML Editor

> A Vue.js, Vuex project

![PlantUML Editor](public/static/favicon-60.png)　PlantUML online demo client

![PlantUML Editor](public/static/capture1_20170809.png)

[![Netlify Status](https://api.netlify.com/api/v1/badges/0e9c5e9a-b38a-483f-887d-18e4927af717/deploy-status)](https://app.netlify.com/sites/plantuml-editor/deploys)

## Features

- multiple PlantUML templates
- cheat sheet
- snippet
- zoom & scroll
- supports SVG & PNG
- save texts
- create gists
- support markdown
- download image
- print HTML

## Build Setup

```
# install dependencies
npm install

# install flow-typed
npm run flow-typed

# serve with hot reload at localhost:8080
npm run serve

# build for production with minification
npm run build

# run unit tests
npm run test:unit

# run e2e tests
npm run test:e2e
```

or build with docker

```bash
# build with docker
docker build \ 
       -t plantuml-editor \
       --env VUE_CONFIG_SERVER=http://localhost:8080/ \
       --env VUE_APP_CDN=http://localhost:8080/ \
       .

# run plantuml-editor server with docker
docker run -d -p 80:80 --name plantuml-editor plantuml-editor
```

## For development

[PlantUML Server with Docker](https://hub.docker.com/r/plantuml/plantuml-server/)

```
docker run -d -p 4000:8080 plantuml/plantuml-server:jetty
```

> **Notice:** The specification of the port number follows `.env.development`

## Other

Pen graphic by [freepik](http://www.flaticon.com/authors/freepik) from [Flaticon](http://www.flaticon.com/) is licensed under [CC BY 3.0](http://creativecommons.org/licenses/by/3.0/). Check out the new logo that I created on [LogoMaker.com](http://logomakr.com) https://logomakr.com/7Gn1Ck
