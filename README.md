# Rust OS

[QEMU](https://qemu.weilnetz.de/)

```js
// Add QEMU to PATH - Environment Variables

$ cargo bootimage

$ qemu-system-x86_64 -drive format=raw,file=target/x86_64-rustos/debug/bootimage-rustos.bin
```
