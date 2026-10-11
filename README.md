# Repolex Knowledge Graph of agronholm/python-xmlsec

RDF knowledge graph data for [agronholm/python-xmlsec](https://github.com/agronholm/python-xmlsec), parsed by [repolex](https://repolex.ai).

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
rlex download agronholm/python-xmlsec
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ebbc3f7346582b89e9a5697a6eb35dfe8e3ebdf2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ebbc3f7346582b89e9a5697a6eb35dfe8e3ebdf2
│           └── chunk-001.nq.gz
├── blob
│   ├── 014bfe105fda54a32afd53d18a6199023d283bb9.nq.gz
│   ├── 0a0cd4425adfa81a6d2c4e1db2957a39022efb77.nq.gz
│   ├── 0a5008b411c246964ac0e51da3dc1d317af00cae.nq.gz
│   ├── 0d41abef8092d358057421cbe300ca598804d181.nq.gz
│   ├── 15f479855d757abeeca3c146169de881e18ce81a.nq.gz
│   ├── 176a458f94e0ea5272ce67c36bf30b6be9caf623.nq.gz
│   ├── 1788b4d6f2737c3a8b7a60a7dd168c6a4d9523a2.nq.gz
│   ├── 1b82d22d73a2497996b68d5de67eca5a152ff63b.nq.gz
│   ├── 1f888b99784afd6e41f3af9067eb994b7a25fff9.nq.gz
│   ├── 247f1b18965e4a98484bdf74dbd52cbc8d805b32.nq.gz
│   ├── 275c6e4091d402c79510c3fd0d18c12dd40b9e55.nq.gz
│   ├── 2f2592f2d75be609130c398fb99a9587a8826657.nq.gz
│   ├── 2fc490f35c76af79532953b724614f8f07e56400.nq.gz
│   ├── 303d7f8fcfd16cea3fedfa7177f66818a342e70c.nq.gz
│   ├── 35163e88b580a38381a4044ea03a428434d4d343.nq.gz
│   ├── 35329050d6519c3a2cef6a3ff5a41ffdb4b063c5.nq.gz
│   ├── 37cae7850f2ec7f48836461cc668250e5f60a49d.nq.gz
│   ├── 38f0b25ce1846fbca197e9cfa5369813cc7f77bb.nq.gz
│   ├── 39f8d761732e8537fe5029c09fcbcd01e0f27a60.nq.gz
│   ├── 3bae7e555a68d78f6ad080bb641cec54db0364f7.nq.gz
│   ├── 3c3ea94f23ae3779df76dd7d862c1ed8aa6c6c62.nq.gz
│   ├── 3db185829896b21ed1ddeb9eaff171950e4a376f.nq.gz
│   ├── 3df6b50f42998350babc7b529a498d6a9c652970.nq.gz
│   ├── 3f851bdcf227c18495893572720bc431d7384c2a.nq.gz
│   ├── 426bbaa4fb413cc0259ce00aede79bd68e13d9be.nq.gz
│   ├── 48aef81deb40a1899e7165019b19044f2e7db378.nq.gz
│   ├── 4b3b5c3438dff874bcb0049f6e48a5051b81f0fd.nq.gz
│   ├── 4c79c8ded85e6be2a956194b57e9593269e7fce6.nq.gz
│   ├── 4d8d28be30e46669800cb97cb6b2bb5e7e30616a.nq.gz
│   ├── 519c13a06600a34b8e087945f80a057b7d796b3f.nq.gz
│   ├── 5289d7e967d51d75674cf7d4aa8dcc03d6b8ad01.nq.gz
│   ├── 546f7a10e3e194fbea863ba6a910ffe65de1a174.nq.gz
│   ├── 55d2fd9bedd9a9f72c2b54ca322c09062db5c376.nq.gz
│   ├── 5ff04aae1458585b42f6ed75509943d4352cc5de.nq.gz
│   ├── 60fb3ea1e0ca589681f879c572b374f2acf8047a.nq.gz
│   ├── 61eac1398939a8e59659e62e9bf2aa573350e0ad.nq.gz
│   ├── 675258c5a6f521dae586733a0fdcb869cfc32942.nq.gz
│   ├── 687cd778c098f1eedbaf768adeae2d2753354c2c.nq.gz
│   ├── 6b78694af8d6a34e208036938aa6b9d0a0afd74f.nq.gz
│   ├── 6c47dc9c61a137c67a4daeac1678a9e463178a8f.nq.gz
│   ├── 72050efe2b4b1ecb0089b3ec96371ab8176c871e.nq.gz
│   ├── 73245c3cfc2f5e80278421fb305b2a899427a625.nq.gz
│   ├── 7676fffef21bece9a1ab3d103efdfb80fc6a0e49.nq.gz
│   ├── 775794d856066604a537a94751fe5fd33b9be7c1.nq.gz
│   ├── 808a53c228ad36d76b7e95f2d9fcf8260b62d352.nq.gz
│   ├── 820778ef6b8398abacfe09fa17ec8f8a015eb95f.nq.gz
│   ├── 834b9acb7476e62ddd93a951fb859284a81d836c.nq.gz
│   ├── 838a346d338e3ec0c8ed1ee572e6b6dc7378458c.nq.gz
│   ├── 85410d984e73f00c651e42f49d389600afefb9f4.nq.gz
│   ├── 85551d2adaf4680cf60f28d512b616e483cee253.nq.gz
│   ├── 89ba0cdd01d8c5dfb1abc5be44e1a83231450fd7.nq.gz
│   ├── 8c03f9106d83029734bfc8cd661c90a104513582.nq.gz
│   ├── 8db1ee957881869baab7313fcb82e764c86b93a0.nq.gz
│   ├── 8f960391f6225bce5f4fd2d6d3e31d69e46acdd9.nq.gz
│   ├── 92588ebc52b71270921dbb33eae5c6853f6407ed.nq.gz
│   ├── 93665c842b1ed3fc5c499f0b6a598ad177fcb492.nq.gz
│   ├── 96260b8f32c4ad00f614f9ccc61a23fe45fadd31.nq.gz
│   ├── 98f63b6f02c1b0557becd509f0ac3dee2a6ed2c2.nq.gz
│   ├── 9b6324b75f485dc84e81aedbeef4a77c2a7a63e7.nq.gz
│   ├── 9cfc8cc6a482a518c4a4f0c087a87241a98eec33.nq.gz
│   ├── 9e6ca5408aa394d818f560db2498842a1c7822c9.nq.gz
│   ├── 9ed8f1e2038b56ae620e395d8e4729fe64efe7f5.nq.gz
│   ├── 9f96e4474176286fe8decde127896fc2986fac68.nq.gz
│   ├── a056304c9f4d4587c86671d8c3892f64ed131712.nq.gz
│   ├── a250ccbcd6287715185e13f9118bd273186b8634.nq.gz
│   ├── a2695635c7fc02da2575a377bbb9df76c1580d5c.nq.gz
│   ├── a44776b34c11070b4d557c60e5d608430728c5e9.nq.gz
│   ├── a5199fc825805924a8a93ea304f360b540fe239b.nq.gz
│   ├── a6176551ba13add132b81d82e682f43aa148dbd6.nq.gz
│   ├── a9a5e716b8662a425bac9fb30c99d1fcd78e2356.nq.gz
│   ├── ab0b1a6c0070ba3446398e7fd43bf5c109773cb6.nq.gz
│   ├── ac0e44eeb85892329cdd8a8f0cbc66f2a471724b.nq.gz
│   ├── accd29ae67b9c1d325f0d2bd09486892cba58c76.nq.gz
│   ├── ae0eca340109a7ea5fad68b97768311f90e213a1.nq.gz
│   ├── b5782d6cc6df94116ce6290f15b4b3d35ccffd37.nq.gz
│   ├── b5f9bb9548fdc7109b86115f26665ba56b7b7b5b.nq.gz
│   ├── b6240dd03f365c4900be088ea1b1ae312dfe4703.nq.gz
│   ├── b6364f293e30b6ae6279bb18d07420f9e3d495ea.nq.gz
│   ├── b7bf15c34ed8caf7b42a4488e861b415cedbc92f.nq.gz
│   ├── bd1fa5e099861d1f2a66c88f424076181d32f349.nq.gz
│   ├── bdd1014e2387d1195d97b1b435aa4a7089512830.nq.gz
│   ├── c090b4e82d4e1fce87a1f91cc2b49a369096067b.nq.gz
│   ├── c2bc94bfaacd9fdab31bddd51e79cfd9fdeab0cc.nq.gz
│   ├── c98e933b08b263323ed8ed8bbea334c0eb2464b3.nq.gz
│   ├── cdcb182b271020c7d5a545317eea4ae19bbe9ec8.nq.gz
│   ├── ce0258194de9371061fecf7fb490dafb45687b25.nq.gz
│   ├── d0b4bdf96f8e6d240c5e222555e09f229d039c80.nq.gz
│   ├── d142f3bd94d4ddb65e294c0eb9c954d61fd93983.nq.gz
│   ├── d49fc3aeac95253eb09d5ce066d2ed1c18852d58.nq.gz
│   ├── d8996fd6fa7668a4a1799d9077568a8e9ec4bb1d.nq.gz
│   ├── e08f47d997ab61fa1fb91117b8e190dd87a3af90.nq.gz
│   ├── e107756f9e29d5153d7cdd04351b6febd614a172.nq.gz
│   ├── e108afc70a1842106861c0c2836ff48f843c6747.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e70d6509f05014f961a29bff677a802c31498294.nq.gz
│   ├── e8a68228782b3716699afc77edfb289a824d70f6.nq.gz
│   ├── e987cdcea630665c795442c61bf64a6389c36deb.nq.gz
│   ├── eb5434025f2fb0a8344883161289273258409986.nq.gz
│   ├── f359b13834bd9668d4fecf8b756cd3633ff0fd16.nq.gz
│   ├── f46ac1f42c4a190b81b344f5c5a59133949546e3.nq.gz
│   ├── f79d19f0c339febe77034cbfd1153e651b192810.nq.gz
│   └── f8523bc502b85abb90ed548a6d180b31bbfd37f4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ebbc3f7346582b89e9a5697a6eb35dfe8e3ebdf2.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 108 files
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

[agronholm/python-xmlsec](https://github.com/agronholm/python-xmlsec)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
