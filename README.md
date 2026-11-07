# Repolex Knowledge Graph of allenai/state-bench

RDF knowledge graph data for [allenai/state-bench](https://github.com/allenai/state-bench), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/state-bench
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5b333b8d426638d8825f40efe8a508c20eb85730
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5b333b8d426638d8825f40efe8a508c20eb85730
│           └── chunk-001.nq.gz
├── blob
│   ├── 004145cddf3f9db91b57b9cb596683c8eb420862.nq.gz
│   ├── 05e726d1b4201bc8c7716d2b058279676582e8c0.nq.gz
│   ├── 07dfe28f70da31b4371684189293b55b51afa6e7.nq.gz
│   ├── 07f8318c3c290d68163e95aa3e170ad92a235f27.nq.gz
│   ├── 0899f32130352f93c5bfe4be011dcde1e1960409.nq.gz
│   ├── 09e87eb8afb782c77bdb8cde02d8ed89f93b3fb4.nq.gz
│   ├── 0fcf5e8ebf6a694e5c3a2f5a6e4dae846e684efd.nq.gz
│   ├── 1171301ad941ab0cedf4b7fb560ab237efcfef04.nq.gz
│   ├── 1288137d43b8c5291290664c2306cf791b6d9d3e.nq.gz
│   ├── 180afbf31e5a7d5107d4c2df4db9b9cc04f022ab.nq.gz
│   ├── 195730c18194b5493acc682654df1a0287f3cbec.nq.gz
│   ├── 19b379900d94124b674f07ffe2dbba8f70bd8d6d.nq.gz
│   ├── 1b7a51daaad785a4e07a63ab07f0ed5475d43298.nq.gz
│   ├── 1ebe5e3dd1d68665a94098403de7c53c28f2e983.nq.gz
│   ├── 22520dc6aa967eb69f572347970e21ee4ceab61a.nq.gz
│   ├── 236cfc6d3a6920733c15d4e92c3ecb3d06890463.nq.gz
│   ├── 258a65f137d13bc8b19e488600874eeb178388a0.nq.gz
│   ├── 259261b7409b0b2aad025159ccb76ce07629da7b.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 28cb20ee28d27879b50e0b62c0b00943e83a2008.nq.gz
│   ├── 2adbbd7196bbbc02c09c9d522de3d524f96a2ee4.nq.gz
│   ├── 2f541c1595c57ddf9597d956018562e6095491ee.nq.gz
│   ├── 2fa7b9dfdb6f08d62e79f2d082ca89f625a790f2.nq.gz
│   ├── 32e154266ecec525b10e7a40b0efe00aa8036525.nq.gz
│   ├── 382ff1f608e618388a9f986dc17027ef13dcc3ca.nq.gz
│   ├── 3a41625d5a4bd93c2ef047f6e3efcf112b81ad34.nq.gz
│   ├── 3b485d9254d59a754dba96cdd18d02912ccf2d98.nq.gz
│   ├── 3ca3d6b94eec1dc888c49c4857642a38dde6ae40.nq.gz
│   ├── 3e7fc60fa9e0af6a28ec94bd13a1f621aa84436c.nq.gz
│   ├── 491b44cc4842dd2cc1f1a7f88b7691d01d386bf5.nq.gz
│   ├── 4b346e518e65019ff9c98e108e4a300c4f825e1a.nq.gz
│   ├── 4db676abfddcb5d0f57547ee202be65d64315130.nq.gz
│   ├── 5243d362f6b1a51d69c1fade336491860fa330f0.nq.gz
│   ├── 567f17b0d7c7fb662c16d4357dd74830caf2dccb.nq.gz
│   ├── 590c4484280622c32ceb7bbd5a107cf5304aff0e.nq.gz
│   ├── 5916bdb35f225f813b65ad7a340c3565dd19aacb.nq.gz
│   ├── 60b02f525794f2a7ccd79f0ce475da069211e919.nq.gz
│   ├── 61e36849cf7cfa9f1f71b4a3964a4953e3e243d3.nq.gz
│   ├── 64fb5a85fb97a4b39d0ee853ff179fd2510ea06d.nq.gz
│   ├── 65855ad3fc839ab84946ca954ef24178501944e9.nq.gz
│   ├── 69cc2d0294e4b41ab9849a6d4797465d3aa61c5b.nq.gz
│   ├── 6acc30813ed2aa03afaf56819a2035a02b04f8de.nq.gz
│   ├── 6fd8b4f91a490b494ca2805b27946c380c3f3a97.nq.gz
│   ├── 7052f04026218dc88b401a39e75c9c857570016c.nq.gz
│   ├── 7598c3d9c70c9ec1c7853c8479c4caf34a70dcb8.nq.gz
│   ├── 792f9ae14fb5f644be8f10bd110a9ba2a52acaf4.nq.gz
│   ├── 7b74b7b4565797e53437c25677177abc97db1a24.nq.gz
│   ├── 7bb0c157110799b9b53c767517e0d192b7201f2e.nq.gz
│   ├── 899b350e86cde59a52898e1e1d4efe90865f0a26.nq.gz
│   ├── 8a87ecdcb78c5f22f2e43e3a19cee46a7fdf5179.nq.gz
│   ├── 8bf74a94c2f8a20541fbf9833f06e5df12d6518e.nq.gz
│   ├── 8d084a6c104f49135af82355f1b81fe91507977a.nq.gz
│   ├── 8d1fb3534463fb53fc0ff10ce6d5eccebf5964fa.nq.gz
│   ├── 94de59def11fd015e8bc6a16d161bc3572d0334f.nq.gz
│   ├── 9df07df1a9af26bb0bca9b828508c80c4f76f794.nq.gz
│   ├── 9ff4d6882476990be67f67e43433dd4a89bd732d.nq.gz
│   ├── a1aa2c7a3621cfc95c7fe5d4fcc7b6d56c3fc420.nq.gz
│   ├── ab100b29320f094757ff647df1f6e28ef0403f32.nq.gz
│   ├── ae08f93676d3ba1a026104ec8774505bf8d6725e.nq.gz
│   ├── ae3539c627ee001474ba0c0ae71062eaaa7d331e.nq.gz
│   ├── b02db8abbea1818a2aaeac90e5020b77df707394.nq.gz
│   ├── b053f84edfa2f7ebe2d7bc391e771434a062eeb9.nq.gz
│   ├── b2b2a44f6ebc70c450043c05a002e7a93ba5d651.nq.gz
│   ├── b38a5fc513b03abebf4b21c5cf15a95cd8765a66.nq.gz
│   ├── b3cd137862c517c1053481cf6efdf6dd4d423cdc.nq.gz
│   ├── b6d8a34cd5cc4cbf1046431bc6e1c807a92ecf28.nq.gz
│   ├── b89c11a5655a63c2778cd9ebbf7d08b1fcdec678.nq.gz
│   ├── b9fa4a62d71b3084a505b78ffbe1e8b8002d2fc1.nq.gz
│   ├── bcb86054246039000823fedf755e26732932a1e6.nq.gz
│   ├── c0d448a7c722fc9bcfa77b5083061b092fa47686.nq.gz
│   ├── c2b2f34376984744343453838ce66658ad9d9b6a.nq.gz
│   ├── c3472925abe82722a9d7d48d8079f810ca34c594.nq.gz
│   ├── c3fd27021f203adfc17ce2b5d324bebd274e145e.nq.gz
│   ├── c64207f6db277c525b81b13e817e60d65718936b.nq.gz
│   ├── c6df7a03cd5addbc2f44ed74287c29db95afbffa.nq.gz
│   ├── c8bb6cbe5dfcbe3a8da703b6c7fec83cec46b64a.nq.gz
│   ├── ca747cb66b233fedec5ff0c84f97bb4631c05dbf.nq.gz
│   ├── d0526c5b8a63e0356f3053c22f341acd1367f5d7.nq.gz
│   ├── d2dd83cd250ecaa6ac022559fc9640271f2b2dd5.nq.gz
│   ├── d5834b79de0d71118e2b5bcd90f6510f3194edad.nq.gz
│   ├── e002db7c52b32a5575866a7ec89a00963ef9e808.nq.gz
│   ├── e44565834c56280ade6e74170397044e4e215148.nq.gz
│   ├── e4fba2183587225f216eeada4c78dfab6b2e65f5.nq.gz
│   ├── e62a9e7273a1a5f48c18086203598ea0fa2a110d.nq.gz
│   ├── e63de9d939856e3abbc11821fc9b1febb62294d9.nq.gz
│   ├── e768d1f139f7e272f5d09d496606c135bb9a385f.nq.gz
│   ├── e9ffa3083ad279ecf95fd8eae59cb253e9a539c4.nq.gz
│   ├── ee27f2a2309f7690294b5897d6c7e1b1663f941c.nq.gz
│   ├── f529cbfe38bcf009840c214df49f3cb21b4db260.nq.gz
│   └── fda64d92283e4540a6b9401206664012bb80e398.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5b333b8d426638d8825f40efe8a508c20eb85730.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 97 files
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

[allenai/state-bench](https://github.com/allenai/state-bench)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
