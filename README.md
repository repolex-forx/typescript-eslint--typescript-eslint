# Repolex Knowledge Graph of typescript-eslint/typescript-eslint

RDF knowledge graph data for [typescript-eslint/typescript-eslint](https://github.com/typescript-eslint/typescript-eslint), parsed by [repolex](https://repolex.ai).

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
lexq download typescript-eslint/typescript-eslint
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5311ed312eadf4e238324f2726ae0b1f3f2206e6
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 5311ed312eadf4e238324f2726ae0b1f3f2206e6.nq.gz
│   └── repolex
│       └── 5311ed312eadf4e238324f2726ae0b1f3f2206e6
│           └── chunk-001.nq.gz
└── blob
    ├── 00048844dac8a63dfd383272ca8047b49ef31042.nq.gz
    ├── 000601b07303fa697b1fa62632f064960af1414c.nq.gz
    ├── 000b5cdd24789a3f3f529f285cb352b122799131.nq.gz
    ├── 0016d97b87646b8c2e7e7ea2f4daa28e35c1b9b6.nq.gz
    ├── 001f684f183b4e6acf98aef372db091bbd8e0dda.nq.gz
    ├── 0024b52130c7761e18684c9d579f7475bd73138a.nq.gz
    ├── 002d28f6bd7bc021e465c6240b6fd0870a2501c1.nq.gz
    ├── 002e337885a18264206b1b079a0d31697ed98ea1.nq.gz
    ├── 0035d60f9a3b04ea9441b2c953125edbba110f9f.nq.gz
    ├── 0048c59f7185af08429c10d43e3c001708c401ce.nq.gz
    ├── 004a3b18df7fda6780e9077010b58e184ef8afed.nq.gz
    ├── 00507051d9c144a8d33db70099100c2514493ec9.nq.gz
    ├── 006f376ee7713e67d30ad5b5c7482927f7340c03.nq.gz
    ├── 007f5b6f48f377937b6f21855bca7b28978bd34d.nq.gz
    ├── 0080c6a995654c9e582a8f5a3159fd748b5481eb.nq.gz
    ├── 00995932c907e04ffe62293f5552c2f3941fc788.nq.gz
    ├── 00a45c5c410574ec1041fc1c6e2aed38576ac15f.nq.gz
    ├── 00afdab72fbafcabc781d8b6f0d4417c4af6312c.nq.gz
    ├── 00c8ae67c9bc1b5fd478731589022e02e4564aca.nq.gz
    ├── 00da70da31f41fb71a36f18a7d1833b13442b606.nq.gz
    ├── 00e32626e2bbbb8c77dbc76c7cd920a5c73663bd.nq.gz
    ├── 00e39c0cf9b4b06ce0909b0446aa2b1e3d572134.nq.gz
    ├── 00e4acaf726c67b813e74b4bc8da38e5bdb78f64.nq.gz
    ├── 00f60c625f57bb36232671b351a9f93d6b27e18f.nq.gz
    ├── 00f7eed3ebd2319039a7dec1773ce5f32beae7f2.nq.gz
    ├── 00fae0a513e2f2a7dcb83e4577c4745717ac7ded.nq.gz
    ├── 00faf0b6c777f0289f31049d2894d32f686310d3.nq.gz
    ├── 010213b4ddb0a70b6feeb095d37a8b621b9f24ba.nq.gz
    ├── 0103cf11dbdb324fe06a1bda05b4f823648538f3.nq.gz
    ├── 0108df36632370fbd2a548b11dc218d595d31b34.nq.gz
    ├── 011775eb664803db385b5ab4c569c6504067661b.nq.gz
    ├── 011ed067a6e21118e47cf87162e4864b708f9b66.nq.gz
    ├── 01395d21ecf64dd256aadd8616ae990746c58a42.nq.gz
    ├── 013fb16531eb2af8343da5de05d947352eacb200.nq.gz
    ├── 01421aeb4e1c1ae57dc23c915472d15fb015b72f.nq.gz
    ├── 0143e128d1fe035786441cdb20a57d11a43b21ab.nq.gz
    ├── 0145f27c1f6f10149d8ab936dee5a9bf4fe938c9.nq.gz
    ├── 014670749bd953476ed7c8177153fca7f00340a7.nq.gz
    ├── 014cabd16beb3f18995d8d5d6115628e2a568169.nq.gz
    ├── 014f4d3e257a28928af50cf45cb702de778051da.nq.gz
    ├── 014f8fecca1d26123e33b600ac181a9d0bada912.nq.gz
    ├── 0158742d03bc482774fe3c7638d838102e7a71c4.nq.gz
    ├── 015b092b4a06200b893846b71c68c3f88a98acf4.nq.gz
    ├── 016664d11b0307c3e4d5ad50684ddf0cc957a78d.nq.gz
    ├── 017371d430e0c246646697b9a186c665747879e4.nq.gz
    ├── 01773fd9451dbae28783d253da69eff4af461d77.nq.gz
    ├── 0178fad8eeed52dacabcf2d6d61f70f1900734fd.nq.gz
    ├── 017c2d326596b7772a7f035c63f3c8edc5a0a52e.nq.gz
    ├── 017d50c2645416a7a15bf6b83ddb0b42ff96dbff.nq.gz
    ├── 019de1d9489ed987e272b2a97db815a66dd603c1.nq.gz
    ├── 019f435eb73dd148917191c85fd6e2196927bb45.nq.gz
    ├── 01a47a9dde78eeb0a9718b651bbf45a18b78eae7.nq.gz
    ├── 01b14ebfc7b284185ba09690a9ed000dc1e28c12.nq.gz
    ├── 01ba49df38c09e162fff1feb0046a70663a98bdc.nq.gz
    ├── 01bd31b00cb46383dacdf02b2172ab86f2d2c23b.nq.gz
    ├── 01c4d100b383bbf104cca4688eb8292027bd345b.nq.gz
    ├── 01c5f7b79c8e5f1a11d3d9e1a9c6c1ceecb57fd6.nq.gz
    ├── 01c67fc786c0787bcdc17e89e4e6f0833bbaa4ff.nq.gz
    ├── 01c9c47401c519bb24984e361a7fe4e508ee2097.nq.gz
    ├── 01ca91d3215d5f3ea6298981f99ad27f8ea54e9b.nq.gz
    ├── 01ce5acc4c3faa96ef17181ed1935c58e50c2c96.nq.gz
    ├── 01d77f5def1ffbfd22b6e6d1ccdfd1f6459288be.nq.gz
    ├── 01db37879fb099ceafd54e85173c8eb7f66c7ece.nq.gz
    ├── 01ec8a8048e46111fd6e928e3920057700456e90.nq.gz
    ├── 01f78914f24cd5f503a353cf5252b7644a36c385.nq.gz
    ├── 01fb05140eebe39991d56115fc59c5ccbca6a4b1.nq.gz
    ├── 0214de0e541f350e2eba373393aef65a2c15bc75.nq.gz
    ├── 0215e4f1644228b46e968668a42526d060bf4ee3.nq.gz
    ├── 0216a00ae4631ac6eb3db476cd81b7008d87f943.nq.gz
    ├── 02170a78993d139cce120ad5c0f8f75a67431f3e.nq.gz
    ├── 0218c219c9876b4366bed8ac71ab2d671e9f49b5.nq.gz
    ├── 021a18d5d736406541c2b199b30c3dfaa483d928.nq.gz
    ├── 021fe5ad90fba3863377e6a92bb8e582621b18f0.nq.gz
    ├── 0231ce8d316f921780ce6ae45016019fc63114ba.nq.gz
    ├── 02421a25dea9a86c3e0615e12999fefac3f5234b.nq.gz
    ├── 0257a34705acf1905f7d42d1018000c68b82b34c.nq.gz
    ├── 0263febe3c21e56f8ba4a5894b0fffeb683699e9.nq.gz
    ├── 02674752acb01b4ec6b07a9592a05240cdc3300d.nq.gz
    ├── 027d51a2444a64aa4d7f4ea1cfc7f5f065c371dd.nq.gz
    ├── 029048eb65dd457c9015d11be20b9ceaaf3bea04.nq.gz
    ├── 029433b2bdd6e33d03a69dd36dbe604a5368c690.nq.gz
    ├── 02a7a696431445bf4150d0b10c18d17fa4022558.nq.gz
    ├── 02a8f19281e706cfc0bddec95cc099b7514784a2.nq.gz
    ├── 02acd310e72e092a9eb1a81897d773eed3e94945.nq.gz
    ├── 02ada9f4cac06b722090d7c32474c74f89e288df.nq.gz
    ├── 02b5d86e06e4650bdea24b1151a1e7f6b1008b15.nq.gz
    ├── 02b7dc9776b7decd9d76d7705d4ac77da35237d4.nq.gz
    ├── 02cdd6178061918a52afa1c4d9bcf3c2326dd130.nq.gz
    ├── 02dc462820ffc73857a36dec15761a0679887543.nq.gz
    ├── 02e1a31e716e38835021426e64f1ffe4ac8cd35b.nq.gz
    ├── 02ef2816f789a8e191bda55941840c5f19eb1a3a.nq.gz
    ├── 02f927169a1c85db3cf1354d0d9a9848f5894529.nq.gz
    ├── 02fb115a22c77d1c21ffdb72d7baa5dcd7bb21c6.nq.gz
    ├── 02fd70e56cb32f115e2cb0a4ae950566d5f3f99e.nq.gz
    ├── 03085504d2ba8da1a362e9fd61bd0a6cf2789352.nq.gz
    ├── 032ca2eab23a00996c3024e0114af870de7e5e70.nq.gz
    ├── 0341d1690fd799af4376c3d9881afedc5fc9f695.nq.gz
    ├── 0346b41d38d4860445800d63d8fcbd825d69a087.nq.gz
    ├── 0367dc4b8cad2a40e98e09d8e65d9876e0174b95.nq.gz
    ├── 036b254e3a0be095ba0fd6b1a0e577ee4fe02439.nq.gz
    ├── 036f1181e9b74b031823ecb79952f42ff5dc6be2.nq.gz
    ├── 03789a1a73af90527c09e48ddff28fd7837ffc75.nq.gz
    ├── 0386d9255b007b9e55afff3e32962902fce3f0e3.nq.gz
    ├── 038e4b8ad9c40b4ad2eaa7d3bc2c72aca473c4a3.nq.gz
    ├── 038fbb18159b4934434f022516d1c2e81e9563e9.nq.gz
    ├── 039239d51c722e8c36c1f887cdb3925b597db53b.nq.gz
    ├── 039606144f17cdcd1588a34141fbcb6157ab92a7.nq.gz
    ├── 039ef6e695a794710b8df38c4a2595b8520f762c.nq.gz
    ├── 039f02e2bfde0f0cef5c9752a1fc012866ea74dd.nq.gz
    ├── 03b997963643b390ebbba5052f3cf3be1a97f290.nq.gz
    ├── 03c870ab7cb196b9485624b89e4b64168cd647b4.nq.gz
    ├── 03ec08337b25ab862f6d3f40736fce0e51b2c0ea.nq.gz
    ├── 03ed7d03652367708e2bd7d90e3a0541233d0278.nq.gz
    ├── 03f1a06f5ff12ab3477c5036ff80574080ad3720.nq.gz
    ├── 04110c3dbb0ec9f47f57b438e82cd615231b6f91.nq.gz
    ├── 0421ab7b73be362d985802983e73c2e95923ce3d.nq.gz
    ├── 04293cfa77f9e1168ca287c335730b9a40e1cf98.nq.gz
    ├── 0433e82fc8c6777812b9fe9581784d8bf565f045.nq.gz
    ├── 04350071ad74c0b51c7ef0adc4c956c8e7e85c3e.nq.gz
    ├── 043aa6cbd84cb3006e25afe5c66787e73a3a4ad6.nq.gz
    ├── 0441c298d36518cc5f4a848d9b2ca48306306e9f.nq.gz
    ├── 044a7dea2be49216169594028cecc54abfc935dd.nq.gz
    ├── 044bb445ba3d093cc5c80c60f3f1393ef4046722.nq.gz
    ├── 046a008ac8eebec5269520887908c70062ef0aab.nq.gz
    ├── 047477013de14693b756e294023bf080232b0599.nq.gz
    ├── 04824de376258167ba8ba283016865a4c92fe701.nq.gz
    ├── 0482553071a0773b0af859fbd36acdd9e5ada13a.nq.gz
    ├── 0485030e021789c723aab86e40384a709e3a3aa8.nq.gz
    ├── 0494e57eb41b68fe229c4a6083d8fe2eaad13e67.nq.gz
    ├── 049972af9027dc312db6eee77b92623d5fb28e57.nq.gz
    ├── 04a70d3af29fedd5ff35be7e39752ee2bb2ab9a9.nq.gz
    ├── 04a7fb3b3b0a6d6fb8ff355a475ddaf3b1747196.nq.gz
    ├── 04b48b3a1daa033bf3396c8a86c32698007b5c97.nq.gz
    ├── 04b4f308da932f0351903529bc76a8a8862d9df0.nq.gz
    ├── 04b59df7bb506da384921189dada5c7c129194a0.nq.gz
    ├── 04ba7300da91be5b5308d00e97dc53253ce3e364.nq.gz
    ├── 04bb4b42ac80e465f271a2c2c51a2708be148bf7.nq.gz
    ├── 04c024be457c1e26a5de235ed09c612f4625ee0c.nq.gz
    ├── 04c7bfdcbc9876ec27816b09d24b71aee1466755.nq.gz
    ├── 04d2dfebee776dc15c1dddd7fd4cc1cdaa377d69.nq.gz
    ├── 04d9179319beecf3d5ece8fb5cffac2e81df02c6.nq.gz
    ├── 04e4f4ba7e5637d7eb8e7b2c52bbb1892a311a8c.nq.gz
    ├── 04ec5b3094ccb43d1ce1b0a7d927fa89d942d730.nq.gz
    ├── 04f8aa8adb0cbf415de0d868d48260c563289815.nq.gz
    ├── 0504fb619a175cf0ca38b881113848040c0df6ae.nq.gz
    ├── 050fb5c745f59f8c96e8a50c569605a86c839b76.nq.gz
    ├── 0513b28e4cf8dd58f5e5feedf8e8c3683d4859f1.nq.gz
    ├── 0519d2d579bc9cdefa60d92bda12581e1dc637e9.nq.gz
    ├── 051a827ee7205f1ce2bfee0063d5a11befa48eeb.nq.gz
    ├── 052455292f804bce4274ea0aac670c6f66b2c964.nq.gz
    ├── 0526542eecd29080158010a132ad2d7e7383a783.nq.gz
    ├── 055e5908b89577346f0c277229d6f0ad8bbaa04b.nq.gz
    ├── 056333536528b6ba90221189758d63687a4475d0.nq.gz
    ├── 056e74c313b87ccb37d028dd843fca238a062200.nq.gz
    ├── 0573a2a76faff5e2d45f990c1d081c9c9d8d02b8.nq.gz
    ├── 0577026fae054f42beabb4e215f1fc696e19fa89.nq.gz
    ├── 057e66bed74079a29bdc888024cad329fc655a0c.nq.gz
    ├── 0587657ad4e3b25a12e3b94838e68c44021c7832.nq.gz
    ├── 058ec7181202d4b3fe4c1eb48ba7a849c5b7fe72.nq.gz
    ├── 059147e710f576d0980300c2f095ed70ccfbf744.nq.gz
    ├── 0593d2fc6187c86876f5370fe56e15385e23f009.nq.gz
    ├── 059c8eaf43d7353dc1abbc49516317524ac3cab5.nq.gz
    ├── 05a6560e407ce56900c48841941569a1b9e3beba.nq.gz
    ├── 05a831f68b45aae168e62d11cd7537d071a8be61.nq.gz
    ├── 05c1ed2c92cfb311a75b423b30e72dc049e68d1a.nq.gz
    ├── 05c530843e703e8e753341d6bcd50c04530c7f88.nq.gz
    ├── 05c93176fac6c2e87e4d80bd670240c3b80d3306.nq.gz
    ├── 05d4ea7b39a44d90de6b260365c0359de1746d10.nq.gz
    ├── 05d907a57d5bf115ea8db32655cf149c7d97a87e.nq.gz
    ├── 05d97442cba702e92575139885d6b905a61e3d47.nq.gz
    ├── 05e20a74c9642b9ee24003e0a300e20e2c1ed31c.nq.gz
    ├── 05ea31e51c91370142f9c896a292fd3f66f133e7.nq.gz
    ├── 05f63a56dd203ace327547ce47e16f17502872ef.nq.gz
    ├── 05ffab6afcc184815a7a1b8f737881808b9cbb26.nq.gz
    ├── 06005684dacea85e267ecfd2ee522709ce1662f4.nq.gz
    ├── 060ae5187cf31de351fac6961c75b42aa4685909.nq.gz
    ├── 060e140c20f569dd640f730e85d82041a62eb83a.nq.gz
    ├── 062477b1fedc5477c6084b2358bcbd290160ef49.nq.gz
    ├── 062ddd8e19387470ac0c695c92bcc68625a5dd4e.nq.gz
    ├── 062e4baddd0acc331a5eded7a3f0c56829ff3a23.nq.gz
    ├── 06340f1bf5624905c92ebc9b8536becfc3749db2.nq.gz
    ├── 0649b9eb7758d79a4ffdcc60091f2e95d51057c1.nq.gz
    ├── 066251720ff49d7fe1fbc616c5fd8c6792f989cf.nq.gz
    ├── 066b3808205a98196c44541549e7a5682037e21c.nq.gz
    ├── 066d085773e51b174b3175f308349f88e15bc1ef.nq.gz
    ├── 067419e5adbbf26f51a3b2eb7ad24740de69299b.nq.gz
    ├── 0674fbf83d26c3d143c3d8eedd3e49e06ca67fc6.nq.gz
    ├── 0676e7bf04361b85432b3f97210245a6d7c7af2f.nq.gz
    ├── 0680b631102c5a12f7a6fbf9c20d676ff0176fba.nq.gz
    ├── 068661594fbfbb78d353a0d5e2d17dc61acb45ef.nq.gz
    ├── 06930d2c1d28192b8bc011fb5bc1da3af1e02fdd.nq.gz
    ├── 069498bb5713edfe921d1fcc32b07978867a044a.nq.gz
    ├── 069937bca25f2ced692b3f79e44a13d27148124b.nq.gz
    ├── 06a0a9e07163ebaa0a107c3137cbf3eba664aa17.nq.gz
    ├── 06a8a8dc4e5ffc9e08be5fe96ab41418fc2cf9c7.nq.gz
    ├── 06b0af68841fddc2de3975648618b92f4ba0a783.nq.gz
    └── 06b0cd7562e6a88acf769dbd36c5ba23fcb29c94.nq.gz

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

[typescript-eslint/typescript-eslint](https://github.com/typescript-eslint/typescript-eslint)

---
*Parsed on 2026-04-10 by [repolex](https://repolex.ai)*
