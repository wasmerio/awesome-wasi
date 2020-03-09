# Awesome WASI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Collection of awesome things regarding WebAssembly WASI ecosystem.

Please read the [contribution guidelines](CONTRIBUTING.md) if you want to contribute.

## Contents

- [General Resources](#general-resources)
- [WASI-compatible Runtimes](#wasi-compatible-runtimes)
- [Utilities](#utilities)
- [WASI Programs](#wasi-programs)
  - [AssemblyScript](#assemblyscript)
  - [Rust](#rust)
  - [C](#c)
  - [Zig](#zig)
- [Articles](#articles)
- [Podcasts](#podcasts)
- [Resources in other languages](#resources-in-other-languages)
  - [Japanese](#japanese)

## General Resources
- [Official Website](http://wasi.dev/)
- [WASI GitHub Repo](https://github.com/webassembly/WASI)
- [Mozilla Announcement](https://hacks.mozilla.org/2019/03/standardizing-wasi-a-webassembly-system-interface/)
- [WASI SDK](https://github.com/CraneStation/wasi-sdk)
- [WASI Preview API (Previously known as WASI-Core)](https://github.com/WebAssembly/WASI/blob/master/phases/snapshot/docs.md)
- [WASI CG Meetings](https://github.com/WebAssembly/WASI/tree/master/meetings)


## WASI-compatible Runtimes

- [Lucet](https://github.com/fastly/lucet)
- [Wasmer](https://github.com/wasmerio/wasmer)
- [Wasmtime](https://github.com/cranestation/wasmtime)
- [wasm2cil](https://github.com/ericsink/wasm2cil)
- [WAVM](https://github.com/WAVM/WAVM)
- [wasm3](https://github.com/wasm3/wasm3)

## Utilities
- [WASA - WASI layer interface for AssemblyScript](https://github.com/jedisct1/wasa)
- [WebAssembly.sh - An online WebAssembly WASI shell](https://webassembly.sh)
- [Wasienv: WASI Development Workflow for Humans](https://github.com/wasienv/wasienv)

## WASI Programs

### AssemblyScript
- [wasm-matrix](https://github.com/torch2424/wasm-matrix)

### Rust
- [cowsay](https://github.com/wapm-packages/cowsay)
- [fortune](https://github.com/wapm-packages/fortune)
- [lolcat](https://github.com/wapm-packages/lolcat)
- [viu](https://github.com/wapm-packages/viu)
- [rust-wasi-example](https://github.com/wapm-packages/rust-wasi-example)
- [Rust WASI Tutorial](https://github.com/kubkon/rust-wasi-tutorial)

### C
- [OpenSSL](https://github.com/wapm-packages/openssl)
- [jq](https://github.com/wapm-packages/jq)
- [sqlite](https://github.com/wapm-packages/sqlite)
- [quickjs](https://github.com/saghul/wasi-lab/tree/master/qjs-wasi)
- [duktape](https://github.com/saghul/wasi-lab/tree/master/wasiduk)
- [WASI C Tutorial](https://github.com/CraneStation/wasmtime/blob/master/docs/WASI-tutorial.md)
- [Wasm Clang](https://github.com/binji/wasm-clang)

### Zig
- [Hello World](https://github.com/bketelsen/hello-wapi)

## Articles

- [Porting Redis to WebAssembly with clang and WASI](https://medium.com/fluence-network/porting-redis-to-webassembly-with-clang-wasi-af99b264ca8)
- [Compiling C to WebAssembly using clang/LLVM and WASI](https://00f.net/2019/04/07/compiling-to-webassembly-with-llvm-and-clang/)
- [Running WebAssembly and WASI with .NET](https://ericsink.com/entries/wasm_wasi_dotnet.html)
- [WASM to WASI](https://rendered-obsolete.github.io/2019/04/29/wasi.html)
- [My First WASI Experience in Windows 10](https://www.codepool.biz/first-wasmtime-experience-windows-10.html)
- [The Promise of WebAssembly](https://dev.to/ryan_levick/the-promise-of-webassembly-2obi)
- [Running WebAssembly in the Kernel](https://medium.com/wasmer/running-webassembly-on-the-kernel-8e04761f1d8e)
- [Blockchain-flavored WASI](https://github.com/oasislabs/rfcs/blob/blockchain-wasi/blockchain_wasi.md)
- [Announcing WebAssembly.sh](https://medium.com/wasmer/webassembly-sh-408b010c14db)
- [Wasienv: WASI Development Workflow for Humans](https://medium.com/wasmer/wasienv-wasi-development-workflow-for-humans-1811d9a50345)
- [Wasm as a Platform for Abstraction](http://adventures.michaelfbryan.com/posts/wasm-as-a-platform-for-abstraction/)


## Podcasts

- [Ashley Williams on Web Assembly, Wasi, & the Application Edge](https://poddtoppen.se/podcast/1106971805/the-infoq-podcast/ashley-williams-on-web-assembly-wasi-the-application-edge)
- [Wasmer is taking WebAssembly beyond the browser](https://changelog.com/podcast/341)

## Videos

- [CppCon 2019  "Applied WebAssembly: Compiling and Running C++ in Your Web Browser" by Ben Smith](https://www.youtube.com/watch?v=5N4b-rU-OAA)

## Resources in other languages

### Japanese
- [コンテナ技術を捨て、 WASIを試す](https://medium.com/nttlabs/wasi-6060b243ac90)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Wasmer, Inc.](https://github.com/wasmerio) has waived all copyright and related or neighboring rights to this work.
