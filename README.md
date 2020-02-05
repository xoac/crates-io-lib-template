
# cargo-io-lib-template

This is tweaked `cargo init --lib` for FOSS.

## Use `cargo generate` to clone this template
```
cargo generate --git https://github.com/xoac/crates-io-lib-template.git --name my-project
cd my-project
```
[Learn more about `cargo generate` here.][cargo-generate]

## Update Cargo.toml
There are some basic information you should provide.
[Learn more about Cargo.toml here.](https://doc.rust-lang.org/cargo/reference/manifest.html)
This is limitation because of this [issue](https://github.com/ashleygwilliams/cargo-generate/issues/17).

## Update CHANGELOG.md
At the bottom of file you need to specify correct url.
This is limitation because of this [issue](https://github.com/ashleygwilliams/cargo-generate/issues/17).

## Replace this README.md
Create description of you library at top of `src.lib.rs` and generate README.md from that.
```
cargo readme > README.md
```
[Lern more about `cargo readme` here.][cargo-readme]

## What this provide:
- Follow [Rust API Guidelines]
  * license MIT OR APACHE v2.0
- Contains default `README.tpl` that help you generate README.md with [cargo-readme]
- Contains `CHANGELOG.md` that follow [keepchangelog]

[Rust API Guidelines]:https://rust-lang.github.io/api-guidelines/about.html
[cargo-readme]:https://github.com/livioribeiro/cargo-readme
[cargo-generate]:https://github.com/ashleygwilliams/cargo-generate
[keepchangelog]:https://keepachangelog.com
