# Repolex Knowledge Graph of modelcontextprotocol/go-sdk

RDF knowledge graph data for [modelcontextprotocol/go-sdk](https://github.com/modelcontextprotocol/go-sdk), parsed by [repolex](https://repolex.ai).

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
rlex download modelcontextprotocol/go-sdk
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 53effc04ea258b9ee618886702e03abc4306a160
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 53effc04ea258b9ee618886702e03abc4306a160.nq.gz
│   └── repolex
│       └── 53effc04ea258b9ee618886702e03abc4306a160
│           └── chunk-001.nq.gz
└── blob
    ├── 001237c0c58b674f9710838daeb5e2241b826b1d.nq.gz
    ├── 01c5ebea9f2a4a5fc36b6391b498a2f0a6dbb05c.nq.gz
    ├── 039c21b23dbede5fb0ed3ac99d529e05eee994f2.nq.gz
    ├── 03d9f85d32bf343db07e6e472d555d0a7be41c58.nq.gz
    ├── 046a79bace83a021389fc1cacfd8c2c15efe0008.nq.gz
    ├── 0507dd608a235624d81c8bbfb3d1a0d9a53d3953.nq.gz
    ├── 06c1b77b3f915498d2561fad71bf0015a006a169.nq.gz
    ├── 078b2f3319012d7ac6ee3a064b70ef1345d40f31.nq.gz
    ├── 08d3b15fd5cca9e06e463b0cb39ad8398ebdfb75.nq.gz
    ├── 098fce34c9cfc152dc5f93fb5f5646a3e5cd6d0d.nq.gz
    ├── 0a2cfbd214798cd094fbe63162e78e7cc5bcab33.nq.gz
    ├── 0c7b24eb42fbe2646485d7b8bd2e6715b9c97702.nq.gz
    ├── 0e77149a863d3fcd979db1a07842e2a1600f4339.nq.gz
    ├── 11486feae204a856314a169e3957237726c88954.nq.gz
    ├── 11ad100eeed9805a926e93a02a1470965f4c1bec.nq.gz
    ├── 120789c389fd11302eebb94733593e13bdf5648c.nq.gz
    ├── 151da7e5180368792c6752dc1deb3e80a4dd3926.nq.gz
    ├── 16321a46ab04733dda8f7b7982cdf613bb6d5c83.nq.gz
    ├── 16aad6a94f24c3b8c1139209efe9d7b7dd6af02e.nq.gz
    ├── 17341605132189ab5ca3a0226853deaa968b6bbc.nq.gz
    ├── 193d29f792f29d94d10f0bbb68588473f4b8c113.nq.gz
    ├── 1b19eed5e6509d6dbd75bbdd78f76c4c6e983943.nq.gz
    ├── 1c3ed8097cf1e665c7b9ca9e0eeb73f8eb7c7de4.nq.gz
    ├── 2042187cfe12668696c4139f76c1e239a8c2dff4.nq.gz
    ├── 21ad38631f2d2d08bbfbad90e366cfa6d07eaeaf.nq.gz
    ├── 23b02e7824682e28320c824f4457d684bce13653.nq.gz
    ├── 23d57be1d43e478b65713bffaa67bb3f61a20dc5.nq.gz
    ├── 258b75340a13d94e5d9b7d481e95866738259c7a.nq.gz
    ├── 262d726eb4da6a8c7d4f7d70acea585a4c029933.nq.gz
    ├── 2655114c4ebbc1be70b6c7dadac48ba3b00b90eb.nq.gz
    ├── 2d8e16860acaaeb61d1c7da0e6275e1e0c6af1e1.nq.gz
    ├── 2daa939547b381ebd9aa6077fc3009c766233a5e.nq.gz
    ├── 31b74a6820db9af55ac326d958aca71530b37713.nq.gz
    ├── 3287a95780c8160bdbb4554fb2f509ca369197a4.nq.gz
    ├── 331e8bd0cfd76f496874cd14243cf15a4d16f423.nq.gz
    ├── 34d8188c21d4ce58b0f721581e6c28585ac58f1b.nq.gz
    ├── 34e0a359dad61ef7b3053b937d383458732f3816.nq.gz
    ├── 356be180df33f83e961d9a8f003b156420b0dd39.nq.gz
    ├── 35827523a39ff8e93e086c3f7bbeca0beee67cc9.nq.gz
    ├── 3a0b3d8c5a0565a25bfa25677eff371b9f1edea2.nq.gz
    ├── 3a0e52b2ae1f40c401683c0b0ab73dce752de871.nq.gz
    ├── 3a4469b56867e37a33603cc143b9a2bbf291cb66.nq.gz
    ├── 40987b15ae955f7252ce77c16a91e5742086dc7c.nq.gz
    ├── 4164060019d87588e9e81619789f055f8999bc39.nq.gz
    ├── 434f6de5926201a833b41eaececbcafb430c3601.nq.gz
    ├── 438370fe58b87bc88a7731c85a53d3d69afe50ac.nq.gz
    ├── 4461b94ac35b4bf88386abaf6e9648059ed208f4.nq.gz
    ├── 44816189b3412e3a7efd2d2f7a69403b8ee21789.nq.gz
    ├── 45667689b19cc24e4cbf27e75495ecb36390127f.nq.gz
    ├── 4775c33d2180d9a78d41056e3631e7cd2951abd9.nq.gz
    ├── 4867fe9953497c02446d3abb851cb2c0ddbb1e79.nq.gz
    ├── 48923cd8fcbe146227c8badc9d95e63982b9d4a7.nq.gz
    ├── 4987239b335c6d7682780168a270b1034976cfcf.nq.gz
    ├── 499b026373d6fd694d7b922748d99105e8dc6a31.nq.gz
    ├── 4b3094efae8536cf6b2e4e94438a5a730603729a.nq.gz
    ├── 4cd68264aea044bd7aeb0cf76ae3f6ea76bd1c16.nq.gz
    ├── 4d6d31e0f3f47201015f3534a6a3c21f65843e58.nq.gz
    ├── 4e4c1e5bfa75a74bd175f65c235071f8f0899f4b.nq.gz
    ├── 4f0c345888ec9d2e9462635dc096dc0e870919e4.nq.gz
    ├── 50292420096eb98f07f3945dc30325fe8b17a2af.nq.gz
    ├── 5220b0ee712b78a69d2d6e8cafeb17828fb17c95.nq.gz
    ├── 522ee1fcca9e5cd4903d11b028d7acbf9643cf75.nq.gz
    ├── 54af6caab1f93066200060d7db8f4bdca8d21a5a.nq.gz
    ├── 56e950b869823ddee322c7c31b172eeeb878cd32.nq.gz
    ├── 5791499cb05de764964be318abf88ff59b9a82c6.nq.gz
    ├── 59bc25cf0fe4a175d56a24f3b00c791d4e9d6c75.nq.gz
    ├── 5aa37c13cd8f0ce4adb798a34f89241b9f11ac72.nq.gz
    ├── 5c351b3f9f444003c911bec7ee89a9b6a87a81e3.nq.gz
    ├── 5c6c4ad32ce4abe5eed2c7ba5764f56a58b20d31.nq.gz
    ├── 5d40ae64d59cf289b722492dafd70d0d151b4287.nq.gz
    ├── 5d7656dfee636383a270578d85a621b5828b928d.nq.gz
    ├── 5fb032d3cc0f5327701d4eb49ffc1688b0103f7d.nq.gz
    ├── 610755b78b77868a0207d55496d06ae5508c13e3.nq.gz
    ├── 62f38a36af77f359861c3ebf3cf673d8dfaebe27.nq.gz
    ├── 64414caa90947864aea41740fe13d5a6b08671c2.nq.gz
    ├── 64e7de0d7d72de1bce0f03425fd3cccd303e237e.nq.gz
    ├── 652aa7f32d6d3f8fc2f03f714f06962096d2a51e.nq.gz
    ├── 654ca26b832705bd2913f04c2fcd2bf0249df3b6.nq.gz
    ├── 66834f2cf01c9fe9adc91c7f50b38988e3309af0.nq.gz
    ├── 6956a54089867292f274ed6e95b82656d4e27ce2.nq.gz
    ├── 696aa9f923d6235707eae10baf5ec7f0a0a1d95b.nq.gz
    ├── 6974ad5d814ad44e08d14c86eae1ca7d7cce2918.nq.gz
    ├── 69a7ca60aa8ea710ca616fcdd88db00fe1cfa242.nq.gz
    ├── 6b2861fe2f91b6dc2ca5c2137e01699806132681.nq.gz
    ├── 6df9b16e34f4191d5652bc13782dd6105119a3a8.nq.gz
    ├── 6f54df4e09b3b9f53bf8a57469757305d2f2baaa.nq.gz
    ├── 711b17a43d0ae085277a82eb7d667706c6cf7448.nq.gz
    ├── 72270208cb60eee326878add3ef1d60b15f84155.nq.gz
    ├── 74940b3ad29bf9a0bd97612222bde59f7a5716bd.nq.gz
    ├── 74d82f12452274dd6f3eecea2fcd8439759a1418.nq.gz
    ├── 76a5116131aac8620eec6fb14be80322a0a9f0e7.nq.gz
    ├── 77d1de260aa2c222febb5cfbf4e073e76986d3d9.nq.gz
    ├── 77ff81a206717409197c3a9ff0ba0e0a8d947457.nq.gz
    ├── 796feff87200d2759bf7db272209073c23b341a5.nq.gz
    ├── 7a3ecab66be28a103109449fe6c0b557cac96cac.nq.gz
    ├── 7a82c96dd5ac8d5d313db7f11340900909bbaa0b.nq.gz
    ├── 7c98207a0521157f030b8b95ba1e1e5222ad3fc2.nq.gz
    ├── 7d5acfb2097acf5cdd92c040c414412054d16fa1.nq.gz
    ├── 7d6b01b5cfde793ee0d67a1407e4fac0f09026b8.nq.gz
    ├── 7e5d464593d4c57eb1a6af75353e2eb51e4cbfc1.nq.gz
    ├── 7f8f7ca355fefe13d04397e6c8b9cb0f470ccd52.nq.gz
    ├── 82292630ac2e4a9d7023073cc90fdaccad5fbe68.nq.gz
    ├── 83342032acf1f9379aea3574d5bef03dc4377de8.nq.gz
    ├── 849060d57ea61365e178fb9aee6702d4d79b8f82.nq.gz
    ├── 86c997010b9e10b0605dc0ecab15d8eff0e5b2c5.nq.gz
    ├── 86f04140282a15a0658687b5471914080c8fefb0.nq.gz
    ├── 880d1bfa0986428910bdb033d9d2f0c91389ca8b.nq.gz
    ├── 888cba54defdfd9e7b4725179be6434c4cf74c58.nq.gz
    ├── 8973e3ae94cef637e2c6c96d5cf43c8c6adb5904.nq.gz
    ├── 8a573e56ae3e49eeea6d64d885bfd3c162b78637.nq.gz
    ├── 8afdc20b2e841038f4d05614739e3a491016d64c.nq.gz
    ├── 8b64d0cbed94f52612b9058c11e86f7ea72a6339.nq.gz
    ├── 8b9677061643a96ae85d97f045dd723293308ef0.nq.gz
    ├── 8d05365a7b0451c2870f714cd59e30647cdccbf1.nq.gz
    ├── 8e08571d326bba9110ea3ced50e6769d0e100b21.nq.gz
    ├── 8fc997278a0541d359c2a636ef8cac2fc0213f10.nq.gz
    ├── 8ffaa74ef73d49047c08902b5c6b4b7e29d8b4e1.nq.gz
    ├── 90751f74019da9e17f7f58a1a6b0d77b25e40958.nq.gz
    ├── 914c5cdb699e08625d8c36536b8a0667b46676ae.nq.gz
    ├── 9159563c9d5a44a93cb90c76a28322a96c08232e.nq.gz
    ├── 91738816bf0326accbfbd7b45da381d45b22aafe.nq.gz
    ├── 934af532f22bfeec9f92fed7fa7e05e08b958b47.nq.gz
    ├── 94ad9ae3ff6ddaaa425a018f50437ae2ce1fcda6.nq.gz
    ├── 94da6ae3aa9a0bfd8e1244c5f3a810f7b17f2dc7.nq.gz
    ├── 950eef7271ef79960277909b2d152d1262bdae1b.nq.gz
    ├── 9536bdd4c592d32509a00e1ad0f484c1ec171e16.nq.gz
    ├── 97d8ad3eef0fc7b1740b0b9f7f967c7ffe31a443.nq.gz
    ├── 98373373f9ee3017abf7cfbd58eb26ae27ba58b4.nq.gz
    ├── 98ac3b173ba2f3d8b6593be459ec3ef72c15b85a.nq.gz
    ├── 995b378c80d2b5a36e58d437ec960841b31f695a.nq.gz
    ├── 9b6d1bb3676ef460915d54d5af4404ed1156e3be.nq.gz
    ├── 9bbbc32021e929ace7493f0d8c4b4abaad4c6fcc.nq.gz
    ├── 9cd9b9354cabe704fd381b4c525cbd59dead4017.nq.gz
    ├── 9d3ff7a4f8075eee1a762a056fa95ea8b1dce270.nq.gz
    ├── 9f8f2234b8fde1225987c7b3b696862a7159a6dd.nq.gz
    ├── a08cac83ae29e86de480d448d80a07406389df2f.nq.gz
    ├── a14b1344e9bfbe95a494a16c9daa4d1f7413b0fe.nq.gz
    ├── a481e7b7cb62335a27193452ada92303ec18a862.nq.gz
    ├── a9ea78fa840d30b4ff38173bdd95d4029fcab751.nq.gz
    ├── ad83ca0b2680722f7f75834ccce103579df8458f.nq.gz
    ├── adb2048ecc31855599b4353dfc7487b6ed6f1168.nq.gz
    ├── ae4318ffc4dc2fd00b7c9f67c953e64c9d55c48d.nq.gz
    ├── ae6bccbe3e108b96597684b54e555818e44cc356.nq.gz
    ├── af0244dab227307fb7081f7d3464853d1cce1623.nq.gz
    ├── afe9ecc6f65e5ec3e3ce1208a769523aea58ff6f.nq.gz
    ├── afeb4c0236de2146a9e5c4c102f0388c5b58928d.nq.gz
    ├── afff34cdd336af91e746a930c89503bf4573cbcd.nq.gz
    ├── b1b5016b5bd959c7043259639245f8462fb11ca4.nq.gz
    ├── b1d110ce6b83262b819ea346b3ad1c790072d190.nq.gz
    ├── b2189a7c4027fb0cfdaa6168291e47b391b16e20.nq.gz
    ├── b2973de7c992580d03e870831c6541db4142a084.nq.gz
    ├── b4d6ef66f2f72e8758987ef7ab3489e8692bbb2d.nq.gz
    ├── b531eaf132a20d7725d45db0b4b9311f0dae92f8.nq.gz
    ├── b7057ffdb4e7eca0e2d3ff53d1f0bdf379cc13af.nq.gz
    ├── b7d8ba0ffd23579c193b27a2f518c7d763cead51.nq.gz
    ├── ba6fd33e146127936aea7df75202c3ef5374323f.nq.gz
    ├── baeb3e7f7cd2faf81200c0b24f2e670c60fd85a1.nq.gz
    ├── bc659916c94e2af4fce56eb5d3bce53f68df9891.nq.gz
    ├── bd97e60cc5c14dc4c4b9a9adb4e2f742406876c0.nq.gz
    ├── bda479fd495c6b38255caa279f2b06822669c72f.nq.gz
    ├── bf97eb8706bf91acd933bcabbd4f68f97c0a29ef.nq.gz
    ├── c07f5be178c37f7698e4de36e74060a114230ffc.nq.gz
    ├── c0f1546fe718db5c7ff4cb099bdcbfa3e0261406.nq.gz
    ├── c0f64b4bcc16a5d7a46e55e668b00973f6a46748.nq.gz
    ├── c13454aad50d66edfca523be20fd9c230ff100c7.nq.gz
    ├── c1a618df78b7c096283027417ad123590f6d1a9a.nq.gz
    ├── c367cb62bf4203c32206ebaa038d6b609e32c529.nq.gz
    ├── c53c098b04a6c0cae9a46e33b481d9dc44ce9c99.nq.gz
    ├── c65d8b06614cb1d61b045949dd60ab062d2b12a1.nq.gz
    ├── c69fc4b1f0a16bd4dd6e524734a1c95a38bef915.nq.gz
    ├── c7c76c7933a31f2857c15c0405a4aa42cc3efcb5.nq.gz
    ├── cad1303d7eccaa853f4e3ad7a286516633939702.nq.gz
    ├── cb67bcb99b1d98fbb8e56e6798472b30a370f8e4.nq.gz
    ├── ce1f6fc3e01d3968c82156e07bd09a964db622bd.nq.gz
    ├── ce398c1631680de85ecade4405c6229ecd8b240b.nq.gz
    ├── ced4871e9bef1d64c1a39bda7104dc8ec80a57a8.nq.gz
    ├── d028037ad3c6b93e2dbfe71211ae134dd4a1be9c.nq.gz
    ├── d255e6311a6a71bd32ae024f22d72650c718300b.nq.gz
    ├── d2ecf10da296cafe8f708c70392cd24745b70daa.nq.gz
    ├── d32641548b2262730f7b9d93188e78510e950aad.nq.gz
    ├── d5ef54000f6c527637ce01a36948ff089c7466b9.nq.gz
    ├── d7f4f740c6489bcdb66ffd62fa88ab902a0055f2.nq.gz
    ├── d96621987fb1e0705b23d0e9bc92ccf54aa5d2fd.nq.gz
    ├── d9d259bdf7776a334312e06b61fc97bdd482427e.nq.gz
    ├── dadf196b5b170f995b129484f1dce128986b5522.nq.gz
    ├── db32d97a1a0413495efa56c490ca9897fd202be0.nq.gz
    ├── dc02d7d66f342309229af8d967c6f794ef7cd404.nq.gz
    ├── dc2407dc1873ca16d1b80d88635a4a5dd86c14be.nq.gz
    ├── dc3755435859473baf8fbfd45c2b4249e193556b.nq.gz
    ├── dfe437bdebebc3622d41956323785d23e7042ced.nq.gz
    ├── e056a64e0b0ad500cf705b5999d66443be828dc2.nq.gz
    ├── e107183fbb50326eae4584f51c164489f69aada8.nq.gz
    ├── e2641335dc09bd8e76ae92f598a4a1d9353bd96f.nq.gz
    ├── e58d4381955fe5f9eb37d8b9836a48a99ada1b4f.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e8b00a8424d7eb1f4cf270381073959765c659bd.nq.gz
    └── e8d0cd73b05d2b605919a78311c36439398aac51.nq.gz

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
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[modelcontextprotocol/go-sdk](https://github.com/modelcontextprotocol/go-sdk)

---
*Parsed on 2026-10-04 by [repolex](https://repolex.ai)*
