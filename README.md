
[![Build Status](https://jostein.visualstudio.com/audiophile/_apis/build/status/josteink.audiophile?branchName=master)](https://jostein.visualstudio.com/audiophile/_build/latest?definitionId=1&branchName=master)

# audiophile

A [Rust](https://www.rust-lang.org/)-based, self-contained tool which analyzes your audio-collection
and identifies extra high-fidelity audio-files (>16 bit, >44.1kHz).

Currently supports analysis of FLAC, WAV and ALAC files.

## building

Building audiophile depends on having a Rust toolchain installed.
If you don't have that already, please consult [the rustup
website](https://rustup.rs/) first.

## usage

````
git clone https://github.com/josteink/audiophile
cd audiophile
cargo run /path/to/your/music
````

