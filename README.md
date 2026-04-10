# Repolex Knowledge Graph of jadejs/jade

RDF knowledge graph data for [jadejs/jade](https://github.com/jadejs/jade), parsed by [repolex](https://repolex.ai).

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
lexq download jadejs/jade
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c1156948afb5a078449eca10ad26ff3ce4fd7a2f
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── c1156948afb5a078449eca10ad26ff3ce4fd7a2f.nq.gz
│   └── repolex
│       └── c1156948afb5a078449eca10ad26ff3ce4fd7a2f
│           └── chunk-001.nq.gz
└── blob
    ├── 059b54bd214a40330159ffb4af9c41c7eda4a7aa.nq.gz
    ├── 069467774f085d610a916cc8993a13a27592b8bf.nq.gz
    ├── 0767f5f533dd68bea0f43585b6e95ed178d1037c.nq.gz
    ├── 0771c0a4ec6b83a1a66b615d29bbb6227d5053cf.nq.gz
    ├── 07868c2e82e1c377c8e12006c7aee8dc58855902.nq.gz
    ├── 094e42af5f83abcd18e8e6e133b2933711f334e0.nq.gz
    ├── 09899923a40f3f44b9929086407425952af4f07f.nq.gz
    ├── 09f00fd7a4bc5662ae99a2ee20c703fcc370980b.nq.gz
    ├── 0c14c1d7f8c3a21d67b56409dd44aa42ef245dd6.nq.gz
    ├── 0cabc6481acd520a2c53dc55872d4edaa1953192.nq.gz
    ├── 0de55bd88894752cfb2c7973028730cb2be1bbca.nq.gz
    ├── 0e5422d38b74c01c2488b48c72fd60d63b2fb58b.nq.gz
    ├── 0f3c76789296f12b9e911c543d98a1cc507cd8a2.nq.gz
    ├── 0f93cec26f2260f03407cb4074b6b37ad304d15b.nq.gz
    ├── 0fbe2ef0d269b8cc90ddeb117a61a7035f90326f.nq.gz
    ├── 11ff9bc49a1f573ea8657ee05dfb3850d67b8bc5.nq.gz
    ├── 13077d9ef49eab32a2d04d0deb80a2f29f51e2df.nq.gz
    ├── 1428be6d51773f84c10b971eeb3eaf575027d534.nq.gz
    ├── 165dffb0bb7716a6585f97ee4b67eee2e7e38821.nq.gz
    ├── 16808f6cb71ecd4e097f72c48cb7f26dbbf940bd.nq.gz
    ├── 168c549a0521383a703af0f21f19c4e32e63799c.nq.gz
    ├── 17ca8a08c1c5561a0f7f358886485bbde220d7a1.nq.gz
    ├── 17e775950ff8ca2ca495368ad20d0dae4477798e.nq.gz
    ├── 19842fce02bab01ace2b1dce1db79f5d248b9eb5.nq.gz
    ├── 1a3d6199a1d79151d4cd26fffc0c9f2b3941a21a.nq.gz
    ├── 1ae990942dc8f48b39d1742072a1b70e3ff8e513.nq.gz
    ├── 1b5238cc6636e057c23be22031b0c6fa8481f423.nq.gz
    ├── 1b558720084af5d22b7b15f8f3be5a1ff1fab4c4.nq.gz
    ├── 1d2d2d38983b8b91b5a3bb2d09f8545bb8c70174.nq.gz
    ├── 206c74019342f14a6898f28f1af4d1a35eb32d22.nq.gz
    ├── 20e086b544be18f6805577ec823f88b87ea8a4c4.nq.gz
    ├── 213a823c454ca91fb4b893ee74a6ebf81e57fe9e.nq.gz
    ├── 21958a85e53ff4c1bd69dd48038cd0707d9dbfa8.nq.gz
    ├── 224225f3345922d2e6cf9228494e1acf94698893.nq.gz
    ├── 2439cfe257c7fe9f7c13ffc1cf8a4ff679d2b9ae.nq.gz
    ├── 2511f522ca1484aa5b77031e99a18d8d262153ac.nq.gz
    ├── 25ee9e0cb4edbb9a57586f798aeed4a64846da5e.nq.gz
    ├── 265bce2b80e4cf49c4ae719e4b50187825fc24dd.nq.gz
    ├── 2729803d57133949d7d629cf43d1845a79a7c09a.nq.gz
    ├── 27794a4aa5c1b566704bc62de3a245b72e1e5346.nq.gz
    ├── 2b21fa408254bf02c81b79700a50f2416ed2e3ef.nq.gz
    ├── 2d8c161f8437743be18ee22d9cf782f99219825e.nq.gz
    ├── 2e33e5b0eae9c98fcaef5a90128733843a8f66bd.nq.gz
    ├── 2f478fc302e6eeacd0b3647d41512fbfa01216d3.nq.gz
    ├── 30623644b72724af29124aa794f6cca74e1f20ff.nq.gz
    ├── 30c9990dda6987b4ec393be5be945f02f3b786cb.nq.gz
    ├── 30fabcf33de6022279def4edf93a30a80748e2a0.nq.gz
    ├── 323d29c4e33f37aa9841347f147e0c3e433e5e13.nq.gz
    ├── 345cd410f8d802dfe430f68be51f44697c4e710a.nq.gz
    ├── 347b4c80c810fe190bc7bc8ab789e89e94601871.nq.gz
    ├── 34ccdda1dda8b80967b4b4b2687666f96c507bdf.nq.gz
    ├── 35fa2aaf22b8b991485b45dc65d51fbf973ecb48.nq.gz
    ├── 36a4e10d35c5f7f3d2346df8359347148e6c9b3b.nq.gz
    ├── 377acc8611e31279ed2cd8c18550361a1c0feb30.nq.gz
    ├── 3ab355a6a45d1f60a394977be6dd2a4e962be359.nq.gz
    ├── 3cbf016665f2c5529336e93eeb2294ba189533d7.nq.gz
    ├── 3d014937f136fc37879c796b4bb8dd18d728dadd.nq.gz
    ├── 3d2faa10805fac162f56ddc49f8f806f527df981.nq.gz
    ├── 3dd566e0d0c92dcbc37d80cce6c3d0d3d80fa20b.nq.gz
    ├── 42264334f14ca44e89627b51c4d0e4f577bf141d.nq.gz
    ├── 426e459a83800d57fa5b4851538c5b6e0354dcf3.nq.gz
    ├── 45946b49cac24fef67fe5be9a44a7f360255b21e.nq.gz
    ├── 45ca24a33ad9f82eaed3faa9fcbe8e2dd7f0250f.nq.gz
    ├── 46451a94575432e2b8795280499a1983638afc6f.nq.gz
    ├── 4659a11923de0733dfe80e3ea87577f68a1688ea.nq.gz
    ├── 4698dd9a5c4a5c250a4d62271c54a3b388855015.nq.gz
    ├── 470c47654100f52104870650d7fb784e8b8bd881.nq.gz
    ├── 471aac8855797315316ed4fdeea2c2d46674a023.nq.gz
    ├── 4782f430a41ef7a8f9bf5dad151dab3c95384ce2.nq.gz
    ├── 48bf8864d3de34da104091fff918fae91049b2ad.nq.gz
    ├── 491fc70bd4bed756430e1ec08f477bbb82eaad78.nq.gz
    ├── 499c835c5b93ecf87723401dbb0cc1f49babe4cc.nq.gz
    ├── 4ce3a6fff5c2b7e166891a9aa9ef5b843751b266.nq.gz
    ├── 4e1c895ebb56f3e245e3813181e4ea8d6909e444.nq.gz
    ├── 4e4567125a4fdf3989d1e3978efa99d163198951.nq.gz
    ├── 4e670c018fa47a1ae11fcea788dfec9432d05400.nq.gz
    ├── 4fd9aa0d786926d120f1bcc94f4cb99810771abc.nq.gz
    ├── 516d01b8362a4b7cd5f8ed4535ff30644b18d3d2.nq.gz
    ├── 520761b4cc1efa737435778c6d9fa1059216a014.nq.gz
    ├── 5346ac94c9f396a518e25188a6383ee726f12bb3.nq.gz
    ├── 53bac827aedfa6286f28c6c9f07d60c3336eef0e.nq.gz
    ├── 53f89ba6ccbae83d21b0e1909dc4a892b74d9a27.nq.gz
    ├── 54a2ea265a25479c69e938d62cc5ca684274ebd2.nq.gz
    ├── 54b5f4de8a3c2340f338a7dfd2ad1280ba5939da.nq.gz
    ├── 55fbed19dbca34c6cfcd156aae109ee366fe550e.nq.gz
    ├── 5634861277d951ca6abf0cece04e710a30df2430.nq.gz
    ├── 56b3385996a39886119cd0841613c2e46a0e6509.nq.gz
    ├── 5811147033f0b6d5c47c774c9982a3cdc2e37683.nq.gz
    ├── 5842523267dfa2bd0b0896dd798151331f732708.nq.gz
    ├── 5a4fdf486e8a867da034fbfdaad11f124e6b187f.nq.gz
    ├── 5c24ab55e9eabadd5075137fd30dc6ced9f92a74.nq.gz
    ├── 5e66d840798c6ab9329d4e70d04851520843ffd8.nq.gz
    ├── 5ec7d32549e302446c12ee60fe25917cecb85733.nq.gz
    ├── 5fe8bcf87ac185c94a9007013b18c597f80bbde0.nq.gz
    ├── 607bdec943d755fee5c20a3890e23349bb7bd70d.nq.gz
    ├── 61033faac291613d47168e801368b613f6a2a282.nq.gz
    ├── 612879a9d0d796e2f3d6a00265ceb9e74674e333.nq.gz
    ├── 616d7e86724043d82ae83030dd1c0a290957dc50.nq.gz
    ├── 63d02db8b9ebca0c98d261243bcb8348c3429bc2.nq.gz
    ├── 65bfa8a374b9059f4b7e21232e2863c114e260ea.nq.gz
    ├── 671b3c91a7077e662a2df61ba723da3be2163c06.nq.gz
    ├── 67b06976bc3766a5a95bef2b1cfd38b11c03f270.nq.gz
    ├── 67e1a1bc5445d66eb0d33b36d12a14e16566e19f.nq.gz
    ├── 6893341c5f4431f81f1a330ea842e59c15e7131a.nq.gz
    ├── 6adc86f1e1deb00064ce3c24d165a3010393ea56.nq.gz
    ├── 6b34fc8e160198009b69374cfdeaf0b724c5d33a.nq.gz
    ├── 6b9bb01b33d5950f916aa1aa2e4ebeb047879596.nq.gz
    ├── 6dae996ab0423ebe0e0f8144cacf96529f4b9fb6.nq.gz
    ├── 6e99a89b2164b8d008359d7845024879f0f5ed0e.nq.gz
    ├── 7040eec694538dec63453a60dc8555f38e73b33b.nq.gz
    ├── 72d723060dd349fcd56b4552f6173d1a2b2c10ad.nq.gz
    ├── 73d3a0d19fc6f7731ea0b9674b93ebaea4d0011c.nq.gz
    ├── 741b6f0da8f6f82a4da1e449ff8f9cccac2e0dfc.nq.gz
    ├── 745854351dcf4b5b9164d16a34c3d1caeef40ab8.nq.gz
    ├── 74977d1cd808f88a93bd809a32e7dad57400aba1.nq.gz
    ├── 75673c573230bed92660167728f268c9b9d68a02.nq.gz
    ├── 757924131d81a6f8324df06966a27a1ad9c7aa75.nq.gz
    ├── 762c08978bb01d2ba7ec3bc6671e0ec78c6f6de5.nq.gz
    ├── 76738159d922a637339cacc1afc134dd47e07cbe.nq.gz
    ├── 767f99a3141e8800519d65dfe706d4a2d255f501.nq.gz
    ├── 76c117029bb44aead1b35a112963e74f89611f82.nq.gz
    ├── 77066d1b12a593a88b45e10f8229c4bfbef7e384.nq.gz
    ├── 775a5dc6c43709f71e78ac02dea3d606d73d77da.nq.gz
    ├── 7761ce2e3e865e9a466d961ec67b63e27ed4902e.nq.gz
    ├── 776e5fe909bfd4636e1a4bec5322b5386d2f78b2.nq.gz
    ├── 78c6ddee23e5601eccbdcebb19e66b766c4175c0.nq.gz
    ├── 79d15b1112c43ea856b0df33ed77cbc06c2790c5.nq.gz
    ├── 7aa64de3f9431dcccf68ff4fd1d9cfe35a582ee0.nq.gz
    ├── 7ab7132f4013cdd9348d85d90022d257f2cf1ee3.nq.gz
    ├── 7afcaf047c5b02acf56130738278729e32099bcb.nq.gz
    ├── 7b57985e85ece66c2450251f35be241c5394af0e.nq.gz
    ├── 7b5f21d7decea97451255c0b0d06630c9ac6323a.nq.gz
    ├── 7d183b338bf3057f0dc28c7ee9bbebff2f0ae5c3.nq.gz
    ├── 802810c4d0b20546c4b7df944ad8ab7e7669eeab.nq.gz
    ├── 82a46ff9aff45fe78ae67b8be09f6dd3b8a861ba.nq.gz
    ├── 82c8f1d91f7f8e99905a0db4850a1bf233431713.nq.gz
    ├── 85154062289b9cfeaafc79d095b647e62d6cee9f.nq.gz
    ├── 87518e52f9a27bafeef751e064341ac4f9e82d66.nq.gz
    ├── 890febcb256e7f45e153af0107e725b87165e0b4.nq.gz
    ├── 8b0542a2d8e09326b7ce2bd33fadc3658f7f4824.nq.gz
    ├── 8caa9223f169ee840106dfb4b3d54f74f330c8c5.nq.gz
    ├── 8cb467c4458e58c19449fa4ebcabf2d8f387780c.nq.gz
    ├── 8dc68e26408fd6e2925b8409cf7825cbe3687f68.nq.gz
    ├── 8e3334a6c5256601a4b7e77e27e86b06d6ee7e85.nq.gz
    ├── 8e3c3051634ddf02220f8535b614e796644c0d90.nq.gz
    ├── 8ea3e540970d2a2c6d6f0de7c92a630072409275.nq.gz
    ├── 910c13a25fd3991a1be486bfbbc2ea273369890e.nq.gz
    ├── 919c16c2584339c87be3380c398318d5afff0da2.nq.gz
    ├── 9207c3202fc8198ab1fdd7cb4a3694ada9e258d3.nq.gz
    ├── 923e9ea0f7d82051309cc7f1698a1f25e3069099.nq.gz
    ├── 929a9270eb029fa265ed65cfea484c6cbc5dd4e0.nq.gz
    ├── 93c364b50f6187a01069dd46c3b09d25c98837a3.nq.gz
    ├── 93ff87ed4f5eaaa4caa8c07729b28d9294f4881b.nq.gz
    ├── 950708e36b62f437a3cc4ce49d32f1886ed7acac.nq.gz
    ├── 961835327b32320950d39f2ccc4bdcbf412371f2.nq.gz
    ├── 9632624b5b6a9e362132dad53768f69d094faf80.nq.gz
    ├── 96734bf94bd5f53a6b57331c52d6a42f80aa0b3a.nq.gz
    ├── 9723cd7dd74d6fe72f8daa1577ed27b79dd0cad1.nq.gz
    ├── 981321a359e035135be92f680e9bcf21ba96eb9a.nq.gz
    ├── 992885e4526f8cce95910714bd3974469feb7d45.nq.gz
    ├── 99649d666541b7d5267c3d2ae12852c50c87be90.nq.gz
    ├── 9a32814e21e124179a8bb14103134d9558ba6a21.nq.gz
    ├── 9aa454b0d32e1359b75fac2be92c94e6ba567330.nq.gz
    ├── 9ab68548246eb3318787db349284e67e335f724b.nq.gz
    ├── 9cb2605f80f17e31ef745b9de09a26a5451a723d.nq.gz
    ├── 9e5b4b6d17d160e977104b125a9231f9aa33b34a.nq.gz
    ├── 9f9a408302459bacf6bc84487e038d06a57aae57.nq.gz
    ├── 9fe5a9ee4c431e21cff8e7f5566e3b3ce2e5a8c4.nq.gz
    ├── a032fa71e1b18fcadfed47d1f56b507edfb84a9e.nq.gz
    ├── a235db7b108c917446a6e4eb5adc0cd7e54819ab.nq.gz
    ├── a23b70f3b2f20454ad0ca2b3c6747c4cd77cba20.nq.gz
    ├── a3df94582f805d6c7b75bbc776075b40e95da90e.nq.gz
    ├── a6221b338db6a1dba432f979b17774115ba27038.nq.gz
    ├── a79a57d604151bd98d91f603be199297161f0295.nq.gz
    ├── aa4c71571eb7db3c30ecd9a8f67659173f82605e.nq.gz
    ├── aa794a101b77a9069f0a90c34af054990071879a.nq.gz
    ├── aaead83db45df71106862492f49fa644d40a7342.nq.gz
    ├── ab47e09bc4ce10c6fa6383c5f3b6689c0a5bd9c9.nq.gz
    ├── abc178efff3aa2c0ad26bb7445227a0b42c33ece.nq.gz
    ├── ae7ebd98bb372f3365e149710e201796301757dc.nq.gz
    ├── ae8fc7424ddb401b060158911857c9fe9453e4f0.nq.gz
    ├── afe324995e5470867567aea452bcd794befd3860.nq.gz
    ├── b0af6ccf4ae638a8d19c2cf05a0c00cc4c1c6d67.nq.gz
    ├── b1b0c1d8ac8d71dad5aa6a1048c119125b6b7a5b.nq.gz
    ├── b24c25a13cdfedcfe17f1689a403e4b8b4c5e16c.nq.gz
    ├── b4c7a68acc3475f1eb0d8bcfa9df55e6cd93949e.nq.gz
    ├── b67dfc3c5afc9a899d88bde8c2167225311b29b5.nq.gz
    ├── b67e2008b64cb76a6dbffd8f7088206d0c3bf2dc.nq.gz
    ├── b7f5889366f1fd35cc08f2031c438c263242fe2a.nq.gz
    ├── b8baa5f77947000af32188f8f98b6f1b664eee81.nq.gz
    ├── b9c03b410adcb6822cf4e396c16ee50f1b3cdc03.nq.gz
    ├── ba2ec93d3a98e860096ca27cefb31a7adbd9f1bc.nq.gz
    ├── ba5cc9931521547e615fd088ca6f17d6fa63a298.nq.gz
    ├── bab754061f4fea0d1d0b0eea356e4beab3608a32.nq.gz
    ├── bb7b6d2471dcb026761f190b9eec56fa8b84f096.nq.gz
    ├── bbac037dbbb73272cce6226f1c4352d424451736.nq.gz
    └── bc83ea50b3452332e245e8b16930acb25fefc4ae.nq.gz

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

[jadejs/jade](https://github.com/jadejs/jade)

---
*Parsed on 2026-04-10 by [repolex](https://repolex.ai)*
