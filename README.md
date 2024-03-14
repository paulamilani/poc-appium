## Appium-test

POC usando appium para testes mobile.

**Contexto**

Appium é um projeto de código aberto e ecossistema de software relacionado, projetado para facilitar a automação da interface do usuário de muitas plataformas de aplicativos, incluindo dispositivos móveis (iOS, Android, Tizen), navegador (Chrome, Firefox, Safari), desktop (macOS, Windows), TV (Roku, tvOS, Android TV, Samsung) e muito mais!

Ref: https://appium.io/docs/en/latest/

**Requisitos**

- **[Java JDK](https://www.oracle.com/java/technologies/javase-downloads.html)**
- **[Node.js](https://nodejs.org/en/)**
- **[Android Studio](https://developer.android.com/studio/install)**
- **[Visual Studio Code](https://code.visualstudio.com/)**
- **[Appium](http://appium.io/)**
    - A macOS, Linux, or Windows operating system
    - [Node.js](https://nodejs.org/) version in the [SemVer](https://semver.org/) range `^14.17.0 || ^16.13.0 || >=18.0.0`
    - LTS is recommended
    - `[npm](https://npmjs.com/)` version `>=8` (`npm` is usually bundled with Node.js, but can be upgraded independently)

https://github.com/appium/appium/tree/master

https://www.npmjs.com/package/appium?activeTab=readme

- **[Appium Sample Code test APK](https://github.com/appium/appium/tree/master/sample-code/apps)**

github projeto exemplo

https://github.com/ofindley/appium-webdriverio

install appium

`npm i -g appium`

install dependências

`npm update -g appium`

start appium 

`appium`

start projeto

`npm init`

`npm i --save-dev webdriverio` 

npm i @wdio/cli

executar wdio config

`./node_modules/.bin/wdio wdio.conf.js`

obs: na execução do wdio é possível instalar appium server