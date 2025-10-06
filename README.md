# OpenSSL for Android
Automatically compile static OpenSSL 1.1.1i library for Android by Github Actions.

Added `-fPIC` to fix linking error.

with `clang` compiler.

## Android
`armeabi` targets are no longer supported with NDK R17+.
|ABI|API|NDK|
|:-|:-:|:-:|
|armeabi|21|r16b|
|armeabi-v7a|21|r21e|
|arm64-v8a|21|r21e|
|x86|21|r21e|

## ChangeLog
| Date      | Content                                                              |
|-----------|----------------------------------------------------------------------|
| 2025.10.06 | Build 1.1.1i based on OpenSSL3.5.3 (NDK r21e) |
| 2025.10.06 | Fork from 217heidai/openssl_for_android |
