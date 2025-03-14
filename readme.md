# music-os-core

[![dry run prettier](https://github.com/music-os/music-os-core/actions/workflows/prettier.yml/badge.svg)](https://github.com/music-os/music-os-core/actions/workflows/prettier.yml)
[![unit tests](https://github.com/music-os/music-os-core/actions/workflows/node.js.yml/badge.svg)](https://github.com/music-os/music-os-core/actions/workflows/node.js.yml)

<p align="center">
  <img src="/assets/logo.webp" />
</p>

## installation

### Prerequsites

music-os-core is dependent on an Ethereum full node JSON-RPC interface.
Consider running your own node or choose an existing service from
[ethereumnodes.com](https://ethereumnodes.com/).

```bash
cp .env-copy .env
# and replace `RPC_HTTP_HOST` with your node's URL
npm i
npm run dev
```

## contributing

See [contributing.md](./contributing.md)

## license

Licensed as [SPDX-License-Identifier: GPL-3.0-only](https://spdx.org/licenses/GPL-3.0-only.html)
