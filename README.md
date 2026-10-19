# Repolex Knowledge Graph of klen/pylama

RDF knowledge graph data for [klen/pylama](https://github.com/klen/pylama), parsed by [repolex](https://repolex.ai).

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
rlex download klen/pylama
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 53ad214de0aa9534e59bcd5f97d9d723d16cfdb8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 53ad214de0aa9534e59bcd5f97d9d723d16cfdb8
│           └── chunk-001.nq.gz
├── blob
│   ├── 00aa95dc26fb485198a815a8bcd0f7639df9c289.nq.gz
│   ├── 04e78cf6ed2af94097966632e123531404daf5da.nq.gz
│   ├── 052ef219c6f078692daccdb9336beb95c5d3bba1.nq.gz
│   ├── 0bd78c5b04af6102b0aba0441b50ef35ab65fbd8.nq.gz
│   ├── 1af659a99042cb5f825291aa19c178e7b1be2bfa.nq.gz
│   ├── 1b5f99ff1ef9a70fe42a97cbce5844dc110efe6b.nq.gz
│   ├── 20f3528ace70e7c54d00038417d3d194afa3125a.nq.gz
│   ├── 26cf07a54b439349cc19fd8e514dda989a30ae06.nq.gz
│   ├── 2af02a511ee5b1bb9dba8a18581e8862b93e487d.nq.gz
│   ├── 2b981333116b7ed51500ff00fb6608ca3bbcbdf5.nq.gz
│   ├── 2ee8fd73cada81aec6b055d1d800076cd82327e7.nq.gz
│   ├── 3d57428018dc8dcfc7045312d106631f6a074693.nq.gz
│   ├── 420a91021a3081cc5fb2f2dabf2994620558b324.nq.gz
│   ├── 452661009f6cddd8445497fd93abf300ebea424b.nq.gz
│   ├── 49317484f049292226ae48479ce4d30d7b66a916.nq.gz
│   ├── 4efd70ceca509312f8227a8fba9c3d15b0cbd89c.nq.gz
│   ├── 585fb31a6adf2562237062827e7a23345c96d699.nq.gz
│   ├── 5b4441e1957e5a7cceb8ea7aee619dd28ffd179b.nq.gz
│   ├── 6365eb0980d2e754249ed012b1ae58a0c02467be.nq.gz
│   ├── 655801851274a41b09522b3f66436a295ffd6f6b.nq.gz
│   ├── 664e86c4b0464d33f6c75b1401ddb8a3bb6d2a7d.nq.gz
│   ├── 7409198c2d9dcbfb7422679e0bc279235470bd79.nq.gz
│   ├── 74f09fda9774150f67b9b42a31bf072446df4d62.nq.gz
│   ├── 7932314610b61d4dafe1a3b9cdd079184545f328.nq.gz
│   ├── 8009a5167729e6895524a1a5691cd52af9e5578d.nq.gz
│   ├── 890701c0dede61db0393b50972fa645e5a39b8c4.nq.gz
│   ├── 8a1a6066acade66cc53e53effe52a3425711aaf0.nq.gz
│   ├── 8af255e02f596c042971b703f1f91d0399604bc5.nq.gz
│   ├── 8e946ef582d8d888a2f333116c79d66f9799feb9.nq.gz
│   ├── 90c55e5f77fedaf91a56ebe050020905e9257927.nq.gz
│   ├── 911aea6b25d1b9ea289f9e54417c6d4416eb7e57.nq.gz
│   ├── 93d8be967b8ff85f7cb92be4836dc15fe8bd9d03.nq.gz
│   ├── 95fec137b4a27b2d43fa36c7838ffdb91ed8493e.nq.gz
│   ├── a0d2abf83e647361aba0d6e50d78344d7c1c397b.nq.gz
│   ├── a9be9b7459544c2e84c8e65ef65ea49b6012b47f.nq.gz
│   ├── b2ef62c890ba26b1cbd0ac7a70e64b6028b5f842.nq.gz
│   ├── b807f82bd4bbaf786e47fa9df5832c8f8977aee4.nq.gz
│   ├── bef7a631093d91216ce164477e2007f99ce37851.nq.gz
│   ├── c19ee6dfc637cea541607ab6dc5d0fe45a227ca0.nq.gz
│   ├── c50dee3e1d3f5dd24716f9e8079bcd7c4b274229.nq.gz
│   ├── ccba09a9f96effd1d61dc832bd4b15bb3ca196b4.nq.gz
│   ├── d786f1ff57b36ea9d7029842ae75389bbc048864.nq.gz
│   ├── d7f4683d57493bea11fd3f317a7c79cf8b62c33f.nq.gz
│   ├── d8926fb9ee45aa5feb45fcde6e541c6e540b2086.nq.gz
│   ├── db9055e9fa5386f367dbcc2eb1473f20b1e27cf3.nq.gz
│   ├── ddadd22594655b0f3041b6b08c06416809d3900e.nq.gz
│   ├── e273c20462492e2551588c0130db3de180d04692.nq.gz
│   ├── e35c47253fa13966402b7ce1d5b8b680bc957ce5.nq.gz
│   ├── e391e246e861d213dd07a517f04777e264a0c4ce.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7fbd2fa77892270b5bc9222731e00559bd7085c.nq.gz
│   ├── e88f56e4481b199b2d6418f2148742f13c828ec6.nq.gz
│   ├── f2f60ffead2d3cc42492cd54e8b7ddb57a214641.nq.gz
│   ├── f74162722f0704d0c219368b654cd82661022f23.nq.gz
│   ├── f7e5f855508fb2e45eddcbde5d7fb1418d3afd4b.nq.gz
│   └── fb21da5e00db42d882720d28822de361ff312c6a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 53ad214de0aa9534e59bcd5f97d9d723d16cfdb8.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 64 files
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

[klen/pylama](https://github.com/klen/pylama)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
