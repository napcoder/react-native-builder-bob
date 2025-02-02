# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [0.23.1](https://github.com/callstack/react-native-builder-bob/compare/create-react-native-library@0.23.0...create-react-native-library@0.23.1) (2022-07-04)


### Bug Fixes

* use correct bob version in package.json ([4a5afb3](https://github.com/callstack/react-native-builder-bob/commit/4a5afb3ea1ebdf9febe0a3822cbabaa32d0a4faf))





# [0.23.0](https://github.com/callstack/react-native-builder-bob/compare/create-react-native-library@0.22.0...create-react-native-library@0.23.0) (2022-06-30)


### Features

* update turbo modules template to use a synchronous API ([1393060](https://github.com/callstack/react-native-builder-bob/commit/1393060e5f36dd4d43b53603d9cf7f814b8ce94b))





# [0.22.0](https://github.com/callstack/react-native-builder-bob/compare/create-react-native-library@0.21.1...create-react-native-library@0.22.0) (2022-06-27)


### Features

* add a template for turbo module (experimental) ([cc95a72](https://github.com/callstack/react-native-builder-bob/commit/cc95a726f8019e016cebde76c0de15986eb79c64))





## [0.21.1](https://github.com/callstack/react-native-builder-bob/compare/create-react-native-library@0.21.0...create-react-native-library@0.21.1) (2022-06-22)


### Bug Fixes

* fix generated package name ([09e63a9](https://github.com/callstack/react-native-builder-bob/commit/09e63a9f00821e2e67b301a62e61e7f8175c3e4a))





# [0.21.0](https://github.com/callstack/react-native-builder-bob/compare/create-react-native-library@0.20.1...create-react-native-library@0.21.0) (2022-06-21)


### Bug Fixes

* consolidate gradle files ([af0ae13](https://github.com/callstack/react-native-builder-bob/commit/af0ae134d4a122f2ec0d08bda0572718e2f72174))
* fix requiresMainQueueSetup warning for swift modules ([31cf29f](https://github.com/callstack/react-native-builder-bob/commit/31cf29fa6998563fe7f39c057039220249922998))
* fixed lint throw error without semicolon ([#232](https://github.com/callstack/react-native-builder-bob/issues/232)) ([45c138b](https://github.com/callstack/react-native-builder-bob/commit/45c138bd0ed0e950fbfc2dd15a4f7d601bbab7ee))
* include header with project identifier for cpp ([#246](https://github.com/callstack/react-native-builder-bob/issues/246)) ([2aba2be](https://github.com/callstack/react-native-builder-bob/commit/2aba2be319a2ab3b6e618886306f7e5712bc8b9f))
* remove double-quoted imports from React-Core ([#220](https://github.com/callstack/react-native-builder-bob/issues/220)) ([0de461d](https://github.com/callstack/react-native-builder-bob/commit/0de461d32bf5a74a3c91f0d2aa860f429f369d54))
* use react-native.config.js for linking the library ([1000cd7](https://github.com/callstack/react-native-builder-bob/commit/1000cd7c4d99647f4ad2e90cfcc5874697e270aa))


### Features

* enable hermes by default ([194e279](https://github.com/callstack/react-native-builder-bob/commit/194e2793244f92a3cf2a606e6077a9978a0679e1))
* migrate to lefthook instead of husky ([c3e4bfb](https://github.com/callstack/react-native-builder-bob/commit/c3e4bfb9c6db97b8fbbdc24aa2d10a0b41c9de4d))
* upgrade templates to latest react & react-native ([9bb2a22](https://github.com/callstack/react-native-builder-bob/commit/9bb2a223b0957239db3cc09fc89269ab68fefc0b))





## [0.20.1](https://github.com/callstack/react-native-builder-bob/compare/create-react-native-library@0.20.0...create-react-native-library@0.20.1) (2021-10-15)


### Bug Fixes

* fix cpp template ([#203](https://github.com/callstack/react-native-builder-bob/issues/203)) ([15a82b0](https://github.com/callstack/react-native-builder-bob/commit/15a82b00c4e9a98f467a7b48dccd4551c8da1c3e))





# [0.20.0](https://github.com/callstack/react-native-builder-bob/compare/create-react-native-library@0.19.0...create-react-native-library@0.20.0) (2021-09-28)


### Bug Fixes

* **android:** prefer downloading dependencies from Maven Central ([#198](https://github.com/callstack/react-native-builder-bob/issues/198)) ([ecea932](https://github.com/callstack/react-native-builder-bob/commit/ecea932b52011378db35a223023097fa11ed651e))
* can't run yarn command under Windows ([8bac4d4](https://github.com/callstack/react-native-builder-bob/commit/8bac4d4690a0ba2576e9b83b00be92061ba796e3))
* fix generating cpp project on iOS ([75a4a3c](https://github.com/callstack/react-native-builder-bob/commit/75a4a3cf1b7d5f3c2b14f2f3a20c0be72250a119))
* wrong package name of ReactNativeFlipper ([#161](https://github.com/callstack/react-native-builder-bob/issues/161)) ([981448d](https://github.com/callstack/react-native-builder-bob/commit/981448db9970e42521661a5b6e54fd71fe3390ef))


### Features

* print an error when library is not linked ([#202](https://github.com/callstack/react-native-builder-bob/issues/202)) ([956ffd6](https://github.com/callstack/react-native-builder-bob/commit/956ffd60a6b4132a81494e1599b52e5aee232111))
* update expo sdk version to 42 ([#192](https://github.com/callstack/react-native-builder-bob/issues/192)) ([6276f59](https://github.com/callstack/react-native-builder-bob/commit/6276f59001cb92840a421de6bd01b41697ef1222))
* upgrade husky to v6 ([a78b9d1](https://github.com/callstack/react-native-builder-bob/commit/a78b9d147a2a2d1c42f050c60f808855bb97bc24))





# [0.19.0](https://github.com/callstack/react-native-builder-bob/compare/create-react-native-library@0.18.1...create-react-native-library@0.19.0) (2021-04-06)


### Bug Fixes

* fallback bob version ([#147](https://github.com/callstack/react-native-builder-bob/issues/147)) ([47fdd6b](https://github.com/callstack/react-native-builder-bob/commit/47fdd6bd914f3682b32d5ebd5b7a21d1433f7337))
* fix missing semicolon in babel config ([#142](https://github.com/callstack/react-native-builder-bob/issues/142)) ([b552564](https://github.com/callstack/react-native-builder-bob/commit/b552564a0daaee88001c030b300feb57e7b2fcdb))
* hardcode flipper version. fixes [#144](https://github.com/callstack/react-native-builder-bob/issues/144) ([eb93059](https://github.com/callstack/react-native-builder-bob/commit/eb93059f5ce996139654876a8d08c1081b99ee83))
* update docs with more info ([670ed10](https://github.com/callstack/react-native-builder-bob/commit/670ed10c7faf746e284409ed32d723f00f8a5867))


### Features

* add support for Java templates ([#129](https://github.com/callstack/react-native-builder-bob/issues/129)) ([e3a4c2d](https://github.com/callstack/react-native-builder-bob/commit/e3a4c2def1358240d2ac8f647503904950b2fb9b))





## [0.18.1](https://github.com/callstack/react-native-builder-bob/compare/create-react-native-library@0.18.0...create-react-native-library@0.18.1) (2021-03-03)

**Note:** Version bump only for package create-react-native-library





# 0.18.0 (2021-03-02)

**Note:** Version bump only for package create-react-native-library
