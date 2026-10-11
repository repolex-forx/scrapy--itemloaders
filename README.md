# Repolex Knowledge Graph of scrapy/itemloaders

RDF knowledge graph data for [scrapy/itemloaders](https://github.com/scrapy/itemloaders), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download scrapy/itemloaders
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f3e680016d0fd49f24a656f440938ec14c0cd9db
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f3e680016d0fd49f24a656f440938ec14c0cd9db
│           └── chunk-001.nq.gz
├── blob
│   ├── 003b19e8aabce9ec93c211063fb4858469a9a122.nq.gz
│   ├── 010cbadc906a497d84e21b4566a7397685be52ef.nq.gz
│   ├── 0d897bca5e60621dfc7900f57290d89e108d2ead.nq.gz
│   ├── 15bf40e449e2be745975e12e6ba4868a53406fcc.nq.gz
│   ├── 1a38db513343e2decb6108ee89d5109316b03592.nq.gz
│   ├── 33b0006f61fbcbbdc904fe1230dd3677ef1c3d7d.nq.gz
│   ├── 380c0f9210b3f6688cea2063118270885a180fe3.nq.gz
│   ├── 39a0b067850ffacbce816228a2f9856388fe5dd4.nq.gz
│   ├── 3ad58f7a8859aa9144a9222e6dbfccaea02cbac8.nq.gz
│   ├── 3bffb65ed91657bcafd877df182de8f308d78ffd.nq.gz
│   ├── 447af5f56afa9fcecd840d1df1572e02c8d8221f.nq.gz
│   ├── 453858dd08dd3fc74397959a4aa0cf3eff44460b.nq.gz
│   ├── 469c34924590d18d36b4c5e33487893616c73499.nq.gz
│   ├── 4d0a0863ad6724fd6fdd10407169fe288a3cc95e.nq.gz
│   ├── 4dc602abe248ad01871827453b9e7d8686c2190d.nq.gz
│   ├── 5dd6b201c60505e97ab66b6e19b423756b8fcd2a.nq.gz
│   ├── 623d48cfa6b6f2ba551dde2435254ed5a1b63862.nq.gz
│   ├── 72787ec4c551e850901550e57e3ab3e5b1a9211d.nq.gz
│   ├── 777ca81e0553c077dc37fb3304e2600ba05525a3.nq.gz
│   ├── 80e2a3cfe6c4b58b7db6a8fd0885e188f05f9aa0.nq.gz
│   ├── 874f182face71a7dae0ee68df357b907ddf23505.nq.gz
│   ├── 87713fb777b121c9414b4e6ca7740a5f6135f87a.nq.gz
│   ├── 88af89229eeb7364ae4426b5a394ebafca8e1270.nq.gz
│   ├── 8af936f1518d9c67ae8303b8e7387d821c5bd950.nq.gz
│   ├── 8d647f2fb6d2e98c6092d47ee9ea9eb742da4fcf.nq.gz
│   ├── 8e7b55b5b58d69a0340395fc72c9d2856c9c6dbe.nq.gz
│   ├── 948842b3dc44471fed75e614bd95f85191703441.nq.gz
│   ├── a1f977670a40309eb622a220374e347550e03fe4.nq.gz
│   ├── b0eeb95f38a2b26a338a38674b0435038d61f75b.nq.gz
│   ├── b5da838aeb19226aa1d81e641fa1d2235ca971ff.nq.gz
│   ├── c125f59ff9f984194fd36ec8b8f0077452751beb.nq.gz
│   ├── c21e620135785f860a4e9d7846bead27eb902b66.nq.gz
│   ├── c6bf88980a47ef885911d6536e64ecc051ea0d47.nq.gz
│   ├── c74762ebbeb6f111f58770ea97c9533de6c3a86b.nq.gz
│   ├── c7b96808dee5a7477d176764d67c0b5594048efc.nq.gz
│   ├── cc6b873d21c97edf7bca8a983e0e83caeb5c8cf9.nq.gz
│   ├── d22e07916c0d3567a6b0efdb5da78644648ecc44.nq.gz
│   ├── d3a82c2e80c614caf290a5f94b5b4e72bb2ea8ca.nq.gz
│   ├── d52f8b0f4c20916c253780bbf99ec475a1f4d814.nq.gz
│   ├── d9537ee6fb607f58d09514f6badffe8f2ee0e89f.nq.gz
│   ├── db2da6f35d23d3e56c12d6a716ef8648c4569db2.nq.gz
│   ├── dd5ce06bb0601b8affc188b238752cbaa435f58d.nq.gz
│   ├── e5ff9b890d503ab503a7160590d5005e928cfb8f.nq.gz
│   ├── e64966b94e5e6ff003ed69d434d54abea3079177.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea6dcc511f16f67978d1892bbe58444ce3a097d7.nq.gz
│   ├── ef103285cdaf7f1b53c53a93dfcdd05756d591cd.nq.gz
│   ├── ef7f86a6cbe40d78d9ec0bffaf90e6999fec9789.nq.gz
│   ├── f4a34fe4c237f5895a446b6fa6571da2fd9aa8e2.nq.gz
│   ├── fed113ef6e9b4de1bfdba5c231416e44f368302e.nq.gz
│   └── ff68bf1ae769c32dfb33fb679d8e532332f43bd7.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f3e680016d0fd49f24a656f440938ec14c0cd9db.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 59 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[scrapy/itemloaders](https://github.com/scrapy/itemloaders)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
