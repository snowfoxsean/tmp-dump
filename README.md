# tmp-dump

Self-built Linux x64 bundles of open-source agent CLIs that publish no single-archive release
of their own. Each release holds one archive: a launcher script and the bundle it unpacks to
`/tmp` on first use. Nothing in a bundle is modified from its upstream.

| Tag | Bundle | Built from |
| --- | --- | --- |
| `v0.23.4` | `hermes-agent-0.23.4-linux-x64.tar.gz` | [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) v0.23.4 (MIT): its source tree, the dependencies its `uv.lock` pins with the `anthropic` extra, and CPython 3.14 |
| `v2026.11.10` | `openclaw-2026.11.10-linux-x64.tar.gz` | [openclaw/openclaw](https://github.com/openclaw/openclaw) 2026.11.10 (MIT): `npm install openclaw@2026.11.10`, Node 26.13.1, and the `libatomic`, `libstdc++` and `libgcc_s` it links |

Each project's licence, and those of its dependencies, are inside its bundle.
