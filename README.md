# riscv_emscripten

An attempt to port [riscv_em](https://github.com/franzflasch/riscv_em) to JavaScript using Emscripten.

A full instruction will available soon.

To build now, install Emscripten sdk and run:

```console
mkdir build && cd build
emcmake cmake -DRV_ARCH=32 ..
emmake make
```
or
```console
mkdir build && cd build
emcmake cmake -DRV_ARCH=64 ..
emmake make
```

Thanks!