# Repolex Knowledge Graph of geopy/geopy

RDF knowledge graph data for [geopy/geopy](https://github.com/geopy/geopy), parsed by [repolex](https://repolex.ai).

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
rlex download geopy/geopy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 402cbba8b093e5e3f89c81b902f576d65608a123
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 402cbba8b093e5e3f89c81b902f576d65608a123
│           └── chunk-001.nq.gz
├── blob
│   ├── 028c7ad415c1b30306fa783471ade34200e6ecef.nq.gz
│   ├── 02bcec2b35ce9347f728f78db948f46cc94d7ea0.nq.gz
│   ├── 03aadff24203c7455cb12f8fd0cfac1606712728.nq.gz
│   ├── 06d5725ee0e9b5517e26bc6528afb6e2129aea6f.nq.gz
│   ├── 06fb4518474d8d886ce225586f5b948a1fc7f340.nq.gz
│   ├── 072d4b0d8fc3771ba6ed332d054b4b62f3c5f7dc.nq.gz
│   ├── 0ce297f0941b25b9791df8183bcf96d744d3431b.nq.gz
│   ├── 1126bd9e5943c10cf09613a052a20ca95510dede.nq.gz
│   ├── 1182fe975fd633dd4ded622b03c353b88459f06b.nq.gz
│   ├── 156a15e5d417be1a8d6cca6d7a7934c49d85d56c.nq.gz
│   ├── 1c652a8dcd1933a4bec305be2702f14fa8270134.nq.gz
│   ├── 2190a4c72e63302e6c216c0de1f8526cdf561070.nq.gz
│   ├── 22761195fc08585c87d3d023661dfeea5ed0a2d4.nq.gz
│   ├── 228d3818accbb3ce5e9642e4900e362568b8fc5b.nq.gz
│   ├── 23144ef2296467c1704c12ca357c8929ad6bb91a.nq.gz
│   ├── 24eb47673cab77c1dae7d55d314baa8e3dd57b76.nq.gz
│   ├── 2c6fde49b0f4e954d0ff58603aa2a657574270c2.nq.gz
│   ├── 2cc9bb7c6beb31679256560d7b679ba167f6c709.nq.gz
│   ├── 339f4d232f2a6dd2419ca0f77969826e894b37ef.nq.gz
│   ├── 33a91508b1c1e8ef0e2cfa149667adfe0623eb6a.nq.gz
│   ├── 3559726ba1b6ecaf4734fe7e91e95957099929aa.nq.gz
│   ├── 39b31828dd8476e32d88a69ec9f238d0d864c580.nq.gz
│   ├── 3a6d22351c3f67c081056d88747ff2a8b3f0c110.nq.gz
│   ├── 3a7c621c78b2d88f1e5b61920608919c357849d3.nq.gz
│   ├── 3e2d9eea7204fb45c7e4f429772c52ce791d90e9.nq.gz
│   ├── 40b8e94323e064bad961990f8799a4da59f08e5c.nq.gz
│   ├── 4393d232cfe862d9d01291a181b5ff74ef1e6c48.nq.gz
│   ├── 473181a6a51d9b661a79986aacbdfe15627f6489.nq.gz
│   ├── 4ad4f10ee2cc20ceb6383b6704dace3015f8f3a5.nq.gz
│   ├── 4c33b7df1fb6983792b88ff3d525d50c8ff05fec.nq.gz
│   ├── 4f40d0f43fb704a3cf2e0d4586762fdf334e861a.nq.gz
│   ├── 512d9673df7f4ee5ab2bfeda2a7ac58d15da698b.nq.gz
│   ├── 54d43d45b5ae6c3c284977055087a3d9ddfa552c.nq.gz
│   ├── 556dcbaa7f21120d6f457743c748f7f56ec21982.nq.gz
│   ├── 5597d90f000c36a5d9536aacd44b089f05f8bc63.nq.gz
│   ├── 591571ded0b2b68363c647832f47c5f5add19b5d.nq.gz
│   ├── 59dacc094eb2a596ef762342705d4471a5a9da3b.nq.gz
│   ├── 5ea6931c26a5c836f330aa1a3f592844a3203b00.nq.gz
│   ├── 5ee50f7914127bcf1c7b32f4eb2ba2ea24b52b03.nq.gz
│   ├── 5f90decd3e29282c5434992913bc1d32ed2c858c.nq.gz
│   ├── 606e8916c1d419de4170bb84a5de401db72b0cd9.nq.gz
│   ├── 60aac0e796d51dda5ce3cddbdb7618aaedd3ebdc.nq.gz
│   ├── 646a0e654f5fde8e8731a7183fc4d5a74a6c7083.nq.gz
│   ├── 6630de1eea713d08393c7f543cc41e057d42e129.nq.gz
│   ├── 69b53122790b1ad04ac3ef29499555bc90a9527d.nq.gz
│   ├── 6c875f5ef450794aadd6531901a93cbf5d09f8d8.nq.gz
│   ├── 6d1891886422fc17f5157594bb6e197e84327020.nq.gz
│   ├── 71495e6050da93beea9d4276261556942ae5064a.nq.gz
│   ├── 715a3d412ea12516f24da942693fad98606262fa.nq.gz
│   ├── 7348f3e7d1485d72032dbb35a6a91e0e4313d75f.nq.gz
│   ├── 73e50e8a9af9518356844300311ff0f6669b4bcb.nq.gz
│   ├── 74a84b68692b46da6114c7d6dd38e0c3a17fcd88.nq.gz
│   ├── 75b088fcc46731c8f9b1479e278b9f94dc1676b8.nq.gz
│   ├── 76cfe59c3b3e13ba42cc05df17826c499e1566cd.nq.gz
│   ├── 776ae5c1476c33ae40441e21701d2d1e663b7044.nq.gz
│   ├── 7798a738ac5f299428f1bd186e1e45ab2e17a1dd.nq.gz
│   ├── 7f5920054659c928928b363e1b9a23d6640c970e.nq.gz
│   ├── 80fd22e5343258de419a37159bd5cedc906c7021.nq.gz
│   ├── 83320a2a297c7979c7e0e62b2b22c442acd14583.nq.gz
│   ├── 84d3ce1683e05c815db6b7f0da44b94f47f646dc.nq.gz
│   ├── 85ea86199542bca707da9f91c6acc0471f7a794b.nq.gz
│   ├── 89c48485645e98740614970670b4c936569a1f7c.nq.gz
│   ├── 8c3e1297a7b9a70a482e4c6967168ec84e5d399d.nq.gz
│   ├── 923a61b6b949c98380190b42632d5189b7fe6189.nq.gz
│   ├── 923ba4a1e73c1cb27d8918b24b23aef8b519884a.nq.gz
│   ├── 93154424506235e8155f597e458d315114b5c776.nq.gz
│   ├── 935c8fed19d19abc79834196317ac91448446e5c.nq.gz
│   ├── 9573cdd44ff96d92e0d986fac3a9420d1bee7d25.nq.gz
│   ├── 96d8167e5cfefe33bc81b1bf0f9ee934ada4186a.nq.gz
│   ├── 9f27aa75609b9e7ab78d89b87d42c06aeb9cbbbe.nq.gz
│   ├── a1c3a96b86dd14f0a7aff3259cbf4336d55799e6.nq.gz
│   ├── a44f9c7d9549d87409a27173860c326eb9cb0e79.nq.gz
│   ├── a5eeb2c3d1b37d1fcd25859c852d2969b28668ce.nq.gz
│   ├── a645fff0e692656d63b58ab08ffe7e211eeb95cf.nq.gz
│   ├── a815030840c9b218f6f8c5b912d22e1f25e853b3.nq.gz
│   ├── ad2f2fff73ab67034e2a2cc1e371430177f4c7a0.nq.gz
│   ├── aef28f2c54ea3aa163143390625519dab072cf9d.nq.gz
│   ├── b06639596bc8bfb6271768d544e3597d67709b8b.nq.gz
│   ├── b307c47347254f9fedbb3379f853f2afe2676fb2.nq.gz
│   ├── b7e73f97a75ff68c75af8f8a97c9f78c4ee32223.nq.gz
│   ├── b80a53ff88f765575dfa05d4b9b18c643e583f10.nq.gz
│   ├── bc35cdd3a348e3501fb27fc8aa723cd55911a496.nq.gz
│   ├── bc70728b6839547d102e90117bec4698cc553721.nq.gz
│   ├── bd2b2c927ca5ac75e78dba2e038d16c634297145.nq.gz
│   ├── be3d689e5c8f4f05b0def06ac6987dc394a46bf3.nq.gz
│   ├── beb0cb92fab1a47474a28fc3fa604bdad12b76a4.nq.gz
│   ├── beda28e821662c8d9fdefee034d83a5d75f9c023.nq.gz
│   ├── bf42ce6b7c5ea1285de48234e06fe8fefaa0ec42.nq.gz
│   ├── bf8012b580fe2278396ac927887686bfdbb971b6.nq.gz
│   ├── c40290eeba0db06f991d971f953cb558e3b1d4bc.nq.gz
│   ├── c7a4465335ba09c4a0d2f6da887a67d208f87a24.nq.gz
│   ├── c8c4af765b858c35df81a1977635d70b2eadbcdb.nq.gz
│   ├── c9a2c9263ee4c7851483fd19fb2a5df1094a683b.nq.gz
│   ├── c9ef06e86c0b69cbc4f570bda479d81eb6c421e4.nq.gz
│   ├── cb311409063368f9571e0bec0801deeb2c52f977.nq.gz
│   ├── cc50a5b72ac0e9e123b757f6de252cb16eea1c7b.nq.gz
│   ├── d304b6dc2643457f0556dfb4c783f17629aa46f7.nq.gz
│   ├── d440718f9c217b5cb071a84232678e4d7833034b.nq.gz
│   ├── d9ab80fd92b58875e0837f42734d30086faaf31f.nq.gz
│   ├── dbba680100196d4d731a0c751975d261cbfd6fb8.nq.gz
│   ├── ddac6418cee21370daaedbd4ba089d38dd16282b.nq.gz
│   ├── e0ce83dd3d0f5dd9a4ce9961434c44eaa7f72644.nq.gz
│   ├── e3cd8084c55e7bc81b215addccca24388c668d31.nq.gz
│   ├── e61ca19ce7d5ef5447535341479b59ade832967e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e753b052891eafc0bb24a63d1ad098714bb78cb3.nq.gz
│   ├── e9aceb87b22f38e42d25edb3f0e09c2d6c3fd398.nq.gz
│   ├── eb4db1af0fe6b94753e625b968f97437500b8adf.nq.gz
│   ├── ed63b44db825702cae328b8e958dfbdbda9e3b40.nq.gz
│   ├── ef2f7a486aef67fa4b11f26cb1eea5d97bf3a00a.nq.gz
│   ├── efcf942661ab0f43a7fd948c642df39f36255f3e.nq.gz
│   ├── f27e6d64cc807eabe178cc116ec4cfd200860c00.nq.gz
│   ├── f34b1abe79e61b68f78d4a420fa2afab786332de.nq.gz
│   ├── f899d0b0e168cb2277e603930f7a38c71c4fc2fc.nq.gz
│   ├── f8afcf24bbe14c754ebf90f83d2f81fdc21e6c1a.nq.gz
│   └── fc212a61e28bcd8f83425a719265ddacb1393b83.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 402cbba8b093e5e3f89c81b902f576d65608a123.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 124 files
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

[geopy/geopy](https://github.com/geopy/geopy)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
