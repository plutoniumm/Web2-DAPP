# WEB2 DAPP

This is a perfectly decentralized web app. Without Web3. Make no mistake it is stored on multiple devices and uses them for auth and data verification and all. It just uses no blockchain tech.

> Because as always

> *Web3 can solve this*

## Caveats
This is only a proof of concept therefore some features are not enforced or implemented
- Username uniqueness is not enforced. It can however be
- The data is technically encrypted but not secure since the encc key is in the code itself at
```js
// src/Chat.svelte@47:25
const key = '#foo'
```
This key has effectively been hard coded everywhere