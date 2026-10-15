# Repolex Knowledge Graph of carltongibson/django-filter

RDF knowledge graph data for [carltongibson/django-filter](https://github.com/carltongibson/django-filter), parsed by [repolex](https://repolex.ai).

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
rlex download carltongibson/django-filter
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── daddf7b65535a4f7c670793ff4a2df2f17e2e4ae
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── daddf7b65535a4f7c670793ff4a2df2f17e2e4ae
│           └── chunk-001.nq.gz
├── blob
│   ├── 0186498cf16c610ba1f37828c759e8c658c35837.nq.gz
│   ├── 0ac4cf16f10edaee72a3e3541c1d257d2aac1a64.nq.gz
│   ├── 122fe4df853fbe889cc25faa3a31edb2dafb5ee3.nq.gz
│   ├── 130c07462d8c905f1fd37d04952b0d317a9a9cac.nq.gz
│   ├── 18cb472483ee1be42758d6ba6752a96dd47b3efc.nq.gz
│   ├── 1c77634ec883f3c431d9722dbaf7befb333df7c3.nq.gz
│   ├── 1fb9cb6a8d8a9c7d7bdf5e462bb8baa1ae5ededf.nq.gz
│   ├── 242bc8074b2f257e73708d907bd603c57f98fa15.nq.gz
│   ├── 255fb20ef67f3184dfaed2d748357d301b95ed01.nq.gz
│   ├── 265ee99a182efba4db78c1fdc8b998957f05967c.nq.gz
│   ├── 2ae9948f350604fd51707afbea1f098c4a95a297.nq.gz
│   ├── 2d4da2442e9c45db97f543d7232ebc9d3b17a379.nq.gz
│   ├── 303d17f6b60c629dd1deb2a3ed1068dd5040f0b5.nq.gz
│   ├── 305fc7270e5250cc06056bfcbf3c64e443245e12.nq.gz
│   ├── 3338ff7a7789d12ed5c5444aab75f4a0b73fabb0.nq.gz
│   ├── 3417fe8edc79b6aec7c5131b952ba8b8511060c6.nq.gz
│   ├── 3441d25eda42593b2573c9d335bd7adddd10c3ce.nq.gz
│   ├── 375fed91e1c5aef5021989aed5a1564fbe5d3f62.nq.gz
│   ├── 385b3d3e4de23ccb28ee3b9db85adca8ac9ae59a.nq.gz
│   ├── 3ae91db583902b4ce35e2ca558acbf1e08c26c25.nq.gz
│   ├── 3f4932bf2eccbca447d6e1b170401e4809ac49da.nq.gz
│   ├── 4092d30bfb9e035ac64bebc52e9d11214da18c24.nq.gz
│   ├── 426edca816cf814ca58b86712d33f4ab8a9873ec.nq.gz
│   ├── 44967dc8e0f484b9e1a09436772892466dc2fca6.nq.gz
│   ├── 476cc1228cdac20082d8de9b15626b6a0f73bd65.nq.gz
│   ├── 47f4970922928571998dfbe4a6b63d70005bf621.nq.gz
│   ├── 48ecbeb39fdbd0793ff8343ce7f4f3ee0a52af29.nq.gz
│   ├── 4b73093970d09c9f8df3df52373b1142bbdd8c74.nq.gz
│   ├── 4d9bdb52c9d4be2a8e8bf3996232808bc612544d.nq.gz
│   ├── 4ffc4084ef0a0a10aa3913da87470e4b659c1345.nq.gz
│   ├── 50859eb4d8a5b77c4fe7441540b06ca03950492a.nq.gz
│   ├── 54a8915c0957e01903e4ab8416aef2f8d3f87466.nq.gz
│   ├── 595dad9efb1bc1d7c37a0b9fb3b8cc9a36e9cab3.nq.gz
│   ├── 59a77187a0c630d55d84218d7535eb62c186dac1.nq.gz
│   ├── 5a615953969e68ad016402dc88e81af932a3bf1c.nq.gz
│   ├── 5baef32f7e89ce973cb097544810756d26c29c95.nq.gz
│   ├── 5ebe2a0cd80b03582a245b2c004188f91d95d1fe.nq.gz
│   ├── 627341c561b30953e52e4e54ca18c427ea255890.nq.gz
│   ├── 652d5e0f3536ecaab4f607dbfe488be6a0609395.nq.gz
│   ├── 6ed8ddc5b50ebce502e128f9ea42723ee9380c7f.nq.gz
│   ├── 6ef53377d247b4599d8d7a5a70c434346c93c1b2.nq.gz
│   ├── 7047a5e13f617e0e3d107d6bc323a579c2c4a5b5.nq.gz
│   ├── 73fca97a5e729018c3088444f29ddc0d585b3bc9.nq.gz
│   ├── 7764f3bef47ae08cfc55e45506baf8ee2d8d00b7.nq.gz
│   ├── 77fafee51ed6867b43cf29bf22e19e81f7439951.nq.gz
│   ├── 7f4778af14252d65c1cadde0ab8ff71a27fb134e.nq.gz
│   ├── 7f8da301d8b4be112316e816c3804f0ea418f4d3.nq.gz
│   ├── 8160cd372690eb05730633899f7bee68bc22a89c.nq.gz
│   ├── 822b095042136a7a1d200ad2353231a4f1333482.nq.gz
│   ├── 84ab34215d07233bec96cd9ddf5d1e6b67f41d13.nq.gz
│   ├── 84f7e940ed2568fbb8d009c7378617b2c5a90833.nq.gz
│   ├── 896c2c8de8b4c21d882ef58b04a5b75a9e276a8f.nq.gz
│   ├── 8a8c48f45fb1f347f2a2f404d4444df2301d53e0.nq.gz
│   ├── 8b2fcb8df58a2dd60aa289764867514ffee4b5c4.nq.gz
│   ├── 8bfe83a19447207699752e530802999268eb237c.nq.gz
│   ├── 9262d12972cf3f8b466de9e2fc9011963f871872.nq.gz
│   ├── 9309fe4b11d45ef7ab5b37267db8768c705b937b.nq.gz
│   ├── 93aa5b38aba20d683b33e00af2adaa5194cd0d62.nq.gz
│   ├── 9553bbbd2dcbb537d56009e6d96280a6e5e05d38.nq.gz
│   ├── 978bfb37e1d85283cdeb946e8874e9c5dbbfc4be.nq.gz
│   ├── 98d84797ac4b89f4d9278d2fe0536ed051131071.nq.gz
│   ├── 996c451f6f8ada996c0da4d3849c45887fc768b4.nq.gz
│   ├── 9a48a0a90a2d53629acb8b809eef835006080073.nq.gz
│   ├── 9b3f872835c5494b90abdc0d2291d8883da4b510.nq.gz
│   ├── 9e47b28166f285cfff10004cc7f337f62708f9be.nq.gz
│   ├── 9fb5ce9d756754f7c1804e48969c3a86f85b5b90.nq.gz
│   ├── a4ff1ce33683d241306b1e34e110f16adc96604c.nq.gz
│   ├── a622b232da1f113ac6dc0238feaaaedd1fa3b49a.nq.gz
│   ├── a753624229502b607c1b1fd94b66b52a25db5d4b.nq.gz
│   ├── ac563430351466b2da353e11d11c438f193242ba.nq.gz
│   ├── aec81d50f8c79b368bfcee5a8f7726b4aaccdf61.nq.gz
│   ├── af02db9fd64b6e09e2d298548051f8195e98321d.nq.gz
│   ├── b1b876f573a3011cc6617615b5327c09c7f5efe9.nq.gz
│   ├── b27a84e82e9ee0b4d05d7263b380fab4b5c0e08e.nq.gz
│   ├── b6f89cff5eccc389974c92fb37caa9b5bee1e8db.nq.gz
│   ├── b811569ac6093a70a392f2beafbe29779fdf84d4.nq.gz
│   ├── be006de9a1ae3b9628e796c74277cd6d61e0a34a.nq.gz
│   ├── be962f85f08397fb4237d231c714871b1892098a.nq.gz
│   ├── c249b021bbd808dacd3825bdab8e67074b0cffb7.nq.gz
│   ├── c24f9abac5187043fc1066922899e95e2b2333fb.nq.gz
│   ├── c27f77b8bc809f7f41f8efb1f8cbde873e16f1c7.nq.gz
│   ├── c63c47501d90cbcffb2f2aafc66d8e841eb45a42.nq.gz
│   ├── c7fc0f592f069027378d72c6be75f6020ecd9a58.nq.gz
│   ├── cada331cb2e8ec06232dc370fdb0d084e747e529.nq.gz
│   ├── cb460178d38f3d3ec5634b687011ea0d0610b07a.nq.gz
│   ├── cbef0b76c7858e96af2f894335ecac498db7371c.nq.gz
│   ├── cdf26b6465866078eccf38a65a434e409cd695b6.nq.gz
│   ├── d6ac79cb4b46060f7caf9f0416afc8df5981ece8.nq.gz
│   ├── d9c67d890166eae569fc062218eba2517b4d85db.nq.gz
│   ├── dcfae01a5231e84fc2fa401491253f7abb313d49.nq.gz
│   ├── de07d2895d656a6e15b9822b2aa1b14ded9094b0.nq.gz
│   ├── e16148d1482d99cf113a777287419c466d074758.nq.gz
│   ├── e1a391b213977ebb0753649c1a43546e761d4e45.nq.gz
│   ├── e298a582801a199a7e34e72c61ed277cf391a720.nq.gz
│   ├── e2c8f10e335e908d726f89f5fe8919bda5862230.nq.gz
│   ├── e37474c05e42b0ff9081597a7894216b0cecaa32.nq.gz
│   ├── e640c19f3cc32c01dfc26517572b5907ac6db8b2.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9a150d809787b7973a441e4292eeb7c09718f31.nq.gz
│   ├── e9cc1a8882e9192392bccf953d1f632118ec211f.nq.gz
│   ├── ea750ef57b0edf7d1f76536c4fae8f80a7f44111.nq.gz
│   ├── ea87f235ac7de67168898986c47f233bce6654f0.nq.gz
│   ├── ead6f2d7e6f04f0747acfc38157f1ac85ebb05f7.nq.gz
│   ├── eb904f6b385419399ef00dd25b5d0f9e9794bc43.nq.gz
│   ├── ef22b9155543f20f4824cf7b9f514666636c9f79.nq.gz
│   ├── ef5b2ed8c17177beb95def0001cc7362f06b73c2.nq.gz
│   ├── ef72447d8d23da846b8e14f629b21a6bc0e238e3.nq.gz
│   ├── f1128e95dae2e95fe95851a26b6293bf1bc8c1e4.nq.gz
│   ├── f40b2af36c3640fb37026167e859f490f77bf468.nq.gz
│   ├── f449f724929a3bbee7482d70e7f42b0b627056f6.nq.gz
│   ├── f53c4eaa17f3609e45b985b69968e1ea3c82b7ea.nq.gz
│   ├── fa69e4cc6d73bbe8477544ec64c87b512aca5a9e.nq.gz
│   └── fdbf09d482aaf689692fd17d17becd69f598c4c2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── daddf7b65535a4f7c670793ff4a2df2f17e2e4ae.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 121 files
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

[carltongibson/django-filter](https://github.com/carltongibson/django-filter)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
