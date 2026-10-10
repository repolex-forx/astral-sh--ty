# Repolex Knowledge Graph of astral-sh/ty

RDF knowledge graph data for [astral-sh/ty](https://github.com/astral-sh/ty), parsed by [repolex](https://repolex.ai).

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
rlex download astral-sh/ty
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d5da069f4973382a75882de35f57b0ffd9386420
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d5da069f4973382a75882de35f57b0ffd9386420
│           └── chunk-001.nq.gz
├── blob
│   ├── 014835144877ea9c926d027ece3e1a26290cf481.nq.gz
│   ├── 0159744e8ba8315cefdef5a3cbbce09515b48676.nq.gz
│   ├── 0596a5811cf694679b9d70eb87bc612cf057eee7.nq.gz
│   ├── 0819b1e80e6166edd9ed187e6abcd04bb4802ac9.nq.gz
│   ├── 0b009f37f40de0b2402f60041cabe66e45c27124.nq.gz
│   ├── 10a6fe21418d3ebb1e1f91605360638c1f3ffdce.nq.gz
│   ├── 11691e40db6f2fb170e95192de5f2a03cdf1dd2f.nq.gz
│   ├── 1223b95ff790ef6fb14cb357d84b152b528b1b81.nq.gz
│   ├── 1a87c88077c4b8e957d81843a4325bd2a7e4b788.nq.gz
│   ├── 1edb1fd7f41b0daac41f1b56b280de2242e74a7e.nq.gz
│   ├── 1febb9f87852428471ec13a4cdb408996116bf21.nq.gz
│   ├── 221f2c0233708b49b068c8fe9b4a557577a99e06.nq.gz
│   ├── 2291af0d59bc447b293fbd1bec1f186e5662595b.nq.gz
│   ├── 22d2d020b64e440b89ae6c810afdaf020d75e12c.nq.gz
│   ├── 24ee5b1be9961e38a503c8e764b7385dbb6ba124.nq.gz
│   ├── 258e6f5866faff2af1ec2d1d7f74a4cc2836f749.nq.gz
│   ├── 28490d5bcae4081185a9abc49390ba3bc2c9a1f2.nq.gz
│   ├── 28874e9be311e38da7cad7fec2e42c2c8d67d9d2.nq.gz
│   ├── 2a31a219d1cfde0b3ca1cf7c8f009a70de6477cc.nq.gz
│   ├── 2a9e609decd0e79b53b72a969ea9d6eb32e23cba.nq.gz
│   ├── 2b79928ba448673d0d1d26cf6ca2ecdbde2d4224.nq.gz
│   ├── 2da75b736984e79d696db58c1fad3fe9edf83665.nq.gz
│   ├── 304bb9d3743cdd97ead6baaca3a8fd9fa271ebf0.nq.gz
│   ├── 33efe6c172f84d0e22c4443983360f9022e0f318.nq.gz
│   ├── 34de9f8ffd70966de8cfce00791a106fb89b0342.nq.gz
│   ├── 35fa4001676dd846749df89545a550969afd14af.nq.gz
│   ├── 3a899dea22ab0b6f4aef3de7ad968cb74e31e102.nq.gz
│   ├── 3ffb6434dd5bfc123f5fc7e11f669313e1646ab3.nq.gz
│   ├── 4181ca245ae3496e81b48a9559a677e14341a4a3.nq.gz
│   ├── 4266763b9ad5635c75cd9e87bd7d4e048da0f350.nq.gz
│   ├── 4865c33a5566c41f5654f6d90cde0b99740c9739.nq.gz
│   ├── 4b20727cd3b38ef011b9f779a706d977089c487a.nq.gz
│   ├── 505a3b1ca2716907d5b292ab90c36df043c42bb6.nq.gz
│   ├── 524db2ad8afb8a5e3292cbf42d8492e1146171bc.nq.gz
│   ├── 5b5dd361cf2c6ee7d67d80556000c3b39549f80c.nq.gz
│   ├── 5bf29adf1debf130b531de01511cce803a3d717c.nq.gz
│   ├── 5f1b9ec48e0fe174960389e65eeb171cc39112de.nq.gz
│   ├── 610706c3fed5bc83ebb48c1962cc9fa2b4018b18.nq.gz
│   ├── 665f1772b5a5a75f34abe2f019e2707fe9256fcc.nq.gz
│   ├── 6ad2cb82ec186d14112b850a409228a9daf66f67.nq.gz
│   ├── 71f73b1cf751a3d4a8cef5625e3949f5eb2a2499.nq.gz
│   ├── 724c0b11ab1790267016f13cc3631d6386e1158f.nq.gz
│   ├── 73dd66a085c798d1c888031387fdba57840fa01d.nq.gz
│   ├── 76354d471172194fed72d3029533f580a2c8bf53.nq.gz
│   ├── 76d0b32c92e03313ba6e347dad425adc15c4eefd.nq.gz
│   ├── 7af8f6c7319afe5f525f51a229f1bcb8ac9e6362.nq.gz
│   ├── 7f183ffad0e25c538f4de375533f486f195cf0bf.nq.gz
│   ├── 84fd6e0dcae2b7ae8246623615a122461f060707.nq.gz
│   ├── 8725e0389e20f2d6eddf237c91b50ef63f045ecd.nq.gz
│   ├── 883af8f3a1b691eab4f97d03a26e500e370c7e24.nq.gz
│   ├── 8953e98d58db523cbbaf9e94408a5720cf7c48bd.nq.gz
│   ├── 8a3c03f3021b4850f903af1edac0877d78628248.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8b6a8c8e33268a9ef64184663336c6d443c2e154.nq.gz
│   ├── 8b6e40b5002eb8653df9b664950e579e2aedf53c.nq.gz
│   ├── 91b8d45c454e303ca4b82fcb491c42c40c70743f.nq.gz
│   ├── 999db89499c8b9efe7d750fe44d80a46a4d95e61.nq.gz
│   ├── 99e91a0490c645d6fc3bb85d6f24dfef275f2cf1.nq.gz
│   ├── 9a0b1f9d1391885fc92261078d041dc1f0528447.nq.gz
│   ├── 9ac94d020e3ca048943e98714fa8c63acfde9602.nq.gz
│   ├── 9fb055a07293103a40070cf6500649c84a97a49c.nq.gz
│   ├── a0c256db705094337756bcbd1abd8cb003996bba.nq.gz
│   ├── a2f52b14864deb0a9d5945756c34c37c84e86212.nq.gz
│   ├── a361d0ab68947818de2bad7b75cb0cbe091dcce7.nq.gz
│   ├── a5e899ff0a051d70b488e17649105816ae6a6e97.nq.gz
│   ├── a8ade0bd19b226bd0c4b4f01ef51e5a678774ae0.nq.gz
│   ├── ac9a0b09776b84e515a40e91fab9fc69edf6afca.nq.gz
│   ├── b26a50bbb17e464791ca49eaef0d01e304530c63.nq.gz
│   ├── b6cff89e61d4d3bd3d8fbfd302f49a3e3a9dc211.nq.gz
│   ├── b6e730d82ce5ea3a449a9e7f17aad1f9f236b449.nq.gz
│   ├── b72dca079296097731266e53fa9b497160ab159c.nq.gz
│   ├── baaaf9b334cfe6e505ac51621d32fe7658af15f9.nq.gz
│   ├── bcdcef86133efb6358d41032633cbbed0faded16.nq.gz
│   ├── be092de99908a46ea1f611729c4ed8c3dd59ebd5.nq.gz
│   ├── c1fb1a215115cedac30e36611816a1153cb4af6f.nq.gz
│   ├── c6ee524e9c42fb7295858cd208b7208fdefa7789.nq.gz
│   ├── c8306663a3c592fe64f4d2b735029befbf6fc000.nq.gz
│   ├── c8e5603d47069e329033b616594d3262bc72673f.nq.gz
│   ├── cb6e5a548ed65b986276d7fba1936dcf9e246b23.nq.gz
│   ├── d2ec9b69cb70e5392585a201f98f5482468d053f.nq.gz
│   ├── d40cbeb9fb43fa88ce532deb164c7c8874efdfc8.nq.gz
│   ├── db2e6d9c68018a3206434c6fc5c84dc9dc9224e7.nq.gz
│   ├── dbc45beb782d00f4147f8ae32267ca19c471ba16.nq.gz
│   ├── df24a24b0e8a8e3fd39869a11cbc0d938067d797.nq.gz
│   ├── e64ad447dedd2295242c1b65f274b9d7431f0209.nq.gz
│   ├── e6e3a9c0548d5eebc5b8b479f8c389513402ff0b.nq.gz
│   ├── e7074fa451041e7a47bf48794d597bb53fd038a0.nq.gz
│   ├── ebe1a3be5c882e373169f5893e00b558c15aad69.nq.gz
│   ├── ed50642d333e0d5b401a646e0f450cb6c27690dd.nq.gz
│   ├── ed5923bba0f8229f0742691aa4da6d0ac06ee448.nq.gz
│   ├── f09baadd0cd6df3b76fa7606a78e1190f1b53c7a.nq.gz
│   ├── f10527081fc58ad8741a68d5274b1db0d458373e.nq.gz
│   ├── f1858408dc4334b03b8fa8c560fb898b461dbd46.nq.gz
│   ├── f3d17d83f75de82182ced68bd089a677085ed660.nq.gz
│   ├── f6e02c6b5a8a241fc2eda94f230fbb6692dff1b8.nq.gz
│   ├── fafbf70cae0f754044b02d45242cd8140106d915.nq.gz
│   ├── fc6649a31a40926fb9fe2aa16b512a319c768b6c.nq.gz
│   └── ff3388818875f7a7eacb26c49ae1d33e402596eb.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d5da069f4973382a75882de35f57b0ffd9386420.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 106 files
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

[astral-sh/ty](https://github.com/astral-sh/ty)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
