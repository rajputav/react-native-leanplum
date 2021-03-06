# [1.0.0](https://github.com/brandingbrand/react-native-leanplum/compare/v0.1.2...v1.0.0) (2018-09-26)


### Bug Fixes

* resolve inboxMessages with empty inbox ([2fe1490](https://github.com/brandingbrand/react-native-leanplum/commit/2fe1490))


### BREAKING CHANGES

* inboxMessages will always resolve, regardless of whether or not the user has messages.

We shouldn’t reject the inboxMessages promise just because the inbox is empty. This change causes the inbox to always resolve even if the user doesn’t have any messages.

## [0.1.2](https://github.com/brandingbrand/react-native-leanplum/compare/v0.1.1...v0.1.2) (2018-09-26)


### Bug Fixes

* remove commitlint/config-lerna-scopes ([1319340](https://github.com/brandingbrand/react-native-leanplum/commit/1319340))

## [0.1.1](https://github.com/brandingbrand/react-native-leanplum/compare/v0.1.0...v0.1.1) (2018-07-02)


### Bug Fixes

* **ci:** add changelog plugin ([eb4ab61](https://github.com/brandingbrand/react-native-leanplum/commit/eb4ab61))
* **ci:** add git plugin ([42a7754](https://github.com/brandingbrand/react-native-leanplum/commit/42a7754))
* **ci:** update package.json and CHANGELOG.md ([e3a18ea](https://github.com/brandingbrand/react-native-leanplum/commit/e3a18ea))
