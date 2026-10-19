# Repolex Knowledge Graph of hukkin/mdformat

RDF knowledge graph data for [hukkin/mdformat](https://github.com/hukkin/mdformat), parsed by [repolex](https://repolex.ai).

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
rlex download hukkin/mdformat
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 56b24ef0c6cfdab501844925971204f858185547
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 56b24ef0c6cfdab501844925971204f858185547
│           └── chunk-001.nq.gz
├── blob
│   ├── 001c1d75775416fc2cba05f800fda7eaa4a9c29e.nq.gz
│   ├── 011cde1a00d640fd930ee498e9940b2aca353a40.nq.gz
│   ├── 01b9f8dd57f5718001fe2ff3013c9822899a1400.nq.gz
│   ├── 01f3ab37cbaa4706cbacddd9e31da4a7c06f0d01.nq.gz
│   ├── 023e674c517a0e7e5859c75d75a267599a9bc345.nq.gz
│   ├── 04e69bcae7134c1d7f740a7c13f4a78ffe44dedc.nq.gz
│   ├── 09781c3ee9cbd7bfdd6cd8d0e02f1fb728ab589a.nq.gz
│   ├── 0faac615286f88261e287d17cac49b9e1e678432.nq.gz
│   ├── 15658ac9fe9a4554b13dc4de94bf7afdeb8127f5.nq.gz
│   ├── 18bffe10c25d3a22f65028cb051da12bac8186fb.nq.gz
│   ├── 1a0d7f9bc38ec315ce29b9be6487ac169ff2a899.nq.gz
│   ├── 209c4bc2b0f8187b1cc879da3d720107d8375d5a.nq.gz
│   ├── 23212e81ae8592ff7e73f5425c79857f8b648789.nq.gz
│   ├── 234725283add0ca3a8136523162f774fb3ee3796.nq.gz
│   ├── 23771d1b0f04b7f2e1911c0afb95049346cb2847.nq.gz
│   ├── 238dd07d471ac57b9bc70b31f56913aa0f01e5d7.nq.gz
│   ├── 28c362233622cba0d41110052df182490ac9f434.nq.gz
│   ├── 31bd13ade5e72aed2a94c8ab6204b18f78adb867.nq.gz
│   ├── 332fb98781c53cd7305fedbca1900fe2dbafbc43.nq.gz
│   ├── 333201fa0abaf1eab68ac13a31c2d49d7ca7b5a3.nq.gz
│   ├── 34586bc8ed461d628198f1d2e7b156e8044d2fb9.nq.gz
│   ├── 380906e7f08341b7fedc904085970321b16f4461.nq.gz
│   ├── 390ec903cb262b9a4282b2815da92131dadbd2c0.nq.gz
│   ├── 44a5dfd4e75f94aa55b0f39abd83e7b808e82b8a.nq.gz
│   ├── 466fd9e5e309da752136a89f016df9fe89b901b3.nq.gz
│   ├── 4808b64a9a82972363986bd4ad0cd34f972ae322.nq.gz
│   ├── 508f19e9b8b87f3199c660c5ac55220e0293f480.nq.gz
│   ├── 51527727457ee0965794193ae500ba2e51df0b9f.nq.gz
│   ├── 523367383ce02e84fb5758af840c0429c6c09dc8.nq.gz
│   ├── 524976fb8c0b79d37bcc16eb90854edfb8b5463a.nq.gz
│   ├── 5c2a86a8ab865d57fa1407909b9de58097070881.nq.gz
│   ├── 62c8dcdba82910d310033bf6063b5079778850a0.nq.gz
│   ├── 645ab2a5431c1fbb105d36f04674cee62af9cd26.nq.gz
│   ├── 682b7896c04aeb9ff76d43f112e525a2a3060588.nq.gz
│   ├── 6ad0367af33c3f06b0ec21fb2e4fcde738ed47e5.nq.gz
│   ├── 73177d7ab8e6c5327375ea5dbfaae136a2a4ae5d.nq.gz
│   ├── 7632ecf77545c5e5501cb3fc5719df0761104ca2.nq.gz
│   ├── 7f1d4538a0413b5d1a5d0950140ee377d40fb593.nq.gz
│   ├── 8200eec48c0e765da99c30b00525ca5558d544b3.nq.gz
│   ├── 94f9385c8770ad52e487b99737c34c1b1521aeb5.nq.gz
│   ├── 978beb9d3df2cad2004b513e6e1f1631e9b5b862.nq.gz
│   ├── 99c748d123edaae835d5516c3d4e040a5e79a7eb.nq.gz
│   ├── 9bb366f31c6d45f2da8895e264af3ac7e5f2761d.nq.gz
│   ├── a01a9fc28e0b3f0f649534b365027fcc3305a253.nq.gz
│   ├── a037d3affaff064a198c9a4b6a19e9116047f57e.nq.gz
│   ├── a22517e5b8da0cc4aedcf3a1bbfce4be7f97235f.nq.gz
│   ├── a7eb724660a691a726222ce12d223f221c76503f.nq.gz
│   ├── ac2875d27687c18fd78f1681475418c9ce712955.nq.gz
│   ├── b400c7bd541515825f3fb8ee2d643669139adfe9.nq.gz
│   ├── b487ed2bed698c4f0a2c3a994b0e53a2d85951aa.nq.gz
│   ├── c335c378a90bde1b429ec8671d868f1b658b7c10.nq.gz
│   ├── c4bdef0f7c9c4a8b1e81a0617db15406bdffe3e7.nq.gz
│   ├── c797a14a9f21cb1256ae7a93db15214ceca3ab24.nq.gz
│   ├── cbd2698ff0e7bc62c30be5000d8402385142ea52.nq.gz
│   ├── d36e41fe868e1f57ef674d881fe656da1d582ddc.nq.gz
│   ├── d50a798d27667fc31ad66f550ef0527f73c45427.nq.gz
│   ├── db6d5faa2d8400d8dc73cc706bc0a10840d0c6dc.nq.gz
│   ├── e4db36bebbc44c0fed0d136eb268f177d757c599.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e859590f886cd78344206af1a8ccb3080d4385e0.nq.gz
│   ├── ec16eea8e5a19582c5beeb0dc3e60ba72b653d19.nq.gz
│   ├── ec1a89e57bb83bf0175ded889ec69e7e79eac63d.nq.gz
│   ├── eceede9f9ce0ddfd565017729705e403eec8bdfe.nq.gz
│   └── f647e9bae849382df1e94c11215ee45642f2bf8e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 56b24ef0c6cfdab501844925971204f858185547.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 72 files
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

[hukkin/mdformat](https://github.com/hukkin/mdformat)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
