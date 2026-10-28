# Repolex Knowledge Graph of databrickslabs/databricks-sync

RDF knowledge graph data for [databrickslabs/databricks-sync](https://github.com/databrickslabs/databricks-sync), parsed by [repolex](https://repolex.ai).

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
rlex download databrickslabs/databricks-sync
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 25405c7b771987d2a67527086d75108f71cf0a06
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 25405c7b771987d2a67527086d75108f71cf0a06
│           └── chunk-001.nq.gz
├── blob
│   ├── 01a477a50e66a173708bfb15f05b88952fe5a5e5.nq.gz
│   ├── 01c16803d3b94d5aa767f074635444b3f32ec2d7.nq.gz
│   ├── 025d572e0429e9a503c3938c1d711672ec0e4264.nq.gz
│   ├── 02988f96e30939c964f810ffbe0d5ead4d3482d8.nq.gz
│   ├── 03843e3c23a8b8ad51cd27b4a09b59dce204026a.nq.gz
│   ├── 038d49e56417b0382bdb9bf0edfb44679dfb6c65.nq.gz
│   ├── 03a3cce8458e3077413a585b0efa250c6d90f884.nq.gz
│   ├── 055661163cf5cd1f2da7350dec8c593cb6bf5653.nq.gz
│   ├── 0908a152774cdf66b2e652ada4697f2f6b951340.nq.gz
│   ├── 0bb5e38959a55942b9809c3a220d390ba6f20d65.nq.gz
│   ├── 0c08db37c7003d097eea6b354c83368a006c6c6d.nq.gz
│   ├── 0d842fcdd13502a228c9336aa0a7e2bb8ff5f96d.nq.gz
│   ├── 0d9884df773fafce91ee10461e5d138f1c513983.nq.gz
│   ├── 105d5ce75e3c02730357b934ff2048f455ad0ece.nq.gz
│   ├── 10e140368b01dbbbb2d84c19e4a4391e58ccbaf0.nq.gz
│   ├── 113e8def9808d7d853e93ce5d0fa1b046d03bbd5.nq.gz
│   ├── 11e4e23a80ea76b085f312bf0f9cf3fee7b3512b.nq.gz
│   ├── 1219a4e566c6394da40a2258125bd59d3b59f318.nq.gz
│   ├── 1393d4f2ae4bcc677fff04d4596f117e2f416c10.nq.gz
│   ├── 14fddf6bcd134a53f89e4f36e441d7c95ff4f2b3.nq.gz
│   ├── 1b0f2678fa714520a713793ebd3a9b9b16887bb9.nq.gz
│   ├── 1bae961c055857225d696261b741b426145af9ae.nq.gz
│   ├── 1d4e7a898079945009487ffc72b7bc6c0d7e608e.nq.gz
│   ├── 23995ab2a1de74f6db82c0517bc929b788d2a728.nq.gz
│   ├── 2751208c5aed08569b4db2959936fcf8f150ccd4.nq.gz
│   ├── 29963a11507d1041a53c60d22c084ff298b4aab5.nq.gz
│   ├── 2bd385ff809ddf14a036509f883d175b5e7702cd.nq.gz
│   ├── 30595b1bd4cde8be45a0aa748238090a3df63662.nq.gz
│   ├── 33eca2d29a993359e940376d6c13c5c8ed2a5ddd.nq.gz
│   ├── 37c28e0a160df34c1bbcb3025fec1e343d5c44ca.nq.gz
│   ├── 3e78c14a74dd5a35248905f10cb9514aa4ca8ced.nq.gz
│   ├── 3ec0224c225324ffe25fda0d1c05355d5a29108a.nq.gz
│   ├── 422458ac4989edb3397820f82de4aaf476483320.nq.gz
│   ├── 43ac083909687a9b99b2b57b2eeebcc3974cb538.nq.gz
│   ├── 43fccc5edd7a24469b1e271d122dd3e1699fccce.nq.gz
│   ├── 446a174376aa2bd95cfa35dcbbbbb181f82d194b.nq.gz
│   ├── 46100a5f15bb2ed6ec922b9ced3ed611c007a397.nq.gz
│   ├── 4627ceb26132279ec08a52c8dda15afe27fb3ca5.nq.gz
│   ├── 466b1dd08f99b549819978f7a6f340d6590d8fd3.nq.gz
│   ├── 4876bc08294a9e59d5a076c0002bd10729d6e052.nq.gz
│   ├── 4bcea884aab666251062353cb87390cc5d5ed307.nq.gz
│   ├── 4c83d91915bc69e5eb245420263185daf1d3e20b.nq.gz
│   ├── 4d3c1e85970cab72592122f4710f170c2e815072.nq.gz
│   ├── 523b148a7adbd0dda37e5fd91291986d451593fa.nq.gz
│   ├── 52c28519ec506b209daf6eb7df04c1fa7eb36830.nq.gz
│   ├── 52f7eab72e0521670648c662950b328791c83319.nq.gz
│   ├── 5bbcbfea1226df4e763d4361336f75d942bc476d.nq.gz
│   ├── 5dcd3ca4bd3f9cfa62ae4a6444309ec834331a68.nq.gz
│   ├── 61a5d50117d110a895ca64d0f4f6446f1159cfc5.nq.gz
│   ├── 653326a1f58caa7049bf61e2c19bce721d0858c2.nq.gz
│   ├── 669aa74d7e06290cd354cc83c64da33f45e115ea.nq.gz
│   ├── 6ecc4a8fb92d661f2b77d1ccaaed3fed3274fc1d.nq.gz
│   ├── 6ef5998e3beeb5713c476cd74eaeb8da1dc83ff8.nq.gz
│   ├── 7078c16be949fd7b09b5d7f9f3939d5d4f652299.nq.gz
│   ├── 71f22f212882ce8196dab87d75c8b7a77d03a3af.nq.gz
│   ├── 73949fd569d437b13808ab0fc2b0a3b072c9af8d.nq.gz
│   ├── 7993028a8aec6cb9081e084331ede3a9cc14181d.nq.gz
│   ├── 7af9ca7a1e8ee83c8be95a98aa60ba621a7976c7.nq.gz
│   ├── 7cba21d0a274138b156c600d8ac5846767599da7.nq.gz
│   ├── 80964ef3ca4089adf7954dae2bdeab467fbb5d80.nq.gz
│   ├── 822178a29dc17905c685201fb9760c849980cee9.nq.gz
│   ├── 83317a2916b05489a8163dc4cb0d6cf26c0f4223.nq.gz
│   ├── 8bd852e8b281381544f954e1085a6ecfd21d83bf.nq.gz
│   ├── 8d35073888275e8e12eb7de37bf4214779e25f71.nq.gz
│   ├── 91d97b1ea54661b97e50f15486889646f21f80c4.nq.gz
│   ├── 92016bf92d81d4ec887407b73cf8005f03c11848.nq.gz
│   ├── 9227817dcff0732d942678701a58332f2195db22.nq.gz
│   ├── 93ea1073e14ae0dba591e3a118891e3c65fc43ab.nq.gz
│   ├── 95a806b2f6851d5cdef72964893b45b4a99d4fc4.nq.gz
│   ├── 95d1316655d4eae302c46f1475dccbfd6c361a30.nq.gz
│   ├── 95ecfbe2eb1a34a30e16e780e108ad3c0cc787c4.nq.gz
│   ├── 97c92adeb6f0a60612927dff6906c50fd575da72.nq.gz
│   ├── 9a913c2e4f0bb10eb9d6eebc5fa3d4283aca3b79.nq.gz
│   ├── 9ce5e16cce011d91199d31876ea749f9986075b8.nq.gz
│   ├── 9d4aa2286e71661d79fd3e9e1b936fee0021b3c4.nq.gz
│   ├── 9dde69e07fc197e8ba2bfc0eb971935f93304065.nq.gz
│   ├── a00bb62bda2a3acfb5b596b9bc77a4e09b59ee81.nq.gz
│   ├── a044a05d2d82f1499726a41b1763d923a452fb05.nq.gz
│   ├── a2c8f3fd6da555f0bb12e2f0953bb49feab537d0.nq.gz
│   ├── aad1cdc5a8c50db878e4b5fab1710bcba3bd15d4.nq.gz
│   ├── aed133e3804a45bfbc6c118a8cdd5140430c82c2.nq.gz
│   ├── af93957af37f973d77ea9d459b8dcf6d733aa2ac.nq.gz
│   ├── b3390f93f2aa5312c313bedbb5bc9c176738b260.nq.gz
│   ├── b3e9aaf97d9f391dcfc8aeb017143e7c4457d382.nq.gz
│   ├── c1dc9c70b45cf2368208a9191f78712131f9a1f5.nq.gz
│   ├── c37119f92eb9b825291480e6239be6250b0aa41f.nq.gz
│   ├── c438ee12da2f59fbc0f091a5599e5702c9e5aa80.nq.gz
│   ├── c478db27424282d8429ecc153be4b9c9c40379ae.nq.gz
│   ├── c69afa1eae4b7e17378bce6bd9b2346ac45f6e72.nq.gz
│   ├── c6dabd3783b3e56b222623b81b62d8802413e889.nq.gz
│   ├── c90a718582a92c4f9daee799ece69470db3cb342.nq.gz
│   ├── c9c0e5f8ad1a460b9660cd8124c4bfd429923322.nq.gz
│   ├── cdad7908b17153d8202ce0ad6cebc6ddffb65c00.nq.gz
│   ├── cef331cb14e2d28aad841bb7b7fd25e730d2fd6c.nq.gz
│   ├── d3b9ae7657cfc0127732918eb9b16230893165d0.nq.gz
│   ├── d6e13727ab7b1a6039edd0d3a3d42dd0898e78ee.nq.gz
│   ├── d80080ec331b8108ea0b41e493450c468529cb29.nq.gz
│   ├── db0062f6d6d4f1daa8946c902c37ec96f85281c7.nq.gz
│   ├── de07a4c6c0baaf623f20790851a16aae4c81fcb6.nq.gz
│   ├── e1364040aead094f2f5e2231be7505c9208ee9a7.nq.gz
│   ├── e5509b06e2ad82a5fd3a7bf428483dc3f40bc1f7.nq.gz
│   ├── e5d545e904d5643c35664dac4c4898a74bb17a41.nq.gz
│   ├── e5e284ebb4a6f77f0993bd46b86a449868ea02c0.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7816792f53b91847458f0564dd6110744380109.nq.gz
│   ├── e84b7acaa0ddbb2b9143d998a2fa33e40fccddef.nq.gz
│   ├── e8d7595357498a207cd86be18953990ebd27bf46.nq.gz
│   ├── ea53f68c5bcd53e35c8001dee0ae45b363643f5a.nq.gz
│   ├── ec08b66a54460777ffa1118faa36e2384c6446f3.nq.gz
│   ├── ed2c2bcb273d2606d48162c3385cb71e1e0c41e9.nq.gz
│   ├── f017e210668f4699ccb19ee66796b1b99b4df08b.nq.gz
│   ├── f5be99bd23dee0c4c5dbdef27315c5a6480d7926.nq.gz
│   ├── f773e9c4e72e8ed892bc814ec56fcbea3569ad7b.nq.gz
│   ├── fcb7dd941b6f3605c700933ea5274981e89dd563.nq.gz
│   └── fdb9daaba0e3aff811152b8afa25b43d866c0650.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 25405c7b771987d2a67527086d75108f71cf0a06.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 123 files
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

[databrickslabs/databricks-sync](https://github.com/databrickslabs/databricks-sync)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
