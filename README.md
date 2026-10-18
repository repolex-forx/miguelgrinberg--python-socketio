# Repolex Knowledge Graph of miguelgrinberg/python-socketio

RDF knowledge graph data for [miguelgrinberg/python-socketio](https://github.com/miguelgrinberg/python-socketio), parsed by [repolex](https://repolex.ai).

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
rlex download miguelgrinberg/python-socketio
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5b49d7ca33e5eedecf94e35301a847ae0d2bd52b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5b49d7ca33e5eedecf94e35301a847ae0d2bd52b
│           └── chunk-001.nq.gz
├── blob
│   ├── 020ab024dfe56dcc233fa54eea3856f87f49e0d9.nq.gz
│   ├── 0232dca7c949696792fccc45c162ed94b44335cf.nq.gz
│   ├── 0276d74e1d9117ddbdf09adf5187e850e67dbfb7.nq.gz
│   ├── 057950346c41c220a1c3109f36c93ea8f9b6e280.nq.gz
│   ├── 07c392100ab95825a9fc02e4dbf28697d2c60137.nq.gz
│   ├── 09533707d7fa0bbd4a7c68270b2220211cb1c0c9.nq.gz
│   ├── 0d94aa7de3d720449f26e4466b612a8c80d6be91.nq.gz
│   ├── 0fad02921b3ee9ae2fc4ca5c89bd6c27af824a72.nq.gz
│   ├── 101455ea21a68b0439e997c177bc353ee38bd939.nq.gz
│   ├── 10dd5123f09ac5e739bbc1f760ce5d6b798a83e5.nq.gz
│   ├── 113d475e575ae779b714912a8901d82fac8cb88c.nq.gz
│   ├── 14b5d8fbfda9525ba62bbf40fc888c63cf2eea6b.nq.gz
│   ├── 1568ca1f575de8bb1b3b53b2a427a07858471d0c.nq.gz
│   ├── 160bd329af8c302c0c7a1ccd807ac543acb8de29.nq.gz
│   ├── 16fa4caf9b86a0291205c914ff0254d3002a6ee7.nq.gz
│   ├── 19028b040fab1328e26ebc9fafd72799cc7e7971.nq.gz
│   ├── 19d6e39e8d709326b007f6c29aa1994f7d225200.nq.gz
│   ├── 1b0f4a42095d04fe43b0774ce33f8b7f634cdd9a.nq.gz
│   ├── 1be759cb2a3b2eab1f5976d6a84ae26ccb9560f4.nq.gz
│   ├── 1e23c7490cb3d2e9ec45c026af9e0b08afde9599.nq.gz
│   ├── 1f0f0d1c713b47bd10b050f32ced4f97746c8d44.nq.gz
│   ├── 234d2d9ed82c9c52cb3d28ed95a7590358d6c396.nq.gz
│   ├── 23b094d8c6a38b134a13d34e6721930ed26b14b1.nq.gz
│   ├── 24e53a362cccb2e69eccf4980b02bf6d50ea80dd.nq.gz
│   ├── 250f570e6e94706459402810dd05090ea476a264.nq.gz
│   ├── 252c77f8c29039852b459ce42177414c4636905e.nq.gz
│   ├── 2667f523b4ac487e36daf80f60f62a6083581ec1.nq.gz
│   ├── 27f573b87af11e2cbbd9f54eb1ee285a58550146.nq.gz
│   ├── 298ea9e213e8c4c11f0431077510d4e325733c65.nq.gz
│   ├── 2f7c58ac32228b7fdde02435967a3f65938f6083.nq.gz
│   ├── 2faa14664240168c9cdb8578b46d9f73c4562dca.nq.gz
│   ├── 3070a03e1858a35d9a87c0d34b2e626134f414c8.nq.gz
│   ├── 313462da6d07b4841f8265974a8ce0d2b561d73e.nq.gz
│   ├── 35ef79b538fd3274c8ed4eb5c727ad21213534b3.nq.gz
│   ├── 3a9d2de47093fd2a6633c89035ba9a5bc27ac2ed.nq.gz
│   ├── 3ebf676888b6ebfb0b90330b699d8d4ce6ee88de.nq.gz
│   ├── 3f4e29c61fcef7a5430578cb8ba1e121322be506.nq.gz
│   ├── 3fa1e1456e700ccc455728753ea81198f91c2a9c.nq.gz
│   ├── 402a3799d56eda26bab0a56ff2d2f3fdbc098d61.nq.gz
│   ├── 4035e336272aa3d518fad362c45f81b3cf76969f.nq.gz
│   ├── 405e6e56f51fc8ce9950234be7cf232e20b7fd55.nq.gz
│   ├── 40966bf87cc08883a46859b6554562d10f1f7d2e.nq.gz
│   ├── 43236fe86ec6ddffa8c381a74f4665617bf4095b.nq.gz
│   ├── 447ddff65c0206c03c8f0dde455432e4f0f754b3.nq.gz
│   ├── 452f17c0867b8fb91ec0619b50bb6cdeb74b817c.nq.gz
│   ├── 467291999cf234a5b7e1553aa9e3f55ee0ebfe33.nq.gz
│   ├── 4d560a7198b10821df59c2d75dd81f22bcaf1294.nq.gz
│   ├── 509eabb16c73d031685ddf27965f70efa7d495f4.nq.gz
│   ├── 526d67694845c56172e09231648bd50c627b2db7.nq.gz
│   ├── 52b30f40ed8eda4544b65119cb239884ff4ddbc8.nq.gz
│   ├── 57102139107d54594250adbef058eccc4ff97678.nq.gz
│   ├── 571050b7e5167e3dcff601c682d93dab86783c70.nq.gz
│   ├── 57be604df4095c8488b80d262df623ac18760758.nq.gz
│   ├── 58317d9b7edcac3161053992d32e289ffe095040.nq.gz
│   ├── 5ec9c33a06bc48f88b634f23aaa725339bc48f4f.nq.gz
│   ├── 5ef411382e474267af2ee2091fe1427e54a346ea.nq.gz
│   ├── 5f9ff88d59e1dd7ba4bffaf54d59588224494a77.nq.gz
│   ├── 60cab783164206ee35f24487adc639970bbe2141.nq.gz
│   ├── 6239577c663af635a72b7d38b1787635f5795a30.nq.gz
│   ├── 62806cbbed4c09bebf794af516b0758cfa94b16d.nq.gz
│   ├── 63735bec84563eafa93f2ca270b5b6693b8aa328.nq.gz
│   ├── 63c93260f6acad2f2dc05ef698e43c3967a0fb48.nq.gz
│   ├── 64ce330d46881c803edd39a85ee28df97249a8b7.nq.gz
│   ├── 6861a5cb6ccfa47e24a7e213c9e08fd2c71929be.nq.gz
│   ├── 71a7a5403d28bcec244b803cddcf530fc3201ea8.nq.gz
│   ├── 71a836239075aa6e6e4ecb700e9c42c95c022d91.nq.gz
│   ├── 72806b68982face5665719e0d2ddae654db026bd.nq.gz
│   ├── 732d1882189ec8cb4cfc8828a40066fbfe8fa2a4.nq.gz
│   ├── 771cae2e9eea6fbea6af2e5c58ada71f19a9c67f.nq.gz
│   ├── 77f61610255f3700d941e330066434c7ed5a7397.nq.gz
│   ├── 797dac47611533a0b31d488508031ad8aae4f79e.nq.gz
│   ├── 7a7bfa7c763d8cabaf770f11e5245acaa8f5724d.nq.gz
│   ├── 7bfa0fe6df87d146baef25657334064a5be51261.nq.gz
│   ├── 7c48da12ab52f81ec52304ecbf0c429bef2b6b18.nq.gz
│   ├── 7ce503c2dd97ba78597f6ff6e4393132753573f6.nq.gz
│   ├── 7e1a8a5b59cc3fc63c2c3f66f463e291d0bf6af1.nq.gz
│   ├── 7e1f03c411a356b532ba8f3f0acfd2926f6449e6.nq.gz
│   ├── 7fc871b4d2f13b0b25c2888463aa1348e6cfe349.nq.gz
│   ├── 813d0a0d22f21ec19b14519ecff5a342f56bc35a.nq.gz
│   ├── 828c8cd3cbfd70000af584ae6a2ded4000289e1a.nq.gz
│   ├── 82b918e5e79960e613bb632ea872cb3747909392.nq.gz
│   ├── 84978de41243a0a9637ab5c687e1e1fe095bddfe.nq.gz
│   ├── 8812fccf97d68bd30ad817a5cc73b28bb6730bd0.nq.gz
│   ├── 8b2046c91d7a7873d21bdbd2306219921bad69b1.nq.gz
│   ├── 8c38f3f3dad51e4585f3984282c2a4bec5349c1e.nq.gz
│   ├── 8d69a850afb42772723819f8f26e38960f09d097.nq.gz
│   ├── 8ecb71217b9d3e2edc0becbe656054f7d011573b.nq.gz
│   ├── 8f14992ac474840b0ddba700a765b052cb75db12.nq.gz
│   ├── 9421b55ce9babb3485616a163c8ebbcd515e9796.nq.gz
│   ├── 94dcec9da4350b38a3e7a70a37cd8a647623d7a0.nq.gz
│   ├── 95642f446f642a81d538a5d3594791452cec53c0.nq.gz
│   ├── 977da10736e8c2c55fbf6b3c77a233d928bce14a.nq.gz
│   ├── 996dc27287790289b29113e71b1b684617ded816.nq.gz
│   ├── 9a77e3f6af9f2be5148b109ae7b0d213bf6b339d.nq.gz
│   ├── 9a862943145f39beedaa3b212cf0a7f53c613815.nq.gz
│   ├── 9bb301dfd19f822a3fc1501f40cf6e00b0dbcc62.nq.gz
│   ├── 9cd9a8af774bc854da082cc32a90a5bdd1522f5e.nq.gz
│   ├── 9d0fc9f37bb40f5541c7de34d46241372f9a2778.nq.gz
│   ├── a28dfd1c2f02efb499aeb4fad5e21967a309b570.nq.gz
│   ├── a2be9946c24e2026be2918119c41712842fd0062.nq.gz
│   ├── a2edfaca9b8bbe29fdb593ead7ce8752a2950262.nq.gz
│   ├── a3847898f6c8cd1b0b5563518ee068b35070a42a.nq.gz
│   ├── a386fca9164636bfb38578a98a2937f5ef3e0b19.nq.gz
│   ├── a4d0928d984c84ac3971e0ef0f4d351bcea55aca.nq.gz
│   ├── a4e875f4c912bd1ec90d787f4921c5b1db98979f.nq.gz
│   ├── a5fe7c10c783c40d2ee5e88a9d20e28aedd43576.nq.gz
│   ├── a706135b01432bca77e09f2378c85406e832acf0.nq.gz
│   ├── a8975663399608c8cb2b600fbf61d08427a42070.nq.gz
│   ├── aa890649b21ba31b95a0a4d6e9ab049fd76b9726.nq.gz
│   ├── acc8ffd34d90984e75cab6fcacf8884a031709b0.nq.gz
│   ├── af658fa4f48fd23072eeeb64843829a58d97bcdd.nq.gz
│   ├── afa28ff93d0f433b6f934ad374f843d0105260cf.nq.gz
│   ├── afce173dbebcd0632ede7d0f22b4eabac5abc034.nq.gz
│   ├── b29e521d67282432fcfc980f3daa5aea9f618c8b.nq.gz
│   ├── b3878a2a921689500e7a38d7ab5a87d1edd9f874.nq.gz
│   ├── b4659f4740789b92b9c42d34a1e4dc25f87f9a13.nq.gz
│   ├── b6902e0d4202b963047d5fe97115b203f8af622a.nq.gz
│   ├── b6b2d70e0980186cb4dcf3543d4a3a1132027ed2.nq.gz
│   ├── b6d5e336c076ad9deb664dbb0f359f5fbc591cde.nq.gz
│   ├── b7f0193ccc6dc1dcfcd9b249daa9712e856223af.nq.gz
│   ├── b9084eeacabd7b013b776a32816bb5c0ecddd57c.nq.gz
│   ├── bfcc834c9cd86f221960e6ce3755db78bf5de8cb.nq.gz
│   ├── c15655183a72a04d883b6124e48e89d70ce4b655.nq.gz
│   ├── c22109a5755a6c5ef0c591e9b090bdbefd4364a0.nq.gz
│   ├── c4dea11066d1d850849f0da9e9aeb035dd2c148d.nq.gz
│   ├── c68b3e60ddd7e8e268e5d8ad135bb92efc262e30.nq.gz
│   ├── c6a039a0c8d698c33ec0f40dbb7d2f7f8f8842e4.nq.gz
│   ├── ce5dab04deebc1d93eb78ef663f67020b7565be0.nq.gz
│   ├── ce99d0a47806ded490926c0473bca67850dcbc93.nq.gz
│   ├── cf6fc820140a8ab3f436ed7335967181978dc445.nq.gz
│   ├── d134eba1f1e365ceb7b69ca801dcd45b43301d5b.nq.gz
│   ├── d20bcad97867feeaf6e97b56488363ba660856b7.nq.gz
│   ├── d386a9c31108f46f5a119a49ff8dc87a10f548d3.nq.gz
│   ├── d3f4f55d5bca592ae86e5aa71fb5c2cec1fde922.nq.gz
│   ├── d9744803dd1053e7a6efe0e20e534983e82a6a23.nq.gz
│   ├── da2ef2db8da761193800d5acd44d2230a743dba2.nq.gz
│   ├── dbb8cefc38d08a455b3ffdd39dfe03bc69e56cd1.nq.gz
│   ├── ddafd420fc77f9bd7f24e4d3fb0c176557351d3d.nq.gz
│   ├── df70ef35f03a87a62318affd2de2563ed39fca4d.nq.gz
│   ├── df983585f323ff4fdf6638f709bbb0de8177671d.nq.gz
│   ├── e247f4d4b3facdf1650d072e1922d775b81c4933.nq.gz
│   ├── e59da8ab0396c2f3a992ba0e75e1e69a0817d72e.nq.gz
│   ├── e5aeb6cc124b4a43df58009699e3d838e629b32a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e73f14c571e930ecbad4e3f888ae427006772290.nq.gz
│   ├── e8a76ca303f8cdbda1663d4e7ea9ae234c5e38d8.nq.gz
│   ├── e8e83ea43d950eed70b758d650ce505798d06b06.nq.gz
│   ├── e965313adc5c61855c19408451f215103431d78c.nq.gz
│   ├── e9cd703d60b46876f45a2aef03c12ec282b61134.nq.gz
│   ├── eaf55e28f447df73d4d05dcb12fee89da0d8e6a3.nq.gz
│   ├── ed78fc0d81601118161f28abe0dad31baee4baf3.nq.gz
│   ├── eddc1738df7512a4206b8dcab0ef02a8b22dec74.nq.gz
│   ├── ef4d0863b46aade7d677848e895bdcb44d2f8dbd.nq.gz
│   ├── efc4d6f9b9052342e669772a523a5f742755eb6d.nq.gz
│   ├── f1476e41c7f8732f15e898a59016ac8892898577.nq.gz
│   ├── f25602b105b1bcf3e8d26135d4c8d25d0a984334.nq.gz
│   ├── f4b71137b9b600e4cd85ea275fb4e0375bb895b0.nq.gz
│   ├── f54e1d67d94ac018e1034a83a30ea8aeb94d8c0e.nq.gz
│   └── fa268870609cba3a5eef0512820ec1145aa1b306.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5b49d7ca33e5eedecf94e35301a847ae0d2bd52b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 167 files
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

[miguelgrinberg/python-socketio](https://github.com/miguelgrinberg/python-socketio)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
