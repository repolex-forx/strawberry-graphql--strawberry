# Repolex Knowledge Graph of strawberry-graphql/strawberry

RDF knowledge graph data for [strawberry-graphql/strawberry](https://github.com/strawberry-graphql/strawberry), parsed by [repolex](https://repolex.ai).

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
rlex download strawberry-graphql/strawberry
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0eb1c5ecb66d4a72ed0d9f6387fabb7996daa3b7
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0eb1c5ecb66d4a72ed0d9f6387fabb7996daa3b7
│           └── chunk-001.nq.gz
└── blob
    ├── 0001ef9fcb8be4c8b1cdeab378602ed8c6aaa6ee.nq.gz
    ├── 00980b31e8028529ff01c303452595f69157faf5.nq.gz
    ├── 00a06d88e64efbc964ba9aceff3d7a4dc888c208.nq.gz
    ├── 01530dc434e295ab33f63209c8088dfaace776ee.nq.gz
    ├── 033b01a2c6380885e731778596cdab4179543995.nq.gz
    ├── 0393fb158d23b0f21bf044938b0c177e3e92a385.nq.gz
    ├── 0403b0947bc150d66f08b1360babf44a2c63f36b.nq.gz
    ├── 04c5fe328bf6b35f6a023c367d52d0b1fe67e8e9.nq.gz
    ├── 04df0e6cbd39216d47c95facb35a61d0374e008f.nq.gz
    ├── 050bec17b399a53918ded2eb1fec284c1ff6a747.nq.gz
    ├── 0534233a57b6dd67afdef9b3887f18ae9ca83dd1.nq.gz
    ├── 05a91be3cca88a83a9b04e0fb885b81776a523db.nq.gz
    ├── 06030e71ec7eadba3be13854a5d95c63c64c4374.nq.gz
    ├── 06eb1a239cca46c5799d14992d7cfed6906212d5.nq.gz
    ├── 0760514b9e85137111876942b4e404a65ff06f8a.nq.gz
    ├── 0853289e304ecf51cafece44fc63cdea356d9f53.nq.gz
    ├── 08866d524bea644bf71adc6fa53df7575112bb30.nq.gz
    ├── 08e41701a8a755f9110bfe257c7cb2e5518ded46.nq.gz
    ├── 092408a9f09eae19150818b4f0db5d1b70744828.nq.gz
    ├── 0a5a4f192a73916de90cccc3299c332a13e20d5c.nq.gz
    ├── 0a738bdcc66252ae02baff3db5a28aca7d034de6.nq.gz
    ├── 0ae9310fe0c9bbf3b8d79d32ad7fd1c2d7212cb6.nq.gz
    ├── 0b5238252e59fcdbd20f5561a3d8abe543d9c260.nq.gz
    ├── 0ccf9c37a6147cc4176a664347e72207a11dbf73.nq.gz
    ├── 0cdc664d76c6ef5168c610b1780dc496976656d6.nq.gz
    ├── 0d0c7ce4dae2e62e905b6e040e788ca0e3e7589a.nq.gz
    ├── 0d5fabafed4af6b302232ec79bee7c3442a24784.nq.gz
    ├── 0de153ab0b443fe71577bcd0fc2ed4938f49fe05.nq.gz
    ├── 0e1831795ca87a068784f5f931e90bc5230a906e.nq.gz
    ├── 0e63171e7458781318846c8fbe1f435382bc0e5c.nq.gz
    ├── 0e7595425c9ce8647f1c0908827f4869017517f3.nq.gz
    ├── 0eb2b2f32581a25952dc1a05970ef5f661176552.nq.gz
    ├── 0f7a10118fb2b2d572c3440d88c985e70ee902a0.nq.gz
    ├── 0fe909d7c867679c9c50795891b4574fb1102201.nq.gz
    ├── 10d83233d711de8f4047c012af679dbd303ff052.nq.gz
    ├── 11120373d32da662ef899956082e603a09265296.nq.gz
    ├── 1116307dd7ce66dc60403f827ca3a941ec30fa89.nq.gz
    ├── 11f02fe2a0061d6e6e1f271b21da95423b448b32.nq.gz
    ├── 134700fa66185d08f35609c761392b940089b73c.nq.gz
    ├── 13debf18c376a551a6445dca35d5004e85a21d78.nq.gz
    ├── 13e1db0b7a1ac62bb3aa05b8b2894a350bd46e6a.nq.gz
    ├── 143749f49f3c7415c3b9d548c69ddc4102d6b1a9.nq.gz
    ├── 145aa1c2d9fd6eee9240debe5defd61ac8228e13.nq.gz
    ├── 15e102be256b65dfd185a67d47e0705bf20bfa09.nq.gz
    ├── 16f381babe6faf2f559d733e15b78b8d092c375e.nq.gz
    ├── 18850cba9e4f531ac364e0ea16931e3fa02eb5af.nq.gz
    ├── 18f197c8f386be8da3942616cbe44f1ed37559e4.nq.gz
    ├── 19b0aaa94b1cf31459327fc48e77c68b049e4c2d.nq.gz
    ├── 1a6a643b3263d71b005808095d4e78ffe90181ec.nq.gz
    ├── 1a6fa0758f8d07cccb73bfc366e20a961d98b75f.nq.gz
    ├── 1c1dfaf0a1c9d4f269f56bf7e53c27e3c193dbf3.nq.gz
    ├── 1c791c3f58ae830000eeab18c40e5d97686acfbe.nq.gz
    ├── 1cbef356e338ec8b8e9814d4afa3e4dee31ccfff.nq.gz
    ├── 1d1d459a3fd847a43ad01ed18e9251922cdf7ba6.nq.gz
    ├── 1db6a3d87f1bb3358a4d10c185dfb4cb9ecf9fef.nq.gz
    ├── 1dda35190fd9008301f34e891b70ff573117eec1.nq.gz
    ├── 1e31219b8a1e28ab06a2c850bbf48339ddbe7495.nq.gz
    ├── 1e3b394299045895a723529411b99986082145d4.nq.gz
    ├── 1e599bf7304882cc61891386d3b953126a460f46.nq.gz
    ├── 1f68092ce1fd64d98807054ad573d64f9b27f94a.nq.gz
    ├── 1ff05af541178b4ea952655b718bfc15130433d2.nq.gz
    ├── 2039c13bb90635cba0cc41614c1a7cbaedcc17c3.nq.gz
    ├── 205b93b2b216ef34ecec15e33bda451e1ab470cd.nq.gz
    ├── 21be3ba1bd65b762f51a85aa227aa464bcbc9de7.nq.gz
    ├── 21e6808ecffff3140e8724ef2eaa5e84bedd8d15.nq.gz
    ├── 21ea1e645ba2c50edb561261ad6c15a67016c430.nq.gz
    ├── 2217c630cfcd96f98a42812a5272a3528c81ee81.nq.gz
    ├── 22524a985b5d703fd23d5c369f511fe8a84d5d3e.nq.gz
    ├── 2254e852032c3f40771e214d16c29ec9aaa9902b.nq.gz
    ├── 22bb46068d71db104c2329b8ee139e50ec384e57.nq.gz
    ├── 230b2a94c7c9718a3d0729afaddd0b1e860029ed.nq.gz
    ├── 2356061132b2fb05b955576eb5a3cfaed7e0d651.nq.gz
    ├── 238bbde2a5e68eaba3a0cec779b793b357d93e9d.nq.gz
    ├── 23f2f87cff27ef088381b55ac6a75974566af731.nq.gz
    ├── 245450126f12b366abb5197703af56562af3705c.nq.gz
    ├── 245a444a701b485ac941f439737d480a6070f271.nq.gz
    ├── 247e17fdb7d9391e2a08ff5504acc3268a8a0fbb.nq.gz
    ├── 2543bc7392002990a1b83cc48b132a72794c7fc9.nq.gz
    ├── 2555ee75e9e12d6f05866c87747f3a8fad12c2bf.nq.gz
    ├── 2585aff5c3ad3b9149053c8f8fa79dc4e481fe67.nq.gz
    ├── 259040ee7ffce30879f661fa1964ab434aef0d48.nq.gz
    ├── 25997be387ea519234038fce5058cf4751115ece.nq.gz
    ├── 25e556f8aebf960e4090bdd7ddc6e315339e93e3.nq.gz
    ├── 261d48108a6a5743045e971852af40ab4b63d839.nq.gz
    ├── 2697e71700b38a512b20756c01c5e5e36204bf1d.nq.gz
    ├── 2793f91ee034fea9f552833b746018a3d86eb84a.nq.gz
    ├── 27c649165bca3a87d52e0f2abda2a7d8152c3103.nq.gz
    ├── 27ecbb36ebd5a094ad1b452e8919ddc8be13b807.nq.gz
    ├── 27eec5d916e39ad4fffd892e72c678660840e297.nq.gz
    ├── 2843f39846bb7b450f4957d0b93b188346bd7e23.nq.gz
    ├── 288516d74750ab1558b32565acd453bbe6e1fe6e.nq.gz
    ├── 2893766e79239f4fd1c1dda0a833fa258ffc2ed9.nq.gz
    ├── 28a5a1589a1e657bc89c08ae2e3af48eb1bc3e60.nq.gz
    ├── 2951f74a98a75ff81a99ce1a3f41033674bc5bc8.nq.gz
    ├── 2bd8bc13b0d7b0da1ba576826b3e345c105abdba.nq.gz
    ├── 2c4f578d3068af4cf00fa4f9d3d6b573b06a8793.nq.gz
    ├── 2c5df44bcd7af953fae68eeb96f09b6a19ebd16c.nq.gz
    ├── 2d2f178c87d7ad10ecd85be8193f7e3009694c72.nq.gz
    ├── 2d4b033a12b9c80dd353f4300305e5ba290b61aa.nq.gz
    ├── 2d9f09d1ba639ce2628d4bf33e2df7e912825a27.nq.gz
    ├── 2e10e62cc20dced718e97393944e074d5b201c92.nq.gz
    ├── 2f03e0bb4b8bf3b6f7d620d4ceb58137af804339.nq.gz
    ├── 2f70f333a26a74a5ea0ef129c274b76deaf714c0.nq.gz
    ├── 2f7eacb18560036325d3f7969e56d0de2c9a54f5.nq.gz
    ├── 2fac7f6df34ede9434fa2c2435e438ed5ac6e9ed.nq.gz
    ├── 3079238f34a72e87e978de6660b537449f9650cc.nq.gz
    ├── 30cbc6864d52b149e5f916dbc0af88db04ca60dc.nq.gz
    ├── 311b8de95a71557aef852a3a63b31ce0824bf891.nq.gz
    ├── 32d8d36743b16b19009b00302a6bbc8112e43947.nq.gz
    ├── 3429e1a99112f6a65e7c1f59d0a5bda696284554.nq.gz
    ├── 345ae401bbf369cf8325818583eea6859508de78.nq.gz
    ├── 353323614343c1e41977d03c2b59f6e0018aa88e.nq.gz
    ├── 3583c8d63f8ba3c9a77ee052317a14af636e50ef.nq.gz
    ├── 358f132ec0118df31cc0e1ad6fe7aed8a849a156.nq.gz
    ├── 359bfbdfdaec761a2b611f5477f470a7cc519d93.nq.gz
    ├── 364c1bc8631161d66eb3996b36c22bb5e86bb528.nq.gz
    ├── 368c3c40d6eafef0760dc374bc637350167c20e5.nq.gz
    ├── 36bf092af36cd56f666d391e986eaa5c4a72ed93.nq.gz
    ├── 36cdc527b923acd8a752824d799489e34df8798a.nq.gz
    ├── 3761b0db5fca495cd9a497100fef957e5d892242.nq.gz
    ├── 37a4648f53354cb179782bdc580544349971dd0a.nq.gz
    ├── 37b2d6878cef0d5de9fbca2143baf5dfc20b0eba.nq.gz
    ├── 37be476dd8dd05a33a04dd6685f03442c3fe03bc.nq.gz
    ├── 37ef122cfcf8a7aef4109a1fe3f9f37fcfc590de.nq.gz
    ├── 383d58b0b18c24bb68f34035b1cbaa6d2344683b.nq.gz
    ├── 39b58ad2de2dc6ac68ac0bc40f7f2aaf2cebe724.nq.gz
    ├── 3aa52fe3ef388ebf7660021c383b039e93862efa.nq.gz
    ├── 3aeda2cec973d807f7e75ea5d593e7c3bdbdadb1.nq.gz
    ├── 3b5be180638f24753acaf4ecbf5077f72b72154a.nq.gz
    ├── 3bf83ba5047b229007e6a17ca79225e5da3b9b29.nq.gz
    ├── 3c6b8518d9000061bd26d894028d0de863cf7665.nq.gz
    ├── 3ccbb0ed4fe9c715f694c738f135e109a200fbe9.nq.gz
    ├── 3db33c1537e6fff81dd3c23faab78a309acc597e.nq.gz
    ├── 3ec6f1a0ef62b00237170e6c4f7e50f826ba7cae.nq.gz
    ├── 40d16a662c4117b8bbf820622d92334826de25a8.nq.gz
    ├── 414c4799adc09e508c9b9338ad2006826a57ecb5.nq.gz
    ├── 416400c4c02e97c27a089b3bee9f5d88cf000610.nq.gz
    ├── 427e29f0e4ebbc163b6e22301b211f82500332c5.nq.gz
    ├── 43187ba9970b5d87275101962eea114007b26bb1.nq.gz
    ├── 43587e1422998a7e4bd6139f2ec19fb98c048925.nq.gz
    ├── 43c032884fffc7a342ae19f8bccadeea56476b8c.nq.gz
    ├── 44c91f456521957984358116b70956dbfc24673f.nq.gz
    ├── 44ea6852d41f640e2b6da6f80b626dea6e6020f4.nq.gz
    ├── 44f58156007bc3acb5763ca42b5df8e7fd6da557.nq.gz
    ├── 454d7e9720faf33cf010ab99fe7e6bbc34f2140c.nq.gz
    ├── 458112b9b909dad6f61c916ac4d98ee1c016ca7b.nq.gz
    ├── 45a4bfeeffbdc987993c2b123edd14e0670e4135.nq.gz
    ├── 461375424529c7afdc721f52b7e8264fba79003a.nq.gz
    ├── 47a91fc2d8351ae2526e4765baccbd768289217c.nq.gz
    ├── 47b4c12cc0184efbcac5ed461a18e9df23fb5404.nq.gz
    ├── 47c615333122503cf2d3c9f0cba9f58424af6b13.nq.gz
    ├── 484185b92660433e0da8f91c5b61194eaad8d27d.nq.gz
    ├── 48be8e6835e547c7bd0786f6a44249fd79e7e055.nq.gz
    ├── 48ca38b7a42a74d58381030988d59f213ab7dd07.nq.gz
    ├── 490ea71c44227600fd2c60eb8a7e8621303b38f5.nq.gz
    ├── 4bc6c2dbf37975489172929753a7a7b7ea80179d.nq.gz
    ├── 4cb27be5dc43a8add308f710c67d3c5b4bf3bafa.nq.gz
    ├── 4d27f64b1fc3edb977083ef7f6aeaed21825602c.nq.gz
    ├── 4dc261245cc1188a1f6ac807a32fa9ad01714726.nq.gz
    ├── 4e75fd9af4ea8364a9492a1bb448fccd31dfdcb9.nq.gz
    ├── 4f58ad75c7d6d4c20c6471e0f5a45662f604dab0.nq.gz
    ├── 4fde361ce50f781863edd52e0b7391876b11dd89.nq.gz
    ├── 501a1640f1885098a5bf87d9fbcc4d070c2981ad.nq.gz
    ├── 515272642d326a94615fd1de2435dde652632fdf.nq.gz
    ├── 51ea96bf7815cd9bdfcf5164f6aa2d688b6d59fa.nq.gz
    ├── 526aeb5c3509aee24f62b60b3598fe008db9d3d7.nq.gz
    ├── 53db1707db17878f3c378f7273a14fbe0be7cc78.nq.gz
    ├── 5482196b561bb7b4d3bf633d012793b348e8cae0.nq.gz
    ├── 56c989e147058a976864c7b7f3ec7917d449e69e.nq.gz
    ├── 56cd3de8e2053708890255ea66e7920d5876d5c4.nq.gz
    ├── 5709c2a8ff309e40cdaaa76de6bff2d13534507b.nq.gz
    ├── 570ba47f8af7f064caf74052a906d2cf0bc6abbc.nq.gz
    ├── 5782c00719d75c0ddd15010ea5e88f7cde8a0b74.nq.gz
    ├── 579219543ac4c74e3bf6b65cc54c281f8885edc2.nq.gz
    ├── 57f63a5767aed7096e6c3f82933c86e25f65d7f1.nq.gz
    ├── 57fc5200b6dafe62e3d901e2a774f2132d6e8326.nq.gz
    ├── 586a0b22c6df90c5a6905ba1da13d7c576e1858c.nq.gz
    ├── 58ef84afb706eaa9cdd4205249ae343e4dccd671.nq.gz
    ├── 5a54fbfe0457113a8eb7ec36883fe16ad8ddf500.nq.gz
    ├── 5a76f2ee4e1cd19057779edf95e43610ecbf6dea.nq.gz
    ├── 5aa59de82300647e3e429bb169dd0712d1cd5e13.nq.gz
    ├── 5b55e1a18d151a10c73172cb4f150e607a58b3b7.nq.gz
    ├── 5b6dfada014043410f2cc63fab4a077b095b7f08.nq.gz
    ├── 5cb00aea338f6535d98ae650f002dc4eb29f5693.nq.gz
    ├── 5ce3aa6d7c578cfac782176e9bb398e54dba21eb.nq.gz
    ├── 5d09745006d0577e2bb9d8f38003be50c9870f16.nq.gz
    ├── 5e34c9258f8b834966b92ef98de95f1eb20e593e.nq.gz
    ├── 5f4c6ab9d892eb440d8b16bdf7f128917cdfdefb.nq.gz
    ├── 6067852afb54bb4414e7b9d53c61c44f4450708f.nq.gz
    ├── 6075166347961302ce8d8a7e46e32cfaa442c370.nq.gz
    ├── 60a47556acb579058496df528fb85de768ba57a8.nq.gz
    ├── 60ce8ef1c2e45670768fce7994782d38d3eb6662.nq.gz
    ├── 61a6de7ec478845797e16cdfa3ff2b77c2866186.nq.gz
    ├── 6248de0f18807e18fec10e5152aa0c184df7e367.nq.gz
    ├── 637f37925a3af6478a504300895331b92c952597.nq.gz
    ├── 6409ad0b4cda2938f1187245b31a29451893cb36.nq.gz
    ├── 642845a58b5c64c2391ebee4b6c74c5767091166.nq.gz
    └── 64d283bc8fdef2ab59960017df159870b7fee63f.nq.gz

7 directories, 200 files
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

[strawberry-graphql/strawberry](https://github.com/strawberry-graphql/strawberry)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
