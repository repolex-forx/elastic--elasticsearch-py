# Repolex Knowledge Graph of elastic/elasticsearch-py

RDF knowledge graph data for [elastic/elasticsearch-py](https://github.com/elastic/elasticsearch-py), parsed by [repolex](https://repolex.ai).

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
rlex download elastic/elasticsearch-py
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ba53123a99f31797a5e438e4563dbfc5c3568713
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ba53123a99f31797a5e438e4563dbfc5c3568713
│           └── chunk-001.nq.gz
└── blob
    ├── 00c954001cb77b71ba8bd49b1ba20ee9aec43f77.nq.gz
    ├── 01ddcfd66ee6bbca44645c80e885b525c62b52bb.nq.gz
    ├── 02ad2f12e79a29996a6092a223f42916ed694ccb.nq.gz
    ├── 02c2cfbd75565223d13bc66bf0d926cabb8f85de.nq.gz
    ├── 044c538d97570b51354a3897b1302eee3ff7b130.nq.gz
    ├── 0483b3f8027d8b785d290bdc37b850251581bd03.nq.gz
    ├── 06969d9fd06c9031bf7febab3912bbeb73209969.nq.gz
    ├── 06db20d8f844332a4e71ac2c261a36002e930c28.nq.gz
    ├── 06f1008ce7df1600badcf798e1812b78e27843f5.nq.gz
    ├── 075024d3673867c4018a7b81752c39426edb5f0b.nq.gz
    ├── 07cc9d549fbebba1053bd9088bd8f6f8bd55faa7.nq.gz
    ├── 08cabd09693f6b74210c0c8fbee7fd43974c7365.nq.gz
    ├── 092ef6e7ad40842629d1d4b0a8b4848440306760.nq.gz
    ├── 09ee5992595d62d9cff4f42866beb29736042f4d.nq.gz
    ├── 0af7902a402efa6e84786c4cab1d7770c5bb6afd.nq.gz
    ├── 0c7721e3303e9e6543c439349bbc65d53d6fec9b.nq.gz
    ├── 0d76cacfc6ce1435e1213f607bccafacdb2cd6c6.nq.gz
    ├── 0dd4534b26f338d40efc56ee5e4dd239d3ee7977.nq.gz
    ├── 0e2e9f65e9a87fbba909a7639dba15f8cd2867e7.nq.gz
    ├── 0e75ab6c51b6200eb680f4235295c3079af2fee1.nq.gz
    ├── 0eb88d6b137458a27e605a9c88f4e9bdc3b1c313.nq.gz
    ├── 0ef93680ee69d234b6c9da2df4dc2b32c3184864.nq.gz
    ├── 0f2a5076f46fbf476070b68d66119fa9280c1f63.nq.gz
    ├── 0f80fcaceaedcd49f01c0e50c89145b6ca3138de.nq.gz
    ├── 0fc04cfc29bb6c99739184a8ef681df3b5af501b.nq.gz
    ├── 1090015147832c322bfe4eb9d5b2073e9ff0af11.nq.gz
    ├── 10f0be019d55180103fea5bc78fa06f8d1112f59.nq.gz
    ├── 11183ed1e4808c512cba13c0a9afcfd57b24eaf0.nq.gz
    ├── 11b1807067cd0b67964ade977453726aa9f1d1d2.nq.gz
    ├── 1241a7d269c27ea49a45d59500825e387b670822.nq.gz
    ├── 12cf1dac212f6c7828badaed24b21ee47c7e8a99.nq.gz
    ├── 131ba3f8f2ba01112fe919d5ecf58d5458e1f0ff.nq.gz
    ├── 1360db5de16b8c1b2936c4fcfc03d1d50a3d0cdd.nq.gz
    ├── 14522e393beed98d1b6fc491a3b05e4bd9e378f0.nq.gz
    ├── 1516f5346d868dba5ba29143033bf68e48ee6a8d.nq.gz
    ├── 155d8053d7b66de5dfffba81421dc627fbd62b02.nq.gz
    ├── 1577b15f75e9f18a42d3f9b85e1edd6821599947.nq.gz
    ├── 16dc6ebc3f2bdc1bca596440dd9e0b264f90314c.nq.gz
    ├── 1816e6e93efca3db53921aefc2c75f8eda314a44.nq.gz
    ├── 1837f38995d89d232741868007e88780ee79fb14.nq.gz
    ├── 185309639305ed9fcb891fccfc6cd366715bdb1a.nq.gz
    ├── 1858a055a204123e5038b2de919f5f5acf200c05.nq.gz
    ├── 1895c27cadadca5ca51d3bccff4b81f512ee434b.nq.gz
    ├── 18e25a5468ac3078d090b82fc2e5027ad43f3351.nq.gz
    ├── 19be5e48ef45b23f5b7abb0a2490876a4930e271.nq.gz
    ├── 1a0a14bdc4d00bd6d3990bd3e25c1ff7ce60515d.nq.gz
    ├── 1a1361ffcb3eb7d5ae984ae2de55bbab28c05e6f.nq.gz
    ├── 1a1654ace40847e8c2935a5685bd48d58d0deeca.nq.gz
    ├── 1ab1bd21873c780b8f0314bf6e060f3e47834c07.nq.gz
    ├── 1ae0d830b991a6f0afc5372c4741796a4ed1c282.nq.gz
    ├── 1c5929b2be42ede6ce3b446c70794254e1e322f8.nq.gz
    ├── 1c9029e23ebc052b4b4163f09d08d4eeb34fd141.nq.gz
    ├── 1d350ebc2977fb4eb47a743b89288d4d10b72aef.nq.gz
    ├── 1daca10806870ae64aa0864a5646b26b384844c6.nq.gz
    ├── 1e70a342eb90a822a2d11e7e64bd7c585eb5fab0.nq.gz
    ├── 1edbb7e20babea87f5504527189d03f442c87bc7.nq.gz
    ├── 1f12b2a09446c76bbcfac672cc97ee809edee95f.nq.gz
    ├── 1f3e4192bc5e08f9b50fcbfe3a5256b672751c41.nq.gz
    ├── 1f9b196a79fe8588db886732085a6009b5522526.nq.gz
    ├── 1fa7800c66212afcfd8b2c1662ff743af8c7afe3.nq.gz
    ├── 210ef25c7c123cd5b0b7bf500eddc66987bfaf24.nq.gz
    ├── 211fedda635bf5efddbb5174a6cd1fe633758fcd.nq.gz
    ├── 220e41901c5383a4f40e30b8a95e1f14e9bf2b23.nq.gz
    ├── 230c3095c3d8ae48bb5451a2ae42ad834ac79344.nq.gz
    ├── 230ffa85a05100d1b1f4828d7fcdf6361f7b8281.nq.gz
    ├── 2336f7674264d1486f76533d2bf2ab2d2ab68e3c.nq.gz
    ├── 23cfa5c17eb562ff11e2b841a74132740614bc0e.nq.gz
    ├── 242b68d99804d17c8c1459a0343e030126e8be65.nq.gz
    ├── 2469f6b639b411ede3d32952568a721a2e2374fb.nq.gz
    ├── 25ae2ca45876dea2629c3778a384051e378aabdc.nq.gz
    ├── 269e5c18beb78c1206218cc00f8f9b923ebc83d0.nq.gz
    ├── 26e15bc315bbb6faeda8bbd4c7a706d2d3fa356a.nq.gz
    ├── 275200553526a660517222ab34981824fd4e99a1.nq.gz
    ├── 27bf958e0abca1e9a27b9c56f00dcd11947d4d88.nq.gz
    ├── 29151f6fee5ae1ef496e25808a4e6d5bc98cfdd3.nq.gz
    ├── 29e1fcdbe50fdfb44f8335718b993f325599dc2c.nq.gz
    ├── 2a2e20cf0b5811703e50dfc077d1ab439fd16004.nq.gz
    ├── 2a307f89012eef254692e7c7e7147582f9bce543.nq.gz
    ├── 2a6c0681f896deb75e7f2fd3fcf00c890faf0734.nq.gz
    ├── 2a87d183fe6211f828c4b2f6f12eb4ddcbc772b9.nq.gz
    ├── 2c16c93b6e2e0989239e0e3aacafede3509a4155.nq.gz
    ├── 2c5b4ba3a6b320e21b8f97cfeddbb6eb7defaa8c.nq.gz
    ├── 2c6b64a286490da2322b0c2d14d4e02f35ebce52.nq.gz
    ├── 2cc88b81d403872efc04d87197f46b68f71270ac.nq.gz
    ├── 2e00f18c93db8dd7b5c49b22335af968113533f3.nq.gz
    ├── 2f32af3b6a7a92626a488c177964a116bc3012fe.nq.gz
    ├── 304ea62c6c4f8043e61564dcda1811e42fbfd78f.nq.gz
    ├── 3103cc1203df49e9db0967696d1b001226b9f2e8.nq.gz
    ├── 31c18d331f94c80b316415a793c462ccfaef2921.nq.gz
    ├── 31d95a5f26d8538174304ca8ad6a2a19fe64e34c.nq.gz
    ├── 31f9c89ecd0f780d4a4971765db063e06effcb1d.nq.gz
    ├── 33e1646ec23dab1eda7735989bf173e02ba76e5a.nq.gz
    ├── 340a95e60b5a06c38d72fb9303fceb4498e702dc.nq.gz
    ├── 341d19fdd7c689b8ecde935ed27323055b09d541.nq.gz
    ├── 349d2c1d61937184c7c9e5893df5385ef78217e6.nq.gz
    ├── 352868b73fb1e4eb0ddc319909822bab4b512381.nq.gz
    ├── 3557e85c58df4dba36840d7b1b7eae50c6961821.nq.gz
    ├── 35a1df0e308c0d5353b8984716fe64fd91a8ca38.nq.gz
    ├── 35d48c1f84fd76e6aac0e7ee11ddaf87a16b842e.nq.gz
    ├── 35f2440da49feea4f46c98d364c88e60e7545ad4.nq.gz
    ├── 371ab5d65cbd8923f601015f43ef79d8b6b68ada.nq.gz
    ├── 374f36af553a32a24b84f8530f053471f3c4bf37.nq.gz
    ├── 38d6308d536f68acf551c8fc4bdd4957bb8e88f4.nq.gz
    ├── 391042f13c4e6367f599dcc82c3d1af95c6a1306.nq.gz
    ├── 39ca9ab8f1fa3ee0005e41b4c5a2b169a7891aaf.nq.gz
    ├── 3a3345871cc2902ed58d5d34a0a6b80ac803c1cc.nq.gz
    ├── 3abec964f3e9634d18246606f60d31cb98d276d7.nq.gz
    ├── 3b030c27d003e22f029b946c825ac940a48888f6.nq.gz
    ├── 3b58c3f016c63401c2260bbf59c69b0c95ba453f.nq.gz
    ├── 3b61c96e5f1602e85397669accc11b9505527724.nq.gz
    ├── 3be18be28d00aaea3e6dcb81766a3892e546fcfd.nq.gz
    ├── 3c86a66ca73f3d86d8e7804a6ea2c83f43238a14.nq.gz
    ├── 3cabc3382defbb21e0767f0d0ff6e45d8b6eb381.nq.gz
    ├── 3cf758d97004525c2a8669108a039b01fbff4e10.nq.gz
    ├── 3d588dde2ef75b6d7852790ad5f75f9b41572189.nq.gz
    ├── 3d9beee42ae137b25a067460a0ec7e222426516b.nq.gz
    ├── 3df32bd61021d24157f8a95f35639c99537a408d.nq.gz
    ├── 3f7ab3deee5243acfc519dacc13edf6902e57517.nq.gz
    ├── 424726c8e62e9cd57afef736b56295c4d1d87696.nq.gz
    ├── 435e9f6081007d8190c1815a683e2e3a91d84354.nq.gz
    ├── 44157ab00186a57da99408d15c4d4106464d002e.nq.gz
    ├── 4422e2335cf5b3f653b48c5df8b1be306f744462.nq.gz
    ├── 4458d2c857f38262bb66abcabbb99a9ab9646412.nq.gz
    ├── 455b6a2207a486b46d6e05e4e4f2ed21d9c06ccf.nq.gz
    ├── 45cb8338849d5b5f7a99799ea0728846cef5a720.nq.gz
    ├── 460e9b6426b61612eb0c87eee98874f698decb6a.nq.gz
    ├── 470fb6c3a3eee02424ba4120e00c6f347553ba73.nq.gz
    ├── 47dc9dee62d02f22e0821dddd825a0b3e72b4e5d.nq.gz
    ├── 47ed9e030c43462b465a7e872e66e57116c86c1a.nq.gz
    ├── 47f9418336de7850c85e9b34a3742ffbbf70e375.nq.gz
    ├── 48212d2f42f515d029fcd0eae75008cb25177b3a.nq.gz
    ├── 48329183caebb4937e20c5f78b23877fdedbd286.nq.gz
    ├── 4b7b978c511bafc2290b27520345d5d86f4a2d73.nq.gz
    ├── 4bc3af87a945464205fbefb92b3385201a12a3ad.nq.gz
    ├── 4befbcd9581881e8a354d1e72c02ebd3bababa62.nq.gz
    ├── 4c986a6ed5742a73310f16a99cdb93c5e4844a19.nq.gz
    ├── 4ddd520bcaaa57a7fd210ca1d9775dc300f781e0.nq.gz
    ├── 4e880cc03c83aa196bd617916c2cc0b9926fc0e5.nq.gz
    ├── 4ee080da8aa5bec08e9cd2ab1e915ddacb5a34bc.nq.gz
    ├── 4f80d30ef8513635b2b19423a99df8c29c9178b5.nq.gz
    ├── 4faddeb83e333de9edb19d1aa26f47c25666b666.nq.gz
    ├── 5007151bf8a37b3da7dd25f1a872d628cf90a24b.nq.gz
    ├── 50cdf22c16c45447af210e93b3e37b12452b8e09.nq.gz
    ├── 51098d6138071034e9c88c84d375a1028f453a11.nq.gz
    ├── 51a025513ba371f9869eecb9827d33e713065f38.nq.gz
    ├── 51e0a88f20b40390e6f2d60e1e3f0628230c5ae7.nq.gz
    ├── 51ebb80411a5a8f3ba1cf3919c790712d13e42f9.nq.gz
    ├── 52477014cd6782ce62ae148abe671e91aa877ee4.nq.gz
    ├── 52702d084e7767e7a91cbcf3c936a11705fc2736.nq.gz
    ├── 527a3cbe23754c578f1ff115ab7f20efa7b44512.nq.gz
    ├── 52d65d0bf7857d96937312f70daaea896e3ce59a.nq.gz
    ├── 53ab5fcecdc3a32dae6861f2685806391c2b0ba4.nq.gz
    ├── 53f7a6681fcaf3ab44302e063b4a6f724ea1077f.nq.gz
    ├── 5422d12d18ab0b58424eda5e1640bc9581f59496.nq.gz
    ├── 54d35a87f72b56bb0695a03964aa14d6af4274c8.nq.gz
    ├── 55663fc1bb97834d9d02291c5d499d78851d94e5.nq.gz
    ├── 558cc0bd3eba4c1d645bcee1624fd2036d382893.nq.gz
    ├── 55b8271c52dec43d2a154d20cc5acc07705dee49.nq.gz
    ├── 55fa331a214dd04b90f5329dc3255bd31a6b7a46.nq.gz
    ├── 569f9d2ad0b70184e2a7571a4dcc5e0aeafc7077.nq.gz
    ├── 56a80efcdf64c313f07c170ce2ff199f42325dbb.nq.gz
    ├── 57c17674315cf3d9b401261404eb74b6af452488.nq.gz
    ├── 580779626795fddc4f58e417a22e61aa221b49e7.nq.gz
    ├── 58ddd86d24abbb05dd11905015b0bd8adc59cd3a.nq.gz
    ├── 5908fcffa2f1313bff3a82af924dd85f75ac5e53.nq.gz
    ├── 5a1aa8a017200f18b37cce6d2eb746a8a75cc8b3.nq.gz
    ├── 5aa8a29e7e1e524ae59bbbae1c89b8195aa3c2ab.nq.gz
    ├── 5ad7fc06e79e57b63e527c8070aef60f42b73efc.nq.gz
    ├── 5aedd6b3c532ce0ce60bba44aef7701352d299a4.nq.gz
    ├── 5b86d02a88ba88801340bbf991bbf4c36b946f16.nq.gz
    ├── 5c0150eafc5c2fb1dd7d23635e454f383e36d1e2.nq.gz
    ├── 5c156be061eba4a6b6f9856e843b2e60d58f5391.nq.gz
    ├── 5c708c78b3db9767a98616d54c641083b69049c1.nq.gz
    ├── 5ccef54b744a33e7cd96ad7a986c8333ab9b523c.nq.gz
    ├── 5d54bde0d60d4110950df17cb0478ed510762aae.nq.gz
    ├── 5d577108a748c760fe3e75ad75a9f8cc593630bc.nq.gz
    ├── 5d821b2071280689eee632f2749d2cfcdf91eeaf.nq.gz
    ├── 5f643884b05bc05697cfa188a828881af4a5587a.nq.gz
    ├── 5f80de6e324f91ab4f4d08fa2c831cb021b9d462.nq.gz
    ├── 5fc60460c6d1f600703d4e4c36169cf611213e41.nq.gz
    ├── 6049426e5b0a55570124a06fc36dfab6bfa0b636.nq.gz
    ├── 604fd244911753113bd5a7bff416059fdd511473.nq.gz
    ├── 605a6ceb6ed47be88f566a624fad5f452066e0bc.nq.gz
    ├── 606ac367bf4e3911c611a91a44157ac10b4adeb8.nq.gz
    ├── 60b08876110d3d1d64dcaf0766d6d5e4f4570cd2.nq.gz
    ├── 613da2de006ed6a031a0af8b00291e49b748d32b.nq.gz
    ├── 61b2c90fe56f11e306fc3220b95ee46a0686bae4.nq.gz
    ├── 61d7fc15845e20fbd42d45b35ac88909362539a0.nq.gz
    ├── 62a9e9421b528f4acb3753fb582f62dab276ebf2.nq.gz
    ├── 62ea35cfd24fd1dbfa23fe693c3e13be34cadcc8.nq.gz
    ├── 63436572c4142fde94b3fbe6ed4c090d32a27bb8.nq.gz
    ├── 64164c66e0255037d540343d3d0cec63e1823ae3.nq.gz
    ├── 641e78f4b0ac45f939206a2a9149e5de4f01af18.nq.gz
    ├── 654e8e078e4db83baeba6a097101db5f419f6e9d.nq.gz
    ├── 65a5725cfdc930582f7f407d6245a262a4607856.nq.gz
    ├── 6607a5085ebcf9c6081d70b98a391129a0c7364d.nq.gz
    ├── 67df96154e7957404c99012a8903d1ca6ab5f55c.nq.gz
    └── 685c48a979bb8c4b9b7ce121450084b7a3a54e28.nq.gz

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

[elastic/elasticsearch-py](https://github.com/elastic/elasticsearch-py)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
