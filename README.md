# Repolex Knowledge Graph of paramiko/paramiko

RDF knowledge graph data for [paramiko/paramiko](https://github.com/paramiko/paramiko), parsed by [repolex](https://repolex.ai).

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
rlex download paramiko/paramiko
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d87f9c01c158588fe3ecb635ca7c0d7c0c1a26cc
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d87f9c01c158588fe3ecb635ca7c0d7c0c1a26cc
│           └── chunk-001.nq.gz
├── blob
│   ├── 033f8c536f5a484f6143b9936da9ad4081be25d1.nq.gz
│   ├── 03e836de8c56e24b87afd3f32d8554233b4a6146.nq.gz
│   ├── 066cd83f03297b53169ffda2db8478b85d89f842.nq.gz
│   ├── 06f733fce80566a913ef322a0a7b52f550752e38.nq.gz
│   ├── 07eac6959314ba49147866df04ad16db593455ad.nq.gz
│   ├── 09b69c8ff340a14eaa88d4a91eda7201ebe32ab4.nq.gz
│   ├── 0ad0535a39f1e0937184ab5dd2eb0d17c6779a70.nq.gz
│   ├── 0c0372e9c38bb4400983471fad0345f6f9f8257d.nq.gz
│   ├── 0fe2b34862f4c950250761d60012fc194d4e7017.nq.gz
│   ├── 10541993a2fb37d02c4dd4dc32a4e8a314ca33c5.nq.gz
│   ├── 108dfa7263fdd7e9a0f0a7a17d4cc28d81b3405a.nq.gz
│   ├── 14d6ac12be8d7a027e14b19a9587cd78d7ec3a58.nq.gz
│   ├── 1628986a3761f5248123f0b1f88d622ceaebf47d.nq.gz
│   ├── 16b451a2262cd1a1c36ab97222fac7f27e93e72d.nq.gz
│   ├── 172ee116d2cd8274e21e65bc574079d396ad0612.nq.gz
│   ├── 179f0b7f60505e317a90c303fa31d30e362dd6fd.nq.gz
│   ├── 18ff4843461319b2cc8795c661d8b1ac4cee16b3.nq.gz
│   ├── 18ffbf868db5fe2e33858d95f097c5366d59f880.nq.gz
│   ├── 1905c0cc5b6831a6e9b9cc0d3018913c19ace952.nq.gz
│   ├── 191cebb563d304cb6888fcbd1aa4e35f836170b4.nq.gz
│   ├── 19743ad6f01c28a626b70c73e0bd806b99671588.nq.gz
│   ├── 199f3ecc14fbf2d313c53f9b8c43e9450848e78f.nq.gz
│   ├── 1b135d69f9cb342fd6a0806f2bab13d0890f4235.nq.gz
│   ├── 1b8d133a57bccfab9b3bda29ec2921fe38892885.nq.gz
│   ├── 1cae2c03b1b2b6b1d6a71fd5d5afa576447229fa.nq.gz
│   ├── 1d7a26d6dffa660c8cf6af752ecb7f26ac638133.nq.gz
│   ├── 1da1016e607ce0a4de9a21c6448ea3a63c322395.nq.gz
│   ├── 202815f8df963fb38bb417c6aa4620ed2cfdded6.nq.gz
│   ├── 20c16d1619515a104b67afa88373e83fa3dc9aeb.nq.gz
│   ├── 20c23e42a0fac7e215e1c1f23650fae3a85b2ac2.nq.gz
│   ├── 20ebbc868968c28ac8a1f2155b7572a693917589.nq.gz
│   ├── 21e927fc8f2a93bfb74bee2ceb6d56ea21081c34.nq.gz
│   ├── 22c2c9c32e4ad48127ef9e0493458e6af47ef776.nq.gz
│   ├── 25326caba3da41e736b9553359b6ca5098f73ad6.nq.gz
│   ├── 2eb9ce246b1979167ba30e08ffc91b414f01ae50.nq.gz
│   ├── 30ce38c88fe3a4829c32b55f283e2590783df113.nq.gz
│   ├── 35e2cded5b22e6c8594262ac3b08d186c31f03ad.nq.gz
│   ├── 35e3b0e2605759abc921d044b4c1ad6145100c39.nq.gz
│   ├── 3617d1369de2760dcca8ac02312c35945a2ca23a.nq.gz
│   ├── 3c5f961b34d64d78d6d38a42eedbd1d20c252b5b.nq.gz
│   ├── 3d53cf48ae62323d3380294c521367da5e99f5d0.nq.gz
│   ├── 3e33781b3a153b1e2a5a3e69327ca9b67a9e233b.nq.gz
│   ├── 4089203b38000015f676dd2ef3cbc573163059cc.nq.gz
│   ├── 40f2d1afbcfb541c01da8d5683a980ef7cec3172.nq.gz
│   ├── 41ab9cc4aa97c2e45cc2230edc2b8cf1d5d0bf3e.nq.gz
│   ├── 41fab46bd0dea5d5dd53c321d700a66274342523.nq.gz
│   ├── 427382ba0c64604e14e67bdb6486daea2d2d8d4f.nq.gz
│   ├── 42954574be43e801cf787e0d58b419e350047a9f.nq.gz
│   ├── 42d447340d0b2a88dff3b5f7e97beb6d80c48f77.nq.gz
│   ├── 4600cb9db7ff35c33b65945479d84c9c44f012cf.nq.gz
│   ├── 46238251b65fa200c5c017aef8f78ed009f6161b.nq.gz
│   ├── 47fe961cb0311506c198a35b39d49b8f88535876.nq.gz
│   ├── 483823d5ee772035eedc22039004db60ac49d84a.nq.gz
│   ├── 489b14e7d7c733613316d2cd8b88519162ce93dd.nq.gz
│   ├── 4957461de725df02520bfcd5323fe03f3046a141.nq.gz
│   ├── 4a68d3814bf9e8dfba8d584955e5e0dc7e68f65c.nq.gz
│   ├── 4ae3f737be61faac943ea0a0dabb1cdb608c8958.nq.gz
│   ├── 4b350b0b0bb1dfdbe8c6baf14020f645e3256c28.nq.gz
│   ├── 4bda14a21347406d26f472e3d1f7b3fa9e206010.nq.gz
│   ├── 4d5b2e346e960e4ca0a898f11a1694edb6a0bd01.nq.gz
│   ├── 4e01415a824a4e5f19e523c1b339ac9d86802b40.nq.gz
│   ├── 4e5dab043fb76ecf3bdd64546f36e25c0681b30f.nq.gz
│   ├── 4e64eef26a7e343ce77f10b7acf28cb9ee30b5a0.nq.gz
│   ├── 4e9ae8a5d5b83df4839b3c6cd4dfa49f8f4c4aed.nq.gz
│   ├── 52dadeae9ad03a1ee1262915cb0a6855a6deee76.nq.gz
│   ├── 531112cb389aab89638da2d6b7088d152fa0179f.nq.gz
│   ├── 53129721c2a4c9a310aa0ef2c44d64d1dd329efc.nq.gz
│   ├── 5392f5b92116e0bf0fbee3ddc9d9c4aa9faaef2e.nq.gz
│   ├── 54d87c59860bb40c79b6b3dc05853d8eaa293eb1.nq.gz
│   ├── 5674b4423473e4ca84cc57b12f891b4e40bc1a74.nq.gz
│   ├── 5986b930f206fd0684c1887dc09dead267c4445c.nq.gz
│   ├── 5b2440c0bb6af2adc2778cc81f590523fa390242.nq.gz
│   ├── 5d58089a6bc276af607c02a9995e01e900c15902.nq.gz
│   ├── 6077c10327e29e9ba7f89d83206c2b73081bf54e.nq.gz
│   ├── 614b5898ce1bb468cf2704dd6539bc9b11e0357f.nq.gz
│   ├── 61ac1b199d7c99614251b10042790eb209f993d9.nq.gz
│   ├── 62a147aa21d643c9160b7270bc0a764dfa15e71f.nq.gz
│   ├── 63634039c8bad349fd714b635a6036751d7d09ad.nq.gz
│   ├── 645ddf643d869e14ef4081dc22db92af760c284f.nq.gz
│   ├── 64872dc200adccf3b6631391b66bce0a2ed9bc26.nq.gz
│   ├── 65944fad3cb8418146b6b706a6efd9e161b08457.nq.gz
│   ├── 65a11ab4f20510d4f6dea65a158c4c502f4745cc.nq.gz
│   ├── 6623553ac32321e806fe1daff3a4fb04a0858158.nq.gz
│   ├── 663c58ed4918a71546a969e90a1bbe1af831603f.nq.gz
│   ├── 67eae0da76c80c5ad911e73dfeab826b640c7e31.nq.gz
│   ├── 69cb76019a474330e99666f147ecb85e44de1ce6.nq.gz
│   ├── 6c8d3fac5ede06328fb4eebf8cd71e7840308710.nq.gz
│   ├── 6ce9d8017cef5042b4ee0f471763b94c0e9824aa.nq.gz
│   ├── 717686ad4b7806c99892eeeb867ce1e6eb9e031f.nq.gz
│   ├── 72b5db940bfc8f2527e9a1b3d0d762167dd064e3.nq.gz
│   ├── 737345e8a9c5dd0db3d08341ec84f0162bbcd985.nq.gz
│   ├── 7421a6c2e28dcbe28a4147607e4c2703b510b367.nq.gz
│   ├── 7487ab66403a8ab65ea4958491fa02be3707905a.nq.gz
│   ├── 74b7501e8c1f896c06e2383dce5b8a014999a073.nq.gz
│   ├── 7673e0a094e894fc3a13dc86c1994b3c3ad58cf7.nq.gz
│   ├── 770652fd16d9b7001c3b381974bc700763e52bb0.nq.gz
│   ├── 771304951ecb76d8e4f2f363e509570f283c6c6e.nq.gz
│   ├── 7785f6604eafaf0f853fda8d570f340b92dcc9f4.nq.gz
│   ├── 783d939ebf6c8a932ecabbc9e6b6120745c8a31a.nq.gz
│   ├── 794ee9d55db0a082af826ba6c1be31823e82de17.nq.gz
│   ├── 796bf4176023c14de7da410e4f25d0ea46eb8cdf.nq.gz
│   ├── 79958e6d91dfe0c36ad2bbf6107363ccb47f97b3.nq.gz
│   ├── 7b979408fd056da410d09a8ba794cb29f78ef87f.nq.gz
│   ├── 7c5d3f3ee114890d999cb92d3dda855353902cf6.nq.gz
│   ├── 7c9d9fd1fd45fcf10affb2e9c45671baa639654c.nq.gz
│   ├── 7d1110c370d544b3e86e1b21f56c2f90f0c92b53.nq.gz
│   ├── 7fd274bcbc1c60c0a323ae4982ff73063e5a40ee.nq.gz
│   ├── 80ea2f94e5c4a35cc019d3045a7f0537a5b05e36.nq.gz
│   ├── 81332fe84033bbe930f74a5db6f5f97898509df8.nq.gz
│   ├── 82f90663e55b67c34de48551f1a1760e493689a4.nq.gz
│   ├── 86cbff5d80777d1914f182dfd3ea235e68be39fe.nq.gz
│   ├── 887b51c6e5bd203aee768c7c7b483ca058b306bb.nq.gz
│   ├── 89b3d9a99240142bf99042de217d7e22e130bf53.nq.gz
│   ├── 8a160ce2897d9e2cabb24d63248ca4044713bbcd.nq.gz
│   ├── 8ce93829aac7ad83314ff7f03088572321cfe1ed.nq.gz
│   ├── 8d4dd2dd346c38846d6b0f7b21d5ce4e803788a2.nq.gz
│   ├── 8d531e01d8ad542fd0801e011cf79a933b71401c.nq.gz
│   ├── 9015a77c8a8593b7821b297889cf0fe9d1762b78.nq.gz
│   ├── 90c7ab0923bf0c41d23c83f2157f57d4777b369f.nq.gz
│   ├── 91fc9c0d51a2904927ac5ae730f80cd91ac2d1f5.nq.gz
│   ├── 92c3875f6083696f7f3790590fbc402c0a0d2731.nq.gz
│   ├── 9344486b08b2787ae8f237c83907ca7eff8dbd02.nq.gz
│   ├── 937c910e8ac6c121f5e6f320f4ba38acb82b248d.nq.gz
│   ├── 93fe3beba2dc69480905fab938124cc81bed532b.nq.gz
│   ├── 956eada21d350186818898a1432588fa238163f4.nq.gz
│   ├── 9a2b1d82f1d9f4eec14d1a633a9d8ea8b8bee236.nq.gz
│   ├── 9b56bc0e351b12df4d14361e28a84254e35a6f55.nq.gz
│   ├── 9c1c3bf31b68a165fa36a6fffd358c305f878b24.nq.gz
│   ├── 9c3bb3aae306ffe30743d441a57d0ea694dd8aba.nq.gz
│   ├── 9cf0f34b2071eada31c35a709bc2f0e2a37f1050.nq.gz
│   ├── 9fa0f0ab5496ae1da8f1f0dad3ca7b2b051d2a72.nq.gz
│   ├── a36abb988e9a1773064743f1c459052570ae5d3a.nq.gz
│   ├── a37400132af324039df7ef93ac293d4304c698da.nq.gz
│   ├── a8d619e5015dc45d5e4b4639afa9c183fdf230ff.nq.gz
│   ├── aac8d123dd3b4930791832c641f9445cd419a18a.nq.gz
│   ├── ac3bef271ec6399a8beacbe07ab1a169a3890dff.nq.gz
│   ├── ada9dc1fd6c1ba392f624adff5067ecba4485917.nq.gz
│   ├── aee21c21ef108472ac0564c575ed99c248b98dbd.nq.gz
│   ├── b201812fd2b642e3fe8c30515db897b650400740.nq.gz
│   ├── b20262249568c97ab2381e53909d3585629a89c7.nq.gz
│   ├── b20465260684008413600f10509b00fa80739c04.nq.gz
│   ├── b3528d4ebdabdf2375e574920872ed11fdbff828.nq.gz
│   ├── b57149b75386cb1b60a99730a238f9e54b7fbf9a.nq.gz
│   ├── b6bce36c736e50f8fc02b975d5cc3a4c723e0c56.nq.gz
│   ├── b8287f5de3ef2e207d84cb9853a82134a25c0d29.nq.gz
│   ├── b87dc90f54161374a7cf968f236b3a5a1c195959.nq.gz
│   ├── ba79c51e26b1011e7477afd0086917d7a4310bbc.nq.gz
│   ├── bb50696ee1433417fc502197d0d1685f5a294e0c.nq.gz
│   ├── bc4f4eee64467d5760c8f23a209ef9f67a623505.nq.gz
│   ├── bf48edac05a301034c45b1a8be02fbdfb55c7ee8.nq.gz
│   ├── bfa1e150b0c83243c50ef8ce4c64732765c54b48.nq.gz
│   ├── c19279c0236088f1ef109288e14cdeb82bccccb6.nq.gz
│   ├── c224937e02dc8f47711fd11643868946428646bb.nq.gz
│   ├── c30038034cc02324b49bcc8a3cc0f7e7e02a0c87.nq.gz
│   ├── c488e2e072cf414d6c0f3b28b394f63a7365489e.nq.gz
│   ├── c74695e0ccc26bbe60f2b64dd3d45ba00b179671.nq.gz
│   ├── c927de6578ec2a4a4fcddda5c4de8a20802455a8.nq.gz
│   ├── cdfa2032d327a20af3844700d08eaf9e7d8adc99.nq.gz
│   ├── d12bef0c5a9d251034217ab1e404412f43023492.nq.gz
│   ├── d178aaaec44fb40099d018c7dc1375829cd50ff7.nq.gz
│   ├── d6c20928d73bb159eb59769bf0c82d14890bd5a4.nq.gz
│   ├── d93b9ff3beb75c7a233ccafc1c2f259c59dd0838.nq.gz
│   ├── dc00054c2e596d45b348d984bb9a9e182e54717d.nq.gz
│   ├── dc5103c373a9d0539ede52087c7933881a26f887.nq.gz
│   ├── dde9f77bc004a9a95baf5105b8e3be1edc8843ff.nq.gz
│   ├── df66f7dac520c115204e7d21a104f22b0ab803ea.nq.gz
│   ├── dff7d9088e69beee9512b4000b0b271fb6896a47.nq.gz
│   ├── e2b6306cf50231ee6021915b7c5ccf283aa49c2a.nq.gz
│   ├── e480446f7edf7034b925ebb0119d7e03ffd16683.nq.gz
│   ├── e4a888b3b513147d035e5fccd0fc9a2822f81688.nq.gz
│   ├── e528dc64d97b70229ef120458204f603c386f702.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e69fbc6ff1a801327f194e9f4f1bc7f7007e48b2.nq.gz
│   ├── e71526f65da0246cdddd6e32974699f0349b993f.nq.gz
│   ├── ea854544a5e20dd9ddfee287b6baa2c08b9d23ce.nq.gz
│   ├── eb7910ed5fc7b8c1ca8efd9069b86d5b3a3339c4.nq.gz
│   ├── eb9f94c20ace86e2a7c32fe90d876af99b394ed2.nq.gz
│   ├── eba33c1487fad546bf98b187c4b426957116d284.nq.gz
│   ├── ec8d13ee34f94f39c0be5fe16d30835bda986d97.nq.gz
│   ├── ec985f6aaf1cd508e315be4e2e872f23e982fc88.nq.gz
│   ├── edffd3344e7ab975a5c144a363bf4c65f988ed1c.nq.gz
│   ├── f01ad972eb2b0b0e9568bf725d83e25d3d5c316b.nq.gz
│   ├── f178ca458cd4fc8cc4d78fe763195e6b4db1630a.nq.gz
│   ├── f1de4b00581ce00dda9d3d91660fbcaae04a0f21.nq.gz
│   ├── f2c93ccf340c31b56bb46de7159705f5c9b27d0c.nq.gz
│   ├── f3f56b707d7b54296fdc1bcfc2d01878406cbcfe.nq.gz
│   ├── f43975d29e1cb579c2b5779675465e33b1648355.nq.gz
│   ├── f50e9c53859bb938cbbed9ae5302bda46d6a18db.nq.gz
│   ├── f51e190a1f80179a16cf70af1071077cc4806b97.nq.gz
│   ├── f6f9cbd11618e4622dd9c513ef93496304ccb2a5.nq.gz
│   ├── f7609c984026e043e292203b47540d38a35f8339.nq.gz
│   ├── f8f0117ce5785b892910d01d06dd010f73643aa8.nq.gz
│   ├── f9dc270129b0da4bdb352f8b63b0435a11a66f60.nq.gz
│   └── fe4a276c9c4f499035e51e365b108ccfd8d03cd0.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d87f9c01c158588fe3ecb635ca7c0d7c0c1a26cc.nq.gz
└── issue
    └── issue.nq.gz

11 directories, 200 files
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

[paramiko/paramiko](https://github.com/paramiko/paramiko)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
