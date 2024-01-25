# Blog OS

A minimal operating system written in rust following Philipp Oppermann's blog [Writing an OS in Rust](https://os.phil-opp.com/)

## Dependencies
- nightly rust (`rustup install nightly`)
- nightly rust-src (`rustup component add rust-src --toolchain nightly`)
- llvm-tools-preview (`rustup component add llvm-tools-preview`)
- bootimage (`cargo install bootimage`)
- QEMU (Install from here: <https://www.qemu.org/>)

## Run
To build and run the kernel in QEMU, execute the following command:

```
cargo run
```
