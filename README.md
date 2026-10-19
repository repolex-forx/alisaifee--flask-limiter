# Repolex Knowledge Graph of alisaifee/flask-limiter

RDF knowledge graph data for [alisaifee/flask-limiter](https://github.com/alisaifee/flask-limiter), parsed by [repolex](https://repolex.ai).

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
rlex download alisaifee/flask-limiter
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0e715b6fbb4655756f747c78d95d61deaa69dd1c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0e715b6fbb4655756f747c78d95d61deaa69dd1c
│           └── chunk-001.nq.gz
├── blob
│   ├── 05373f1b6f404c2ef2602e69d336f9e4e21d0b6b.nq.gz
│   ├── 078986389572133222a5a06044d6d6161744dad9.nq.gz
│   ├── 0a91b92acca0b243b06a93c93104428516483c9c.nq.gz
│   ├── 0d82ac33f719e316c2b94602095d48c63ec1e489.nq.gz
│   ├── 12b2f939d290dd0d1016dcddfc856d99c7952d3a.nq.gz
│   ├── 130beb604bacbcd424c7a9af074e2a07ce2ff4d0.nq.gz
│   ├── 14c58523a387aa906c549439db89737fc4645cd6.nq.gz
│   ├── 14f80f3585733faf31ae761e80e8e6e1a209ff47.nq.gz
│   ├── 18c91471812cb6f4c4e8d0fc407f70c4612e1648.nq.gz
│   ├── 19f9b4f45bf8002e79c5e6bbade927f056bf8561.nq.gz
│   ├── 1c54017344eee77984f58b654001b8297be2a9c5.nq.gz
│   ├── 2261d327ad9be9232d7d08158db2ccae582b98e6.nq.gz
│   ├── 229b89cc56e1bf386aeaff223df183cc84bf22a0.nq.gz
│   ├── 28aff2c53dc21f9f613887ad7a017d350d83b55d.nq.gz
│   ├── 2a1445438de16230aa83eda0340d5bcc7075de3d.nq.gz
│   ├── 2b6fa29ac48a87aaa00f4ecffe6806252288334a.nq.gz
│   ├── 2c0dc9ee16ad6750a7951b0373292a7a01ae7771.nq.gz
│   ├── 2fcfadd602b15d6532f0b9e1aa27928ce594e45a.nq.gz
│   ├── 31f6e2e06794f25608f83a6f872fd78261847aa3.nq.gz
│   ├── 33b7acee7d6cb4282ac9cd8ad6cddb646e733016.nq.gz
│   ├── 3e4bf02da31475aa3031b2781cf5d3a3f3b158ac.nq.gz
│   ├── 3fa04c15bc1f92dfa9c53f37a5af361a7a1a6838.nq.gz
│   ├── 40995ca4c308c35513869b82e112e214abcb2311.nq.gz
│   ├── 40b317d0e44e9ad3ba1c78ddb14310547fd747d0.nq.gz
│   ├── 44ed1cb4dcb3d518eb6b1c41e3a5e9e468908760.nq.gz
│   ├── 541a18199673ce348441da64f90dec717a105882.nq.gz
│   ├── 5c73514f38f57cddd13ee536524331de23154a69.nq.gz
│   ├── 5f2e348f2ee7b8b9c397a2ebb9b73df05da466fe.nq.gz
│   ├── 5f740a13098eeaa69ca40af0d2bc3409658f3fa3.nq.gz
│   ├── 6464fe2e1c6146d9e044b65c2dc70c29d5215e61.nq.gz
│   ├── 6487ce2cbf122552fbe3dec27f019db2987e8aac.nq.gz
│   ├── 65835637f2c42c34e97105bd31a0ac497c268fc4.nq.gz
│   ├── 66512905a0875a8683a0c27961fd6f180e9175c8.nq.gz
│   ├── 706d225716bf488704f65cc0d54ddc6424385726.nq.gz
│   ├── 70cbd8d54b21c94377d1b4e1753c40bc9ccc9bb7.nq.gz
│   ├── 72a8f5e6f023ca3ef216fe8a472fa65ac72ee593.nq.gz
│   ├── 7742ad64a9289880d56f1d3e05b037bf0ba5ade0.nq.gz
│   ├── 81b2aea55804187797036198e36e469f6f7b097d.nq.gz
│   ├── 82400699ca8ed1d0daa22582f4d3b58f6c7315da.nq.gz
│   ├── 8597977440bd11b36e782af869372e55ba419fa0.nq.gz
│   ├── 86e980cf7b80478d6fdd6c02db7a69fa70fe361c.nq.gz
│   ├── 8a0fae98554765f96ae124800a174460c21980f4.nq.gz
│   ├── 8edf6c2013609ecfba410f5cf15133430e793b27.nq.gz
│   ├── 965427fd453b956e4c128ec8bcab4e2b7d829111.nq.gz
│   ├── 9ce02965cb5870fe80cf82441b29de424e9f05cb.nq.gz
│   ├── 9d0491f7e458592cb6ad19f8b05fbf25ea5c3c80.nq.gz
│   ├── a42b11cf914e8ebc9b60b66f5c5446e4b20114b1.nq.gz
│   ├── a6d8fb5d9c89c5920bc6c5a40f49a08272c37d7d.nq.gz
│   ├── abf2e5ed79533d92fd1fe372b53e9730e18a2a1b.nq.gz
│   ├── adf0f67440d7ffdc051efba2603f14f1953bc626.nq.gz
│   ├── b665b742ade0068ee9d060c7ae4f78e7ffdc2643.nq.gz
│   ├── b6793be469d2c7d5019b1fb8fc96bde3bf566086.nq.gz
│   ├── b947f378d32cd29c717e0da405c7f5bc16a393f8.nq.gz
│   ├── b995a59970cbc8c95bbed59c968f9dac791cdd64.nq.gz
│   ├── bcb1623c4d2136e60e9d745da93b1bf49eaec875.nq.gz
│   ├── bda5b5a7f4cc3cdc8ef37ca67f3a0d26c3c0aad7.nq.gz
│   ├── bdf3a1781a4c24282f72275dfe5b7ae9fd660157.nq.gz
│   ├── c0cf282805dc46e8aae3b074e53d869867b151a2.nq.gz
│   ├── c74f371cfd89de2caa4a5d75b6ad4897f906df9d.nq.gz
│   ├── cd344e0adf529b6d6ba3f2a52eb496d27f0c98b7.nq.gz
│   ├── cfcd8a7ed945ec0b4e84c368e3eb64f2895a3861.nq.gz
│   ├── d059291c0da506aa76598061c481d27420b4e58d.nq.gz
│   ├── d0f5d0c1dd1836b3043902c2b18c5c7b30ccdec0.nq.gz
│   ├── d466c6728928ac09595c1795c4b75acffcb23083.nq.gz
│   ├── d83aee2b19ae34e0bf42c68fdf2ff0e5ba6196ac.nq.gz
│   ├── d97ed88e8e929a7556cd084d8d673a20ef6774ff.nq.gz
│   ├── da9c516dd744b6c88dd8c91f58f7bcf8f7e8341b.nq.gz
│   ├── dd05c401349b4928d3c6c74256fda1333433ea1f.nq.gz
│   ├── e1e47da03aa04b5aa037876a19d52f94e99348a3.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ee38e230bfbf814e84da2cdd5436c6711721d6e2.nq.gz
│   ├── f32cdd749d21edd1d6ee5d22886111e039afd2b3.nq.gz
│   ├── f5a27b5ed58da508531a314ac633512a5b9484c5.nq.gz
│   └── ffe93afa69666b47ed6fde356784c44e054be9de.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0e715b6fbb4655756f747c78d95d61deaa69dd1c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 82 files
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

[alisaifee/flask-limiter](https://github.com/alisaifee/flask-limiter)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
