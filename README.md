# Repolex Knowledge Graph of explosion/weasel

RDF knowledge graph data for [explosion/weasel](https://github.com/explosion/weasel), parsed by [repolex](https://repolex.ai).

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
rlex download explosion/weasel
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0e688d4424632fb70d474759bff3ade4f08e1dfb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0e688d4424632fb70d474759bff3ade4f08e1dfb
│           └── chunk-001.nq.gz
├── blob
│   ├── 066b84b920f2b395081a2ac3f79c341b15db27ff.nq.gz
│   ├── 08aec9479c5459618ed0ba619705cc731efc9eff.nq.gz
│   ├── 0969c965f4831baedbb5537b27ab6cff34bd7352.nq.gz
│   ├── 0d218eadc0ef2fdb943609c7b8b7b149e43d8f4a.nq.gz
│   ├── 119627f892b568cf019a67604384d5d5a0c59b8b.nq.gz
│   ├── 11cf8d8a0590d1b420fb70be757eea777da7bad6.nq.gz
│   ├── 1372225c0f56a4517d43599fb6892ba6180b9510.nq.gz
│   ├── 14a1760194706250a00725f7cda750a513a3b10f.nq.gz
│   ├── 14b83c2126ebb7fbf4a3fc7d3de3559060937509.nq.gz
│   ├── 157d0a681fb85ec4f23ad7c251e7ae9c43579a15.nq.gz
│   ├── 184fe8067c69b10244bb2ec6b8b194feba13594f.nq.gz
│   ├── 1d8d799eebe7fe5221feb6828c7483abccb3f322.nq.gz
│   ├── 3558f3d2ae1a0c07ec1c2fad23692ead0d0b30be.nq.gz
│   ├── 3b0a5b01f4e208ec7b04f08814513cf2c7501da9.nq.gz
│   ├── 3b9de2accff3939d9eb6bfa489ab8036d3459a70.nq.gz
│   ├── 3d19098e702161bdba0d3745848cca6b3d54ebb9.nq.gz
│   ├── 3e0546624581f76177708eb09fc6808a7f22c5b5.nq.gz
│   ├── 401d73ad4e39782afdafaf66a7721932d79964aa.nq.gz
│   ├── 40d04a05a583df6949d1a7449cf219aec744f541.nq.gz
│   ├── 4c263412c028c5f4125d240b02d057473d861356.nq.gz
│   ├── 4d73207f320f3fb514ecb1303429ca9357b02419.nq.gz
│   ├── 515171aa9ac51d029f078ae8e34edd5e8c1af973.nq.gz
│   ├── 552e26fe38bdb5a5f3b485f7b0996d480f398efe.nq.gz
│   ├── 554885022b34ba462a1e26b389dcc890aaff7126.nq.gz
│   ├── 56c1ae299b34658c7e35b74e142ee47fb37e08de.nq.gz
│   ├── 57dbd43113df4fb50eb4cb4101ef6f918ac6d33a.nq.gz
│   ├── 5b01ad8d632ab52d56e990adb3419c2864c11ab6.nq.gz
│   ├── 5f7b01dcbf75e285b5a3570418c5a9c1b3dab470.nq.gz
│   ├── 607ae8c415f0ebf845485b344af26dcd9f07688f.nq.gz
│   ├── 612bf0393ed1eb9260233baba3f4facd53250c07.nq.gz
│   ├── 61fa23d3f6a2ac86c08b57548838ee80e3cbc092.nq.gz
│   ├── 666649062c58f1de23227670e558ad3e73d6b4c6.nq.gz
│   ├── 696cbd432e86adfda1dc8836705a63715dbce4b6.nq.gz
│   ├── 724f2956d46d5af8d20dfcbb4d129c5a73347664.nq.gz
│   ├── 73696173b9a566bea65235d8ff635186f3c37a2a.nq.gz
│   ├── 76829255aa05c01c978a8922f5a79b8db933e9da.nq.gz
│   ├── 7942619a8e283daab859dd15a80a42a5edc13ef0.nq.gz
│   ├── 7b263ccd7f494c369b61e165e3090206e5b5616a.nq.gz
│   ├── 82171c680a3ace61795228ed8a114a62cfaea37b.nq.gz
│   ├── 8561d7a319db2a6c5ccd238288bf2c76177ce0c0.nq.gz
│   ├── 8c9367111f97f1795d96cdf16a239e8ac16848bd.nq.gz
│   ├── 8d887577db0d888df2af15888c06573087413ade.nq.gz
│   ├── 8f617d49fcd435b2179f34c26d5d76b035811c2c.nq.gz
│   ├── 96a019fdf5afdf42402540f2c54ca5ec64983e44.nq.gz
│   ├── 9c132d1794f45e5888f8df9be707070b392a8f0b.nq.gz
│   ├── 9d56b9de7f9e940e264e1015ce33bc3cc2d8429b.nq.gz
│   ├── af22cd06582730599b9b2f97d02ab0d4e861c119.nq.gz
│   ├── b1f131116a72915192623dfbea11aa46173655dc.nq.gz
│   ├── b351b9069d2f349bcc831815d4e842ac24cd7a2d.nq.gz
│   ├── b62857467df8607f5433e70aca65464163685e8b.nq.gz
│   ├── b651abca9c8fd42f7bea654015a17c02b28d830c.nq.gz
│   ├── b80a0b10def6705fc96c137931df0d0fe97a063c.nq.gz
│   ├── bd983e237236a0898b25bcb0c1846ef922949c88.nq.gz
│   ├── be3c49ec1c50274d30b6095d8bc350bc9e31396f.nq.gz
│   ├── bf3e0d77f131ef6416e332b0002e3f59f8478b08.nq.gz
│   ├── c6c468a5df945260ff1e02ca65e4828edfc46fcb.nq.gz
│   ├── c8d0f57cee749e67d73af638d8799e9310872b36.nq.gz
│   ├── ce0aa0a54b3e057cacd5c3dfd1e0f52a57a93b66.nq.gz
│   ├── d3f32b53dbb296dd5e0341d9f2ba98eff7dd3128.nq.gz
│   ├── ddb47cc32d319d4c3286b3a6a51d61569726d4ba.nq.gz
│   ├── e638278aaa3ed17525376dcf52688c174fcb6204.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── edc6b42887acd2c446f3000bc01b1f6c6059f7d2.nq.gz
│   ├── f23ca97ad2e5c1b033eb449917aa5e951e402e9b.nq.gz
│   └── f94b5d8b894cf82f394c94ca87f9810c0b87af41.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0e688d4424632fb70d474759bff3ade4f08e1dfb.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 73 files
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

[explosion/weasel](https://github.com/explosion/weasel)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
