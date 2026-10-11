# Repolex Knowledge Graph of litestar-org/litestar.dev

RDF knowledge graph data for [litestar-org/litestar.dev](https://github.com/litestar-org/litestar.dev), parsed by [repolex](https://repolex.ai).

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
rlex download litestar-org/litestar.dev
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9e5f55dffc05b19887f3eda923195b5652c44cb2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9e5f55dffc05b19887f3eda923195b5652c44cb2
│           └── chunk-001.nq.gz
├── blob
│   ├── 00d4fe660df779ee1756ccc53d535028ced6819a.nq.gz
│   ├── 05155f370d23a5b879feff7aec3f721b1d99f3a7.nq.gz
│   ├── 05963839f1ea9318f2d437a108cf6a010da56f2d.nq.gz
│   ├── 066130ac194ffefd313addcfb065c72c5540318e.nq.gz
│   ├── 075315566391c074648f53f004efc48319a3148e.nq.gz
│   ├── 0a774e71ff8cf0cfe81701ff5c7d49053e9e5aa8.nq.gz
│   ├── 0ca9d4ac84063655fbeb6e13cce0640acdcf51bc.nq.gz
│   ├── 0d26914aa004ba7858e128c4d6c59dc8a86cb1b6.nq.gz
│   ├── 10a6e09991c063d22f699bfa5476abf83806a406.nq.gz
│   ├── 10f8d941db9f9e1458623491ec9b44008bd4846d.nq.gz
│   ├── 17cb34e33e2190809b966c28f5678aa077d2a937.nq.gz
│   ├── 18993ad91cfd43e03b074dd0b5cc3f37ab38e49c.nq.gz
│   ├── 1bd3edaea4e6754ba19c50ae285f4a53b6724808.nq.gz
│   ├── 23071cc3017d6c80211c041df373be178e2030cd.nq.gz
│   ├── 248c431dc949527c812b7d2aee41f2d5fcb5a89a.nq.gz
│   ├── 259944bf6e028c1b21ab84d6a72d4c9054a1e950.nq.gz
│   ├── 289e56209b3dd56b46330ca6581a0f6fc0a5ac73.nq.gz
│   ├── 29377a8c5de79ac3fadfac96528072c7393c2b2f.nq.gz
│   ├── 2dae59f9f2f8cd88aaefb0fbfd73eb5e023c241b.nq.gz
│   ├── 2e58493d2d34790a52b6f8e48eac2f4612ccca58.nq.gz
│   ├── 302c1c284b71e8141380e048f63947b677590671.nq.gz
│   ├── 307b2134b94b63c404ad3f3254b768ca337c7a37.nq.gz
│   ├── 31c0d25cd448015d4d8fc994b60642362ea435d1.nq.gz
│   ├── 32f4e7e99d2df766fffc58417037ce6d26fb96dc.nq.gz
│   ├── 34473bbc5b2515e972d5fffd2f8480aa3a3cec22.nq.gz
│   ├── 36761b15480b1e0375e0212b56db8ab80553acd1.nq.gz
│   ├── 36ca06646e9e42ee8b5e9027e042958307c0ec5d.nq.gz
│   ├── 3a80a88d704f61b7b21a4599fd47fd49c447f0b3.nq.gz
│   ├── 3b3f9d2832481f8001adc3d0be9dfcf547987423.nq.gz
│   ├── 3b7c94df10444a1e8c2fd2d92dd18aadce83d444.nq.gz
│   ├── 3b85510f8663c372dbad54c6aa2fdc90d3bcbe18.nq.gz
│   ├── 3bc0e35b758ed60a5a41b4fcf19baeed4dd70553.nq.gz
│   ├── 3dcb95d68279e6f4d42cfa37487a1f54fc2c53ba.nq.gz
│   ├── 3f8fd79913422d880de2a4022cca404b97a5cdda.nq.gz
│   ├── 4013d566ffde013c51cb3afb3e2d6527bfef5eee.nq.gz
│   ├── 40c5be3f64902649fe9d1b7522d5da40e0208545.nq.gz
│   ├── 41103184b810f3890c3537ecd07941b41fb5ee70.nq.gz
│   ├── 412751a3e291179aa73bc7ba80e15e75d25691b0.nq.gz
│   ├── 41607caf331ba2f4087a15145260bf33697d4d9f.nq.gz
│   ├── 425fbbf910b6b0b6a0d1b7dbeed295ddc03f907a.nq.gz
│   ├── 42955de09c88cee4b08f3eea5c628991673a78ab.nq.gz
│   ├── 456db1d81ddae18d6fe8db24261565e92a9c7ffc.nq.gz
│   ├── 458529f401776b7e141482b24e1c33d71523bfd3.nq.gz
│   ├── 45ba963e02d43fe8f436b2f3f8752a15e23449a7.nq.gz
│   ├── 472d3fa9c3182ec2c04ef39db75de89478d0e8ab.nq.gz
│   ├── 47ddc7a5715033de5a6a012287fd73c66feca7a9.nq.gz
│   ├── 47e9a0176c44dfbae206b2bf13d619aa5f8a7f6c.nq.gz
│   ├── 4885eb55d0b19b0a5d875401c5d4b2febd4ea7d8.nq.gz
│   ├── 4a587893e624565660cb83a59d3c7967a448fc72.nq.gz
│   ├── 4b876eaaf6d1bc6270f014b35021aa6a13bb2f91.nq.gz
│   ├── 4b8c55f5bc6c4a9356d92e3291a7dd3eef085ddc.nq.gz
│   ├── 4c3ce12c1d1b75c7e1488f69bb99f34f4d75f20a.nq.gz
│   ├── 4f356d7285f90443baea80058079da8251ba039c.nq.gz
│   ├── 540783f005d0723df3ca6122553b8528d27a2650.nq.gz
│   ├── 54903aab2d4812aa25c2e4b3db99fca0d530a946.nq.gz
│   ├── 5afd862066b94edab58f599bc1ce061fc7b135b7.nq.gz
│   ├── 5bf29244f97c1ceb5c8cc024b24bbcbbc197af11.nq.gz
│   ├── 5c260db3fb54a5e5a2a978c490cb1b51fc4fd4b7.nq.gz
│   ├── 6076e387f03e8c6ef04cce743fb84fb5ed8cf568.nq.gz
│   ├── 634a1e336d25953c39506cad26350676124caf32.nq.gz
│   ├── 642ff4ae964b92ccac401b3903256db44678405b.nq.gz
│   ├── 6529ac4bd72b2e799e428285c8c963e5e586910a.nq.gz
│   ├── 657893972e9ae00a16773f319a72a880ab5a7d54.nq.gz
│   ├── 65f8302ae1f68632dbd7458027f436ba94755d04.nq.gz
│   ├── 6646abbc78f0dd9ae9654b9a48e9f70cc600f1a8.nq.gz
│   ├── 66977ffe4417eb6f2e88bbf5142039208f34fb44.nq.gz
│   ├── 68ef73eea73f7f96046bb3a16f473405abcd55db.nq.gz
│   ├── 6b2260fd93b81bf107c643bda25bb53d1450da81.nq.gz
│   ├── 6c243e8471a49147d26613d82e0e0b15472ddc1a.nq.gz
│   ├── 6e5153c7d07a332c9eb9b777b82cb9b890c08e80.nq.gz
│   ├── 7175975ec14605b5026fdfebf61069c8296c5e34.nq.gz
│   ├── 744602261344c09faa3670acd2a9e2f621cf49a0.nq.gz
│   ├── 773d0b7d720796d9d23977d0005e7d9e6cacb77f.nq.gz
│   ├── 774852f8ab84dc61eec4021d50ade9fb5506d0e4.nq.gz
│   ├── 78605d4871573268a870845ab5f8800f41f4e1c3.nq.gz
│   ├── 7927a406e2171fb1191303378a21887c5acf5220.nq.gz
│   ├── 7959f6defef89c23cb159aa4e066028995b18d8b.nq.gz
│   ├── 7d2a228b78dcb69b9f0ddbe54551bc1934b1d352.nq.gz
│   ├── 7dd8aa4d14f5fe37e4993724b065a51ce1bc74b7.nq.gz
│   ├── 80671396ba940ec2403d4c64ef996c2a88929269.nq.gz
│   ├── 811c5f54ea67d0d53e85d39ff7af7acc299eb5ae.nq.gz
│   ├── 83428a584f2294968e34cbcfb61273f2539d6668.nq.gz
│   ├── 84b70d4e4676d0d0cac12dcfb3821cdc00afa5c0.nq.gz
│   ├── 85d466e3a78ab7b3971c024961a94f0c765c0e96.nq.gz
│   ├── 864a5985ed804c999f7268f9ef476b69c2df0aa4.nq.gz
│   ├── 8878bf5e2204fc0169628faa0f2b8d0f27a88677.nq.gz
│   ├── 89a2a35ddedeeca4b2aa1ddca56067c01db73250.nq.gz
│   ├── 8b63a1d39f5a0ea7e2c8eff6865de21b7f989b8e.nq.gz
│   ├── 8c041daa6635258224d944f8f7acab540341cd85.nq.gz
│   ├── 8d78ce0c5802f96df5bbe7b37959f717aeee4fa2.nq.gz
│   ├── 8f1ec7ef117bcbaef6ff473aea25180dd0b8f0f7.nq.gz
│   ├── 8fad6353d150879bf31738b2b23c697349c2cb26.nq.gz
│   ├── 9136880d8b74a4ddf9f467d1c29ca1ea51704ecb.nq.gz
│   ├── 9148aa84f6da1a90c83830dafbdffda63bfd59fa.nq.gz
│   ├── 93c21db39ccef0228e6c71e6e75ea56d6debd480.nq.gz
│   ├── 98b0ceb1ed769fa77a0cdcd77d39de597227b920.nq.gz
│   ├── 9a4e456538390a66032cbf5b48a59a0dab10bdf5.nq.gz
│   ├── 9a613a81170c9d3346e1bdb35a60868f607b7cb2.nq.gz
│   ├── 9b1b977fc00dbaab0609a556b2b6f3ff6baf8328.nq.gz
│   ├── 9dd5a2ed4966533bb3a69cd3433f5f1fbc2c9985.nq.gz
│   ├── a07969441f7ed2bd9cf0db594860508b664da67d.nq.gz
│   ├── a0c5903906efac5abdb3e6319169cf7402d1d5f9.nq.gz
│   ├── a14a1ad295de446d63352786ae2b8f02284bbd10.nq.gz
│   ├── a3424435da166432f0ac3ae1137fb7a45e17eb56.nq.gz
│   ├── a45fd52cc5891570d6299fab38643103c3955474.nq.gz
│   ├── a70ad82a2963d8fd50e11f71a7a9d2108af72e75.nq.gz
│   ├── aa1f9f420e9487b9d80eb70c5b9d63be4833307b.nq.gz
│   ├── ab52c0d9d0090bd2fec981f4906f61ebdc25956c.nq.gz
│   ├── b2193bc67909a51b108d6999ae485cf3d634a021.nq.gz
│   ├── b3e95f0ca9b13331e10d6ec8d28add6898e18cde.nq.gz
│   ├── b9a78389a2aac8896ea5c27f68655d8977e0f296.nq.gz
│   ├── ba859cd731dafbe0336c230685dd4fa6ec264d1c.nq.gz
│   ├── bad4f2a1b338be658983ad4f84b54b981a35a6ac.nq.gz
│   ├── bd47976c389d168f25b157a6a4e498aafb0a70e9.nq.gz
│   ├── bde33de9a5d82fdf0f0b5566ccf467c08c8f0948.nq.gz
│   ├── be225387749b118049e44d531e5fedb7417b51fa.nq.gz
│   ├── be458c3ca09e6a5afbde8270260a0faa9048883c.nq.gz
│   ├── bf30e67a0afc7802d630382e65ba61222b5fa85b.nq.gz
│   ├── c034af89f59cf937a5004abda8b5a7f8f9d4befb.nq.gz
│   ├── c1e42792a48f8e493e715d89c5b2f5e02116bf36.nq.gz
│   ├── c23a3de6a95f4b6c3f4d4f2920a2dc11e5d5f61f.nq.gz
│   ├── c3c7188cdcd98be23db6ab6ad0549e695b922356.nq.gz
│   ├── c4d0a0dba3e19b3480862ac874f307a59949a153.nq.gz
│   ├── c5cf12ed978521185e60a9f07d05cff70f65e1c4.nq.gz
│   ├── c6e46e98c3e4b4273da2cac4b3e2b5cc170d7d4a.nq.gz
│   ├── c7a4f6e34ebe77ced990a197cc7a86ea5c569085.nq.gz
│   ├── c7f7a160b55d2320f04688608f03de3114d38719.nq.gz
│   ├── c8083052282d77841d3e22f483d33dd32d787db3.nq.gz
│   ├── cd6168f23026f29895f55a57ba488139b392ff31.nq.gz
│   ├── d05af3ba863b384153640e03df88693ed164b38d.nq.gz
│   ├── d09680dc19e7d2271daeb4db53f0526f61240cc3.nq.gz
│   ├── d0e5a7c73972e91f3dab4935f2960ccef11aa3fa.nq.gz
│   ├── d29cc8cd064a623ff6cc00012a043f2d3780ea2a.nq.gz
│   ├── d47248d535b24a07677b1d53398018da364e9eb2.nq.gz
│   ├── d4c467eb8eeb0ee5dafb4c8d135048157eabc3cf.nq.gz
│   ├── d9a2bb706ae453f27a5f7e15f6da0100bec01325.nq.gz
│   ├── dbf3672eeb47115606013db67a0ba67771e581e0.nq.gz
│   ├── de11c17725e490d290f2ac9229aaa97a785c68de.nq.gz
│   ├── de1c66836b6828cbfffbad30778313b8fa082b0d.nq.gz
│   ├── de400867a0ac8afef3a09dc3cf8d2efc7cbbab38.nq.gz
│   ├── def953736154a4cd574bfc0d8e267df3a8130336.nq.gz
│   ├── dff6c651c88d0d8d4bcf04ac9bf8e300f9ac8954.nq.gz
│   ├── e341e0d374e9da55a38876a32c9def26484778a0.nq.gz
│   ├── e56835b150be97a32c5a76dca722b7c760ed7a41.nq.gz
│   ├── e8b2246c785e96f4ca0b2ac27e1df0802cb19284.nq.gz
│   ├── e8ca785af5ecf78a995a8eedb4f58270eaed0630.nq.gz
│   ├── e93925469e5d3928b15b8c25166573b8b9aebed0.nq.gz
│   ├── eb85d2bb863931540abd8e08fd3ecac500bb55d6.nq.gz
│   ├── ed3e92af904fcbd8ceaff5ab6225ee9a49cd8e95.nq.gz
│   ├── eff25b9be15152a1695b25f763e6316b80abfbe8.nq.gz
│   ├── f3ad26bd14364b0400c711895bdf1b2df5ae0a4f.nq.gz
│   ├── f6aee7aef087fb9efaea41a8ad7236187d6d70c2.nq.gz
│   ├── f72c406d6f6f65968350db80b357c5bc263100a8.nq.gz
│   ├── f7592ac560854386750486e3cdf8639826297570.nq.gz
│   ├── f7fa6c490e09c9e4760d72b7c5172884b0e638a0.nq.gz
│   ├── fdf16527f597bfc14380f2ec6d25b5f87fc206b5.nq.gz
│   └── ff6f27ceb10bb9eca804805598918887b872fca3.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9e5f55dffc05b19887f3eda923195b5652c44cb2.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 165 files
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

[litestar-org/litestar.dev](https://github.com/litestar-org/litestar.dev)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
