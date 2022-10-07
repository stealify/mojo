# mojo
Is the Stealify Implementation and Tooling as also bindings for the chromium mojo interface

This document and the other docs are partial a subset of the [Mojo documentation](https://source.chromium.org/chromium/chromium/src/+/main:mojo/README.md#Mojo-Core) as also some additions and Stealify wording.

The JavaScript/ECMAScript API exposes the capabilities to create message pipes, data pipes, shared buffers and watchers. 
The API is defined using Web IDL. You could find the IDL files [here](https://cs.chromium.org/chromium/src/third_party/blink/renderer/core/mojo/)

the low-level C system API is [here](https://source.chromium.org/chromium/chromium/src/+/main:mojo/public/c/system/README.md#) for more detailed documentation of equivalent methods.

## Mojo Documentation quickstarts
- [Create Bindings](https://source.chromium.org/chromium/chromium/src/+/main:mojo/public/tools/bindings/README.md)
