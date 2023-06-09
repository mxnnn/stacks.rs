# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.1.10](https://github.com/mxnnn/stacks.rs/compare/v0.1.9...v0.1.10) - 2023-05-31

### Other
- update release.yml

## [0.1.9](https://github.com/mxnnn/stacks.rs/compare/v0.1.8...v0.1.9) - 2023-05-31

### Added
- added downcasting methods
- tuple updates
- string updates
- response updates
- principal updates
- prefixed updates
- optional updates
- list updates
- int updates
- buffer updates
- update bool cv
- impl iterator clarity types
- read-only-call
- ascii & utf8 cv
- update readme
- base account & transaction api
- remove unnecessary clone
- update builder ergonomics
- remove impl_generic_display trait
- remove transaction args
- add base api module
- add core api url
- ci
- update examples
- complex contract-call & token transfer tests
- transaction tests
- add examples
- sponsored contract-call tx
- multi-sig contract call
- signed contract-call
- unsigned single-sig contract call
- contract-call structure
- base contract-call module
- top-level module
- stx transfer transaction
- crypto module changes
- clarity module changes
- example & config changes
- debugger setup
- initial module
- improved crypto visibility
- improved clarity errors
- response ok/err model
- tuple cv module
- cfg! test modules & clean clarity-type
- principal cv & result serialization
- opt cv
- list cv
- int cv
- buffer cv
- bool cv
- intCV & uintCV module
- hash impl_newtype
- update modules
- restructure mods
- hex error enum
- top level error enum
- base58 error handling
- update network impl
- base wallet-sdk
- base32 crockford
- bip32 implementation
- base58 encoding
- hex encoding
- sha256 & ripemd160
- crypto module
- prelude & lib updates
- update deps
- initial commit

### Fixed
- assortment clippy:recs
- remove unnecessary unwrap
- unnecessary result base58 encoding
- base58check_encode network impl
- c32check_encode version

### Other
- update example structure
- added dispatch workflow
- added release workflow
- update rustfmt nightly
- update rustfmt config
- 0.1.8
- fix ci
- Add wallet encryption/decryption methods
- 0.1.7
- change xkey visibility
- update readme
- update version & example
- update version
- update examples
- update version
- updated crate metadata
- update fetcher documentation
- Update README.md
- add crate metadata
- Update README.md
- Update README.md
- Merge pull request [#11](https://github.com/mxnnn/stacks.rs/pull/11) from mxnnn/feat-mxnnn-api
- remove unnecessary impl
- Create LICENSE
- Merge pull request [#3](https://github.com/mxnnn/stacks.rs/pull/3) from mxnnn/feat-mxnnn-transactions-module
- base stacks_transaction
- clippy warnings
- adjust clarity mod visibility
- added tuple test
- change crate name
- base clarity mod
- remove unused snippets
- naming & structure changes
- fix clippy warnings
- bip32 errors
- chain_code added byte size
- hex imports
- chore edit b58 comment
- type declaration for impl Into<String>
- hex to bytes
- base58 error enums
- sha lint
- change b58 error enum comment
- b58 remove unnecessary imports
- added b58 comments
- update wallet_sdk child naming
- update top-level error
- remove redundant into
- remove unused modules
- format sha
- restructure mod
- adjust account impl
- update cargo.toml
- adjust network version
- move BitcoinNetworkVersion
- move stacksnetworkversion
- Update README.md
- rename hash160 to ripemd
- rename sha256 to sha
- remove debugger comment
- Update README.md
- update dependencies
- debugger configuration
- added makefile
- added README
