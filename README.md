# Repolex Knowledge Graph of sass/node-sass

RDF knowledge graph data for [sass/node-sass](https://github.com/sass/node-sass), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download sass/node-sass
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ee13eb9c62449d1e535189a063cbdd15583ebf32
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── ee13eb9c62449d1e535189a063cbdd15583ebf32.nq.gz
│   └── repolex
│       └── ee13eb9c62449d1e535189a063cbdd15583ebf32
│           └── chunk-001.nq.gz
└── blob
    ├── 014b184505d31b7997b4947de6c996c02b2cf1b8.nq.gz
    ├── 01786fdaa8c06315d1cc2d9d5d691e91b98d8156.nq.gz
    ├── 01bdbe25b2abe2262b5ff83a629ae98142b07a86.nq.gz
    ├── 01bdd076a69c4bbd982e66f0489bf41c97cbda18.nq.gz
    ├── 0279f783b9800c6dacd70aa8db8707ff38facd09.nq.gz
    ├── 03042f3e2da838267b61b79e7a7a0e3c42a8fab2.nq.gz
    ├── 03c6307c46ff96ed957415bf675ec209c928cdbb.nq.gz
    ├── 03c7c927daeb3fee5baf7a39e5e64886f9eb1747.nq.gz
    ├── 05b35cd940e8390120b01599623f7b183e7eef6b.nq.gz
    ├── 07785640f98cdbbea3790df56f26c930bc145de5.nq.gz
    ├── 08eada73380a4c9090408f43e4da4bcf1ba4f672.nq.gz
    ├── 091361b8b27dbfac9d5f5cc7ac5bd1b525328ef2.nq.gz
    ├── 09b0e76ca228844daa1dbad2605ab895000dc35c.nq.gz
    ├── 09ca55066d1fe0b7558b234ee74e10ded4f191bd.nq.gz
    ├── 0afaa2e4cb4756f93788552d5870eb9a04c005ab.nq.gz
    ├── 0ba28e20c9f50c82df68cc598df647b66775b0ed.nq.gz
    ├── 0cbd3e6d8ead00fc27696f0795647ce7d757f112.nq.gz
    ├── 0d9189631caa7ebb5d623063229099b645020f01.nq.gz
    ├── 0da6cb958ce3d2c4f2aacea4f66c8e70b25d7f58.nq.gz
    ├── 0dd67b991bcc89f230291c3f8ae04c9dc150824b.nq.gz
    ├── 0ee040ef03fbc50d7bb827b58eb91c650a3bd479.nq.gz
    ├── 0f2fd48d73837ad6a2c7903be1314d7336198fb3.nq.gz
    ├── 0fc11784cc79b46ece258469f341ce892a2925ba.nq.gz
    ├── 10062803ef63fa8376cfbe7c0898932025a3abc6.nq.gz
    ├── 119a5350e4b59937afa8603df473d7510a06fad9.nq.gz
    ├── 129e47c5a0a8d52a342c7cce5874bb44a758521d.nq.gz
    ├── 15b64ba09bb6542ef497328de21da43d2d977281.nq.gz
    ├── 15cddace2e06dadb10964ae1bec7a1f4471069b5.nq.gz
    ├── 161e689a975a855ba6189cbb866089ef2d09b348.nq.gz
    ├── 164a1c7f19c67f3efd2231753e79696744ef882c.nq.gz
    ├── 1846e9ae2cd2e5edeabea938e6f545b85ae6ac8f.nq.gz
    ├── 1925a6021109ef4a79e7df1ffab16c4a90355d8d.nq.gz
    ├── 19425521ceb3914993c83a283221adb38a15824a.nq.gz
    ├── 197319fb3d81db1b4883caefbbb94a7b6fc819dc.nq.gz
    ├── 1a2818b34542ea7ee5a5ac3d80d167ba69c3fad0.nq.gz
    ├── 1ae5ae4d9e10ddc890666d07653a97c51527b6e9.nq.gz
    ├── 1bf904307ec1e36c8eb77b857153872d5c1589e6.nq.gz
    ├── 1cfd35a4ac50d4da61c591786fd7347b77c4ce46.nq.gz
    ├── 1d71e83fdb3a9f97547f92f0240759e01a9a50fd.nq.gz
    ├── 1dd8b06dca0ff803c426b2849cc05c752a2eeb8f.nq.gz
    ├── 1f0ae603077ab40f6920a0b07483ccae2ee6dfff.nq.gz
    ├── 1f2f86feb54950846ae4796d5b950366ee5d5031.nq.gz
    ├── 23ba360c324e88e705b9ca7adf36d6538b446394.nq.gz
    ├── 23f272ad26683f920bc498daa417126d9585543f.nq.gz
    ├── 24513e4981dc4f3767019f068069b01691d89ad1.nq.gz
    ├── 2496eec0930843ce93560a30d94c577933f22fb4.nq.gz
    ├── 24cab72390508fe69b44954d805c4e9a6d1bfe84.nq.gz
    ├── 2530360a5a700b9fcfb6db1916bea643e31e5a6b.nq.gz
    ├── 25f62e14037bd59537cf3c93e57ae2085c88dabb.nq.gz
    ├── 272671b7c8aec0788c9409a3dcfeaa3d1fffd632.nq.gz
    ├── 275b917b825d9506dff04f27dd58a0348812e7c8.nq.gz
    ├── 279b9e9f62ab5dce3071610f51cf9d6416b28f9a.nq.gz
    ├── 27a496f7a02ee09e68d7104553e07233cdb48ee2.nq.gz
    ├── 27b485aa753f0f4bdaca0a8dfe2d1e2b137e5921.nq.gz
    ├── 27b7e3fa4cfdc8f0a7b0223ebe3086df51506f81.nq.gz
    ├── 281de74d7f8cffa189260044b451299d9e0fcc5d.nq.gz
    ├── 28fe02244e481337022166a4545788d11ad74321.nq.gz
    ├── 2a55ad87e3ef5e2f143a623febfdfda9290d30eb.nq.gz
    ├── 2c6ba3b0a675d8418517046b7bbf6ee64c352542.nq.gz
    ├── 2cafacc27bafd3984cf42e6b37b1dd55f945f07c.nq.gz
    ├── 2d47932387ff58c04b5f7617113083b6aa3e8463.nq.gz
    ├── 2d4fbec9ddf403374839bc9a680cdba4327239cd.nq.gz
    ├── 2d8f83164566cfc842edd2d3c823a5013c933d00.nq.gz
    ├── 2e72c8251ee79e433e3ff5a0e018df81715919eb.nq.gz
    ├── 2f21d7dbfa2e48e47134cd204aee2fb215ff4d32.nq.gz
    ├── 2f67bb37140b8951d6e1c3462a123144d9e655d7.nq.gz
    ├── 2f88d6888049c9a92c50d13dab709e3bf850cacf.nq.gz
    ├── 2ff99d8bd6083a8464af3007b908b0ae9c6eabc1.nq.gz
    ├── 306f5349bee0340351789c98f00ae253137ffac1.nq.gz
    ├── 31004bcf266f282ee486c161fd4535971225594e.nq.gz
    ├── 312e04ca6b43854894f1efad50817880c048407c.nq.gz
    ├── 326f694d5c45bb392a1cca347ca71e5aa72345a0.nq.gz
    ├── 328b2141082711a36b6820102c5d3757f8bb958e.nq.gz
    ├── 32b062794278340e250dd3fd3efb2dc953416081.nq.gz
    ├── 32d4a7c6398a49a342bed41f7527c03d18e0e91a.nq.gz
    ├── 3464c98f622c1dde556019a39fcfbe40a598a230.nq.gz
    ├── 34c591a249bd8326859be10026ef986966d9ce0c.nq.gz
    ├── 3539a9a1677c3a772cb48624fe17efb42252f22b.nq.gz
    ├── 3765616126159973ce7ca6a0c826d3ecfe12d27b.nq.gz
    ├── 37945143f0fe842fcd551c6f6e3654695b93b2ce.nq.gz
    ├── 379ec65778140d2064358bfe31a5475d4cb8d3de.nq.gz
    ├── 38608e1a27a7d59e58d0d7863ff22f874d24b706.nq.gz
    ├── 3884d510e5d1f9755316a278ef355c9dc4b0ea30.nq.gz
    ├── 38a8fe6a044a0239cd08f419a23ce9d057341cbb.nq.gz
    ├── 38c1c08441564ec7d79a10974d0f0894cdf34fae.nq.gz
    ├── 3912c55109481cecde8e31292e74967f50955d5b.nq.gz
    ├── 395b13d2a6d0bcf24b99372e532ed21b352edbca.nq.gz
    ├── 3a68b3a39644e5f0c17925795623e1fa1d5b793b.nq.gz
    ├── 3aa4eb8fec3c31eba6a352f88645ef965945a670.nq.gz
    ├── 3aef2bc728209243aa9c14ab930313e5cc61ec4f.nq.gz
    ├── 3b646d67ed8bdaf72cd38b2633d64cd7cabf0230.nq.gz
    ├── 3bf8f60da7563b6c9a593ad28e227850fa6c43cb.nq.gz
    ├── 3c143b46aea67a9956ffb9efad16b6f3162e8a60.nq.gz
    ├── 3e6d00bc9229a479daed8ebb72548ce042cc3cfa.nq.gz
    ├── 3f7dfae686650760818f4eaa2af90cd07efdcf3f.nq.gz
    ├── 402ae50dd6381b290dd1dccce094db553af92557.nq.gz
    ├── 40358a2c3b13790b35ceeb1cdda91115d493ce35.nq.gz
    ├── 405024e15957822c03e342612cd30639e027261f.nq.gz
    ├── 40ea22ff7e84d06a17e51188c5133f66a621f738.nq.gz
    ├── 414af5e3f8b95869522c8e9c5cd4f55bf5013ef2.nq.gz
    ├── 416507f3c6df7de574b1a15a59488b3a3bf7a4ca.nq.gz
    ├── 42511b3934504c60c7626936af0e3e50bde17679.nq.gz
    ├── 43d8373a6afbd16aed5fb29bd8374b8c3020e6d3.nq.gz
    ├── 43fe05e67e9ac8ea0a42a425a62d5b4edecdc223.nq.gz
    ├── 43ffaaae10739ed5bff17c65bd69d0e8a9b23a48.nq.gz
    ├── 4593b5356d67e6c2412bd80462a262f05eb5ae08.nq.gz
    ├── 4622f5dc59c32abc7cd15f202f4285403c270f3b.nq.gz
    ├── 47f8c1ddacf3e56d82cdce08adf5c5850d4ee3b2.nq.gz
    ├── 48a02361fa30448ee83d154ec1a60a572a52892f.nq.gz
    ├── 495cb05cbd1a906dd1a26df5e5e0ce772d0b0397.nq.gz
    ├── 4a2d470ef13dfc4779762babc9e334edd7feb63e.nq.gz
    ├── 4a57c901f9e73bc230907bd72a09ed87985883c9.nq.gz
    ├── 4a6837dddff31be1432625d3b7d331e40707ff34.nq.gz
    ├── 4aa35684adc4f11462de18a2692dca5d5d4914e9.nq.gz
    ├── 4b04915eee2cfe27a0fe8a624438b711d11cebd9.nq.gz
    ├── 4c79efe0a8cc5b206d09aaed873704eb4052cfab.nq.gz
    ├── 4c946ec9093809aebb5103fa6b07a04c8946cfb7.nq.gz
    ├── 4cd0471440fa43506c9ed56b9dead9b34f95b621.nq.gz
    ├── 4d41f6567e65ab8872728e146a204a37d0da81fd.nq.gz
    ├── 4e6403f16b4d0306568e228e4e10d8f09701b9ed.nq.gz
    ├── 4e9d1a7e4ad99de66c8cf93fec3284137c4c9686.nq.gz
    ├── 4f2a2a0ce8a6d6b71b50c57f543ac7ee57fafc48.nq.gz
    ├── 4fa618cb1cfb2557e0998a448785c499eba1bf19.nq.gz
    ├── 4fe93571e8594f1d09f86fa65eedbea10e18f518.nq.gz
    ├── 50f83b54f0483a63dde18661339619bc653b37b6.nq.gz
    ├── 5145a092b9c4bfaadb837cccfbe3191204708d73.nq.gz
    ├── 5239adcde0cc711199ba82ce71903370b4e13474.nq.gz
    ├── 52a351187330f1ddb2259b4ce71c308cbded2cc4.nq.gz
    ├── 537ebb6dff96c4cda802629d03bf953b251fee80.nq.gz
    ├── 53b1a3844f248f482a902ec0c0820ea923a1459b.nq.gz
    ├── 54f7e88ef94a24335b57aef463f3183e9bfe23d5.nq.gz
    ├── 54fb4a0f757afa1e47b8b27438d40cbebc6e78f0.nq.gz
    ├── 5578fd6817b98f2e82fb6bc9f855d44847db68cf.nq.gz
    ├── 56333b38ea8a04c6de9c46b25bc580e55aabc179.nq.gz
    ├── 56c13bfb4bfb95a4c3a55379b7998ef8d8bf9aa7.nq.gz
    ├── 56ea016a2548bed237ccd89b3456ba92b2c96b6d.nq.gz
    ├── 57fec82b880697842f1ea07dd27eacdcb4522c57.nq.gz
    ├── 5838c291cc64695976728a821d5df9989315b188.nq.gz
    ├── 59634633d0d0182e336a55897ba030196f0c7743.nq.gz
    ├── 5a6c704b0b5f9ff159d6ab20926afef8f44b5373.nq.gz
    ├── 5ba968b68bf37b74db6626f1d58fdd8df8ed839c.nq.gz
    ├── 5c091e685f71f0528bb8545d441016776a13be48.nq.gz
    ├── 5c663ee90f079d7571103e3218e47bdd9f326a3b.nq.gz
    ├── 5c8a42b6e9a920ec71eb791e106bbe1a4d7e8478.nq.gz
    ├── 5cd8cc0c7679acc58aef62c9a3e552b626ee41d5.nq.gz
    ├── 5e879bec38e23815ec58a9402d02ad58724a5d9e.nq.gz
    ├── 601b1fe5e23738859324e0161e16d56259f80c11.nq.gz
    ├── 60226988094c7223321276adae074f035d1ca2f4.nq.gz
    ├── 60f69ab7662eab8aa004f54646e60fc9c2cbf972.nq.gz
    ├── 620aa31b052cc2b8d1d96c3ba0d3c8036badbdc4.nq.gz
    ├── 62c38d9dcd3f8cea17c65e6385dfe60bff549fc7.nq.gz
    ├── 63d70fe757e436183a7d276c84f1ebb8d43ff9db.nq.gz
    ├── 67138461eddd194682a86c543036e97398904ce2.nq.gz
    ├── 68036dbc5ae17d616adf0e965e7d39205fa12f3d.nq.gz
    ├── 690654eaf7069aafab4bca38c41d2b3f087b5933.nq.gz
    ├── 693aee964732709fe6b1c2dae3223a190b05e082.nq.gz
    ├── 69d81d04d1d5e204d2ccc1454ba5aec20f2680b6.nq.gz
    ├── 69f4c216d095b152642eee412fb4163f3363253a.nq.gz
    ├── 6a12fdf7bc44ae12fbfbdc4310c535c88ffc1a81.nq.gz
    ├── 6add52a1097fcbb70b4441a306b470f131e0ce0d.nq.gz
    ├── 6bc4085003f0db36479c275b33e9d6051c7f37d3.nq.gz
    ├── 6c815de018aceb636931c1280fd3cffceb368445.nq.gz
    ├── 6dbc09318f75651fb8c002e2335ca17d48e72d64.nq.gz
    ├── 6e19f215c0bd57affc4b70e79a879e49752406d4.nq.gz
    ├── 7019be9348824b6675692d8fe611d315db7e15ed.nq.gz
    ├── 708bc47a9690ad0ace9969cd6ad1300bcace49f1.nq.gz
    ├── 7139aa80ee0cc4b220bd299acc1728d4e910826b.nq.gz
    ├── 721a41c02c8709ff8f450326f69159e3086d983a.nq.gz
    ├── 72d5fe5170b4d3bba113164f99e23c7d6b637ff4.nq.gz
    ├── 72edd7ced1d118f7dd5528b7dc7de8bbc2355f80.nq.gz
    ├── 72ef966203b7f78bea858757c30d1ef22c20313b.nq.gz
    ├── 741d2cb503b94f7b91fde5129001d29c9421557f.nq.gz
    ├── 745f65508c7dabbc9730502ecea8758488952cb0.nq.gz
    ├── 7645ecbfdd66f3556daa1f58cf3cb35c5f4949ef.nq.gz
    ├── 779f1d2b4299ac2a720135eccbfeeca876cb9781.nq.gz
    ├── 7905647b7b530c84a2ccf7398ad5ee5ef9cf31e3.nq.gz
    ├── 7a1ace9f2f44fae832b3dc5d8e95971098d89d4b.nq.gz
    ├── 7ae2e33d629397f70caf5e208b1a27fd1aa8e4e4.nq.gz
    ├── 7af4132ca05e55b0097f82aa27a711b28ae1d777.nq.gz
    ├── 7b30f5e2bd8a5372620c5a041af8862c106e5b39.nq.gz
    ├── 80561365623af7b5dbfcd01a5aeebe9fb217f029.nq.gz
    ├── 816da5fd805f13535909bd945be5462cfa795eec.nq.gz
    ├── 82b13f59f983c57ea5bba18bcb58f836eaba8d5e.nq.gz
    ├── 832585dd5c4dee6d37405635a0d7016b65f79d2a.nq.gz
    ├── 841f7277b715caaf96477eed3a4aae0d0d03b8fe.nq.gz
    ├── 8639c111778aadcc01375f091ff6a650dd4b5fbd.nq.gz
    ├── 867386c97a2798282969dd83d7fe6ab2d8d3f2aa.nq.gz
    ├── 8736b2cb9dc1e94a5c8e8c77aa3382f1ef0c18ae.nq.gz
    ├── 880bcca37091470b2cabf18f4f21a43ec7d39ca0.nq.gz
    ├── 88dd8d30370705c3de01e4aa79b156a4cfd9be47.nq.gz
    ├── 89032b0810c10619c3853bf4d48e08abaa66ec43.nq.gz
    ├── 89443b4156cd6362b98592504aa25d79cf6b3601.nq.gz
    ├── 8a6ea8d5150e68a3f7232a1e9e0b3fe10d4d257b.nq.gz
    ├── 8ae1fb12cd29c5827cbba1cf1d6069dbc48832f6.nq.gz
    ├── 8b0f5e8ded5bf45eb6248f3c9172dc287f989994.nq.gz
    ├── 8c804256bbab63917a90ed047fe932a7f7eb1e77.nq.gz
    └── 8cfd61f2afbaa296f0be140deca6d5ddd87240eb.nq.gz

8 directories, 200 files
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

## Source repository

[sass/node-sass](https://github.com/sass/node-sass)

---
*Parsed on 2026-04-19 by [repolex](https://repolex.ai)*
