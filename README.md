# Repolex Knowledge Graph of pydantic/logfire-rust

RDF knowledge graph data for [pydantic/logfire-rust](https://github.com/pydantic/logfire-rust), parsed by [repolex](https://repolex.ai).

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
rlex download pydantic/logfire-rust
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 804eca47b0c9668a91c68325f5e3ebf6a3700be6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 804eca47b0c9668a91c68325f5e3ebf6a3700be6
│           └── chunk-001.nq.gz
├── blob
│   ├── 0393bc48ff68556d935535b1530ab99d28662d7a.nq.gz
│   ├── 03a38db46561b3b6aaf7ba68d11543f6c84b1689.nq.gz
│   ├── 03e6726b4f85eb67a4abff70e2c67f594ad56052.nq.gz
│   ├── 07c12f25c6b44123c21e25124158e6580c459d2e.nq.gz
│   ├── 0ccf717897ebe5ba1a47c8ac44c25440a7767b82.nq.gz
│   ├── 18c731919a7f20ae4c274ee23b89276a6cc45c8d.nq.gz
│   ├── 1a9f5ba7b6baa7faa47048bc3e22676081441a36.nq.gz
│   ├── 1d8f0cce23629c1d2d9bc7c3cd9a6317d6953d25.nq.gz
│   ├── 1eb482d33971d0979d953812799e8c1163d48ba3.nq.gz
│   ├── 23b2174ac980bf9062b672a5c3a7e196488544c2.nq.gz
│   ├── 2b64f352f4adaac59345c8220ffc8f319284b0f8.nq.gz
│   ├── 2c2f634728b766e291d9914f4c234363c76f685d.nq.gz
│   ├── 2c96eb1b6517f2617f9ddeae9f07f5fd7bd7ddef.nq.gz
│   ├── 2de2eadbc89203089ceb4f3f463eec4c1beb979a.nq.gz
│   ├── 2f64cf7fc8d1a310ddfc6faae06ea45713838714.nq.gz
│   ├── 30719e91a68fb26e10c3b826e509ceefe8f44ba4.nq.gz
│   ├── 34e7cc9a740fc978b059d4cdf40747343ce5ec24.nq.gz
│   ├── 38b07210b09e8bd9d9d3207eaa7110a47bae9987.nq.gz
│   ├── 3c129c8e96597a96a08321737a8f06d172dd5278.nq.gz
│   ├── 3d0d405928eb4d16ed8132d605d2856f141abcb7.nq.gz
│   ├── 3ea933ae1a5bc4dd9676f6595c818fcb6df383b6.nq.gz
│   ├── 405080c4d033f35a3078d6830c419609bef7ed12.nq.gz
│   ├── 44c34760cea0e4d473b64c7a14d52045a5f6ba4f.nq.gz
│   ├── 4548dfd52e9126b5be27b6546394d026090e5255.nq.gz
│   ├── 45977ee92c20e35f4cb23018be4c9c63ebd90096.nq.gz
│   ├── 4881688b8c6228a2f76e0aa43ab6d6c00ab53dad.nq.gz
│   ├── 53d5e106f100a288aa6cf6da3e61a9172e07dd72.nq.gz
│   ├── 61cc5bdb20b72ba55b4d669eea2abe7a04878972.nq.gz
│   ├── 651c9aa058a01fc079a9eee1db3d7398d5de9423.nq.gz
│   ├── 6588c2deaaca681db555eed8db846fb0061211ee.nq.gz
│   ├── 6905f6215044b0f56de7de5eaae4b9f47942cca5.nq.gz
│   ├── 6c3e1dba484a3b07e49404cb5cbe2936a75dc303.nq.gz
│   ├── 6fc5ef4a4424690d1f4aa1d894f0419da2e33c82.nq.gz
│   ├── 6fda9b48d59f5c6203bc3623f2506fc8aaa96aa2.nq.gz
│   ├── 755272c0a5732bce9ffa377896c54e7aef88b9f2.nq.gz
│   ├── 76d23c2339e795388af860deb39883b8f4d54be1.nq.gz
│   ├── 840d5c5216151fd822971a6ca404f8dba14c333e.nq.gz
│   ├── 87e548a71b88be93caf4b107f8512f2155d04210.nq.gz
│   ├── 88cb2c560cc6a38a3f5b9cbdcafb36e66da0dabb.nq.gz
│   ├── 8b880e77ba6453cc55f1be8d24a4c0ed48bba4bd.nq.gz
│   ├── 8d35ba4cfa636eb15b1e26fca7b903281d2b36e1.nq.gz
│   ├── 93aa74298ee471f05ead982a10f564be45f6f06b.nq.gz
│   ├── 9a0cfdd1d1e74845a3462d06064357578883a9ad.nq.gz
│   ├── a48951e5d8114579102082f5438362301b210ec2.nq.gz
│   ├── a49454ccecd1c3939751ebe9ef2ca61aaec230f2.nq.gz
│   ├── b52a5a3e9fbdcd68e01a5d8143404019a0a2f434.nq.gz
│   ├── b8122aecae48c6f2525f717dff5acafdbf7b301d.nq.gz
│   ├── be0fe616321c175ea52e61111850566ffec13df1.nq.gz
│   ├── c509a557730cd0f7d59891ef784763c5f080745a.nq.gz
│   ├── c71e3b85569c884c9f79470ce9029402ae4ab62b.nq.gz
│   ├── caec092df47327840d87c32bbd1585af09f2ff11.nq.gz
│   ├── d2de1f0aff801c65ef8a750cd96e6d2d22308962.nq.gz
│   ├── d39c99129ee9d8c5fe8852772b779fdce9b85dc5.nq.gz
│   ├── d992e26ef4dc173ca68bdf5b3238103f91f6f4f1.nq.gz
│   ├── e4380973a14d8ff95b555e02779457b7cb971d41.nq.gz
│   ├── e7b7f6f268723770400685f881b27644071b7c6f.nq.gz
│   ├── e98a24636067faf34e7ea809b7f08febc0edf26e.nq.gz
│   ├── eb7a9ef9be03dbd6275c43e87a5a95e4f307dd71.nq.gz
│   ├── ec1ae29fda5ac28872beeb325603750d711bec29.nq.gz
│   ├── ef2b167c6b00bf29d911b2110a677773ce5be0fe.nq.gz
│   ├── f2f5ac1a13fe0b51e18934a789ef524b7a132b2b.nq.gz
│   └── f467941c808711e28dbd7eadfefc0d10322e0340.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 804eca47b0c9668a91c68325f5e3ebf6a3700be6.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 70 files
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

[pydantic/logfire-rust](https://github.com/pydantic/logfire-rust)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
