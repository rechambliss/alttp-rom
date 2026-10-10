# alttp-rom (PRIVATE)

Riley's own dump of *A Link to the Past* (EU), for personal development use by the `alttp-recomp` tooling.

**This repo must never be made public, forked publicly, or shared.** Making it public would distribute the ROM.

| File | SHA-1 |
|---|---|
| `alttp-eu.sfc` | `7c073a222569b9b8e8ca5fcb5dfec3b5e31da895` |

Sessions use it like this:
```sh
export ALTTP_ROM=$PWD/alttp-rom/alttp-eu.sfc
```
`alttp-rom` checks the hash on every load and refuses any other file.
