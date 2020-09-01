# scryfall-rs

A wrapper around the scryfall magic the gathering API

[![Crates.io](https://img.shields.io/crates/v/scryfall.svg)](https://crates.io/crates/scryfall)
[![Documentation](https://docs.rs/scryfall/badge.svg)](https://docs.rs/scryfall)
![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Rust](https://github.com/mendess/scryfall-rs/workflows/Rust/badge.svg)


This is a work in progress, but the basic api is wrapped and can be used,
however until v1.0 releases breaking changes should be expected.

## TODO

- [ ] Search Wrapper
  - Shortcuts and nicknames
  - Exact Names
  - Using "OR"
  - Display Keywords

- [x] Use `reqwest::Client` for faster requests

- [ ] Cache results as requested by the `scryfall` API

- [ ] Fully test the `card_searcher::SearchBuilder`.
