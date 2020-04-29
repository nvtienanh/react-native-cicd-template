# VTSG - Hotel project

![iOS build](https://github.com/nvtienanh/react-native-cicd-template/workflows/iOS/badge.svg)

![Android build](https://github.com/nvtienanh/react-native-cicd-template/workflows/Android/badge.svg)

This is the source code for the iOS App ['Space Viewer - Rocket Infos'](https://itunes.apple.com/us/app/space-viewer-rocket-infos/id1434055829?ls=1&mt=8) and Android App ['Space Viewer - Information about Rocket Launches'](https://play.google.com/store/apps/details?id=com.mariusreimer.spaceviewer). You can see lots of information about rocket space launches from all over the world! Want to know at which location it will launch? Or do you want to see its live stream? All the information are bundled in this app.

This includes rocket launches from SpaceX, NASA, ROSCOSMOS, ISRO, ULA and many more!



## Technical Stack

* Monorepo (yarn workspace)
* React Native (without Expo)
* Code Push by Microsoft App Center
* Redux-Saga for asynchronous actions
* Moment.Js for date operations

## Cấu trúc project
`packages` là thư mục chứa source code của project bao gồm 3 thư mục con:
- `common`: chưa source code React Native
- `mobile`: chứa source code của mobile app bao gồm Android và iOS
- `web`: chứa souce code của web app


## Installation
### Window
- *Yarn*: [Yarn for Window](https://classic.yarnpkg.com/en/docs/install/#windows-stable)
- Nodejs: [Node 12] (https://nodejs.org/en/download/)
- Android Studio
- Oracle JDK8
### Linux

### MacOs

React Native project can be found at [packages/mobile](packages/mobile)

## Build & Run
Install all dependencies:
```bash
yarn
```
### Web version
![space-viewer](packages/web/mockup.png)
Start web version:
```bash
yarn web/start
```
### Mobile version
![space-viewer](packages/mobile/mockup.png)
Open a terminal in root dir of project then run:
```bash
yarn mobile/start
```
Open 2nd Terminal in root dir of project and run
```bash
yarn run-android # For Android
yarn run-ios # For iOS
```

## Credits / Special Thanks

* All the data that is publicly available via the [LaunchLibrary.net](https://launchlibrary.net) API.
* Icon made by [Freepik](https://www.freepik.com) from [www.flaticon.com](https://www.flaticon.com)

## License
Copyright © Marius Reimer

Distributed under the [Apache 2 License](http://www.apache.org/licenses/LICENSE-2.0.html).
