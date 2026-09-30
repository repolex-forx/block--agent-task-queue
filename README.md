# Repolex Knowledge Graph of block/agent-task-queue

RDF knowledge graph data for [block/agent-task-queue](https://github.com/block/agent-task-queue), parsed by [repolex](https://repolex.ai).

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
rlex download block/agent-task-queue
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 48d16da41f57801bbf9462ed2df923713978b6ae
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 48d16da41f57801bbf9462ed2df923713978b6ae.nq.gz
│   └── repolex
│       └── 48d16da41f57801bbf9462ed2df923713978b6ae
│           └── chunk-001.nq.gz
├── blob
│   ├── 063cb806955bec5548f72661132066aa2dfc4b58.nq.gz
│   ├── 0b2ecf8822c80684eda54c3019da439036e7d568.nq.gz
│   ├── 0ba9db25329d0b336e39ca8cde8470c5b7bc45eb.nq.gz
│   ├── 14e14e8e4a844a7511fa062b6ad3464ef8438ae7.nq.gz
│   ├── 1590c91c9da6202113c2831bb66c4df3dea1a3a6.nq.gz
│   ├── 191a36c59a53539fbd737f67ba9d330e757a4c8a.nq.gz
│   ├── 1bc469e68eb776aa52185c6cbfc5cdcaee837ce3.nq.gz
│   ├── 1c6ff572678a0ab30d8b7f27acea043c12ba76ec.nq.gz
│   ├── 1dd2da08da3baae1861b988fb347190f860cbca7.nq.gz
│   ├── 29395514268583b2d1383e309c03d0d4190d4582.nq.gz
│   ├── 381fa3bbb428310e3b25ff93e3a83b1ef61bcbc7.nq.gz
│   ├── 3d77818debd7608b3fef00188608f58285f394e0.nq.gz
│   ├── 3f9136916cfa351ce82e223234b752bbdbe6bc5c.nq.gz
│   ├── 405f0342e7aaa25f00e7055fdab5e2d2ded24d4e.nq.gz
│   ├── 425b1f405f8c77bcb7649f75b64b62168eb31d74.nq.gz
│   ├── 43433fd21aa7fdd0c1427c6b740761bb71a070dc.nq.gz
│   ├── 4b4a9a8e6a7f91b2a346511643dcf6e1174e5534.nq.gz
│   ├── 511585c7380d8c83413a159df9f9051454b8f1fb.nq.gz
│   ├── 5c62ab6de4a8fcf48d1d790e135addb9735d5981.nq.gz
│   ├── 5d19f7b7acf55bfb7dcd9b80eda5531ecc237fd6.nq.gz
│   ├── 5e76faa7735725b657001035d058fe538b02d251.nq.gz
│   ├── 61285a659d17295f1de7c53e24fdf13ad755c379.nq.gz
│   ├── 6487c40421a8278d8ab8659e14705695fa8fb828.nq.gz
│   ├── 65867117bf61891883c55d2743031c7c10c56077.nq.gz
│   ├── 66173aec46f4872ef3626ad8b9abd0a177334f34.nq.gz
│   ├── 690c639f47972c1539cdc5dd2821f1af3543d635.nq.gz
│   ├── 6ab82d4ea695c5099ac633aba753d956563bf629.nq.gz
│   ├── 6bccf43368fd7c96d9c659562a5142b8b8cb98a1.nq.gz
│   ├── 6c27ec7af1c1c921ecacbbf078bcc35c9ec68bc3.nq.gz
│   ├── 72ab37cb69e337d78663783083becc8d8e49ae94.nq.gz
│   ├── 7473f69cdab97c7057d159eec958c6998ad9c270.nq.gz
│   ├── 7645e6189fdc5b34703907f4585030b4a319b393.nq.gz
│   ├── 7a7a3ef6fc1ce0ed142ea220cce1c985faad1b73.nq.gz
│   ├── 7b095145aef392420fa224e040b56172a2980896.nq.gz
│   ├── 7bcdf786eee2a7eafd362e60f2c1190f4edfdfc8.nq.gz
│   ├── 7c410b19acb2b296e9a46de6bb75cc9991181f01.nq.gz
│   ├── 7d52e7e69c239b4eefa3db688674786513699e5e.nq.gz
│   ├── 7ef121b49a78e3d2abb35f5051946709cce91260.nq.gz
│   ├── 8a78ccfb07d378c5bceb4b2d02055717f21ba8ff.nq.gz
│   ├── 8b4794a20d4a3b5a14bd92277e342e41dcb48ffc.nq.gz
│   ├── 909ba5d6f6fc6a6b056e7e47c57d54b521e2f2f1.nq.gz
│   ├── 95632623fb056af3681af75eeff66880ad0eb7d5.nq.gz
│   ├── 9582fc588754f78d9875691a3bd5e674295436b3.nq.gz
│   ├── 98f49cf51aefdf9dd145ad667894b4e605804b41.nq.gz
│   ├── 9d60888a0c6dca681be36dfe814aa4591c962636.nq.gz
│   ├── a0b744b2f1b22e444385598e2690bcb8d61829ce.nq.gz
│   ├── a21039540db80919e7a2afcaf11fe7679bb45a60.nq.gz
│   ├── ab3c8146d98758318c4fcb846a8af52da54f7b77.nq.gz
│   ├── adff685a0348c64b2b64f0b302f1f82b28eeaaea.nq.gz
│   ├── b2ecba326c942689d1c743f987fe3c3e0b5d3b25.nq.gz
│   ├── bf152571a0791ced4d7e658659946dfe9048cde4.nq.gz
│   ├── bf9c9b5cba2048bca4c91036a4b00d2b1e73c4b1.nq.gz
│   ├── bfb6aee39b1be93e5117e07cde6e8da60545cc03.nq.gz
│   ├── c02426b7227013f1c9554444f7ed2ec605148f42.nq.gz
│   ├── c04f20309fbe2ca05247f1bd4a31ad0a725417d7.nq.gz
│   ├── c294691c9a8c021696eb7679a53c9371eba19e93.nq.gz
│   ├── c46d4aab0cf0c452a0f72a338b059190ff6e4061.nq.gz
│   ├── c61a118f7ddb21223f1a2fdd05f6aec1b9863aec.nq.gz
│   ├── cc2c1caa0ef61cf4c40fa7cbb768be3c7c1824da.nq.gz
│   ├── d358bcefdc3ad40ddc6b360c821fea2a699f5568.nq.gz
│   ├── d3e6be8f81a42aa2567c3c860165a6856915f27d.nq.gz
│   ├── d73a9196d4dbeb31fdfa5eaf3c6ef6714a0f292c.nq.gz
│   ├── d7b8389989205925c45c6541fa015f1699b91a2c.nq.gz
│   ├── e509b2dd8fe5579a5954a2c28633ad914cd1c225.nq.gz
│   ├── e83221e27e3e6c8dbcfe41de56919a8b79963e9f.nq.gz
│   ├── e8e6a138b7dd4b84bfa9bc942597bfe39e88e8be.nq.gz
│   ├── ee1392516c7d679266bb813bbe992e7de800fdbd.nq.gz
│   ├── f86c84d7544cef5be782889f8519db339a45cc56.nq.gz
│   ├── f89db6e0aed10bfe56e4218384d809f2761d2793.nq.gz
│   ├── f9d5f58d3d1d1d3a3f1912a8e6c8ff21e4322084.nq.gz
│   ├── fbfd235d8e5d118e167ad6bb85dd4fe1064049dd.nq.gz
│   └── ffe73d50aedf88882f055a22460a1f8d9e944379.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 48d16da41f57801bbf9462ed2df923713978b6ae.nq.gz
├── filetree
│   └── 48d16da41f57801bbf9462ed2df923713978b6ae.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 82 files
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

[block/agent-task-queue](https://github.com/block/agent-task-queue)

---
*Parsed on 2026-09-30 by [repolex](https://repolex.ai)*
