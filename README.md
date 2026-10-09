# Repolex Knowledge Graph of NousResearch/Obsidian

RDF knowledge graph data for [NousResearch/Obsidian](https://github.com/NousResearch/Obsidian), parsed by [repolex](https://repolex.ai).

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
rlex download NousResearch/Obsidian
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 06124f2a8f04f9a026265bbca931dfdf9eef249e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 06124f2a8f04f9a026265bbca931dfdf9eef249e
│           └── chunk-001.nq.gz
├── blob
│   ├── 02a8c6d8dda4f5ac338983251adcdc1d3a99a3f3.nq.gz
│   ├── 04f47a91a74af9ba5686107fb6a4441117494a56.nq.gz
│   ├── 06160f2422b5368f30fb967f7cae635208a1dc69.nq.gz
│   ├── 067b6140fae546e5cb49cb2b1e4e6af660ced60d.nq.gz
│   ├── 091f224bd6504cd7b879d99e2d0c6936698568c1.nq.gz
│   ├── 0bb1a99f24c94b7d2f5c8f8b6c5c8a071d16006e.nq.gz
│   ├── 11bebda29b0b92a3d6928d28a0bd584510e304aa.nq.gz
│   ├── 12311c3ccc3511446298c8e829216266e702ec16.nq.gz
│   ├── 1300cd49992d8c342396cebfebc592909d6391e4.nq.gz
│   ├── 13313441b13fc7a66cb65fd21b482a5de982e2c8.nq.gz
│   ├── 1561785e4e3c6ff5ecd9e75f27051a6a13817cd7.nq.gz
│   ├── 16cf35ce1b77834d9d8888d53e6cd0f7c2c4ccc6.nq.gz
│   ├── 1af397d40c925aa18794ffc9650c7cb50f0430d7.nq.gz
│   ├── 1e324210e229eeba23b75791bba82df7c6e639eb.nq.gz
│   ├── 2065dfb20a6e40128749d507ecc27d01349e2ad9.nq.gz
│   ├── 21a52a29786df84d7ac6be8923518c7c27ff69f1.nq.gz
│   ├── 2487d317855b27d5b07a755ee0389667e4964f02.nq.gz
│   ├── 24e495bd3c88c295630bc4dc768756e28f5a6f21.nq.gz
│   ├── 2563f89c6cedf5e73508afec8f9979105df9b745.nq.gz
│   ├── 25c7bf00d69883a18c1e1d298a09bde7b1076e1b.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 26c7f4e0819bf0bafbace898f5f5a4f052490aa4.nq.gz
│   ├── 26fe3002413a23b5029e540c8b338ebb14307bf6.nq.gz
│   ├── 2754fa66d04134530bb47e6ed2df2440cfe6411e.nq.gz
│   ├── 27555554a960866d6571767db2437cfb4fd95ba4.nq.gz
│   ├── 281afe2f7f3581fba766a9ca1da2c1bce60c5178.nq.gz
│   ├── 2b13589d4e55af529fe0838c4130c2033ac10478.nq.gz
│   ├── 2c1590fdc7511370e8ccc285dcc9c053379b9134.nq.gz
│   ├── 2c2c40295e0351f25709ba25554c9329f15bf0d2.nq.gz
│   ├── 2f424d7b13c327e051d8c3312a0b620878fd7e4e.nq.gz
│   ├── 3139b31b27e6e67b31b27cf0ac7bda317f46d6b8.nq.gz
│   ├── 31cd4f48e6055cd6d00a162af30b1c8139e26b57.nq.gz
│   ├── 31db2eff8d1c4b3ae645583dfc5e156e818b6f1c.nq.gz
│   ├── 358155c384a2d18e6927d62562ac3f12eef36a87.nq.gz
│   ├── 369fe92579051f98a0724a92e52e65e014a0de2f.nq.gz
│   ├── 38190781a15db627641074df137143a4289d32fd.nq.gz
│   ├── 39dc8807ef8d339fb7cde331c0deabfe5ce7f93e.nq.gz
│   ├── 3b39cc7beb12301379af7daebbb5553fa92093ea.nq.gz
│   ├── 3bee468d34515fdcbef1a8b8803c9fc4f7dc0b34.nq.gz
│   ├── 3ebb0fe5b89a0d0345938c27c7efe14d4efd07e6.nq.gz
│   ├── 3fb0009f519d23ca74ff109edd84a3bbc8fcf1c5.nq.gz
│   ├── 418b83ca2363288046f4b48b1d706c5607341fb5.nq.gz
│   ├── 435448394dfcef578ac478f499160fba4ceacd6c.nq.gz
│   ├── 452f8ffd31112ece74ef69b7c39940ed70245bbe.nq.gz
│   ├── 46242a6371e8c9680dcfec5c955c3610555a3146.nq.gz
│   ├── 497a702ab5efb88b8f67333eae81645eecea78cd.nq.gz
│   ├── 4ae55d59c2c8bab80299272314a41bbeb959d8ed.nq.gz
│   ├── 4b71e3d5618a262e4746f58e5d10947b73370dca.nq.gz
│   ├── 4cf61230e8bb115cf9db8f10dab78edc990a3479.nq.gz
│   ├── 4f89ff074d72faf632d4be899038b276724eb209.nq.gz
│   ├── 525bd43b850e9f6a923158abd23bca6f8d15650e.nq.gz
│   ├── 533f3f4097db3844846d4a843d765c6df1762ba0.nq.gz
│   ├── 5376ff024494a78151e651d0fee97a510c52b8ea.nq.gz
│   ├── 537e7f9190713bd73332aeb80702efa39320ca60.nq.gz
│   ├── 565e54d1d4d35791d5ed22ad4e60c43fbdd877ed.nq.gz
│   ├── 567428adb29c03dd83c1f08be6b4e972af453630.nq.gz
│   ├── 56881c770ec5aca56bc2bf6c38cb6101ae58fa24.nq.gz
│   ├── 568a381ae2b302f4163eecb87f6cda75734f1ac2.nq.gz
│   ├── 5921964c43f599b2d820de5092a1c3b4c39de60f.nq.gz
│   ├── 5c3c2c31fc35377a926739e8e4bfd4c23fb39e7f.nq.gz
│   ├── 5dfb79fec3eccb3722767aeb609b438702ec4d63.nq.gz
│   ├── 61b6de158b5eaf7480654ce2cea7aaeb0061d53b.nq.gz
│   ├── 638b078837f175039b2db49a63821288d9681daa.nq.gz
│   ├── 6917317af62da757ca759a92b326ddfa65b203cc.nq.gz
│   ├── 696efe53340f4abe5ad3ba8b9578df056e6c897d.nq.gz
│   ├── 698546e995d365d1ccc2c25a87e6c5cd681e6eb6.nq.gz
│   ├── 6b090faed0e630b03b2294545050f1f4f5032cad.nq.gz
│   ├── 6c02a617ce449808bb5662cb37e51d4f1558d7b4.nq.gz
│   ├── 6c8c1138ac166387d82cba868d00f64ab4e6a33c.nq.gz
│   ├── 6cba6fff0fe21fe222c7ab38eae44a9784c0be9c.nq.gz
│   ├── 6d90fec47ea06b9b2121b2f8845bbea88d181fd3.nq.gz
│   ├── 6eb89c0c1408299f1423064814d78c293acf9da2.nq.gz
│   ├── 6f44ebaba1aa493b8bab3baa4e827b76752b1869.nq.gz
│   ├── 70284585018497b091ba797a05d57c07e8bce3b6.nq.gz
│   ├── 70803e201a3206aa07147f36fdd32b52b882d33b.nq.gz
│   ├── 724b8b77901a482416199655880343c99b9b9b1b.nq.gz
│   ├── 7aea14a9908c8afcfa98c919a34c88a290683c3d.nq.gz
│   ├── 7b6d6fc69b336c0a5d103be9fb13a0e0897c76a3.nq.gz
│   ├── 7baac2f1ad93facc714bc2610faf25db813ff90e.nq.gz
│   ├── 8147382a3152de03c24b4cd91f9870ced1a95d54.nq.gz
│   ├── 84807ec252858cd78bf96b3fce6f42f66b20126f.nq.gz
│   ├── 872943cecae8ce469031425ab82df74abcc62649.nq.gz
│   ├── 8881c41c67002a3798435b051c9a609dd1c0d506.nq.gz
│   ├── 8a2c7f35b9fe3961f0d974ee4799fa517922df83.nq.gz
│   ├── 8af4559c65fc2728b11fd2097a109981ee1ef686.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8c1a6487202a6400a7116a6bd68b493892ef0d14.nq.gz
│   ├── 8c82dbc256bd610c5ef2564ed2449b6a91857968.nq.gz
│   ├── 8dac93823203ead2af275b908f3b3c5e4ccbe631.nq.gz
│   ├── 8e2d1ab08ccee392f174a64b4d885bb96e148202.nq.gz
│   ├── 8f7163c0ba1d9a81d81a950bce61e0f0db06066e.nq.gz
│   ├── 8fb59f2eb46c7e0db50d2994b2e9102d46def656.nq.gz
│   ├── 915947ff663fae5f7cfdc1967acd39fe176c7518.nq.gz
│   ├── 92602258ccd953a1d7137056aaf15c8de8166e21.nq.gz
│   ├── 9314affd72bd06ab260c3e8b36fbf5a4974c995f.nq.gz
│   ├── 9316eaa309ea8c12d9612a01d85958550357b9a7.nq.gz
│   ├── 93959600c753fe250657ed04efd0eda865ff8768.nq.gz
│   ├── 93fe449d943b36780341ce00638c94eba2e1f37b.nq.gz
│   ├── 98967438f8103b31916b92577dcfb93bc272a249.nq.gz
│   ├── 9b0f8ca657a429d92c233aaa404d9637d7500cc5.nq.gz
│   ├── 9ff31ed469bb95e40116e66ad249c38770ba3735.nq.gz
│   ├── a0130f304cd0b39f02f3b155897ff8d92b13126a.nq.gz
│   ├── a1dc3d2e5a895b5d7e016cf8ed7018bd50ccee90.nq.gz
│   ├── a394efd653554ce687ab8f0c908238bef4f27dee.nq.gz
│   ├── a46845a6d35cbe2a6d79360fa962220f8d340de0.nq.gz
│   ├── aa77b39c0df7bcf0c8200f1282b165dee493ad73.nq.gz
│   ├── ab357952c397f47898863e8405c4958bb8de82fd.nq.gz
│   ├── adbf46ef7a6e86181b5927002597ef786add5bde.nq.gz
│   ├── b293aecb87839015f8ab37943afe71c2f8904871.nq.gz
│   ├── b327fcc29eb44d7fe68be35da25bafa0e1d6feba.nq.gz
│   ├── b354be1874dad47a6bdef1f43cf84e2be4197856.nq.gz
│   ├── b4163668a33ff705c28f5b103b727514161e5652.nq.gz
│   ├── b4532882149acfa85d74840784052ddfc7061ed4.nq.gz
│   ├── b4dccd8bd2eedeb0d4a5bed0543539811edab3cb.nq.gz
│   ├── b61fca6ea9fe8aa37acd143784a3d76e90a58b9f.nq.gz
│   ├── b850e137eb1b020c36c9e2f370934e50b188afe1.nq.gz
│   ├── babab6e12b4bb8cfa74a7edfa5e56cd1b3e2bf6c.nq.gz
│   ├── bb4da40c65b96274fed8b1df2c3454db7d6b5f8f.nq.gz
│   ├── be8cf0204969a6c973f442b383d8e425d684e826.nq.gz
│   ├── c0a42186d982283add95b63d99fc118e845bcf9d.nq.gz
│   ├── c1c0826136d14e70bfde68f4b4f8a1e61d9917c4.nq.gz
│   ├── c2ff17c915481fb556aba6ec816a9e08f519c515.nq.gz
│   ├── c65a7b2c6143404e1a9de85ea54463509c5dcd8c.nq.gz
│   ├── c8c10e30e2d7f9bde33105715b04f5251d5c1950.nq.gz
│   ├── c946b8f79deba324a88ab0d61a322942b19fa764.nq.gz
│   ├── c95ebefe07b7d8d9fd0936a014679d07102cc270.nq.gz
│   ├── cd80301dab145a37236ab153bd1bb19c0cdfdcab.nq.gz
│   ├── ce27c93aa1ea8a667a4bdd894be6db1d352ad7f5.nq.gz
│   ├── d0b3a5c63bc7c8bb022ea2be41275cb921e8755d.nq.gz
│   ├── d2eaef8ea3754d8ec0695e328907a8d62553de46.nq.gz
│   ├── d4a24572427098354f723fad5e737ff6dfe223fb.nq.gz
│   ├── d5233419535a2821277d98ce151c0900a27bec7c.nq.gz
│   ├── d60cb2500e3384ed585b91133fdc9b6d8fbfe517.nq.gz
│   ├── d6e407a400a67020d801e6c27a3c32a2ee38f30c.nq.gz
│   ├── d85ce6546a2ee1d73abb8724f130feac99a996c0.nq.gz
│   ├── d9ce3e86f788856e669a597b15939142138fd230.nq.gz
│   ├── dbb9015b0fc9fa93483ba77cc303b793e86c36fc.nq.gz
│   ├── e0a54c2c2bc10f76458c42a43de0970a9251759f.nq.gz
│   ├── e1b3ce52fd6d922f247cc0c48409e88d5af3f204.nq.gz
│   ├── e5c758afa34c534a251fe6d164eb81a6f3a3230b.nq.gz
│   ├── e640c157e8f5581953c518df0611a423225ef598.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7883dc886b96d078883e01aefd16792133e204a.nq.gz
│   ├── e873b06f92f2f794946be9197b0a935cc02d01fe.nq.gz
│   ├── e96127cc9978c014b76e8c8ed138b7d6b52d9df7.nq.gz
│   ├── e99a60879920b389799fb3a0baf1fd864ee0bccc.nq.gz
│   ├── e9eb6fc59b50654ddbe19ed56ad8c0abd1b8efef.nq.gz
│   ├── ec6f4061328337edb130b8298d2b063445e0af45.nq.gz
│   ├── ed236e4e3cee3105edd8d2c0bcee8e1ce22d4614.nq.gz
│   ├── ee26f0a514083ac9848e302d5dbc5fcdaafa1d03.nq.gz
│   ├── fa836ca4b4d836a539f7e6d0aa2a012e6996edf5.nq.gz
│   ├── fc29a0b6b7d828b1b243efedb17b89ea02e2c602.nq.gz
│   └── fd538c93764347a496ba6cdb0859cd8ffcb02044.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 06124f2a8f04f9a026265bbca931dfdf9eef249e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 161 files
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

[NousResearch/Obsidian](https://github.com/NousResearch/Obsidian)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*
