# Repolex Knowledge Graph of ansible-collections/community.libvirt

RDF knowledge graph data for [ansible-collections/community.libvirt](https://github.com/ansible-collections/community.libvirt), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/community.libvirt
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a820e65d210ec7690bf4ca3852ba72ecdcd76477
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a820e65d210ec7690bf4ca3852ba72ecdcd76477
│           └── chunk-001.nq.gz
├── blob
│   ├── 00176d316b3f05e0874e99786ea7e4af29139df8.nq.gz
│   ├── 007b75915ae6be093a3c8d6efc7cd04498542324.nq.gz
│   ├── 022dcfa87ecbe6100f70fe8c622d034d85d0d889.nq.gz
│   ├── 058be4089269f900a77778b8079f688d6327382e.nq.gz
│   ├── 063ac692390ed749e0e3dca48546fc3440c2cb0c.nq.gz
│   ├── 07c6fd12cf18f5cf0fa718a45d64565d09707b1b.nq.gz
│   ├── 0c54a42c8ffbf0be630d64e6c41c119c4b1961ed.nq.gz
│   ├── 0ea05eba9c649854be0f8fcc8b91dfbfcd17e0fd.nq.gz
│   ├── 0ec09d85b18c946ea5bc383c549ed41ca9a01f1d.nq.gz
│   ├── 1128ddcfa9626edfa88b90461553dd3604aeb3ec.nq.gz
│   ├── 113fc5294c530ec429bef14781ffb5d182302969.nq.gz
│   ├── 1257a1add512bc1017baaa95f2e71bd3e9971b4b.nq.gz
│   ├── 136c05e0d0290e2dc7eb89bceaa27b5f011e780a.nq.gz
│   ├── 151c10e5fba1f5241a856aa3f24cbfc19752744d.nq.gz
│   ├── 15fc56611838cbf023a3349331d5d6624b770f32.nq.gz
│   ├── 1864e4441056fcc37fd4024ff19c946244d82a60.nq.gz
│   ├── 1aad4714abdc07eea240fcc5bb7bb99b1c8b42c0.nq.gz
│   ├── 1bf0b2dbcf02030eec778be2f42f94ef313f7d4c.nq.gz
│   ├── 1c7977e1e234d5d8083369914adab63f8360c744.nq.gz
│   ├── 1ccb2a18f0b3d6058e811e5b1207f5371ffdd058.nq.gz
│   ├── 2193b5694b8ceaf9e4ba1eec8a27bca0de0a7ce9.nq.gz
│   ├── 2200502f56a2ee5472634f957f964046bf785d27.nq.gz
│   ├── 263281fec890570c6328b507d97d074d835dbd02.nq.gz
│   ├── 27bb6b2f05040da1a22cc69e989e90f2c08814fc.nq.gz
│   ├── 2a07d36a9201a2d9a968003b21eb4e711f85c832.nq.gz
│   ├── 2e0f0b82e5f1a2fab08202cc2723dd7175b2bdca.nq.gz
│   ├── 2ee3c9fa9b21eade729afb639808ce15cfbbf6b2.nq.gz
│   ├── 322301e3cb53913b4104befd3c460fe4e4a11338.nq.gz
│   ├── 3546233b7c0c07f9ee4e13d8e71477338c362aa0.nq.gz
│   ├── 3645335285e46173e5d4db96dc46b52bd31aab5e.nq.gz
│   ├── 36b74a4edc3a10dc1adfbe58a88737dbcd1a1a3d.nq.gz
│   ├── 377e2a00debc4e0f77c6ecac189dd63b1a400b01.nq.gz
│   ├── 385e70bac59c4b7ed66ff71fb59cdbdf466efafe.nq.gz
│   ├── 39b0909961cdcbf65830fe73738bfee429cfa91a.nq.gz
│   ├── 3ac65452092a522cc2931c9bed856a7f02e23280.nq.gz
│   ├── 3b0117333ceaa2e75ce03fd2d7446e38482661e8.nq.gz
│   ├── 3d9fe0309382a0b062045d879eda7c855e982727.nq.gz
│   ├── 3da24a50cc645d2bfc6cfca4624563573232f74d.nq.gz
│   ├── 3ea55b58bedd9236b2fd9980d58bc18673818edf.nq.gz
│   ├── 3eb3aa61517cff07e48b55cf89facf4745ebfb14.nq.gz
│   ├── 41bf955499aed9c91d6ed0a7e34c287d407fe7f6.nq.gz
│   ├── 43486d16f1be27023d11a52adf9e3d5443ea18a7.nq.gz
│   ├── 44ba6a10d0a26ecb69183b80296e234c9401bd95.nq.gz
│   ├── 45e0605866cd81c8b6dcb8bf2bd13d666dcf4914.nq.gz
│   ├── 46fbcb41523af9cb73bca9c6bfcd2436841b11ae.nq.gz
│   ├── 47d95782d85ad53261e1eb2cf6e8b108c543cf4e.nq.gz
│   ├── 4a329bff0bc028d2a90181589b98895d42b66aff.nq.gz
│   ├── 4a67f09e5388414f9a32ff3d9a9762fd03e288aa.nq.gz
│   ├── 4bf9e05c4d6333a33f1df6b2e034f796cf1cd842.nq.gz
│   ├── 4c1b6cd2b32b0ffbed8086b3574d30b2ee71e505.nq.gz
│   ├── 4fe950955b98178e9a9c6e18d0248c539fb8b10e.nq.gz
│   ├── 50392e8e889c5b5ae6fbfe7cfbbfa959b49a6822.nq.gz
│   ├── 506ade6460cda42c8f1d65d07abc60f75aafca5e.nq.gz
│   ├── 50b6bb868e3d1069a34f1fe6c443e23878b2d3f9.nq.gz
│   ├── 536bb5c2053aa171e25b987394f69b7374023170.nq.gz
│   ├── 53b6f9a549ca13e8d306eb08b659062b17a82812.nq.gz
│   ├── 5492bb66031a544e958b46b76377abffcbd23d50.nq.gz
│   ├── 585478c7b6afc1697d9bb2c789c61ec8ea49cb02.nq.gz
│   ├── 5b024472f201ef82aa4082c3cab5dad6ead4d83f.nq.gz
│   ├── 5b2fdd2a38c5710abcfba0b05228353521ac3b54.nq.gz
│   ├── 5d4473a36bc21576d4e05f7268817c32314853a2.nq.gz
│   ├── 5e665ac28a445f680ebcb020d8aeebe55b3c4fe5.nq.gz
│   ├── 5e8eb8d4c8f479eb5c498fd5a35ffe963e5e23cb.nq.gz
│   ├── 5e95602898897c41e4c62d24540e58c5866df52f.nq.gz
│   ├── 62b7a12e509a5cd9d0fd2b801ef23fb85e84f271.nq.gz
│   ├── 64960fbb83e35560f5e1a1572a31aa2c2abe9044.nq.gz
│   ├── 68acada899ae2570afa5bf5827f67bc8178358c9.nq.gz
│   ├── 69cef2476d243506fc72f9a25e2c274729cc0679.nq.gz
│   ├── 6d184f0b8da1d1198973da2c3145b32b1f2a57ed.nq.gz
│   ├── 6da89a031f5c6e378ab9e5b8d65927eb91ae05df.nq.gz
│   ├── 6ddb77685452b41e26a1a4aeafd20688342eec77.nq.gz
│   ├── 701dd55bcf5c03c351f05a85405c67bd08b5e8f0.nq.gz
│   ├── 74a98eb631193c126246c69e1e1c061201c34b90.nq.gz
│   ├── 74be9495e770160e74419f7227dc1a23047d59d7.nq.gz
│   ├── 768e10eaa863b312d94fb3d770f7b1ee4a4e0269.nq.gz
│   ├── 77e25783046f219692c73b44e2c10e78e425c139.nq.gz
│   ├── 78e053437067f90f95c81403701c69580e2cee3d.nq.gz
│   ├── 7c80653d659767d803f1034057cb6f68bbdcf4f2.nq.gz
│   ├── 7d06d77cd63f80ae82c64c321741333d8bffe26a.nq.gz
│   ├── 7ec4f13f837d08f35b769d09ee7fee6cb00479e0.nq.gz
│   ├── 83e48d02812204754205eb8b5a03639a8f919515.nq.gz
│   ├── 84d73ef2a0810f8347eb8481fbb3932d04108638.nq.gz
│   ├── 889e71429d68634316616c28520d95f60562b390.nq.gz
│   ├── 8a01bf941d0f234104c8d3fdf641843bedbe467e.nq.gz
│   ├── 8cb3ca3cf358b367ab267fba38570c4ce664134a.nq.gz
│   ├── 8d7a1eb695f0612217debefe0a7a24c293d28a2c.nq.gz
│   ├── 9382add6ceb43188fab16a30d15d7fb788a46501.nq.gz
│   ├── 969f1a0ae598ecbdf80b5d525ef0cf23b9dbe447.nq.gz
│   ├── 976161e067d58a344ee20cbe4430942e2d5aedb1.nq.gz
│   ├── 98f08ad6a8474fbcc3e338436bae46663d4aa4ae.nq.gz
│   ├── 998687a5f49d91aaa8f172f78f357606aa7466d0.nq.gz
│   ├── 99c9dfb8aebace5680c8e1ef3c23cbdfa0a4d3f7.nq.gz
│   ├── 9beae3030eab4eac0d873cabe392dbd46566e265.nq.gz
│   ├── 9c3d73d2cdae62763b1cea89af01785154ac8c4f.nq.gz
│   ├── 9e84a28499cdab2cd5b62a94b99b1b6ba5e5b4c2.nq.gz
│   ├── 9fad0d343c07aa82e21752481014bb870092c693.nq.gz
│   ├── a55f4b2389e9419b20c7f8932bd1bf9f5ef81bae.nq.gz
│   ├── a6133f9fb286f03ddc53b7fd27807efd83455a76.nq.gz
│   ├── a7366cc1c2b1d3e4eba19ffa13036cb59728e9e4.nq.gz
│   ├── a947fdf013c094d1fab17bf5d424afd03db120e1.nq.gz
│   ├── ab90481d5d75200bdc779014d93d69ff85bf9742.nq.gz
│   ├── ad7ccf7ada2d16397ae32253ac5712f83b7a4b36.nq.gz
│   ├── ae7c10da450c696106a43e062b7a98311c9aef7b.nq.gz
│   ├── ae9d6a06b601a486fb6cba34ec09534ba3629a68.nq.gz
│   ├── b1d33b85fb8e8d65c6fbf574efc1aaf1b6abb98b.nq.gz
│   ├── b1e21523edbd4ab90f68b2b081dd3d303e33bbdb.nq.gz
│   ├── b259f2f853cf00af01ce268adcf66c3bb6bfb16c.nq.gz
│   ├── b28753e4adba303d2742e060eb1c9e262caf19b1.nq.gz
│   ├── b31664245a90feb7190966a279f9d8145842e84a.nq.gz
│   ├── b3b104f804ca5429a11a27adb7a15e2ba27aa926.nq.gz
│   ├── b6cf3274c46b4d879bd50c9aa40542d961dfc5a0.nq.gz
│   ├── b78447f820c84843d5ae6b4462927d0d04d6a7fc.nq.gz
│   ├── b909641c7c37f2cd48afa85fa5f587cbca2197eb.nq.gz
│   ├── b9ad4aa66e8431b9512877f45c8d893e0a0caa2d.nq.gz
│   ├── bb27ffcdc765657d1ce68ecc45847550a474b052.nq.gz
│   ├── bcef64b8c2bace2b4faa71c08cd827ebcb2e7742.nq.gz
│   ├── c02ecffa3d29f0209da6fdc188ff1338eb4eaf2a.nq.gz
│   ├── c2db08e3cef1d374c153cf2ab2742a8594f7cd97.nq.gz
│   ├── c3474bf31bfa0b3ec7bf5e99b400aede5ce9b69c.nq.gz
│   ├── c3f58a742c10326494a3750d88337e48cfc77415.nq.gz
│   ├── c61dfee76e840ea05eaaa884cf363c9c388acf46.nq.gz
│   ├── c7a244eb00bb0788e2688b27de8af872f6340f1d.nq.gz
│   ├── c7d01830769808293f90856257752c2b6775d55a.nq.gz
│   ├── c94f048a53e598be076390c3f0b90c66987c8870.nq.gz
│   ├── c96395fdc736009dc5c3af68269adb959369ef8b.nq.gz
│   ├── ca63e361886f9d37315f7246e262bb56e88d5695.nq.gz
│   ├── cc1c74d9646cee1618e29f4898b540bba5cd6c0c.nq.gz
│   ├── ccc2248c121e3f7a7bc57883d7e679a8c96fbb2f.nq.gz
│   ├── cd3014ccac732c65cfafb333eb032450e429f95c.nq.gz
│   ├── cd794e20974539bab0682537733446ca1e966055.nq.gz
│   ├── cdf1315d50fe2087525b131d647faad545f408f7.nq.gz
│   ├── ced802fbb60c78cb438bf2fae42fbf6a6862a5e8.nq.gz
│   ├── cee5fc623281173a6f2c25ab4fda432ce6e07f39.nq.gz
│   ├── cf0b18fb3eb30b10fdc57133653a63b76c973b7e.nq.gz
│   ├── cf5715c46d3b15fe07c0dbe624b3ccecd57a833e.nq.gz
│   ├── d20e85fa73829a9a55f8a16333d3953199cf76d1.nq.gz
│   ├── d34f10ca290d871fada62aef8af49bfad9d682f4.nq.gz
│   ├── d3976ff30b2de82dceb26dc809b76c1427240819.nq.gz
│   ├── d46d01897851f5924beb9e835a6a15e637f559c0.nq.gz
│   ├── d6efa63588b02cf865516e68aa397aecd85cb5cf.nq.gz
│   ├── d76c32282d0e7b26fe78d83c58bed5ab45fe4f99.nq.gz
│   ├── da763e47e92c63afcd7e1870d94b2b66e499af96.nq.gz
│   ├── daa79a251f9381503b6718b2ac48121a8e908e7c.nq.gz
│   ├── dc53cdd1c4a02a3c6c920da463527794af2116d4.nq.gz
│   ├── dcf754dc9b5fe4610d06fbacaa11bb3453c8ab03.nq.gz
│   ├── e2a1952cbc601d4f9cb33b6fc7f781e9bb943ed6.nq.gz
│   ├── e35e10e2b07c4cae5958e9f555bcb69e77bceeb5.nq.gz
│   ├── e4b19ec5c5a26948916dcf468b1d5340750f5f26.nq.gz
│   ├── e546735f5a3161f01b5adb3e523587b25ca81e02.nq.gz
│   ├── e670ed51d75113dc771919e35efd01c1568875f6.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6a2a75975c797b5514362996d7e3974c3809e9b.nq.gz
│   ├── e6d056f544d66577b3ccfed97cd2e96b13c15f57.nq.gz
│   ├── e8a8b3cc455370843b2a5e905898921ce027e421.nq.gz
│   ├── edd62a13c45566c713c38dd75029ca20a0c9e50f.nq.gz
│   ├── f15499831237a2c128899e1e31076058a8fb9ed7.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f2be729908e59a7b0738fd042963ba581648158d.nq.gz
│   ├── f3a786c3d472088ef11fc2a0571cbd4b4326dbcf.nq.gz
│   ├── f3f1d1bae83ba3a8341f6bb4d672dec95e9b05f0.nq.gz
│   ├── f60ee6782280b043f8014305cffb9b0d2c4d184d.nq.gz
│   ├── f6422b3c50541ab2b4f990b5b2455c24920bad7a.nq.gz
│   ├── f7d7dd652d6c60e7c28f9b8cbf2c05e50ecc7fb5.nq.gz
│   ├── f81ce64816c2ca5721e252f382bfda9ddb4ca502.nq.gz
│   ├── fb538271b8494d9233811b19d7b42073f20af647.nq.gz
│   ├── fe044d71c079bf29d9982f3542abc95cecee6fd3.nq.gz
│   ├── fe5fef6e13f813c240d4ab7388340495c32f5dcb.nq.gz
│   ├── fee41b035b0cedcf603ffb7f387dd9e5f7769f4e.nq.gz
│   ├── ff944175c7f399a5e93d13238e43e42a6003de4c.nq.gz
│   ├── ffb8acc4d4ce2d9053cc5e147dfda59f52a00066.nq.gz
│   └── ffe530260bf08f67347414f229b6d9afbdb4d42d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a820e65d210ec7690bf4ca3852ba72ecdcd76477.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 179 files
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

[ansible-collections/community.libvirt](https://github.com/ansible-collections/community.libvirt)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
