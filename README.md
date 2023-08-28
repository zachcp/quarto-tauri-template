# Quarto + Tauri

This should help you get started creating a new Tauri App with a Quarto frontend.


## Get started

```sh
# assuming quarto and cargo are installed and on your path.

# install the tauri cli
cargo install tauri-cli

# add cargo bind dir to the path
export PATH=$PATH:~/.cargo/bin/

# to develop 
cargo-tauri dev

# to package. this build is ~8MB. 
cargo-tauri build
```