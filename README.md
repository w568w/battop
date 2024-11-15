# battop

[![Latest Version](https://img.shields.io/crates/v/battop.svg)](https://crates.io/crates/battop)
![Continuous integration](https://github.com/svartalf/rust-battop/workflows/Continuous%20integration/badge.svg)
[![Packaging status](https://repology.org/badge/tiny-repos/battop.svg)](https://repology.org/project/battop/versions)
[![dependency status](https://deps.rs/crate/battop/0.2.4/status.svg)](https://deps.rs/crate/battop/0.2.4)
![Apache 2.0 OR MIT licensed](https://img.shields.io/badge/license-Apache2.0%2FMIT-blue.svg)

`battop` is an interactive viewer, similar to `top`, `htop` and other *top utilities,
but about the batteries installed in your notebook.

**The original repository has been inactive for several years, so I decided to fork it and continue the development.**

![Screenshot](https://raw.githubusercontent.com/w568w/battop/master/assets/screenshot.png)

## Features

 * Cross-platform (Linux, MacOS, FreeBSD and DragonflyBSD **and Windows** are supported)
 * Supports multiple batteries in case your notebook have them 
 * It is free
 * Usually it just works!

`battop` is backed by a Rust crate [starship-battery](https://crates.io/crates/starship-battery)
which provides unified cross-platform information about system batteries.\
[Check it out](https://github.com/starship/rust-battery/),
if you want to gather the same information for your application!

## Installation

### From sources

Clone the repo and run

```
$ cargo build --release
```

## Usage

Simply running the `battop` command in your terminal should do the thing.

Left and right arrows can be used to switch between different system batteries (if available).

Run the `battop -h` command to see the additional available options.

## License

`battop` is double-released under the Apache License, Version 2.0 or the MIT License.