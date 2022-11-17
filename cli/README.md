<p align="center">
    <img src="resources/img/logo.png">
</p>
<div align="center">
  <h1 align="center">Kaaper</h1>
  <p align="center">
    <a href="https://discord.gg/onlydust">
        <img src="https://img.shields.io/badge/Discord-6666FF?style=for-the-badge&logo=discord&logoColor=white">
    </a>
    <a href="https://twitter.com/intent/follow?screen_name=onlydust_xyz">
        <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white">
    </a>
    <a href="https://contributions.onlydust.xyz/">
        <img src="https://img.shields.io/badge/Contribute-6A1B9A?style=for-the-badge&logo=notion&logoColor=white">
    </a>
  </p>
  
  <h3 align="center">Documentation generator for Cairo projects.</h3>
</div>

> ## ⚠️ WARNING! ⚠️
>
> This repo contains highly experimental code.
> Expect rapid iteration.

## 🎟️ Description

Kaaper is a tool to generate documentation for Cairo projects.
It allows you to extract code documentation from your project and generate yaml files that can be used to generate documentation.
Kaaper supports both Natspec and Google documentation standards.

## 🎗️ Prerequisites
[Node JS](https://nodejs.org/), preferably 16.xx  
[Yarn](https://classic.yarnpkg.com/lang/en/docs/install/)


## 📦 CLI Installation
Kaaper is now available as an [NPM package](https://www.npmjs.com/package/@onlydust/kaaper).
```
npm install -g @onlydust/kaaper
yarn global add @onlydust/kaaper
```

Or install locally : Navigate to CLI directory
```
cd cli
```

Install the required dependencies
```
yarn
npm install
```

Install CLI locally
```
npm run create
npm run local
```

## 🔬 Usage


To see available commands
```
kaaper
```

## Generate docs
```
kaaper generate <rootdir> <outdir>
```

Generate docs (comment only)
```
kaaper generate --comment <rootdir> <outdir>

```
The command generates documentation for google-compliant contracts by default.
To Generate docs for natspec-compliant contracts, use
```
kaaper generate --standard natspec <rootdir> <outdir>
```

## Check comment compliancy
```
kaaper check-compliance <rootdir> [--standard natspec|google]
```



## 🌡️ Testing
```
yarn test
```

## 🫶 Contributing

## 📄 License

**kaaper** is released under the [MIT](LICENSE).

## ❓ Reference 

Kaaper, also commonly known as Sheikh el-Beled, was an ancient Egyptian scribe and priest who lived between the late 4th Dynasty and the early 5th Dynasty (around 2500 BCE).

The job of a scribe was to record in writing the everyday life and extraordinary happenings in ancient Egypt.

A documentation generator has pretty much the same duties as a scribe, right?
