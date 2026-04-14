# Repolex Knowledge Graph of python-attrs/attrs

RDF knowledge graph data for [python-attrs/attrs](https://github.com/python-attrs/attrs), parsed by [repolex](https://repolex.ai).

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
lexq download python-attrs/attrs
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7bfc49e9b22d5ba25b6e429524c3d49fee27cb36
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 7bfc49e9b22d5ba25b6e429524c3d49fee27cb36.nq.gz
│   └── repolex
│       └── 7bfc49e9b22d5ba25b6e429524c3d49fee27cb36
│           └── chunk-001.nq.gz
├── blob
│   ├── 037e124f29f32d37c1642d159bf828de44f7c349.nq.gz
│   ├── 039df0790a835e3b70b74e4d867c3aada9edd5c3.nq.gz
│   ├── 057262b1bf99fb4b228fa07524df1aebc58c0046.nq.gz
│   ├── 06fa6696059d132ae5635e4d6d2e3853faf4504c.nq.gz
│   ├── 08314fa884015e91b62912a3e4e18efc788b71ef.nq.gz
│   ├── 09bab491f83ef4d15129f34b5f5a9e69bb34d63c.nq.gz
│   ├── 0a79deef04282fb33a42f6aca59563d49e70d4cb.nq.gz
│   ├── 0b1a294432d294c4f154be2d9439d825c3ec0781.nq.gz
│   ├── 0c120f6427045c8bf279b3cbb84e8d439ff068ef.nq.gz
│   ├── 0e6342bf50a93fc3d8cd53ad9d9ece192aef6150.nq.gz
│   ├── 0f4ab2e3741c719d6bdcb34aab9925ce17427f95.nq.gz
│   ├── 11b6e6fe3f99e87d7e7065d53c0fd6ca11f0a621.nq.gz
│   ├── 12bd0c4f17bdc60fb8904598af0a3d56d5874a9e.nq.gz
│   ├── 18fb112c89562c2b9625645e0babe1207a02675f.nq.gz
│   ├── 1adb50021373d9c09fcb9db0641bbc03248d54a3.nq.gz
│   ├── 1dc78d26fe4eef37be6e6608b72247e2fe2e07a3.nq.gz
│   ├── 2262f2c77b8db0b5537d101a4f4c99ed3f9a8ebb.nq.gz
│   ├── 231d818af6a1c4d42e0adf6cb87becc1e1a88124.nq.gz
│   ├── 2393decf45b257f7b520cdc608e879bc8da67b04.nq.gz
│   ├── 27f18884ad4d7a42f338e31a8ea19bc5d19999cd.nq.gz
│   ├── 2bd6453d255e19b973f19b128596a8b6dd65b2c3.nq.gz
│   ├── 3080f48398e5ed8d3428ca3efeb7500633b0cb0f.nq.gz
│   ├── 3143891daf88493b11e346e8def719df499eec9d.nq.gz
│   ├── 3323f9d2112c54b203763d45b455bd5abbe020f6.nq.gz
│   ├── 3c8d4d8b3568275687fa3203f5add3ec7eec3be8.nq.gz
│   ├── 3e48c3fdfb382a86d941b8af02844672ba5c4cfb.nq.gz
│   ├── 45ced086337783c4b73b26cd17d2c1c260e24029.nq.gz
│   ├── 46af5dcfd691cea269c52cf4cbc99836eea1bed9.nq.gz
│   ├── 47548b44a0625ca3f18c2610ef834a646ab9edfc.nq.gz
│   ├── 4b257726fb1e8b95583ecc3eee8d153336dc4089.nq.gz
│   ├── 4b32d6a71b0d91f3c4eb9ae615771aa46cae00eb.nq.gz
│   ├── 4ccd0da2446dc126ce936b054581a527e247cabc.nq.gz
│   ├── 548d2d447de68422c7e6df5d1da98b2169133f1d.nq.gz
│   ├── 54a2724cbd609d94f7574a38166e70e6379e9d28.nq.gz
│   ├── 54ca2abfc4383dc3f0957424afa389377bfdf255.nq.gz
│   ├── 5551b42bd92cbdec895a6b857445d229cb099308.nq.gz
│   ├── 56ec26bab6db3e5451daf153427d81cf8e6bdf5b.nq.gz
│   ├── 5726ae210a1214c5df118025b01f94c7bef40f2b.nq.gz
│   ├── 573ca99a005f5db074c02a00a1e1437086e4f8c3.nq.gz
│   ├── 5751b284819c34875556556c0878f973f720b2c0.nq.gz
│   ├── 575bc9f092c7b10c0a0d35285c4406d8b175fae3.nq.gz
│   ├── 5b4de7c32e57eaf4ee29ba31131af7a3f00dfe1b.nq.gz
│   ├── 5ba9bed8604d270c0e07b1c7de415595681acb40.nq.gz
│   ├── 5c6e0650bc4bf53806420d7ef5f881ecd2bd77ea.nq.gz
│   ├── 6324d401a069f4020efcf0ff07442724b52f47c2.nq.gz
│   ├── 6364bac4ea29f860934803e5f3ba741812c6dfd1.nq.gz
│   ├── 689b1705a60ff110d6077bab996f8b4588e55b82.nq.gz
│   ├── 6b4305d5bb9750b81340616c855ff754cebc9d0c.nq.gz
│   ├── 6f226c67e467f43e264d53dce5a74cfdcfd47508.nq.gz
│   ├── 72083fee482321b1b3501a1c4edbfed3cae3d4e5.nq.gz
│   ├── 7241cfa28436f8c08a9cfcd09b7496ad40720def.nq.gz
│   ├── 73abf36e7d5b0f5f56e7fddeee716824c1c60d58.nq.gz
│   ├── 741e9946e3afaa1bf4c98e4b73aab8dca72e798a.nq.gz
│   ├── 758decf8ffcb55833a7136219db2b99542bfc7a4.nq.gz
│   ├── 7821f6c02cca81277d1ecc87b6bdafad886d8b70.nq.gz
│   ├── 78b08398a6713fc5fa827c2dc853e0d05de743c4.nq.gz
│   ├── 78d98f68088e224f44b7eed9935ffaa9de50b921.nq.gz
│   ├── 7c5100942aae489ca04d07d2c69a4d8f6f8470fe.nq.gz
│   ├── 8090b4b81ba242ef17e2c56e43ce01da45305262.nq.gz
│   ├── 83718ad889d76d57bd2e54ecf08b512b0fae8e34.nq.gz
│   ├── 8a7da5098efd8e24ac4f6155597debfa5bc70bf6.nq.gz
│   ├── 8b4da42cb1572370d89c9158c1074d00662a02d4.nq.gz
│   ├── 8caa64272ab4018e6126211603dd5d7662be6ba8.nq.gz
│   ├── 8edfbd86b88881c0e9d67ae6cb219d2c7b0d96ad.nq.gz
│   ├── 8ee115b6ac4247b47be437fd0d8a74435b8fa1b5.nq.gz
│   ├── 90dfc2b0cb585f2440ab3db02f22deefab857878.nq.gz
│   ├── 92c04a1b503f45188a754ed84135840bd543a01d.nq.gz
│   ├── 96dc5c3039848643695850ce7f7e38cf29edf77c.nq.gz
│   ├── 974abdcdb51152393d9c9e460c21aa025c45880c.nq.gz
│   ├── 9b62e9d9ce5ba356a1c759f7ee09a5725b718744.nq.gz
│   ├── 9e90a5c11e685e7b9c14d5f84bb645c6a4f473cd.nq.gz
│   ├── a207df4028f7800f964c2917383ad26be61b665e.nq.gz
│   ├── a4f255ac0875af76e4edb43a75bd6ac7d1f3f59a.nq.gz
│   ├── a74c32b030af9d8e9cea97b085f0d2f300457f99.nq.gz
│   ├── a7cbf3e07caabb8d881a73aadcb3026d443ed575.nq.gz
│   ├── aa1b7a3a849e15884c3a2fd1a8ac015307a4281a.nq.gz
│   ├── af4ef5d86396af075e4fdd9e4e19b32de84caa61.nq.gz
│   ├── b02ae6c0253d06ca234a9ad3fd17f7f0a33231b0.nq.gz
│   ├── b044d1949907da5cbfca922f66515fa70ca272cd.nq.gz
│   ├── b06d17d7501abef7b2e968d18fb94d071ff4812b.nq.gz
│   ├── b12e9c0b52ccf4cbe4bfa6bc7870d14cbbfc4563.nq.gz
│   ├── b254e9898328da60a7f09eaa4a813210e9742d4c.nq.gz
│   ├── b26cf1dd1c1b19b5fef008c477c132c3b7420822.nq.gz
│   ├── b26ffac123c23aa6bc8c2b74eb3124ab1db69a83.nq.gz
│   ├── b2ce06c293bfbddc8dd2f6ce4323515963079dd5.nq.gz
│   ├── b3e8d300a6464467565c1379c092e91949a9f607.nq.gz
│   ├── b58afd704e5eb108377201fd919117e9fa847a8e.nq.gz
│   ├── b5aa136fae9a38fb39f5a14db9194db1e5d88ea3.nq.gz
│   ├── b82000ddd0136ac05e8f5eea74fc2292091e67ce.nq.gz
│   ├── b89eadebf61dc0cfca2e39137bd67aaad0dab10a.nq.gz
│   ├── b8dfa4593966688cd3846d670040809716ce0320.nq.gz
│   ├── b98929c982163e0cf92ee97c19d10fbaf1eec521.nq.gz
│   ├── bb08a37e1feffeec75d4bbe51e07b2dacf2eb78f.nq.gz
│   ├── bc68ed9eaf9853bcc6065e7691209a787bf2eccc.nq.gz
│   ├── bc9f57d92113eee36c855af21861b95012c6a84b.nq.gz
│   ├── bdc5c091b7f49c43debc8f9db044c2961ebf1496.nq.gz
│   ├── c318f41943ac569e1d73e85a1c734bb08bfd4cd9.nq.gz
│   ├── c72223778e63a0cf352747b00adb10cf66b7119f.nq.gz
│   ├── c745e3f6163eeb4f40c98670f3063b6d7015b525.nq.gz
│   ├── ca7b71e906a28f88726bbd342fdfe636af0281e7.nq.gz
│   ├── cc7893b04520afa719b1412c7646c3c1b39bf94b.nq.gz
│   ├── cd46bd07565aa2cf3aab3580363284ba2fac0458.nq.gz
│   ├── cf9f52a8faa8a986ef217d202d9d4cc85c558cdf.nq.gz
│   ├── cff4e948bcbe8e7cc8e6ddf545d57c7f6ef74fee.nq.gz
│   ├── d07a85984c95b99935f9ac803db19718116522d1.nq.gz
│   ├── d22cea1bd76a441e11d23d0daef68d6788cef9a0.nq.gz
│   ├── d943904e706d804b390829542ff57265ae65f254.nq.gz
│   ├── d9886f1f6f6bc39913ac3c054c5d0fc93a2b6115.nq.gz
│   ├── daad798da0080bf91b3221dcd7fbf496e6206c61.nq.gz
│   ├── dae09787e15e42edaf20dea19e019702903b27c8.nq.gz
│   ├── dc1ce4b974ea1b3971ced44e3e112e897cf29b0a.nq.gz
│   ├── e00d362f56f108709a09a48ec25d2aef52865205.nq.gz
│   ├── e0463c2157ae9839e35c459f05e2371d60d963d5.nq.gz
│   ├── e193d4ba1f4bcc2881f3a0e99e048dbf1b759c8a.nq.gz
│   ├── e3cec040d17713f7290df4405e830b2576480e39.nq.gz
│   ├── e4bb78e841aecf7c84cd6900045c1846c2302075.nq.gz
│   ├── e645550933831047b05ba08ac0576b6aa397357b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ec8c33334fee0c7b5da22af531a3394e02f63023.nq.gz
│   ├── ee84d9de1947f8cdcd7e7380769e9aae3f3d3e7d.nq.gz
│   ├── efd2e9c25aed56005837e4b80e809c9f73d90ab0.nq.gz
│   ├── f2680118b404db8f5227d04d27e8439331341c4d.nq.gz
│   ├── f3d73bb793dd49c138950961f41943bb26c57fde.nq.gz
│   ├── f42f1a9cf9a330524e4906016434adac6e6faf5c.nq.gz
│   ├── f44abf65847a433b83ad13e197d2a59ccc66c38a.nq.gz
│   ├── fb28110e6d57be3f475a12f32a0d982292bfd475.nq.gz
│   ├── fc462bf406e0f418cfac105ec82d15750b239e77.nq.gz
│   └── fc8546b3b9118ebf43d6128c789ff0ab74c97860.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 7bfc49e9b22d5ba25b6e429524c3d49fee27cb36.nq.gz
├── filetree
│   └── 7bfc49e9b22d5ba25b6e429524c3d49fee27cb36.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 138 files
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

[python-attrs/attrs](https://github.com/python-attrs/attrs)

---
*Parsed on 2026-04-14 by [repolex](https://repolex.ai)*
