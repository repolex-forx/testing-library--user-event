# Repolex Knowledge Graph of testing-library/user-event

RDF knowledge graph data for [testing-library/user-event](https://github.com/testing-library/user-event), parsed by [repolex](https://repolex.ai).

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
lexq download testing-library/user-event
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d42954be66484bcf78486a298cc37f8a7c9e4bea
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── d42954be66484bcf78486a298cc37f8a7c9e4bea.nq.gz
│   └── repolex
│       └── d42954be66484bcf78486a298cc37f8a7c9e4bea
│           └── chunk-001.nq.gz
└── blob
    ├── 007f1394231c0f1ccda5f4462a750002a233837d.nq.gz
    ├── 022a45e170f8c575044b13696b0d57bb06781a62.nq.gz
    ├── 043be008c41b5e8e16f5c57a17c8f45feb30606f.nq.gz
    ├── 04e56fb7da2204b21aae75c2d1af52fa092a4a8e.nq.gz
    ├── 088e4b9ab3f1dea622fd0e0a3b66d19375a40059.nq.gz
    ├── 08dc69bd83dd9df836f5f06aeb618447095f97d5.nq.gz
    ├── 092e72472bf53422bb0a02644b8a34ccdbc3f459.nq.gz
    ├── 09ce73594042c9880e6b1ca98b6a0c579e84bb23.nq.gz
    ├── 0a5b7510c2ecb37ab28ea5330fd8c6ba0b94dfb8.nq.gz
    ├── 0b222777634361b137b8fec338953e98aae9b276.nq.gz
    ├── 0b90c4f4494fb7bdf0a000c0e45994e4b926afd6.nq.gz
    ├── 0ba2e7b05abe187172c3f0b7c71ec44b33044c71.nq.gz
    ├── 0d9cde40dceab1281ff9ca78f0c97a6562694c6d.nq.gz
    ├── 0daab1eea1cf3e81084477c781c6321c2c4df69c.nq.gz
    ├── 0f6ebcbfc88f49bbfaac9860e2529697c3fcf21a.nq.gz
    ├── 12641c8470d43137d511d5f255c1a0b1d513060c.nq.gz
    ├── 1305ca0c6bf7708975a87802d6d7ff5e0b116d76.nq.gz
    ├── 15796f6b0ac65bc6b1ff2c9089378cc63b34f548.nq.gz
    ├── 16973b2a3def474c4b077151ec0179c405aa59f6.nq.gz
    ├── 17c0d1e9fb1517235d39f068efc3ef5f8b0f2240.nq.gz
    ├── 18c70cabff90bb324af6837b87c0059debfc012f.nq.gz
    ├── 1c12e7f6c2fa87b2b602bd95eed28e34f9d561a0.nq.gz
    ├── 1f95a27b08697019e11276e9466c6fa182979e2c.nq.gz
    ├── 210525c4b9d9b5dabca6a4adfee95350f5befb15.nq.gz
    ├── 24aabeadaca128ac5c7e3f38080ccff85e19846b.nq.gz
    ├── 274561aeed009319209b6769719d6b8c5dccc497.nq.gz
    ├── 29d4f3ca0fd409c665cf0703c89989cf585e4def.nq.gz
    ├── 2a15754ee949976eacc4eefa4d2e5f07875b9cd4.nq.gz
    ├── 2a6752990103f99ba7cbc2653dad53eccf0fd6a3.nq.gz
    ├── 2b296dfe00f7ba579d7ef8d5c655cb98dddb235a.nq.gz
    ├── 2d76fc041790d04781ea95637ba1b5469c6ab026.nq.gz
    ├── 2dd6b0ac056dc8ece71d94aa86aef4ce0508afe0.nq.gz
    ├── 30e1f51072fd2b30b27882aee343e3d2ac8fee29.nq.gz
    ├── 334fa6ff6fc9723dca529959c7a33b44844edcce.nq.gz
    ├── 33d96f9b8567df77c70810a235fe205bf8b7256d.nq.gz
    ├── 345f9ea7bfcf559a7d4cf2e8738519d94ea7935b.nq.gz
    ├── 356eeba3bed33708ab7b41f9df6c315e0ea38f1c.nq.gz
    ├── 3594a49212d9af01497d133596acfdccefa55545.nq.gz
    ├── 36efb877bdbd2982fb01909e59c3e43f6eb4e0e7.nq.gz
    ├── 3743b604b597656e5fd284fc875278385b00a039.nq.gz
    ├── 3b54070dedbfcb22e35b81e09a3c088f41ec8ccc.nq.gz
    ├── 3cdb36fa32783460a2bd4d76badcc3b57b718905.nq.gz
    ├── 3d2393977649818e16b88b88838111a41a0c50f5.nq.gz
    ├── 3dbc1ca591c0557e35b6004aeba250e6a70b56e3.nq.gz
    ├── 3dc9bebe6aa61a435885a87a47d643a726420c7f.nq.gz
    ├── 3e7e6b085e02e1377265a3f54be95ffd585ba6b1.nq.gz
    ├── 3e87bdadc3cf15ebae57b3b629b3665ead22524d.nq.gz
    ├── 3f1486bce30c6a8deee3ba44212c17a11ca8770a.nq.gz
    ├── 3f436ccf668e69ca768a010f9bf7d4c26dd2705e.nq.gz
    ├── 3fb3850013f56e672808c1c8435bdcae79f76726.nq.gz
    ├── 3fc08807e85143d79aa118d44f899196d12ae1ad.nq.gz
    ├── 40be12ad75f19048f3ac2296f7d29c0aa0a6d329.nq.gz
    ├── 4432a14df282fa762b9b5e7969feee2e16afb730.nq.gz
    ├── 44fa669a6944e42f9a97a7f0966ba84f0fefe70e.nq.gz
    ├── 4627296dabb70fa074546cc717570061bfd331fa.nq.gz
    ├── 4679d9bf6be92cd766e6d59d40d7da8bdf42335f.nq.gz
    ├── 468ca19512019e7b45a3618d256cfc0b8c445e48.nq.gz
    ├── 481341e278ce438b638535d0de397b5f6863c3d5.nq.gz
    ├── 48a6775ba0ff11cc442207551155bded995ff713.nq.gz
    ├── 49d2f67a2c6aad03cc1028a3417cdffd6cd343c4.nq.gz
    ├── 4b60e04fb354780fd682e9672e74523b7fb17478.nq.gz
    ├── 4bc12816cf989f4001b6dc3919b6d60e673a285d.nq.gz
    ├── 4bd5ecfe23cd40f17925f0a0ebc0e06214a72d2d.nq.gz
    ├── 4d31966b1191618f9b7b65818376590e90bf6060.nq.gz
    ├── 4f42b2f26ae47d53955185436c3b592757fd07a5.nq.gz
    ├── 50659b522f10465998b2d324876bb4caa15f28d8.nq.gz
    ├── 5078655ec639377d92cc72606d48e650da53a5d6.nq.gz
    ├── 527063a1a5c1008645afa5069b2f6ad6943a80bc.nq.gz
    ├── 52d500fa7514f2f117caa8a8f3d81d4f0bfbba80.nq.gz
    ├── 54f174e42c236a1492c844af7e429f9fcf7acdc0.nq.gz
    ├── 55931eeb70758d394ec3c7a782b275fddc6210ca.nq.gz
    ├── 55f2d5a391df1c7a536a49d8e2c7c34ab0ef403e.nq.gz
    ├── 5a9c6a0ec5f3b57e3053b02fcd419ab6567c828c.nq.gz
    ├── 5af41ccabc770aa1d2c2d9adf7ad29dca1efd38e.nq.gz
    ├── 5c72a9d2423ea901ae58d917331803864e20240f.nq.gz
    ├── 5cb87aba9519157c403b9807ef27f78b9da3de52.nq.gz
    ├── 5e45c45dba483c9d907b4e6e7dc7cba401f93710.nq.gz
    ├── 61ec754f1879444cdab3fcb0fef577c1e49a6c4d.nq.gz
    ├── 62350a2ee5064cbb2c56c8e3946deaab196d5752.nq.gz
    ├── 62453734ba7d9a5cfd89d6f657d8d3665bdc5d08.nq.gz
    ├── 6313b56c57848efce05faa7aa7e901ccfc2886ea.nq.gz
    ├── 653a27859958bd35decb64783d7d0f45794abbd6.nq.gz
    ├── 663953f8be47e587dceb9cad7b36c9206db869a2.nq.gz
    ├── 6654757a49dd3fc17d9ba558ce8a66b751a1c1fe.nq.gz
    ├── 66da8fea5b700ee99b30369e23abcd182f070be7.nq.gz
    ├── 66f56993d677429b1e20c2eb3eb4f7e904d62e10.nq.gz
    ├── 67c7b5790f2407dd0b93681317949309dcc3ecb0.nq.gz
    ├── 680214abd4f60c789b34f288f7fb2a0a24522fd5.nq.gz
    ├── 6a4c5254f4b7b18af40fba15663da747134b11a7.nq.gz
    ├── 6aa42c1bdefdc226dd1b985d94f6589fa6e66e0f.nq.gz
    ├── 6b80f794fba6b25d5c2f87a0cbdccc665c7ad626.nq.gz
    ├── 6d428f27f9a1d989abad1fea7a9e98c2156be8f7.nq.gz
    ├── 6ede2b2ab3ee627a553cf6aa1545292eab31c26c.nq.gz
    ├── 725c2524242e43e80fa3bd589f243cc71abcff6f.nq.gz
    ├── 75e5bca9dec481d56ec87a222e137f36d5fe8af5.nq.gz
    ├── 7916f3c85ed1b2f1f4a857a6edee86eff13a62f0.nq.gz
    ├── 7a8ffa912545234c754f45cd63c656d730af1371.nq.gz
    ├── 7abea8bc2f301e5d7a81c649bd7d5fab24b52c33.nq.gz
    ├── 7b93369518b76e930a9789ef448ff9ed458758cb.nq.gz
    ├── 7bc3919639a498a4a9fc35d171e99e2e7f5e9c9b.nq.gz
    ├── 7d420f8b6c8184bbe9897c217aec1f6f51849deb.nq.gz
    ├── 7e75e2ee0d16aa768be12abbdb1dcdcd180c3c11.nq.gz
    ├── 7ecdfd87cda648d25e76c9d6d900ae674d9264e6.nq.gz
    ├── 81370ce6e9712fe20c801340df77c47195d0cb06.nq.gz
    ├── 813f0d762fd96a77d96c663ffbe8ae7057e4cae3.nq.gz
    ├── 818dcbe8fdb3c7ea74b6ecf9f9fab1901ec359a5.nq.gz
    ├── 82ce4a0d9aefa765072ed4fccaa3fde0def4fa40.nq.gz
    ├── 83cda37671f78882119e81bac21b74f0c18867ed.nq.gz
    ├── 8466d63b7ac5cd4f1fca103c156d1b4c4afb418a.nq.gz
    ├── 84a7da3bc31e76c24dffb42ce56a561d66c76ab6.nq.gz
    ├── 8591b4ec1e860041ab731ddbdc506f786ddcb5dd.nq.gz
    ├── 85cf326f54ba32f15668989d1bdd999b91c3f8dc.nq.gz
    ├── 86169f36adaff213b475a1102ffc0f17a7d14e9b.nq.gz
    ├── 87f22bd55d2eeac5e012baed280e2f71b9d2c2b7.nq.gz
    ├── 885c742bb7d9ee865032e7fa047e17b190e619e4.nq.gz
    ├── 88c063fb09335eb770080f996336a6a1eef5ed3a.nq.gz
    ├── 89ef990642f2d306fcdb57963061803dfac722c8.nq.gz
    ├── 8ab15cc8880f0ce7f0a429f08054488e7661f528.nq.gz
    ├── 8b722dbaf2981d5ad2e479b7ba97920991133e3a.nq.gz
    ├── 8bdebe61745405f81f1419434320f312782efe6d.nq.gz
    ├── 8c83a310153d3892aa37c194ae0d84ba0ed358af.nq.gz
    ├── 908d6e813d5053b63e05e58539985b7ee1c4ce9f.nq.gz
    ├── 923f0fe268378b15844ac0c0c5ea28b302fa6328.nq.gz
    ├── 94352d9f2581acfbf4826b5cd10c7ebc58c71c4e.nq.gz
    ├── 963d41d142bf0852f586b1e18fe772d52b496976.nq.gz
    ├── 97fe746da005306de451b18bbf4e3e421f1efd85.nq.gz
    ├── 98bd2f885880a1c71879470097502e53e84f5df4.nq.gz
    ├── 9a30d99425ffb8f92d51c9eafe200633237d9907.nq.gz
    ├── 9a5e2de61ddd8971b3dab71f61e9792e802c5113.nq.gz
    ├── 9a782c491cc4a08e8a000f4374c5bbdd29ad6191.nq.gz
    ├── 9aa9f8a69873c422e5556eb6fb600b50da5b27e8.nq.gz
    ├── 9b7df2742bfe4a5fb886134c7d58d1fe58745d77.nq.gz
    ├── 9c628283b98527a803e7edaef15fb592ab4b562f.nq.gz
    ├── 9da3af8afa0b815c9d94340b6c6236f8dcc74103.nq.gz
    ├── a06528157473699a33e53b023d176882956ade8c.nq.gz
    ├── a25bbc210a29a3802b65676790d803f7bb99360d.nq.gz
    ├── a2ec74aaa1a13972b63d07bd64f413cd47be6bd1.nq.gz
    ├── a2f1a47872aec931e6f69163f0a78867dc10a559.nq.gz
    ├── a348f4db7196fbb168e570c5b8c1d39b35dc8055.nq.gz
    ├── a383d10c2fddb9cafccef8e2fd03db771ff75cc4.nq.gz
    ├── aa5e1b441761fd9d38a2f724bb31951a5dc8c378.nq.gz
    ├── aa78a5dbc385cef778e30f5160ee42a4face4918.nq.gz
    ├── aab44bcd63b8b7e63fc0960f67c7bc3a63b0f1e8.nq.gz
    ├── ac2a104ab3d30a4740504c2654f82e32438d6c42.nq.gz
    ├── ac2de2b8fd1b9360fd3482c19930b46987ddd487.nq.gz
    ├── ae18a622da61f30e01b7f0e511da92f5ffd8096a.nq.gz
    ├── afea40501b69e7a078f45fe27278498f67ff481f.nq.gz
    ├── b0308f38d0c2e510295d3a9f876ba3bc9b870132.nq.gz
    ├── b0fa79ba9c5f65fa36f784c242c8d359845b6126.nq.gz
    ├── b18a9649b636f7c51b703f78bf7adf60578681dd.nq.gz
    ├── b4055181327c29fec144c156a6996b214353c5c3.nq.gz
    ├── b6256cb03a972c0377e954ab72cc1e9ef0b260ae.nq.gz
    ├── b7c66eee4357e493de44d2a625f4791bc1e57235.nq.gz
    ├── b7efbd9625f2db5d3f1bf8d2f33d41cdafd639db.nq.gz
    ├── ba0d5b03d3c76308a5864a6595840730e72134d0.nq.gz
    ├── ba1ce0406779346d76d9f1b2afabaca18653697f.nq.gz
    ├── ba1e1f66c89a86b0edd1fa393da2bd56c3b773de.nq.gz
    ├── bd00b3cfd24e5a83be85ca3a2ecb6bca2fe9bb06.nq.gz
    ├── bf01c9d5b23a3a381aeaf931fdb760d449fb5a54.nq.gz
    ├── bf2dcd8e070c2509983eacbd9ca1721a9ec59848.nq.gz
    ├── c0ed529909a4dc6c7e9d6ad1158850942a7c9670.nq.gz
    ├── c24e3a168cc251d43fb06d2369379206eb4fa279.nq.gz
    ├── c27066c7b16804ab18c1437db19c80a31df8e18c.nq.gz
    ├── c4007bae1af312b74d757fe30c59b08f85b4f21b.nq.gz
    ├── c529e9f9c9ebd94c25e528fdc26335bf6aab46cc.nq.gz
    ├── c544743e88d627de65d6b34bded68408da9044ae.nq.gz
    ├── c5e3cdd19b54359385f4a4d26d90cb3faa99e7b1.nq.gz
    ├── c67fbb0f2151807eb5c9fda0f3fa38c6a6cf4848.nq.gz
    ├── c7b29db7581e2de71ea859252508be1825518819.nq.gz
    ├── ccde82cacbe5b5a8c289d7f532770cb7d17192c2.nq.gz
    ├── cd5eb96777f6487356175b09525d96015d2ee8be.nq.gz
    ├── d15d7b1b936f3a0d7a4ccaeec3c417f26e10d0c9.nq.gz
    ├── d25511b3a7baf2e732cbb955e66cb32dd088a080.nq.gz
    ├── d29d059ff73ba4e22d4596e022ad2d98b53d9ead.nq.gz
    ├── d2a9b70fa7e699b053f77cf8c7aabcdc65f58e50.nq.gz
    ├── d2d590e1cf776a9c68b1e4e8a7ba2d8892272c6b.nq.gz
    ├── d4687c0f8b6ab3dce9d10ceccfd2c1cdf455ce6e.nq.gz
    ├── d468d3a3b5ddcfb6aa8efc2cdc279f1adc9e8f3e.nq.gz
    ├── d58b84eba2428bbec9eb5586e5150901d4aecb01.nq.gz
    ├── d59afc53f4170aa8b9cf087eed0ec1c1608c97ad.nq.gz
    ├── d877dea35f65159cc0d6401402cb6f3ab78d077a.nq.gz
    ├── d8a9b3b5a33a9f588e01e00848504f6f511c2ec0.nq.gz
    ├── d8f6b1368ecba968cea0d0b59c51e22e1b53721f.nq.gz
    ├── d976a7b3e519d3b71bfba53c6ccf60a87ccfd8f0.nq.gz
    ├── da6f10dc57b6af434ea87eabfe5ddc87e3a3ac1e.nq.gz
    ├── da7cf8f3960ed36ed925af2eef9a07d44794c345.nq.gz
    ├── dd4a0a22c899ea21556d620b0f239edfd068ef66.nq.gz
    ├── ddbf190d7497f41d64a6976bff3c63c3efc2a7cc.nq.gz
    ├── de45f07351051c826b6a008437894c14a5a3402e.nq.gz
    ├── deaa30f9ac2ee69f2d116698dff1f8b4f3e44c29.nq.gz
    ├── dfccce21127453db9fd64e23257a0e2c0f3f2897.nq.gz
    ├── e078ea03223602051b79d396c86e22cef576fd62.nq.gz
    ├── e4e9802dff1bfcc687b8b183620fa1fe3db21375.nq.gz
    ├── e50187423ff8577261432a3d061ab3ee70e592a6.nq.gz
    ├── e5958a16efb0d75de1033f9baf4f58d67fe65658.nq.gz
    ├── e5d54204a4bc7dcda04bb02933507723121f01e2.nq.gz
    └── e5df03c87a3f71c675f45bfb578d10c7150d272a.nq.gz

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

[testing-library/user-event](https://github.com/testing-library/user-event)

---
*Parsed on 2026-09-17 by [repolex](https://repolex.ai)*
