# digital-certificate-edu

[![Build Status](https://cloud.drone.io/api/badges/wiasliaw77210/digital-certificate-edu/status.svg)](https://cloud.drone.io/wiasliaw77210/digital-certificate-edu)

Digital certificate web for EDU Depart.

#### pre-requirement

[yarn](https://yarnpkg.com/lang/en/)

#### Environment

Language: [typescript 3.6](https://www.typescriptlang.org/)
Framework: [next.js](https://nextjs.org/)

### Install

Install package which listed in `package.json`

```
$ yarn install
```

### Development

Run frontend at `localhost:3000` with hot mode

```
$ yarn dev
```

### Export static HTML file

Build and export `*.html` and `assets` in `./out` folder

```
$ yarn export
```

### Deploy to github public pages

**If you want to deploy to github public pages**
You can use following command, and go to repo's public page

```
$ yarn deploy:github
```