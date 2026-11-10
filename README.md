# Repolex Knowledge Graph of googleapis/google-cloud-go

RDF knowledge graph data for [googleapis/google-cloud-go](https://github.com/googleapis/google-cloud-go), parsed by [repolex](https://repolex.ai).

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
rlex download googleapis/google-cloud-go
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1ddfb07e171b8c34dccc7e9c15926e94d823c2eb
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   └── repolex
│       └── 1ddfb07e171b8c34dccc7e9c15926e94d823c2eb
│           └── chunk-001.nq.gz
└── blob
    ├── 00220b11118e81e7a05da6e1494a2481dd08581a.nq.gz
    ├── 004bf92d0af5d91e1db27a294514f9e66239a1a8.nq.gz
    ├── 00a532ea88fecbc0bb96f09a01c2cb486d76bdf6.nq.gz
    ├── 0102295876dc1bc40afc7d6dc1f51e916d0a725d.nq.gz
    ├── 011c5f9fa88abc8fd2a3b119f598436d0dfb37dd.nq.gz
    ├── 01248142d4c4b0a0fc6be5861457eda153cbc1ab.nq.gz
    ├── 01307997c655532a2a5f7d72f15c94193a734c05.nq.gz
    ├── 013e58b05f616eb67ea08d9477e4b92d31701470.nq.gz
    ├── 01977946231f26d8dc63682019d9a823cef0ad90.nq.gz
    ├── 01e6b005a9348732a82df1a8fefa0f686dc5ff38.nq.gz
    ├── 02e43da0fdc4f24fc4a637926cae82e7184ed97a.nq.gz
    ├── 047811d5bd8858ccc30870f34736733e11a8a7cd.nq.gz
    ├── 04e764214e632c5b87009bfb5434348724a2b9fb.nq.gz
    ├── 05784c4913b9cf1d7b8ec1314c0e91fd5935efa0.nq.gz
    ├── 05e3f9157ff014029185d1cd7d82ea87c13accf8.nq.gz
    ├── 065d017261636a948ba05f83643cc40097f1e0a5.nq.gz
    ├── 066fcacd6fd4b554a722af737038f342e8687b4c.nq.gz
    ├── 0690570f6088bf198e505a97945b499ce0b1245e.nq.gz
    ├── 074d8edeeedc0ca7fdd5e9df7591f1528b55782b.nq.gz
    ├── 077684335a90bd817fdf290a9703aca8ebb0bd80.nq.gz
    ├── 07befa15822425da23da91e2970175da09aa70c0.nq.gz
    ├── 07c64f6bce222ca1242739eb99ed7c27809a318c.nq.gz
    ├── 07cb0bb8896d1346af0127ba5f2e259758becaa8.nq.gz
    ├── 0823fab9e5b952b43ee5a6725e21e6e2dc2036a5.nq.gz
    ├── 08565a95f6ca8bf0f00b011df91ff8d73007d532.nq.gz
    ├── 08b427d1b9fa7dcee3f75075bcedf35db52ed63b.nq.gz
    ├── 09816ad13bf7548351ec1f2e06bf860132e4a266.nq.gz
    ├── 099aed0247527eb19fbe1b4218eacf33d88572e2.nq.gz
    ├── 0a02061ceeb42a903d6c74ef54849994d196ecf1.nq.gz
    ├── 0ac815eda9f45a0e2351d583b8be20d2c4e54d74.nq.gz
    ├── 0aee58ef5883e5b47e7cd6f2aa57703c27d391ad.nq.gz
    ├── 0b3f697df6ea2f4442de619a60140304c713aa0e.nq.gz
    ├── 0b9d771d0cc1a4216c44101aa42d7bf8dd31d7c4.nq.gz
    ├── 0bb5b2aae01163f60d7b293c217ce38a3445d3ab.nq.gz
    ├── 0bf488405b3921dc92fdee4850cb9999a2b042df.nq.gz
    ├── 0c1a881e6316f438f90fff3215f30c116a0fe514.nq.gz
    ├── 0c6fae8896eba75414fc330eef2b690c1475a180.nq.gz
    ├── 0c8b18b00d5c9c40bf53687411705a1b7a0bc121.nq.gz
    ├── 0e17aa37d6afba0d05b734e4265dc25d8d45be0c.nq.gz
    ├── 0e2aab0a7eb4c1681aa95416ebeb164d4cd90566.nq.gz
    ├── 0e5c581854b39fbc565b8c87b5ae174177ccbe56.nq.gz
    ├── 0ee52e278d6ef5d4e4437ccb026b3f23af5bffb4.nq.gz
    ├── 0f00d20451aff432913479c4ed835eb120f3688e.nq.gz
    ├── 0f45cb51febbcbfed283a693665bac970738d41d.nq.gz
    ├── 0fbfeeb6086512e66d2c0739992695c55e3ff8b9.nq.gz
    ├── 0fe7918e13515ed4eb0aa8246a6c466d6eb3c727.nq.gz
    ├── 112da94b5e813744e2b740ca31b83361df765f92.nq.gz
    ├── 113a0aa588abd6e1383e2ecd1c41f458712af2e2.nq.gz
    ├── 11c246582b19835bfbafb2e01e6c96e5cc9b6ebd.nq.gz
    ├── 13292462c6257f0702372e297a23f1d950e30bb9.nq.gz
    ├── 132d8293356b3b56d5351a1e58863c0d689c62ef.nq.gz
    ├── 1458666d1ba01877d7488849a49dcae2fb4ab274.nq.gz
    ├── 165d865c09ef37a94060da3f31af415d2b65e6d4.nq.gz
    ├── 169736bf450911aad941036130c952dfabed801c.nq.gz
    ├── 16c3c5a626b761f29098a0b17550b5788443b5cd.nq.gz
    ├── 1789e91a385521cddd76b46d586f7d2c336f89a6.nq.gz
    ├── 17f02cba804fcc4124db710e5fa2a4ca524f7977.nq.gz
    ├── 19a2051411c7096b989027d952eabd3422c06781.nq.gz
    ├── 1a250b3f42fbbac47b2b78e9f6689a90ca884f24.nq.gz
    ├── 1a31e28ceea65abec5f4ad0a9e4cc5a2fa73b587.nq.gz
    ├── 1af9ffbd7ba93208373b41519432985402322a39.nq.gz
    ├── 1b37ea2f0350b5be72aeb2868447cdad710f0e98.nq.gz
    ├── 1c150034f7e9ddb41b4d23aef1b886f60ede72b6.nq.gz
    ├── 1ced4bb3ad96f8cccaf0ba7bc637745b9bb10eff.nq.gz
    ├── 1d839f6fede19459640421e54280a8c6eda0fdc1.nq.gz
    ├── 1e332fa72d3a6fbb5484bdcdacc4a7626318005f.nq.gz
    ├── 1fa3cb709b0e0da8f68643ac221e60273ccf4c4a.nq.gz
    ├── 1fffc6920d705c66257f2a169a7119911c9dc4cf.nq.gz
    ├── 205ec6885b4ab260128ea68481cd68c548101b5e.nq.gz
    ├── 20960dcf1e3437542bd9f7377771e056602a4252.nq.gz
    ├── 20ccbb5a5d23736af2476f312470acf481962fff.nq.gz
    ├── 21497945758c5698260db91535040d08a4a2dd10.nq.gz
    ├── 2183fe1192abd4e761296f1ca3b4fbd3266068fa.nq.gz
    ├── 219fd4fc31cf3b0717779ab7d719ba9d839c16f6.nq.gz
    ├── 21e8fcc2aa06a4b7247d85262c0ef6147d4df3b7.nq.gz
    ├── 222e89d37696a0bb4dda818a6d82cc49bda90e0c.nq.gz
    ├── 2289e7e0a678919bca169b1e9237648788e285ee.nq.gz
    ├── 22b23082ba2c33ab973bf3236174f5761e052e01.nq.gz
    ├── 234b4904522dab7008b44fca07fc5814fc3bd77b.nq.gz
    ├── 23512d4b832e3988eb79fdc3e31af6816d61c0f9.nq.gz
    ├── 237906737d1125bd7548423ac89b141787089143.nq.gz
    ├── 241208302b7dd26687b7c24baac5796f581459ff.nq.gz
    ├── 248994d11ddfe5dabbea5978126bfc9db11c8eb1.nq.gz
    ├── 24db5e4b6b0123fcdf0102d9c6b334637dcd3810.nq.gz
    ├── 25557724af42d9860be19219135057535395ca55.nq.gz
    ├── 25fd29108808ffa947d8d9e1626d9df7bb4f003e.nq.gz
    ├── 27f22bed171141813108a1e88f58da2318cde891.nq.gz
    ├── 283fd0f246e306cf39d749488a6d6ff39a650649.nq.gz
    ├── 287dfe151a29b3fe7acbbc894b9ba26c8292864a.nq.gz
    ├── 28fc851a0f72c387795b950a8240232e0beb2975.nq.gz
    ├── 2998d23606cbab726b36e767c2ed62979179871d.nq.gz
    ├── 29ee5bae602a06b42805a2196e0caa7b10ce11e4.nq.gz
    ├── 2a8f1e65936344d9d4838f262f82fec61f50049a.nq.gz
    ├── 2c1b08e0d3b32403fb7983bd9c77c8f568ad5a00.nq.gz
    ├── 2c770ca4711f0d90fc7824fbb896c10be32a73f6.nq.gz
    ├── 2c8072fdcc2abb18dca5728b53d1b4fccbe5e431.nq.gz
    ├── 2cd8dbde3bbc3d1d0cdb2c53ea8772985fcfea82.nq.gz
    ├── 3192ef9b745a952c354a1460f0b6993b3aa24a5f.nq.gz
    ├── 321570d401b0485a673ef712d88011b66acd69a8.nq.gz
    ├── 321bfb83a4109cb2167cd94cf2b4f0f452bcdf2d.nq.gz
    ├── 32910e01f6eb13579a13a00bc4e4447fe2993c9f.nq.gz
    ├── 3296e764093c999ce756ed2c21d9670298c679d3.nq.gz
    ├── 33346eca3312051530c664af15e04f58049f0d70.nq.gz
    ├── 3383e2c8478f7cf196f245bd1d6cd52e102f6c94.nq.gz
    ├── 33c511d2960010db2cbf7d00b5b477f29b53bfb9.nq.gz
    ├── 3464686ad7c7f91aaf2082922b0d4502c5a50a52.nq.gz
    ├── 34bfd8bbdedaf1880e54aa464de01f0870ee02f0.nq.gz
    ├── 3586b403fca5b2f9d5424b232ecbbadfaa85e5fb.nq.gz
    ├── 35b48a7ef18c0b21b09d42069b8ce7c74674a2aa.nq.gz
    ├── 3601fab548a1a6c21854853164ddd2eca3b19a93.nq.gz
    ├── 36be490216757f4886589e2c26cd8f022db664a9.nq.gz
    ├── 372c936e62ffd9cc7c3d69a296c0244cb5880901.nq.gz
    ├── 3748160ba08d8cf4aad552016881b716bd6920a5.nq.gz
    ├── 381d75c9d774fdb728271777a35df5bde2f67e19.nq.gz
    ├── 38b7981e448cbed9e004e4ea588e60806d1be05b.nq.gz
    ├── 38df64f1f301ddc6b017bef616ca91ccde14bd5f.nq.gz
    ├── 38f2bf3fdc3f7d5fbd5ee223fedf0bf00739c893.nq.gz
    ├── 38fdef12f91d8653e9740de5a63acae3b9ab1ced.nq.gz
    ├── 39671ea7b797d415b0cc89669e70d7cb0afc4f3f.nq.gz
    ├── 3a2fc3506680ce87141720e79910f6f5d58ca658.nq.gz
    ├── 3ad3118c87939eb969f4a66c36a041d55455f867.nq.gz
    ├── 3bf4e7060d80cc60c56994bb85e46eb3e7d1048f.nq.gz
    ├── 3c426efc27419571726efa2836f46038feac4b4b.nq.gz
    ├── 3c46b49f7ea02be7ed56f7aa163fd71cb4a34a14.nq.gz
    ├── 3c7de480f113ddeef265c3113ce70ff795b234d5.nq.gz
    ├── 3d346d434a76c48f17bc2207dc24523461f2a206.nq.gz
    ├── 3defc080d719ef568693c4c6f3dcc6387966154d.nq.gz
    ├── 3e99dd4d3a8bce69236d402f6e2fa82844819953.nq.gz
    ├── 3f0e3b2209e5a45428a4efe6750db1cd8793973d.nq.gz
    ├── 4069a51203246c541118c1763a4fa0d56683143d.nq.gz
    ├── 40727e4e8affdd830eaa8a67fdcc4dd419d0ef56.nq.gz
    ├── 415961c5f8a96b2360bd4aa5def4a99cabf5b9d6.nq.gz
    ├── 41eb729095e3c5753b90faeaa25c49686af32c20.nq.gz
    ├── 42585f4f916c38e476a70f4167814e6d9c6d7382.nq.gz
    ├── 439295313cd1ac038cdfc2be40823c35a397d323.nq.gz
    ├── 442e90eec5954c7da62cebcd50c9e48fef214c9f.nq.gz
    ├── 44327ce355707065ba3353b8269c8d9ef1a88dbb.nq.gz
    ├── 4452b37f575fd26ea3ec4ad00c2b6d603bf5e655.nq.gz
    ├── 451d3ac183e0774f0172e6e0d00598ff015951b8.nq.gz
    ├── 4685714ed42f156b1e4d3320897bb143b22e2fbd.nq.gz
    ├── 4791e6d6ab7edf90dbadb233a75fe67b922b1460.nq.gz
    ├── 49e59830402aa6b9258e582f3f5c1079da9468eb.nq.gz
    ├── 4a4d1a12dacd6bf06551609fab7bbba06523b591.nq.gz
    ├── 4a5b3bf85ea21c9b7018de9461044736923067fa.nq.gz
    ├── 4babaf5707c86d17f1d14cedd13a25662b4b94a8.nq.gz
    ├── 4bba225db2c1b1aa102e5cfa9164faf72719fc71.nq.gz
    ├── 4c1936b709a893ed6a19c84523538d3b31303a36.nq.gz
    ├── 4c3343377de4cb821853f7b2739fdad7b4070069.nq.gz
    ├── 4c64c0c70f18fe2c25f24a04c38d11d9ed5acc4c.nq.gz
    ├── 4c6cbbba63d5ca3d1fd664699a0a5349b10dab69.nq.gz
    ├── 4c6db65a99167d0a7b0fcc875aa8ac77527d36c9.nq.gz
    ├── 4de43847066238f85e4511566007d6ad9aba38ad.nq.gz
    ├── 4e1f78afbe9f877e7628508936571536ff81e0b4.nq.gz
    ├── 4e6d6d35a15d1410d4ae96e14f46a3973fcf2072.nq.gz
    ├── 4f48436f8112e6a1b91e8e158d14dca642552070.nq.gz
    ├── 4fa003d72b0e770e6f0b1386332342b93538150b.nq.gz
    ├── 5052816c5e7b1763ac5ba9c22ec557b2d6c18822.nq.gz
    ├── 51127500dc8cd0657baadc7c984252534bfd3e0c.nq.gz
    ├── 51d442d7f908d8a31185b99bfb3447505507bf2a.nq.gz
    ├── 521aeccd7c453a5b1e1884a3c346af059cb09289.nq.gz
    ├── 52a59f85f3df1bca53959ba5d2cf1e9da84fa0d7.nq.gz
    ├── 538f71e107b259165b28b477a43ee28029547603.nq.gz
    ├── 53aa7a97b8257145bddc1a2811f68fb69d355566.nq.gz
    ├── 53f6be8a89e7467121402e708b6104c18b6dc7a9.nq.gz
    ├── 5535a8da2638030b0b69bebb78cfbc8d1a1ffe98.nq.gz
    ├── 553c6fc43b62b5d86f8aa6a9eaaf741341123ad7.nq.gz
    ├── 557c3a29684fa6155a9e2cbb581d8c3265b716fb.nq.gz
    ├── 55bfd0134b9d18623845143849ef699b0ea4491e.nq.gz
    ├── 56835b8be80198b2b7b63d43535d7bdf0ac8b5c2.nq.gz
    ├── 56c147cba6f5d1dd95151ce30d4e25f1bc84cad7.nq.gz
    ├── 56d1d672b8d265d3d00d9e2cb2f17e286d243096.nq.gz
    ├── 5887dec91b9448cd8fb3ae457add2037a5f79944.nq.gz
    ├── 58a46d949488d491b8a970a290c9ef294506c893.nq.gz
    ├── 59911d8d2c2e0b14f4ac7095a7455f7215b41c31.nq.gz
    ├── 5a00de39bfb1ea023ce79840dacea19757ea1500.nq.gz
    ├── 5a1370225fb481031d547c0b87a3503c5133f148.nq.gz
    ├── 5abdefc1a2aca0e7b7f5c34699e0022877646ed4.nq.gz
    ├── 5baed795cf38798ca7fa03013a1ba74ad40c950d.nq.gz
    ├── 5c956c5bbd8f5bfd1b3c5c3bea206cf85e96ed4c.nq.gz
    ├── 5d246ce34b6612f0147c22a069f77aa27bd7fabb.nq.gz
    ├── 5daa4c9f674403a92117a2f064e355e880096145.nq.gz
    ├── 5e13746fd9616c5c20181b8992163346b2d093f4.nq.gz
    ├── 5e3e1982f0cb422e628536665dc4d67188c193ba.nq.gz
    ├── 5e60ff6ee79a8bea593200fb11ffdb39bd31b438.nq.gz
    ├── 5e6777b963b33903e2340f2bc43e3f1c9d7b645c.nq.gz
    ├── 607d2ebe2fc46c00ec2160c5f744bcc89d5a4b62.nq.gz
    ├── 61522b3f1e13e408a1ed6f5a0a0230e3c400de8f.nq.gz
    ├── 63bff0be46985b7a9af454c5b064c1433b40e50c.nq.gz
    ├── 648c7f88e2d0b1a30898214ba5c107292c5137d2.nq.gz
    ├── 65075db55deb486e771822b45a536d72f69c521e.nq.gz
    ├── 652e1c165031237989b80db1706c8f182bb12bab.nq.gz
    ├── 658a4e2cc1bdf641318a20ce3ced16d196fec0e5.nq.gz
    ├── 66031e14687e01a6e99927084c7f83cfa149f598.nq.gz
    ├── 6647b76f41d4dbf65bc0b3232f0e4f801419c5ab.nq.gz
    ├── 6662416f01821d86ef7df0d0c35c99dd4584a28a.nq.gz
    ├── 66a12bce13f134c4e7d12c12a4e95c78bf0f7b78.nq.gz
    └── 675b99d86fea5f3bfc8088eae3070daccfd59e34.nq.gz

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

[googleapis/google-cloud-go](https://github.com/googleapis/google-cloud-go)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
