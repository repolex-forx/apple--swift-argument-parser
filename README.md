# Repolex Knowledge Graph of apple/swift-argument-parser

RDF knowledge graph data for [apple/swift-argument-parser](https://github.com/apple/swift-argument-parser), parsed by [repolex](https://repolex.ai).

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
lexq download apple/swift-argument-parser
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 626b5b7b2f45e1b0b1c6f4a309296d1d21d7311b
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 626b5b7b2f45e1b0b1c6f4a309296d1d21d7311b.nq.gz
│   └── repolex
│       └── 626b5b7b2f45e1b0b1c6f4a309296d1d21d7311b
│           └── chunk-001.nq.gz
└── blob
    ├── 00997feb59327733660e051871d4c72210b82510.nq.gz
    ├── 00b8f60d04c45a77798bf0a84f78bebcf2bbdc01.nq.gz
    ├── 015e07a78e8b90798b42d67509e2aad55008eaef.nq.gz
    ├── 02088dbb344bd1c9424a2b979da672f9c95dd318.nq.gz
    ├── 024a0232a2b11aaa9627add7ce803709fac197e4.nq.gz
    ├── 04f0ac9907ea2214b88b0216fd13c72ca2dac849.nq.gz
    ├── 0525724b129a5f75768c67c68cb256f1a94ff15e.nq.gz
    ├── 056c222d722819903e89698a8b02319bdf322395.nq.gz
    ├── 0589dd167823c1c1ec4b069c72ff515a8b12e25a.nq.gz
    ├── 059c2d6d7a8f736d485faaed6e3e1b3dbbf9377a.nq.gz
    ├── 0730e6f988a72a7e2aec99dfc550744d1d4edc46.nq.gz
    ├── 08a7df1ba46eec69568b14288103f29543149a31.nq.gz
    ├── 0999d9148a57c251736bba0a1b2f01393b43280f.nq.gz
    ├── 0a0d82cc10885b4d249affec0816b60e35d65f30.nq.gz
    ├── 0d32a35c778015d03179bf07fbb0439b561589e2.nq.gz
    ├── 0e2076727b86dbe1cf8bcd8cb3a7c12acc8f1be4.nq.gz
    ├── 0f5518ba84ed991b4adfbd2a00b04690705587ae.nq.gz
    ├── 0fd19c10de6c4577aa815600b27a2dbb02734541.nq.gz
    ├── 1030163908220565530b9b28352af186a9f99ce9.nq.gz
    ├── 113f422a2ac9a870b0e247b84ac129085250248b.nq.gz
    ├── 1199b9e74663587c4b97a5d3695d87de04ef89b3.nq.gz
    ├── 11d90e568a2223abef6e95408f11f78267241d55.nq.gz
    ├── 126fb013414371d9aead7adcc432e423e2c9e9e7.nq.gz
    ├── 137fcdc0ef8c68f7d4b1e575ad9c0b6616654b0a.nq.gz
    ├── 15b522fc4ba5a0c8645beb1a949315cf7aedb720.nq.gz
    ├── 17171955b4c84f6bc034a341fc1f6e4f07d9cffc.nq.gz
    ├── 1738a8cb54c16389ca48eb20f109dc7e6dee19c2.nq.gz
    ├── 180a9a2dfc62c994c743ef236df0d5c6a3ed077f.nq.gz
    ├── 1aa38453095d57e8dacb6d97e5aa9db07d3301ee.nq.gz
    ├── 1ab4ed81ac3c0118b8e9c52654217fa50714c584.nq.gz
    ├── 1d30ab45f395b252afca732cce8b984b9db1ad7d.nq.gz
    ├── 1de975b216ce133b1247d1d796139a3b885293bd.nq.gz
    ├── 1ed0d9f0dbf1145af0a35a6b2da0ba563d981ff7.nq.gz
    ├── 1efd061538ba2a8286c91f54aa16b5e14fff387f.nq.gz
    ├── 20530e99ac06d6d0c4d62f363dadc578308c8071.nq.gz
    ├── 212cdb21353cc756098b8b778a04ff77e631ee70.nq.gz
    ├── 254b446bd155e4275c7f324b3423549440128bef.nq.gz
    ├── 259f4946685a6b0306399273129583993b6f3d7b.nq.gz
    ├── 264a2d4185066b43addb5b14d4128b56c2525092.nq.gz
    ├── 269b425b7d4a5cdc78db6f9414cc8d58d2bd62e4.nq.gz
    ├── 275d8eff14735380115e736493029964064ad76f.nq.gz
    ├── 291821dd9d8edbe3078b041f538228f94926995d.nq.gz
    ├── 29373de9b26438559e51159c8962171cde52ec35.nq.gz
    ├── 2974c4ca12624a2d06996dab1817e1fe3aa6fa8b.nq.gz
    ├── 2b0a6035582f1c83c23011c1190bb23846a824fe.nq.gz
    ├── 2b401b9b85e54a85462c2db8eacf35e583119ea4.nq.gz
    ├── 2b6e4f1ad9c3501c3423acc17a0d9e3a2be4d1d9.nq.gz
    ├── 2cc2fdc676991e8a6dc8bd0c34bf36791154edb9.nq.gz
    ├── 2e25e31f407e10b0685a3f5943ac93a68228eac0.nq.gz
    ├── 2e271928c62dfd3dfe662b960db9c06bc5ca2510.nq.gz
    ├── 2f2604202b6d066f804b2ebaf0061898c1c4760e.nq.gz
    ├── 306fae0d06d46750423e3f48f7c6ba042473ca73.nq.gz
    ├── 308da9e8edcd7a719a06b864767ca81b6fe48581.nq.gz
    ├── 3330d617b3c6f32a461a0579eb56ad70c441f06e.nq.gz
    ├── 3383c4302ec94ba81415320f68fb123f9446b795.nq.gz
    ├── 35f78d16808cd583d26627de023a25a3d627bfe3.nq.gz
    ├── 37e3f98b6134a958ca1080bc725891efa8ca315c.nq.gz
    ├── 3a900475594d498316c2ece76d136425036d4d79.nq.gz
    ├── 3b6d74fdc77c27844490b2e88a0d2504af3d0ec3.nq.gz
    ├── 3c4e6453ec1a988c62526e5eb7f21219afe8d53d.nq.gz
    ├── 3d671138368e76b27656a51af5ed4a41053c9c29.nq.gz
    ├── 3f748b54fa49bdda6d5da9993c69555fd38c3d0f.nq.gz
    ├── 41920e8c3d75e5b4f8f8ee3d93c712165a8ff2c6.nq.gz
    ├── 432e78e5deadfdf7fbc34e5ccf3d723db6058ddf.nq.gz
    ├── 43398f578aae1f7ce7f429e55f836cb895abf117.nq.gz
    ├── 452cc63541363ff78bc5e36c84acb3eab7384d27.nq.gz
    ├── 460e4013e7f802828393d5d4cda2830df72d71f5.nq.gz
    ├── 46f2ad1d415b1385ef089ee83cdba877096a4621.nq.gz
    ├── 48d93d7cb76d4c5f48aaa2d08e39605a45be92ae.nq.gz
    ├── 4927e5b572a1c14da2cf21baa24bca95b1b4c93b.nq.gz
    ├── 4a4ba4334b993d827f1aee10f5f021998bef7f30.nq.gz
    ├── 4c6e5041c4307f2b953be17b390055d442964bef.nq.gz
    ├── 4d46525519914be1a54b7a435806f25d0e66a1e5.nq.gz
    ├── 4f7656368176134f2a7a1e424709c9beefa067e6.nq.gz
    ├── 4f853a5152e135ce13fd83779e8d387c9f1dd1fa.nq.gz
    ├── 4fc313042fe15c5d698cdb4fe99e93b3128a188d.nq.gz
    ├── 5144f8ca78378176a88d204eaacd989349eec691.nq.gz
    ├── 51568de7c888193a8ce67e9e74e120e16064a168.nq.gz
    ├── 52980e109b532f4ee04d6b38e905c723ee8fefc3.nq.gz
    ├── 54cc980da364a6a8ed229cfa1e3eaaab7fa7a3da.nq.gz
    ├── 568fbeda9bb15c72fc2ccaaf20a7ff1feefc775c.nq.gz
    ├── 58916292721a1f936ac8b827285f284440165718.nq.gz
    ├── 596f003c442dbbf07be3577db51ca90682509036.nq.gz
    ├── 5ace4600a1f26e6892982f3e2f069ebfab108d87.nq.gz
    ├── 5adc83fe61e12e6ea3fa67cbbbf24b2f1bc676ad.nq.gz
    ├── 5b584df63ae984c51b5a7ccb2f2f1f92d097d9b8.nq.gz
    ├── 5c37ec34fabfe10f45e2f2aa790e93b3c32c6ee0.nq.gz
    ├── 5c5b4e4c90775ab161db48f8ca1035f8308f4ed2.nq.gz
    ├── 5ce6d8e0f89322faf3207e69e84d0f6ece79e7e4.nq.gz
    ├── 5cf0d7aa79b56f6f90a16aa3d88fb2dcf244f72d.nq.gz
    ├── 5e17f059d8b6afd5385ed9db4c531ea25c4b1937.nq.gz
    ├── 5e341e92a203cf05006051e22dd415481592af51.nq.gz
    ├── 5f2728defe03c879f4057ead5df0c21295530a69.nq.gz
    ├── 606c4d86a2c5f5e03d37055a774db532698c2b22.nq.gz
    ├── 60f104d78d38aa84a013067151f35d6b35e9affd.nq.gz
    ├── 619e81d1cefcdcf417318fffec536c281d29ea3d.nq.gz
    ├── 61b0c78195f2d00acaf658000eeca6ad406a3a29.nq.gz
    ├── 62114659c833d921439705ba8f7329055b7e7537.nq.gz
    ├── 62b3671967bf496c5c7212fd5145a760c5923051.nq.gz
    ├── 62c87a28798c602c2595395852567c8faab92db0.nq.gz
    ├── 62d0d59d3a306a088f2caa880503665bc2e7561a.nq.gz
    ├── 62f95d8feeec2e450c451d300fdc1cde407b1155.nq.gz
    ├── 63833aa9b09f7892cb5a5cc879ba858c3b43297c.nq.gz
    ├── 63e63cc562313d37a4c4636d19fac02a83d53294.nq.gz
    ├── 64f1ac0e033956c87ed8c0da729bc0f8339a944a.nq.gz
    ├── 6502ce8a5ce947074e928375e53b1f09b88aa786.nq.gz
    ├── 652723f57324039dab1010679006fb8511cf5971.nq.gz
    ├── 656e1c5a3cb0ab3d1158cc5e82d06816816df7de.nq.gz
    ├── 6968cf926fea523e557c106e8a1d98e1461fd95b.nq.gz
    ├── 6a37c14b2ee460db67cc2aa3137e849ae7324cbf.nq.gz
    ├── 6c1106891d0633a747c55e6cac7ed88731f5c527.nq.gz
    ├── 6cb5d81c55049769bef6749e3994ff6c8620c8a6.nq.gz
    ├── 6d16c6da3a1b5b8bbb90387db352141590cec8bc.nq.gz
    ├── 6d8eb1aa8150e273bb800cc35a4bcdf00fdc14d7.nq.gz
    ├── 6efb2a55c06b44bc2e94cad74aa55980e6e5f004.nq.gz
    ├── 6fe01bab3c5d165b9556e5da7647cf32a63ce868.nq.gz
    ├── 704d470b4b7a5848765a1382742b2c814705bf56.nq.gz
    ├── 70d3eb3a9eb0e1892772a2964d6ac27789232126.nq.gz
    ├── 70fd11807f3b9a641ab9ac099c217a1183943095.nq.gz
    ├── 722245fed5ecd5978a6aba9c1b8dceb5a8bf5cab.nq.gz
    ├── 723fd733d0cbb434e6a5c5be319a3fa00009668d.nq.gz
    ├── 72422320e05d50f6ab0b21c0b51685ede90e9904.nq.gz
    ├── 724dfab1de7e453012c574755803e2bc3a9b7e2a.nq.gz
    ├── 7282d556c28e638c2e03165b11b8790b2cfa61a8.nq.gz
    ├── 73e953909981bccf79d8677d8236de8b897034de.nq.gz
    ├── 76bb1b925c0f9192cb1b386eee6856a96a0e19af.nq.gz
    ├── 7733ce90b1118d886493af1747a8d207a040c2c4.nq.gz
    ├── 77821be474be12c8023402a150d8ec6c7eb73491.nq.gz
    ├── 77dc92e5431dc646840807ba65ac5dcab8573f81.nq.gz
    ├── 797b9928b06839d4419b233a20b4de7e5acb8128.nq.gz
    ├── 79a10493a5c865acb37faa7bc9713fb8bc21d9ef.nq.gz
    ├── 7c8a99b3405b42fb08b43681d95751f93aea3ede.nq.gz
    ├── 7cbcafeeaa00f18133b874c1243b5b74744ae74e.nq.gz
    ├── 7d15530a2573da9a97bd971ae492225ea4229bb9.nq.gz
    ├── 7da01924f24707205deef4755492c8e0ee488166.nq.gz
    ├── 7e9ea67f2bff7a7549a98f8de70e56f9a7d859e0.nq.gz
    ├── 7fbcd4a6ac8ea70ec011f12b5e5383b80eb6f824.nq.gz
    ├── 80e192ffe44bb6d70606aee8b3acca00e605ea75.nq.gz
    ├── 812cd0142d90b994e01b3959ad7411123cce5548.nq.gz
    ├── 825799781f8d76a5e07d9ff3048807e57fb67689.nq.gz
    ├── 847a7646215be66e9dd9b264f8ec8f58009b7b3f.nq.gz
    ├── 86c62c64f6f69cd09e91fd131b63be55b0717ea9.nq.gz
    ├── 86db8ea07cae44f61e232458595177468d100c7a.nq.gz
    ├── 88e31ec33b9fbe9e0b921b1c7b09d8110ebe46a7.nq.gz
    ├── 892372210c8081c3939692416471d3cfa7e25742.nq.gz
    ├── 8ac5d396a8f991e900cfaab4c39bdaf8b19254a8.nq.gz
    ├── 8b0594d3feec3a874709566d11b89605b91e0cab.nq.gz
    ├── 8ca7f3a06c47ce44e938f67b92e119488f27d247.nq.gz
    ├── 8d8d096380ef38ad7543ff003c2f56510b10d7fe.nq.gz
    ├── 8e0bd387403060d2e6d1a06a6d11577f3c8a5c09.nq.gz
    ├── 901f01a9d95ad0c127a493572b88a738a0d09e39.nq.gz
    ├── 92270756255f95e7f330d0c62522c178f56cdce9.nq.gz
    ├── 922ded496623a2fc22acddc4aa3956df9da64666.nq.gz
    ├── 9364a15907bf47330ba076b81725a3664f64e387.nq.gz
    ├── 939558d972fbffb94bafeb2501d6880bdb4bdf3f.nq.gz
    ├── 95b84438d5815620928df94b34f1e515e8b8d551.nq.gz
    ├── 960280579f67ec51232748e0cf27a63dd74e6af9.nq.gz
    ├── 963525d17e09c81fc7d3902bd223ea0fa2520f32.nq.gz
    ├── 99288bd7fdd1374271ae9a81d87a0d819a0e2305.nq.gz
    ├── 996bb825c69fa705b123dcbe4209b70135b1feeb.nq.gz
    ├── 99f3a88794d30861f55a2af253f0fe8f44af3bdb.nq.gz
    ├── 9a0395e422c0dfc832aabd98cf1d5245c140a27c.nq.gz
    ├── 9a652479cab818d547225d0e022dd14d86f88ec5.nq.gz
    ├── 9a80db981d7069be685ee06df8d10196d4f72ba2.nq.gz
    ├── 9b4d0aa6c12032c7e05e83d39bf0720d31e7a3aa.nq.gz
    ├── 9b5ebd6175ffc4be5f016314bb6e7c70d59d851e.nq.gz
    ├── 9ce4d995a04ac9e5a9c793ecfdb1701baca959dc.nq.gz
    ├── 9db6fa5331b9173cb78b11dcde9238f3ba86d23a.nq.gz
    ├── 9e1466b3a79a6ecc1557698129065c64a7fe6852.nq.gz
    ├── 9eeeb2b3ca421910833b7ad6813d28607c21ab19.nq.gz
    ├── a154961d8d08edee07cc60c96efdfa621bd30442.nq.gz
    ├── a1bab75c59c818bd0ea07f3e52e95c982755376b.nq.gz
    ├── a2550bb9bddd02a995c3a3f4709c4990331513b1.nq.gz
    ├── a27eaa2211ccea118b928f985367da16f5f5d033.nq.gz
    ├── a3f3c31c001c9ea706e7fa7dea23ed49ebbe9b0b.nq.gz
    ├── a7a069d772405bfcab9cca3c4e2df30d850630de.nq.gz
    ├── a823574c75da00d21129faa41c368dac384f21c5.nq.gz
    ├── a9069a6357dc81d0024a15a0f2499d99cad02a68.nq.gz
    ├── a976f26dadf9d40111f84ef3c985357a51ee8b67.nq.gz
    ├── aadec0564f45c356df640f5bfea5d263b3fdb713.nq.gz
    ├── abad256504027b6ff81166956e892bc4a632392f.nq.gz
    ├── ad10bab031bb4e1f5946f86b17efae7fa2633fec.nq.gz
    ├── ad98cea3daf6c1c4dfcadf165bd6086593553b5b.nq.gz
    ├── ae0effece6d45b1ea90be34aa42c356b8df3c0aa.nq.gz
    ├── ae5f85a7040e5f2b474ff2fe43cc70041dd6a616.nq.gz
    ├── ae9882c34a88b671629865eb9a1d7d24f5f75ed7.nq.gz
    ├── b05aef6e5e1a9370a96d5e6c07d884e697f29ae7.nq.gz
    ├── b0aeb07e0bd84eab98ea5b394b5dd19d85bfc1cc.nq.gz
    ├── b1772e671ffba52918635c567f097b6dfe71fc04.nq.gz
    ├── b21c98ce0da661c6e4045684c4827471c4554552.nq.gz
    ├── b3ead232fab53ae7ab692eb30e2b37cf5aa6921e.nq.gz
    ├── b59aa80a87d84fce07a683aec05e8283ffa52d89.nq.gz
    ├── b6c295e1b5e86a132a004af0d4c1e22c9cee9722.nq.gz
    ├── b788802e7b6ec036f56e9cf9314a38024961f6ed.nq.gz
    ├── b82adb71d072d8f63b8f0e2b8e94087a6623f814.nq.gz
    ├── b95827ee29fc60149e79aa31d5d9e9fa384c9cc6.nq.gz
    └── b96d7ace959bbdc55439b3c12db6f48ad433b388.nq.gz

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

[apple/swift-argument-parser](https://github.com/apple/swift-argument-parser)

---
*Parsed on 2026-04-21 by [repolex](https://repolex.ai)*
