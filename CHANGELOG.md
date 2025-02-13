# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.11.6] - 2022-04-08
### Fixed
* use Array#push instead of #append for better compatibility

## [0.11.5] - 2022-04-07
### Changed
* packages are uploaded "atomically": transferred as temporary files, then
    moved, to avoid corrupted files

## [0.11.4] - 2022-03-16
### Changed
* change --lock behavior, now unlocks while uploading .deb files themselves

## [0.11.3] - 2021-04-08
### Changed
* bump aws sdk components

[0.11.3]: https://github.com/deb-s3/deb-s3/compare/0.11.2...0.11.3

## [0.11.2] - 2020-09-08
### Changed
* [#2](https://github.com/deb-s3/deb-s3/pull/2): bump aws sdk to v3

[0.11.2]: https://github.com/deb-s3/deb-s3/compare/0.11.1...0.11.2
