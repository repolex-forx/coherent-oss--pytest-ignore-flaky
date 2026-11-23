# Repolex Knowledge Graph of coherent-oss/pytest-ignore-flaky

RDF knowledge graph data for [coherent-oss/pytest-ignore-flaky](https://github.com/coherent-oss/pytest-ignore-flaky), parsed by [repolex](https://repolex.ai).

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
rlex download coherent-oss/pytest-ignore-flaky
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── be6428645ce2204dc1583056ffa6104ee65bc318
│   │   │   └── chunk-001.nq.gz
│   │   └── edfb155cf9bae93ae8c765c67e83ffee6e34c5ea
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── edfb155cf9bae93ae8c765c67e83ffee6e34c5ea.nq.gz
│   └── repolex
│       ├── be6428645ce2204dc1583056ffa6104ee65bc318
│       │   └── chunk-001.nq.gz
│       └── edfb155cf9bae93ae8c765c67e83ffee6e34c5ea
│           └── chunk-001.nq.gz
├── blob
│   ├── 0935eece0d8626d7cdf22b0d4fb45ed6b8559631.nq.gz
│   ├── 10d412f406891b9683f832fcbc134c9bdf4f916e.nq.gz
│   ├── 1bb5a44356f00884a71ceeefd24ded6caaba2418.nq.gz
│   ├── 1f0e30e01590ea6657b51dbea42f54071cec3b77.nq.gz
│   ├── 1f2aa7533b0423a8eb943f6f4ec02498e39581a0.nq.gz
│   ├── 240329c3604d8ead4c10aa8c88352caa8e4ce7b2.nq.gz
│   ├── 28b83626e21e5cfa5e0f4e640d7eb4739bed1a33.nq.gz
│   ├── 2e3f4dd791a6372b427d618eb0baa8c4dc58e5f0.nq.gz
│   ├── 304196f81e11a168c9894f966e4a617ebf4ed53c.nq.gz
│   ├── 32150488de655c2c2ef3b26c0a8519e7365584b3.nq.gz
│   ├── 35b98b1df96093e99fea65bec2187baff3c12514.nq.gz
│   ├── 3976b2643dc10ddb1be2d725f724d91b6a256883.nq.gz
│   ├── 3d2d7c65071ad021e25ab7efad3b4aecf8ddd4dc.nq.gz
│   ├── 4c39a5b139c5c24eed2c8fe1f67116ef681ad39b.nq.gz
│   ├── 54c9000ec94341dd65c2053251b85b124017b9b5.nq.gz
│   ├── 54cc8303b22089e12053e552d4e6cb852a865b8a.nq.gz
│   ├── 577e87a793a20e413f7321f4f17ec1eba2ea1962.nq.gz
│   ├── 5a4a7e9166ec3143f71b5e3875860802048554f3.nq.gz
│   ├── 5bdc232005af9be104a00437ae9bc64417a4c1cc.nq.gz
│   ├── 6f7230cdcc2315b1e13a17072deb7569c7a42d40.nq.gz
│   ├── 6fa480e44f38768722368d7a986607adacf41d99.nq.gz
│   ├── 700235be57c1b2872455c0be5333f59cf568e252.nq.gz
│   ├── 70612985a7a6f8ae0e29777e7ed3df05e5a717dc.nq.gz
│   ├── 724370638fc188317bbc7dc868f1a571995fd796.nq.gz
│   ├── 7a37718862fd4d6e5ac32613230133ba0033c0c8.nq.gz
│   ├── 85dfea9d42d16274b4e8a4892bf6986d131f4241.nq.gz
│   ├── 89ff33961ba3d6f9cda89322a1fdbf1ac2e35513.nq.gz
│   ├── 8f3034ec7e57b3e68500635063f3e9e53f7e15eb.nq.gz
│   ├── 9a0f3bce1395ae3819030b822e5d9076c85068ea.nq.gz
│   ├── ac0ff69e22507b430cfb9a91d98e2451a3de52d9.nq.gz
│   ├── b20d53352da356ee1bc8b4e0e4aa4d9ed2017c51.nq.gz
│   ├── b6f972769e61a5e65f9f45015b363cc362487e55.nq.gz
│   ├── caa3401c9a12d0b87ae7d1888b8c10694ed2385b.nq.gz
│   ├── cb841f1daa46a2b31e774af81aa03f3c75dbf66f.nq.gz
│   ├── ce5cbbc53afc4392b02184e352f5de1d94f33da6.nq.gz
│   ├── e05a3d4a2ab888e32952006d8cd380864368db5f.nq.gz
│   ├── e06db79359eab7a1edefd183200d28dc43e55c84.nq.gz
│   └── efcb8cbc2043faa7caf4f92fc7488bd6914c934c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── edfb155cf9bae93ae8c765c67e83ffee6e34c5ea.nq.gz
├── filetree
│   ├── be6428645ce2204dc1583056ffa6104ee65bc318.nq.gz
│   └── edfb155cf9bae93ae8c765c67e83ffee6e34c5ea.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

17 directories, 51 files
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

[coherent-oss/pytest-ignore-flaky](https://github.com/coherent-oss/pytest-ignore-flaky)

---
*Parsed on 2026-11-23 by [repolex](https://repolex.ai)*
