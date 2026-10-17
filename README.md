# Repolex Knowledge Graph of spatialaudio/python-sounddevice

RDF knowledge graph data for [spatialaudio/python-sounddevice](https://github.com/spatialaudio/python-sounddevice), parsed by [repolex](https://repolex.ai).

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
rlex download spatialaudio/python-sounddevice
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 626fcb071638ebbb631ccd40f3307f8dce68af63
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 626fcb071638ebbb631ccd40f3307f8dce68af63
│           └── chunk-001.nq.gz
├── blob
│   ├── 08790d0af44b37f78f3827d7bb2b33ee9a1dc5ba.nq.gz
│   ├── 08a52102798f137fd339fbff31ff8c23761a6678.nq.gz
│   ├── 14d4453c47e4c289d266f72f33c94b9fd30bb4bb.nq.gz
│   ├── 229239468aadc20f4c8360ae00af8df1773158ba.nq.gz
│   ├── 32f1fe8c2cbdec5bdf2d340a55ab86edbe855bcb.nq.gz
│   ├── 3affd01a587b2b3bde6a559eaecfad2ef97abf01.nq.gz
│   ├── 4a9eaf4706af11958d37502f6dc368df71c03157.nq.gz
│   ├── 4afca0686f4a27a3d657a498e316e141dbc18e92.nq.gz
│   ├── 53b33d01343879cace4a655c99678bfd85e5c356.nq.gz
│   ├── 5438b1143ad4fa7b7ed7c7a1cb2100e582f97703.nq.gz
│   ├── 59d2fe2d1c11910aa59395b6f00aee6a7da5d0e7.nq.gz
│   ├── 5ace4600a1f26e6892982f3e2f069ebfab108d87.nq.gz
│   ├── 6b99611d0d8bfaf79437079005c35d2aedf89f28.nq.gz
│   ├── 6e4c2b6af8fddec00b505a2ef41d2766fa7918cf.nq.gz
│   ├── 78d16c7f7de6187a56548cd224cd24596af97494.nq.gz
│   ├── 7a60445fb5d87b662f89e63901058e697847cb67.nq.gz
│   ├── 8851a63bd1ad9865565f8a0500af2aed35ebf26a.nq.gz
│   ├── 8e3d39d9fc79d88834a69098bd15f14922c4bce6.nq.gz
│   ├── 8fbb6328654847c84b7e999eb601d91d15689b8b.nq.gz
│   ├── 941fe0bbea78174f46510840e8470826a2a86ae7.nq.gz
│   ├── 98c37ddf0d857a26e97d456da1adea0817d195d8.nq.gz
│   ├── 991367d8969170ace7ebc8db9dcd0892c48cca29.nq.gz
│   ├── 9ceaed5a1c844d499682d12fa1ee0567df1aac35.nq.gz
│   ├── a02e837b8ff06d95fdce463dedff24b4607d6f4d.nq.gz
│   ├── ac84362fe42eaefdc0314050f82680e1917a6f05.nq.gz
│   ├── b3268cba1c34eceafe4cfe315de83802ff878c6b.nq.gz
│   ├── b608046386bfde54c1747222472a9540d2e00301.nq.gz
│   ├── b65d8e9b257f83fe34402a6b78a0f225807ac953.nq.gz
│   ├── b95b5681e338642cc6482349398bf6a9aea6b824.nq.gz
│   ├── bb2a36f239b87ca5aa964ac8f6d8ac8f4d1c7955.nq.gz
│   ├── bd0cccff4cfbb00acfd69ed278ed2bffbe2c700e.nq.gz
│   ├── be5f5a6c6a95a85d20ddbad74102a770f4a651c8.nq.gz
│   ├── bf1445edef0990fb4f86dab6ef855244bf5f4232.nq.gz
│   ├── c2bd4e85cd945744400ad76b04eeb905b04453f3.nq.gz
│   ├── c50dbdac91f6a077bc6428ef365bcb5e9f6a7949.nq.gz
│   ├── cb94d523206d5d01c8f3694f3013fe65b1c240a2.nq.gz
│   ├── cc78a1343e27995444628ee8fabaa904594456c7.nq.gz
│   ├── ce06907bfe7a2fc8b0d88487e48cc555b53dd5d0.nq.gz
│   ├── ce2b55f879187301cf867766b94bccb13767ec3d.nq.gz
│   ├── ceb935081eddee170896bfa3661648b7db09fcf7.nq.gz
│   ├── d1f822847cc76bae2eef1542f4fca11aec9752cc.nq.gz
│   ├── d31a1e3e2c0b68dd927a83e3ff85e807d6649513.nq.gz
│   ├── dc5e1edf6b0ac21f3ac975f1b7cf708bce4f96e5.nq.gz
│   ├── e046da987a3186e20394e8396179580148d483cc.nq.gz
│   ├── e0e1066612db8ea3b1324e27b2a3087ff546f619.nq.gz
│   ├── e3dcd1c59f0451862dab3b04c17d78f92232f541.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8da8a2bbe3007c81771200333c6fb3cfa41440a.nq.gz
│   ├── ed40c806c78956d7770fe35ecc89054ed0ce0308.nq.gz
│   ├── f1a1556aae7033acd69e5db378849bfaa8ac220e.nq.gz
│   ├── f2e96be03f014ba74ed82fa8b8c5550247fc607f.nq.gz
│   ├── f6acf5e0fd4d53b060897c21a7493213800c03ca.nq.gz
│   ├── f885ad77f97595cb8a3167a037e7189dbdeda912.nq.gz
│   ├── fcc12563a92a91243536de9f3fa639c8affff684.nq.gz
│   └── fccb2272ca757c42f990432a4c0961ed15bbaa20.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 626fcb071638ebbb631ccd40f3307f8dce68af63.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 63 files
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

[spatialaudio/python-sounddevice](https://github.com/spatialaudio/python-sounddevice)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
