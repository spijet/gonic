# Changelog

## [0.14.0](https://www.github.com/spijet/gonic/compare/v0.13.1...v0.14.0) (2021-06-22)


### Features

* **ci:** add debug build workflow ([2780dba](https://www.github.com/spijet/gonic/commit/2780dba534b673b1a496d44c9fcc3007fd0f2e62))
* **ci:** pin golangci-lint version ([8f7131e](https://www.github.com/spijet/gonic/commit/8f7131e25b9ea4207cdb9091ccbae26b5118cdac))
* **ci:** test before release please, and only run extra tests on develop and pull request ([cd5771f](https://www.github.com/spijet/gonic/commit/cd5771f88635b95955c7d2aea72379411142b777))
* **ci:** use GITHUB_TOKEN for release please ([608504b](https://www.github.com/spijet/gonic/commit/608504bedc88ec02cef34849cb42fb476dd63e1c))
* create cache directory on startup ([f3bc3ae](https://www.github.com/spijet/gonic/commit/f3bc3ae78990948e75d0b9757c399aad4e5c3b6b)), closes [#127](https://www.github.com/spijet/gonic/issues/127)
* **encode:** add mime-type headers to cache handlers ([4109b5b](https://www.github.com/spijet/gonic/commit/4109b5b66cbb53e9255fcd216195f8e1a773e48d))
* Support WMA files, including those with embedded album art ([#143](https://www.github.com/spijet/gonic/issues/143)) ([7100b2b](https://www.github.com/spijet/gonic/commit/7100b2b241ab5c199aaa17b2631b85b065b383e1))


### Bug Fixes

* **ci:** remove deprecated linters ([3382af7](https://www.github.com/spijet/gonic/commit/3382af72f19eead97b601eee847fd60b6c50ca34))
* **ci:** trim short hash ([6f26974](https://www.github.com/spijet/gonic/commit/6f269745a5f678b256b4a715ba236a2b847e4de9))
* **docs:** update ubuntu / systemd service instructions ([ef6dd6c](https://www.github.com/spijet/gonic/commit/ef6dd6c82a638dcd8aa3254839e2f53580a4ef46)), closes [#126](https://www.github.com/spijet/gonic/issues/126)
* **encode:** Strip EBU R128 gain tags when using forced-RG transcoding ([#145](https://www.github.com/spijet/gonic/issues/145)) ([5444d40](https://www.github.com/spijet/gonic/commit/5444d40018c6f8051fc8d03ef46bd66737dfe1f4))
* show "gonic" not version in --help ([3cf3bda](https://www.github.com/spijet/gonic/commit/3cf3bdafd890ea25247f2bf9af14e775d8d1d148))
* trim newlines when rendering flag values ([4637cf7](https://www.github.com/spijet/gonic/commit/4637cf70c16d9c4ea30c9604ca79704ec0e3f0c4))

### [0.13.1](https://www.github.com/sentriz/gonic/compare/v0.13.0...v0.13.1) (2021-05-08)


### Bug Fixes

* **docker:** bump alpine / go ([1f941b2](https://www.github.com/sentriz/gonic/commit/1f941b2085815d8aa0bf7ad7f3e44efba20295e8))

## [0.13.0](https://www.github.com/sentriz/gonic/compare/v0.12.3...v0.13.0) (2021-05-08)


### ⚠ BREAKING CHANGES

* **subsonic:** don't return gonic version from responses
* bump to go1.16 and embed version

### Features

* bump to go1.16 and embed version ([6f15589](https://www.github.com/sentriz/gonic/commit/6f15589c0889893b7beda85a81d49878401566f0))
* **ci:** arm builds, push multiple registries ([0622672](https://www.github.com/sentriz/gonic/commit/06226724b718883cff9e9150e60e2eeacc2e0a1c))
* **ci:** use ghcr and auto release ([c2c7eb2](https://www.github.com/sentriz/gonic/commit/c2c7eb249f77eebabc910c70357249a3017523ef))
* **subsonic:** don't return gonic version from responses ([58624f0](https://www.github.com/sentriz/gonic/commit/58624f07dc81c36fda79827cc41ac57e89e18b37))


### Bug Fixes

* **ci:** only test on go1.16 ([e9743f0](https://www.github.com/sentriz/gonic/commit/e9743f0cb0e96e9b4b434141e890a0fa16ce3f18))
* don't clutter db close in main ([e6b7691](https://www.github.com/sentriz/gonic/commit/e6b76915daa2bbd6f259f2b019cde9130c62e326))
* trim newline from version ([a565008](https://www.github.com/sentriz/gonic/commit/a5650084d7969a37765d291a6554984e4ae4e2d9))
