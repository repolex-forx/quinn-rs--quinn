# Repolex Knowledge Graph of quinn-rs/quinn

RDF knowledge graph data for [quinn-rs/quinn](https://github.com/quinn-rs/quinn), parsed by [repolex](https://repolex.ai).

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
rlex download quinn-rs/quinn
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 38c036ad39aaa421b0cc2c51c6d708f225c425ab
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5e54ac6dcdfe9dafff011a56de3d234470761400
│   │   │   └── chunk-001.nq.gz
│   │   └── ebad48d34fd3bf4491ec9d28352c2e37881fb077
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 38c036ad39aaa421b0cc2c51c6d708f225c425ab.nq.gz
│   │   └── 5e54ac6dcdfe9dafff011a56de3d234470761400.nq.gz
│   └── repolex
│       └── 38c036ad39aaa421b0cc2c51c6d708f225c425ab
│           └── chunk-001.nq.gz
└── blob
    ├── 0145a3e1383a45cdc800b3fc02fd17971ef1f2b0.nq.gz
    ├── 0198e4504b48fcde2de57d25d4c9da39e253ee83.nq.gz
    ├── 04b5c586de8abec81be4751dc5c59fcb5dbf544e.nq.gz
    ├── 071826f4c86e53db3286dbb1bf9455be0b41dbcf.nq.gz
    ├── 0862f183575094bab283683537d63f6b69f46b01.nq.gz
    ├── 08672c4475e5e9a466a22755da484d5715c99b0b.nq.gz
    ├── 0893b294cca20e2aca66fec6244176d71f951a6d.nq.gz
    ├── 08db3ddad6aab856dd30b552bd672acb8b55e7aa.nq.gz
    ├── 099f0ffc3ead3058909bb6f72110540de9213516.nq.gz
    ├── 0aff59c96d97eb8ef07b786a0afa5e0d822e2907.nq.gz
    ├── 0ccfef92491e61a2688d6c21024298923d4edc88.nq.gz
    ├── 0dfd0f91e5c8f5c8771c75aba921ef55fbfb3ba4.nq.gz
    ├── 0fc0c66338c73cbd92be0aa2a58a0e5a3bcabc8f.nq.gz
    ├── 0fc2093c63796f217f15af1327ee9d593565a333.nq.gz
    ├── 0fcabd03a9fdff110a431a015e41d6a85c87b61f.nq.gz
    ├── 105eee4174bcc453bce0e787cd1d334965914707.nq.gz
    ├── 1075ad163169b9db5fa6c84d221f8216a3fd9550.nq.gz
    ├── 1107c0c699f92d9a7eb86932fe2c74318fdb837a.nq.gz
    ├── 112bd5ebefc1419613937662bfd18416ceb470f0.nq.gz
    ├── 118b2fa89b0469923546bcbf7e49f56f75506995.nq.gz
    ├── 123bb35e4eb3f08dd754396dd7a19524d2d91916.nq.gz
    ├── 129ee1dbaa0ddd5f6c46048e5312118646075c8c.nq.gz
    ├── 12dd10bb5e0384c1885a8d4499465497b4047816.nq.gz
    ├── 146f6c9c00fd79af0175fef490a774812397239d.nq.gz
    ├── 163457b9f774a60d7833517ff7a628ee9d286eca.nq.gz
    ├── 179a02b6954a4024c6d1b59edcf8f3c8686e8852.nq.gz
    ├── 189479c24486f0cb5421bb22f4a3b7c2c93eb6f1.nq.gz
    ├── 18d1a4d8eff44cc74e6f409bf84535c89ae9901d.nq.gz
    ├── 1aee535439e608e86498f8923e7a042325212571.nq.gz
    ├── 1b5f301bfe5f4a51aaa23df5b2142c7092b6a108.nq.gz
    ├── 1b8ed76788d66241c5116f901ff68b4384efce19.nq.gz
    ├── 1c481c25b2b317a57c04287ae86907eabbcb5e15.nq.gz
    ├── 1c52a8c6947535386d0d3cd983eb7b2b1db0c6c3.nq.gz
    ├── 1c633410a10a56405b5d20cdcebebfa4b02a3ac2.nq.gz
    ├── 1d0a508385f516b6c9b8cae086fae653d2301e5c.nq.gz
    ├── 1d2970971b6dda4b658fe066c9a4496e3b1bce3e.nq.gz
    ├── 1e27463af11c135d40518836297b04991fccec98.nq.gz
    ├── 1e75da4dcf95e908a1d9fd2ba2c6f2adedac2c77.nq.gz
    ├── 1ed6d8999130922b340477c57aa7916c2f4c3bae.nq.gz
    ├── 1f6b39c6268fcbe88ae97942891ae50bfcc3f264.nq.gz
    ├── 20b380b9275ef3572aae8b14fe05d3376be5b041.nq.gz
    ├── 20e2395ea8626df6dc7e64f1cc242d282367f937.nq.gz
    ├── 2118e74584f1357a21a896b67121097cdc225750.nq.gz
    ├── 2146716cf54b77659aa13147211cbb976bcc79c8.nq.gz
    ├── 2148ee22e490b3c92c16631ba42640f2b4e2ba5d.nq.gz
    ├── 21bb498d5b4a18409a3cbd73afffcf76dc5caecb.nq.gz
    ├── 21fa028d321f863d1859547bb71c5747d8464529.nq.gz
    ├── 220228fd053ceb83fca6659a94e48f33d67314d7.nq.gz
    ├── 221cc12aaa82e13fa86000f0203928e8fe9819f7.nq.gz
    ├── 23520c6574ae63cf9951495913f931ffc2388ac3.nq.gz
    ├── 24c13d2a47b86a7be74c83a1bb1277b7e417d702.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 272de1f92fb7f1d6c3beb521a30c813e17bd25c0.nq.gz
    ├── 289cb5afeaddfef78f6dd35f27ae0f3ac055e6a1.nq.gz
    ├── 2a1c2b0a86844437fc8c178412cf3552e0f218b2.nq.gz
    ├── 2ac40fc1ee863194fa1621acb34d3e5027e3285e.nq.gz
    ├── 2b8b89e5e27ea5adbbb4b082c9e9b86d9a8dd99f.nq.gz
    ├── 2d03fba3cf9e335782607f68823017886edb7446.nq.gz
    ├── 2df2229eaea4f776e2a5f0a17ace65856c5c326d.nq.gz
    ├── 2f87bf4deaadabf378cd939b8e843fb007362e34.nq.gz
    ├── 2fb37ee819754feaffcf11cc6b925f60fac490e6.nq.gz
    ├── 3104cbf8483cf4ac0548177d0a2e299bd1af7b44.nq.gz
    ├── 3377e7dfcdafc03abd5addac7a29416805edbed8.nq.gz
    ├── 340078e5f1fb316c4cc9fd6e53567778ec682dda.nq.gz
    ├── 3412062b4409d59f7eea024f6f8d6add9d88b2bd.nq.gz
    ├── 348bb003dc97843d3d5151313d7a2709d2bcd8df.nq.gz
    ├── 3501136812cb639f6f93412fc9ef5bb7ce177a64.nq.gz
    ├── 359e6f98bdc6525cb0ccdcbdd6a1966b1f0c4689.nq.gz
    ├── 36ccb5677e49d6805f3fbc17e2d6919765a7cb15.nq.gz
    ├── 36eabf2754621e4dfae389925879d58fd5e76ef6.nq.gz
    ├── 3712da30d33ec499e6f2c2fecbb8f41e074a1435.nq.gz
    ├── 37cbe46d29cfd133eb6c00095159ab9bbccbed63.nq.gz
    ├── 37eb118f4275dd80fc5bc2dcb78dd2ad4abfa270.nq.gz
    ├── 38b4fc7c80e875af0dcbc49c7715d3b5b5fd7d99.nq.gz
    ├── 39a004975c6182c1a00df2a0c9ace8338d401fa7.nq.gz
    ├── 39fa5ba231959f809f2a1c30786ad81aad92232e.nq.gz
    ├── 3a43fad97ae44c499098f58fe58da8a44be06642.nq.gz
    ├── 3ad908f72fa4aa8ab667bcb6b7240d359904c6b2.nq.gz
    ├── 3b5e027f9abf249a033bb26c829dae257b398d87.nq.gz
    ├── 3b98be509a46c40bf29cfdee680144a3b5062b39.nq.gz
    ├── 3dec9fd1a5d49d20411a642a20e28aba9df8a29d.nq.gz
    ├── 3e769c74f9dc72f4415f398f503392325fead8c3.nq.gz
    ├── 3f0b6740f5a53a62aa95607139748e01ce594cd7.nq.gz
    ├── 3f581b6bae9797b9692fae0b18fd693a3afa45d3.nq.gz
    ├── 3fce05f8abc0b3651d4a1752aea55e08ff6ce5bb.nq.gz
    ├── 403ffa5b7c75a5187cba5cf8e1b9886cc96a820f.nq.gz
    ├── 40d29c9dbec3e94d79cca600a0ede00b5c79ad43.nq.gz
    ├── 41e3139449e98b88e7372730443000904f1239f7.nq.gz
    ├── 43ef2f8d26825fc3a4dd78e036141e2bee78b4a9.nq.gz
    ├── 4450724eff2688b324bd9a24b00bf8ac97c2fe64.nq.gz
    ├── 46df9441a51baa7ab6592cd50f07eb5690a6ef72.nq.gz
    ├── 47471bdfbf4a20117f85e5719454d1e8e9d74efb.nq.gz
    ├── 476391d8f52a691af2bf7496c4aecd8d8795932e.nq.gz
    ├── 483ba0f19c7acb879d1225ed05715c23d8b5995b.nq.gz
    ├── 484f57050db5ad5d89d18052cc43a37c14c171a5.nq.gz
    ├── 48b3fae510a0867106b6d06667ae07f19a6a3a07.nq.gz
    ├── 48d6cbaa8fae7456b039419b7e660f97ee30ddcb.nq.gz
    ├── 495f0954fab373612cc103871804b82a39bb1ab0.nq.gz
    ├── 4baf9333690a62f742f8e9d868645e16e136bfcb.nq.gz
    ├── 4c82fc4330238f4f92fde9aba25d527d34a5d4a9.nq.gz
    ├── 4d4eb757c2c88c5415f8869ee5b11961a5470471.nq.gz
    ├── 4f27ab99bffb78c9664816b939b9e79a7eb5b77e.nq.gz
    ├── 502f59906fe54b13cc9e8d08a9e6bec44ad59221.nq.gz
    ├── 50c80ee46e8e1ccd52fd2e24b3b79159cc15df9a.nq.gz
    ├── 51f78ee9c11927be823a3731568a9b41a1e57d5c.nq.gz
    ├── 53a7416efcdd5ed3060acdf15bfcabf5e85d11f1.nq.gz
    ├── 53b86bbe3b9428579c554316879c1aac84a3b4da.nq.gz
    ├── 53b8a8311f47576f572bd47d2e3b40ba98e6b547.nq.gz
    ├── 5455d86a6941dfb62a04a95f82ce8a7940d9a534.nq.gz
    ├── 54605acd1fa53d405fbb8c54dc11f49ad38e61ac.nq.gz
    ├── 5524a36b3476a1272d78fe065ca45fb424deadca.nq.gz
    ├── 566652d0da83cf2b15a819b58d5c966af06b1da5.nq.gz
    ├── 572e03bdf321b6cc3a99488183436905cefd086d.nq.gz
    ├── 5982b69033db7e1d366e05074fdf32098509976a.nq.gz
    ├── 5a8dc010e6a4a587f602b1741946267788bec741.nq.gz
    ├── 5a97d80f259bae6fb73aa6b722d1c94502ceaff4.nq.gz
    ├── 5d1a2a27fcae3f426b417a251ea0fa3746786cf4.nq.gz
    ├── 61fd60e95cb67c1cdf9719575ed0cf413d1a5686.nq.gz
    ├── 63fd883777995afb5a9ff05a1b9d546df2dc80df.nq.gz
    ├── 649801fff81022daea369f6e8dec4282456f3d1f.nq.gz
    ├── 6564cdda634e2a1717aad2bebf62b0ca44927b9f.nq.gz
    ├── 6589b39e9fd1a6b368cb7fd539d1c6ff31c7cd4b.nq.gz
    ├── 65a28f793526b58753d24eff4bc0cb254793b658.nq.gz
    ├── 6723f6d0abca714c85dc7eeb63c28affc78d7fe3.nq.gz
    ├── 68532e56a367d47ecdce22ef1b29cf42e6acaf36.nq.gz
    ├── 69d21f3c263f7dcbe55a016a8d9f17246d482ee4.nq.gz
    ├── 6a985fb62bc1d8fc59277d9f58a64fd292dabaf3.nq.gz
    ├── 6ab361f2ce6ef62e204c9d4cbf25f1c52baa4a83.nq.gz
    ├── 6b34e2854e7eaf491d5ff9ffbf0dab67846212ea.nq.gz
    ├── 6b5bd50bc226368a07e009a060350960ad336e18.nq.gz
    ├── 6ba0e09bf8b6d2919c377b4fab23a0621807a553.nq.gz
    ├── 6c1ae79e9b2930ba39329f36b6950e8277358570.nq.gz
    ├── 6c7dbed62f3492db06175ac6e5aa52925cdc8dae.nq.gz
    ├── 6d4e5cc76e81a72efca50b78913c273ce0eca665.nq.gz
    ├── 6f5d94b29569dca305b38ae0adb5771921708bbe.nq.gz
    ├── 703d610fee707172eff310688f8e0a3327236834.nq.gz
    ├── 70523f68c52b1edb03e890c917f9720bd5a31427.nq.gz
    ├── 70e41a2d6f1d00ef29c4d2cb3cd89722d9e60a85.nq.gz
    ├── 71bed1a970e489ec27c564688ba651ce4b14711b.nq.gz
    ├── 7216d119a42e918dc603e6481212f68b7874b5a6.nq.gz
    ├── 74caba1e742a4fd18c5085fdd8da4275253fc672.nq.gz
    ├── 7585238efedfc33acdd9494b0269951aaf3909ec.nq.gz
    ├── 75eb3da98f27c6e9bb45cf3c50513040a7868917.nq.gz
    ├── 76219eb72e8524f15c21ec93b9b2592da49b5460.nq.gz
    ├── 766f3f6adbc050c28fad11c1091414872e848791.nq.gz
    ├── 787754f24e219f688cc5f8854e22034c37ab104c.nq.gz
    ├── 789dce22b53ebc419dfabb772f1b14547ad644df.nq.gz
    ├── 7a403addf0a5753a8a5980412bb46d30f8b80e89.nq.gz
    ├── 7aae56820c3b97bae45ce85e098a426a0a623dbc.nq.gz
    ├── 7af4eca84ad5371bd5fdf949ad91dc43c9fbc4f1.nq.gz
    ├── 7b0c473e2188e8cf6c7bbd2e7f2410cc4282052c.nq.gz
    ├── 7b19f5e9004b5e2c237d8cfb15e82b156603317e.nq.gz
    ├── 7b3db809a129fdf4359e497ef995fbdea62a58d5.nq.gz
    ├── 7b5ad09eb206c776c0ef846f4576b97b4272fb40.nq.gz
    ├── 7bcae64692c07c9f14b5f04a749a3d988616d45a.nq.gz
    ├── 7c6fe7e119e1f299716e9036b47a09390b5bd4ca.nq.gz
    ├── 7cb5bf65e12de935eb4f26b841bbf59bf70b6818.nq.gz
    ├── 7cef681d89341da045e38e61cfa8b8a250fd9a74.nq.gz
    ├── 7e6fc1d8aeaf4db0785c1ff5f870e0af8ea0f553.nq.gz
    ├── 810f5603e7b9c6505de08c3333579e095672f4e5.nq.gz
    ├── 81555d998c1ab3aeda30d863c3c80c06df24bfbd.nq.gz
    ├── 819ee1015159709e1be6abfb433b79919cc65637.nq.gz
    ├── 82171385270b8767884380d337a712f4c05ad4d9.nq.gz
    ├── 8382f28c17be26724c52a167e744026c995f2a42.nq.gz
    ├── 851ccc70bfab0091b608c493f07e4b98839e06e0.nq.gz
    ├── 8537654e95231ccdb01b58961668ffcfe18575c1.nq.gz
    ├── 863276b5776379a5925d2522c18bcc11aaf67030.nq.gz
    ├── 86c30c8c13767c6885e190d2f42c12ca644f908a.nq.gz
    ├── 873c9cbb5a741e043ed3a5db8ed4f5704ae4165e.nq.gz
    ├── 885725891603f2787059ec4d677dad9469be403e.nq.gz
    ├── 8860df2c519737088b066b9176e2b634be0c4cff.nq.gz
    ├── 89071f8cae3eda8a0411f80ae7a556812576e561.nq.gz
    ├── 89b470accba776f1ef35809408876a718d09d7a6.nq.gz
    ├── 8d7f417a268848a6978ec7b15a1b1f048cfaca78.nq.gz
    ├── 8de43d7c9da50d68ccc5bb6142e7c049d7d1ed14.nq.gz
    ├── 8de834e9320a0d0db3226cd62c8f1656dc456822.nq.gz
    ├── 90a6fa2c56bab7fdcf6f5eeeef6318e6ae718488.nq.gz
    ├── 91962cb072fad66d99fc2a9cadd4ae3f728a6228.nq.gz
    ├── 9232b527ff7c260748c48c3ed1f7c77c975a27ba.nq.gz
    ├── 932ce14de2363bd1b167bb257c89faed5fe353cc.nq.gz
    ├── 939db57f0c908b2375d618daca3c263addbc67ff.nq.gz
    ├── 93ac76ba8016510937165cf7f8deafdb8f1acbfc.nq.gz
    ├── 94779d014385442a15f2423a01769a82e48312a8.nq.gz
    ├── 94bfc23f9e94ddceec972bd91eccd88b798c902a.nq.gz
    ├── 94cf6c43f15be1aa6d2a29baa167e134e548bba7.nq.gz
    ├── 965b606f331b51d566b46025f9ff311a7aad0c12.nq.gz
    ├── 9762e4b4c5511ef9630fd51ce3fdb0429089a286.nq.gz
    ├── 97a701bc370db2dadc779ae4f6b20985ff668db4.nq.gz
    ├── 9898a0e879cefe57bea20cd93d862b4b6491d643.nq.gz
    ├── 9b9757ec004678fedc821b2df16b32fc0228c2e7.nq.gz
    ├── 9c7b7fa2a5c52fb4c3b2ec0e23c809bddb760cce.nq.gz
    ├── 9d04b08a1e8cdabd5188d184943080048f3c8bb2.nq.gz
    ├── 9d878f0ac5db9461505009f5a67bae08bedcfa59.nq.gz
    └── 9f16e7e86ce3c22aa804e13908d118e757535fa5.nq.gz

10 directories, 200 files
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

[quinn-rs/quinn](https://github.com/quinn-rs/quinn)

---
*Parsed on 2026-11-23 by [repolex](https://repolex.ai)*
