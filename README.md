# Repolex Knowledge Graph of ruby-prof/ruby-prof

RDF knowledge graph data for [ruby-prof/ruby-prof](https://github.com/ruby-prof/ruby-prof), parsed by [repolex](https://repolex.ai).

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
rlex download ruby-prof/ruby-prof
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 769d3a452cb54312fa043224bd6b62b8a27a5acd
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 769d3a452cb54312fa043224bd6b62b8a27a5acd
│           └── chunk-001.nq.gz
├── blob
│   ├── 00b4c36767b6c4e6b04e3ca75faaf525ede9ef97.nq.gz
│   ├── 0298ced6a4a3be0152231a124445c43a11a3fafe.nq.gz
│   ├── 040b16ba522d25cb7e5cf7036aae043674dc5fdc.nq.gz
│   ├── 0635d8e9fd15c5b079cdc703ad0724d07f8c13b1.nq.gz
│   ├── 084f8de43f50043264940a3f7d8c59b03a7cbd7c.nq.gz
│   ├── 08ae12826878b416fefda53230bf39ed870c05a6.nq.gz
│   ├── 0a5b3c2ca1f0df3c3c179e3538c05a08e486b8cf.nq.gz
│   ├── 0ddf1af2c530583386c89c5de1ed13df30b76c5b.nq.gz
│   ├── 0e270037e02876958bb443c6ab2c33ca552ac7c7.nq.gz
│   ├── 0f955dafc426243d91a3d7e97ef6c152489711a9.nq.gz
│   ├── 15fe68ba96dfb4b33f4eb0578fea4df99a98c056.nq.gz
│   ├── 167be9528d03f3cf16db6e9d040dad3828678af5.nq.gz
│   ├── 170a68e1a16de1f50c5eec734bf8595ad6432fef.nq.gz
│   ├── 17946e3dc2195d91052bb08cae6e0d024c2bc1e4.nq.gz
│   ├── 181f19c7d839ca74ec1b2b7570ce3ca64abcfc60.nq.gz
│   ├── 188656cf8b839539b183c7ef5cafb884723530e3.nq.gz
│   ├── 18bcf4842d68fb36a12b8aed7e2d43910f708a14.nq.gz
│   ├── 18d981003d68d0546c4804ac2ff47dd97c6e7921.nq.gz
│   ├── 18f1b18483ac184291f0572cfb3beb3de55d8ccc.nq.gz
│   ├── 199bc0ad9b350118c7574a07cbdf44e010882054.nq.gz
│   ├── 1bf195ed1775acb51d2b07f785eb2ac39f19e17c.nq.gz
│   ├── 1c2a7742b23cf2d2686b69a19d66b328eec8c579.nq.gz
│   ├── 1f7cad76fd19f98ba93d253f4f0f112f82e3eefc.nq.gz
│   ├── 2461678a715c6ce444d2865e5c0a580251536dc5.nq.gz
│   ├── 24fb217c392858f42796788f5bce0584f30c278d.nq.gz
│   ├── 25d0a5225731d93ecd323f36d08f37370c78a751.nq.gz
│   ├── 25efac1c9c3d89ec39f05a20de381d90d73e3451.nq.gz
│   ├── 260cf02a8a4a2dbc8032f04b5138b3b38a38c4e5.nq.gz
│   ├── 276e46febcbd5554fc3563f0b705fee0733ce7ce.nq.gz
│   ├── 2d1b1a8e7016d4d32f294296be74f67c62aadb69.nq.gz
│   ├── 2d5037db73f2713a0d8e0ca402365f18846df037.nq.gz
│   ├── 2f742534d410f18169dfea1265930f383c36c036.nq.gz
│   ├── 3144e7969c556b22b78f0804b1b9390e1399065d.nq.gz
│   ├── 356a1d608ecf0da70687400b16cc6f12f2339c2d.nq.gz
│   ├── 373c2625181109da0db046b4c3c35c31e7442a98.nq.gz
│   ├── 3795ee2ffb8211b6f6d97175d428f3aa442d1ac4.nq.gz
│   ├── 3809f0c085508fb49edf558c1e5a074790c42125.nq.gz
│   ├── 3a75d0624cf25bdd9192230c08af3c25477b0089.nq.gz
│   ├── 3aae42761ecbaa4c205c648466a4b1ebf3680f01.nq.gz
│   ├── 3e9809852003f4c55e4153717528e0e53ec8a77d.nq.gz
│   ├── 3eb5d4be3759190ff3406a8d27ff22a26c86adb8.nq.gz
│   ├── 3eefc0e483e9a1639d51b38ebecb5d5de9856fc5.nq.gz
│   ├── 42916afab24b50731544852eff4df13a2801e7e8.nq.gz
│   ├── 459b8e93f727bbe8d0d599da8302f8d3efe884a3.nq.gz
│   ├── 46b6fb73792c17a348734f21ff383e2f4ccea785.nq.gz
│   ├── 47fa6ddab2504b0030642b44d095b76ef39de8e8.nq.gz
│   ├── 48317a07ca6b714fb0dd68b13a8699804eafd0c5.nq.gz
│   ├── 489a2387fcd15d4f902927f762bd366255ead058.nq.gz
│   ├── 4a4190027408c69e7e37697531d2b71bc5e2d77b.nq.gz
│   ├── 4b04c7227130160008dd90b0e7f35f871c0e4bff.nq.gz
│   ├── 4bc01ce00353db1cc41ddc221a92b4aadffd3ae9.nq.gz
│   ├── 4c104e6b01ce01871bdc49f48dd2fbfec8472747.nq.gz
│   ├── 4ca623ebf53c33c0364adb64fca1def061682f86.nq.gz
│   ├── 4dd4eb5db7ed5848a3c38e9e6cdfd4b475afd785.nq.gz
│   ├── 4e11e02abe606d78489140ef11dbab3ce44b4c52.nq.gz
│   ├── 560763fa364ffac114c8ef00ccc60bedcf2310bc.nq.gz
│   ├── 5636bd7c402a33925c6bf6369615607bc39db145.nq.gz
│   ├── 566b40f720e5643ccf5f15d83b9dc218c6453fd7.nq.gz
│   ├── 595f0cf6c47b8a42ef3dc5a9f9686a7674274bc0.nq.gz
│   ├── 5ccce5d3e7f1bc6ab4d421653d561b6bc1b570e3.nq.gz
│   ├── 5da2fad01c1d103b66f96e782e665d1bb285a664.nq.gz
│   ├── 60ac1d2521eebefcb67e6eeae0697325dd18cba1.nq.gz
│   ├── 622f118f7eafef32ed2c3f01e7c49394c628433d.nq.gz
│   ├── 65b83ca74639bc490ab4d66dece0768fc9913bd0.nq.gz
│   ├── 666f21ab6f0ee52404f963462d2a6932de3587eb.nq.gz
│   ├── 67a26bec78250e6bc62441d77053ca51f0c1c93d.nq.gz
│   ├── 68d61d7c3a4e97ad17a0c60f054f828734b5a1fc.nq.gz
│   ├── 6c147112c6ab0888b3d619d6a74eabcedbb604b3.nq.gz
│   ├── 71eb939a8721d5cf8579e26726494b88b2df3b48.nq.gz
│   ├── 742287adfebbb2cc53e256222bd5d1eb7e191132.nq.gz
│   ├── 751ab49ea2653c56bc985c8882b8121edb0f29ea.nq.gz
│   ├── 769df7c326a61534a138e5fc6c9f18d532e376bd.nq.gz
│   ├── 775a3ddff663578aa3fe3e166e8cec5e2ac757fb.nq.gz
│   ├── 784ae89a4cdd9ee73f2de0a65bc271bd54ee61d4.nq.gz
│   ├── 7a9473f7342f796fcc3aef04cd950ca77f09d9f2.nq.gz
│   ├── 7b50df04d609dd5d8925b5533f29e69d8ea0c8ae.nq.gz
│   ├── 7c1464c9c7486adcfefa8069915e49e9a44d41e7.nq.gz
│   ├── 7d2068c4cf415b27ac4851f2c02673d8fec4fbcd.nq.gz
│   ├── 7e36cc6a670e1ad1063e25a81107924251ff4cdc.nq.gz
│   ├── 7f58aa966f7c1a449f4624388177a9685c43411a.nq.gz
│   ├── 82065521817759762f129d61e2d7a8fa3bdbea93.nq.gz
│   ├── 82c32aea3425b37b346529da4d10ee452ed972c1.nq.gz
│   ├── 8362b6769526e972edf63f798d52a9ee521fe1af.nq.gz
│   ├── 84864620980bff08b373849c2052d3b4ff9cee7f.nq.gz
│   ├── 8778589d7db66530486e7b7b7c33cf32a086a774.nq.gz
│   ├── 89f210bfd12e8a19447c75a5a32a4b5a1c57d225.nq.gz
│   ├── 8d0281d11cf0e411521945a929991591db5fff11.nq.gz
│   ├── 8eac6d83a0169ae93268f21dcb279817c9f67a8b.nq.gz
│   ├── 8f5437426543790aeccb48f8d9b986dd962a4fe1.nq.gz
│   ├── 8f6eb52c1e3a81291fee871df76ba26e64b8c71e.nq.gz
│   ├── 900bef2771ea590b45b815ed4a45414b9a6293e4.nq.gz
│   ├── 91e51167d33218f56da41e6d6e4ffa9e6f77a99d.nq.gz
│   ├── 9405a7122d0718ac12ad73b18b9451888f9407dd.nq.gz
│   ├── 94d27ee15cbfac98460a37159d51b89478d49d51.nq.gz
│   ├── 956439f1ee13bf0a5d4bbdd6c5d4cb5d6e9a8556.nq.gz
│   ├── 989952356d7ba1f5965ebe27ca6b095cd897f9e8.nq.gz
│   ├── 99771f0d1c7196c13dde0dd06e16b70b7c733bae.nq.gz
│   ├── 9cac65d2be9561628e86f63e75895b8cc195e0e0.nq.gz
│   ├── 9d22eb46a9c8ce7e6f0d17b751d0e192ed89fefe.nq.gz
│   ├── 9f749ffb1c80370734f5b54e8df0e796e779e03c.nq.gz
│   ├── a854ec0effe99c240db194d1a536922118229798.nq.gz
│   ├── a93fe036bde1e6aa65cf479e50725fba767575b7.nq.gz
│   ├── af291726e869db19ec9bf0304ae2c0e0fdff33ac.nq.gz
│   ├── b09cdf08890deca926837a2a2c7622cd9e6dcd14.nq.gz
│   ├── b11ca26a7f0efd740e34564223c688d2a7daf0f2.nq.gz
│   ├── b1ad68c75e3a93db840e2bc685d8ac29a3fdea53.nq.gz
│   ├── b2b9213204f4ded3a3bf2dfa93ebc4e02063947d.nq.gz
│   ├── b50b7f3b0b98f201611ebd17bd9bdea4076f0d96.nq.gz
│   ├── ba7f0c69e4dcb2d408d94ad2069ede8fb71cded3.nq.gz
│   ├── bc21e1e7715d0d46d03c3fb9011b8969e4a21bcc.nq.gz
│   ├── bc4f222480d6a6a7c43fe3d3b141b831d098fbaf.nq.gz
│   ├── bd75191cd6528d51ee60b9d0142daae07837aec3.nq.gz
│   ├── bfa228e1b0ac862a7522a8fa16f5281649aae036.nq.gz
│   ├── c0683e37b327b5cf5f02cf077d31e5ef3dabc0c2.nq.gz
│   ├── c38d8bd72bf19e7936ffa9c8af1c890d0e61faea.nq.gz
│   ├── c48e1ed9fad4cb49373ba0bdf340c5a8890dd0bf.nq.gz
│   ├── c4acdb6ff175d57358eccbe128ac875ac42c0af7.nq.gz
│   ├── c93f81df472e7fc4a6e23ada65b7d085c21fcba9.nq.gz
│   ├── cacf36d48b1740a15cb481da2d949e84956edcf0.nq.gz
│   ├── cde1a181e749ed057fab0f99ac1ae70d9dc7d02d.nq.gz
│   ├── cee8efeef53634b1ddb687b767da68488b2c1fe7.nq.gz
│   ├── d2c19a14322b004f711b94529c17e3a11f310691.nq.gz
│   ├── d3c01048b799b6ee5c491c070afa8ebbeb6f7cee.nq.gz
│   ├── d594722f0915e425fd8fe09f00adaa585ae52ed2.nq.gz
│   ├── d6023286745c06bcef7ef127a56ef80228355e29.nq.gz
│   ├── d63a1ee1ff050ef66c45819104c03094376356d0.nq.gz
│   ├── d68efe25a8cfe011a18cffb0b2660a727a5895f3.nq.gz
│   ├── d72ef6237b8269f37cfc5cabeaed7aa59d5bf088.nq.gz
│   ├── d81d8ca2220c661357a3430de3d1dfe87b278d8d.nq.gz
│   ├── d926697133532d137ed79fd27a8b18cfb65c33dc.nq.gz
│   ├── d993482a371a03269333e79166982cece61c84b5.nq.gz
│   ├── da64870a503c3116193b6b94ee52e15e979e8647.nq.gz
│   ├── db515a6b9b3a2f272995b22282e3337059570f65.nq.gz
│   ├── df17af6d4f9cf84d49e97dd2158b685695c21e04.nq.gz
│   ├── e277abe0c500479b4867b4c4cb5bdc80caa73a93.nq.gz
│   ├── e2c480803b8c1e4fb09c533d2b7e8a2116d6444c.nq.gz
│   ├── e315454d8a4cbf25f1ae6587377deac5199d5503.nq.gz
│   ├── e3a77426a2f5797d11e867013f92145b79e2ed39.nq.gz
│   ├── e65c74e1cca320242383336b2b11cfb48eed1e7c.nq.gz
│   ├── e6bee82b40c5b323bbd13685c4395034cc209e87.nq.gz
│   ├── e86526574c94b2b2b861d057e38748ba04c1dc98.nq.gz
│   ├── ec2d0f4a9fe9d70cf346fbbf817c9eb9373cd367.nq.gz
│   ├── ee960178438b217bcd6bc8e245de1e67a19436c2.nq.gz
│   ├── f2e14affcd3fb54da4b82633dde0b527bec5b791.nq.gz
│   ├── f31b2ba527fb162e94e23208dd4f03fdf5866e7b.nq.gz
│   ├── f3d2f4f76383f395ab1bdf655c51199cdbb5b216.nq.gz
│   ├── f41cb917f407f06914156872d9b2d75ec5b8e15e.nq.gz
│   ├── f757613f39da8e05406ff640fc6bf8529a6c761a.nq.gz
│   ├── f78b81fff1fdeb06f0400ef9aa3b0e4785e63c81.nq.gz
│   ├── f8f2e9f9e541a87e3d816c9e98e07737b6cb4143.nq.gz
│   ├── f936ff91302d4b0253fa97304aab75a7411449ed.nq.gz
│   └── fda3e0b51bfa041ba41c0e6b1fac57a0653da169.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 769d3a452cb54312fa043224bd6b62b8a27a5acd.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 160 files
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

[ruby-prof/ruby-prof](https://github.com/ruby-prof/ruby-prof)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
