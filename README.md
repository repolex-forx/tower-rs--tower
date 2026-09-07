# Repolex Knowledge Graph of tower-rs/tower

RDF knowledge graph data for [tower-rs/tower](https://github.com/tower-rs/tower), parsed by [repolex](https://repolex.ai).

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
lexq download tower-rs/tower
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 4b0a6b0e688bd177eb2c9c97f5268dd9703c66fc
│   │   │   └── chunk-001.nq.gz
│   │   └── b57517521098423ea1068a8f08d76906ef8a6d11
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── b57517521098423ea1068a8f08d76906ef8a6d11.nq.gz
│   └── repolex
│       └── b57517521098423ea1068a8f08d76906ef8a6d11
│           └── chunk-001.nq.gz
└── blob
    ├── 0062fe39882d98d1036721c71800f0f96fefbcfc.nq.gz
    ├── 00b3311c28d37ef87372f5a8fb602b8de16c9f84.nq.gz
    ├── 01d8f248aae41be8cb2ae14d83302c4d8f5ed434.nq.gz
    ├── 03b8313233d17e60c8d2b94edc5687c3bb0922f6.nq.gz
    ├── 04d9505b0ef493abca76e28b4fe959302caf18b5.nq.gz
    ├── 0803b17c6356ebad1943bf085e6b9ef2b7bb30fe.nq.gz
    ├── 08115f49289446d0ab44f89af50d882da939f85b.nq.gz
    ├── 0a9f6b68a32e0903e57a1d7e7722775c628dfb15.nq.gz
    ├── 0b056d21eb10d59e43ca7c0a81b29d6c3d7c1582.nq.gz
    ├── 0b0e7fdff39b82eb2ae4162a250a81ce8b2b90c5.nq.gz
    ├── 0c6e73554d100e8c3733518df35a4171e8ddb40a.nq.gz
    ├── 0cac72d1b3293bb43e154ba12cb0ac4cbfd373a4.nq.gz
    ├── 0cf4186573f711bd4c720ac07b22cf0ac9cba395.nq.gz
    ├── 0e2e237076bfcd6d564c1cd367cacdd36374380f.nq.gz
    ├── 0f0f7d8375ebf75f3653c973303ccfd7aabf4d2d.nq.gz
    ├── 1170fd43999a1d293759698a62f66df2584d767a.nq.gz
    ├── 1209fd2ef0294ed9a5fcdf8fba010ff23d9e153e.nq.gz
    ├── 1222240a520b8e7bf4f9632cdea3e84551f686db.nq.gz
    ├── 12744547dc7c4c349545463692d20763e5eea677.nq.gz
    ├── 14b973abea086c0543b934795a9987764c2d0de0.nq.gz
    ├── 17cfef834ef6d77df1a182f77a935bde71919eab.nq.gz
    ├── 181bc96558027ed72aa8a66054170011aea1b255.nq.gz
    ├── 185fa8368d536ef3d4d504458c61e792e5063e93.nq.gz
    ├── 18a30f1808aaf590753da90dbd7c9600c04e5e10.nq.gz
    ├── 18b7813fff24252e7c52b8d34cdaea3c8144ce87.nq.gz
    ├── 19df4f5ccc3f69ce6e2d10cdc8311440d5299b1f.nq.gz
    ├── 1a5d51e3c977c0a611526cbc243b8ddbff113368.nq.gz
    ├── 1a8806acac1c516a8aa83cb4d76efd7b480e1b49.nq.gz
    ├── 1a8cb2b4e97708da735275a590aaa05352088534.nq.gz
    ├── 1aa198f9d3dad27c3885b9da1c37428d52fee13a.nq.gz
    ├── 1b936acbcddaf38ff17dcfbb31033cfe478ecb24.nq.gz
    ├── 1bb5e29ed1ebaf05234d70322907bd5019f01a0b.nq.gz
    ├── 1ca7a54bff62dbddd91c74f87a78a07cc58ae6df.nq.gz
    ├── 1ceb355e1f60cbdf5742b3028b8d4da25d162ab9.nq.gz
    ├── 1dd43b54de44760a3e2e620744fd8632e505d189.nq.gz
    ├── 1f35efd04d00b4813f46a775675c942f6a1c51b2.nq.gz
    ├── 1f6268995dd39821a4b735b2a0740e66a6e1a316.nq.gz
    ├── 2138623bdc80062ca2bfeb38e86fe508afa1599e.nq.gz
    ├── 22ca1e2de767068a4e79535175cfe3953d2e2572.nq.gz
    ├── 22eca35354bd33b59d9607684cb9f40a5b236e84.nq.gz
    ├── 2370860a73deeb93566131379523c18897bee4da.nq.gz
    ├── 23765fc26934d529fc97c8ff78faf093167c5637.nq.gz
    ├── 240649eb3f77eab55d019c3c40ddf28928b58dbe.nq.gz
    ├── 240ed6f06abda94d78aeb56e3ca4443161fc377a.nq.gz
    ├── 24499d71b04f2da5bfdf36cb0f839b863fe00388.nq.gz
    ├── 2481166c6a6438fcc6ebbd70c34ce058509e6cfa.nq.gz
    ├── 25356d11315ab064fa9a0a53dd82f3582330259b.nq.gz
    ├── 2717c54e9aa6439afcbb25c06fe8c9174a24385d.nq.gz
    ├── 279a82627547f8b37f0206ea27e170ebff278aa9.nq.gz
    ├── 27d8fc305d36034aff24391207cb1aac274d84cf.nq.gz
    ├── 2836d4268da36ad4932f30cc2c7756f393fd8a38.nq.gz
    ├── 29243173182e0f8e6ed575ff1083f814ae61b497.nq.gz
    ├── 2a0c80e4e8af2e694a7dddc9a113421cb0722131.nq.gz
    ├── 2bd29131e0deb005ab441a2781a2c7dc4aee0cec.nq.gz
    ├── 2c0006f1d2d1149691b62ddd27ebb5f1380ee7a2.nq.gz
    ├── 2c78a622044b0b6cb55b3f147aa51791ee718c94.nq.gz
    ├── 2d8833692e3434f533900e2ae8cd637995eaf13e.nq.gz
    ├── 2ddbb35b9ec950676530da16cc2639c1fa219b73.nq.gz
    ├── 30257c457ee15667bc76b5445bc7f45ab2c501f1.nq.gz
    ├── 3038932f5b12036c51e2bfe32c8545c5b6922823.nq.gz
    ├── 30440f6d1deb53048e79dce3cc688194f8a0f783.nq.gz
    ├── 30b505e65bb1a61e0491ce097885f7f751f21335.nq.gz
    ├── 30cbcdeca7a97945e54388f18715f50948e3547b.nq.gz
    ├── 31a9655e70f75e31c97d84542277d8a279b68b2f.nq.gz
    ├── 32d23132c695b4275589a963e904bcf94d0db324.nq.gz
    ├── 331c495f2492c6aa0f8416ac7589ed1552a2c3d3.nq.gz
    ├── 33415701080a622f8d2848f64f75a15dc4268d48.nq.gz
    ├── 3469057997318ce0bcb828da4473736700f9b0be.nq.gz
    ├── 34d2e585f7eaf346e5e3afa9fc061fdd58fd9060.nq.gz
    ├── 34e65fa43af6c86216f1017a65fbd450b2e7deaf.nq.gz
    ├── 35cec96b16e4235708fbb2c916a840473d8d6390.nq.gz
    ├── 35d099962f7040651b2fd0eac4b84a9684c38c3b.nq.gz
    ├── 3605090489b7c8341de58681076c8d30572e57e3.nq.gz
    ├── 362ff4fa10a5621862a0527484fa40e4ebda015d.nq.gz
    ├── 363bdd57c8537cd86c9015cfefed60d294f01058.nq.gz
    ├── 36a8057d62e62a87e2b171fc2164b9f564730bb7.nq.gz
    ├── 36f1352783d949d9ec23c414d50efc246ae8c420.nq.gz
    ├── 371950309fc700f84ccda8203a0371ab4955a9a2.nq.gz
    ├── 371abb4d766e8e506d033f09ff4431afb062f7b0.nq.gz
    ├── 3876abcde7195485c4a7de8db040f613c22cec34.nq.gz
    ├── 392365781878b12234acb80a4fe20bad4f2b6beb.nq.gz
    ├── 3a2f0fbffb6aa1f2227fca660351fcce9835838c.nq.gz
    ├── 3a5a5abfc4f8564ea566168f3e6bab2ae3d4e5a9.nq.gz
    ├── 3b3bfbde68034a8d7790cf234002c605a0244396.nq.gz
    ├── 3b52e5d1b2053314beccfaac4edd40b121e16f8e.nq.gz
    ├── 3bb12aaec770ab23ebed2b44269fe7c0c9c85647.nq.gz
    ├── 3c295b96184916607829162be0cad1e8461b34f4.nq.gz
    ├── 3c40c6e8114bd790b82c51d34cacfac27467420f.nq.gz
    ├── 3cb2d6333e3a380c5323abdf8f7abfd3d4048991.nq.gz
    ├── 3d5573870f90ac7242df24335c8e93893e36c245.nq.gz
    ├── 3d5990f9f025208af0d2942ea2b269487f3142e8.nq.gz
    ├── 3de94c2affb3305cd60f132f35b965274ea68bde.nq.gz
    ├── 3fb9159c6ac104fc51857d98a855fd62ad970028.nq.gz
    ├── 401f80c2037f18f56b756cd1cd237c3d074b2fd5.nq.gz
    ├── 40554ebd27045eb0ccba542ebd0617329ba4a2ba.nq.gz
    ├── 406565cfcc25bf772d6adaf701697c1d2e2e5bab.nq.gz
    ├── 41b90c1b7cbb1e66d0ed690024d475ede9e0f3e0.nq.gz
    ├── 422f308809a0f352f4e84994baa956750c6f749e.nq.gz
    ├── 433d67f1b6ce02da5c373b9b2814d85e40506b1d.nq.gz
    ├── 444af14e9bfa69e6fe8e0ca4ef49aaa5433afe0f.nq.gz
    ├── 46efb148d4c556a17a1977933260fbee6fcfbac5.nq.gz
    ├── 47b24cabbcced25dbda5fa846db9121f1bbbd88d.nq.gz
    ├── 48fd6e69f9319c546e873b5249d16226b4208154.nq.gz
    ├── 49908f17f95a9a94b72ae163821a3cc929e92d29.nq.gz
    ├── 49b9fc62504cd1623863866fb4aaaf14dc7cb28c.nq.gz
    ├── 49fc04aed25f708fbc76f0f4de3c9a14ffc96c9c.nq.gz
    ├── 4b07a15933d646d3280b2220430b8117e53b9a77.nq.gz
    ├── 4d0207093b15696bfb747466d4fa65f7f00cc9f5.nq.gz
    ├── 4d47630c012bfa0e390403bb10883572cc211ec0.nq.gz
    ├── 4df56d73441e8190c92e433971ae6cf7f6cd5d00.nq.gz
    ├── 4e0eed942abb62e9988e04b5102a535b82b0830c.nq.gz
    ├── 4eb60cc3915d795aa8789d4c00fbf30e38834e86.nq.gz
    ├── 5028d85c702c84fb17f463f4b55a1edf34a418d0.nq.gz
    ├── 50c441164ac5cf02e29579021a46799f4ae54619.nq.gz
    ├── 51f7e7d2732134e41cbf15766cbd4a94980c16f1.nq.gz
    ├── 52b179b8c00cb7dceabc9dfba3f9e2465555a68d.nq.gz
    ├── 533cf41c91c475c534cc90e4145ab37123d891f8.nq.gz
    ├── 54120e7243bb007682c8c5e788369e0e7baa75ab.nq.gz
    ├── 54633ad36cf65dafbf1367210a627a38d46c25ff.nq.gz
    ├── 5585db79698010c7eb82b23bd6a53ceb0be7d02e.nq.gz
    ├── 55bf96d07d19200928ae5715c0d07120659c3a3d.nq.gz
    ├── 55fcc72ce74a2fe24403992b7291a4312f4c224d.nq.gz
    ├── 5657c53a8916e4060c951146a3c0636da427c8a7.nq.gz
    ├── 5977f9685d663a0af28c8ce990143ecd693f44aa.nq.gz
    ├── 5a96af2d17fe0cb2dad4054e1987dc62d96bd632.nq.gz
    ├── 5daaf8a24771209393a94a3bfb473cc803ffead1.nq.gz
    ├── 5e93450677113ded9dd16b040e035f7d75a293e1.nq.gz
    ├── 5f863f83c7ef9bd61aba1d470352a2ab0d35c5e0.nq.gz
    ├── 5f8d31aafe0d811d2bc9886a050dc88f3059f303.nq.gz
    ├── 5fb9faf0d011c4a174a296b5745a6c2b9650dc80.nq.gz
    ├── 61ea092eb42826798ce462c06901911bcd8a9530.nq.gz
    ├── 62a781aa25f8200c78bac9e1a1f82d1d6f6b69c7.nq.gz
    ├── 62f2de3cbd5117360139b43687b4abef90826b8a.nq.gz
    ├── 63ac8c9f6ccbc0f802b13bbf35860eb79f298694.nq.gz
    ├── 643e16c3a3a1df282846161010399f03e2a062e9.nq.gz
    ├── 6506e9542cc087c22b2d7809d09a22a68d5ced95.nq.gz
    ├── 65585da92bc1bc3ecfc90f142b0873a4413950e6.nq.gz
    ├── 66538ecac2d6d192f8ab18a814b8e9c16150fd52.nq.gz
    ├── 66643dd537041caefae8face2043c07491dde850.nq.gz
    ├── 66736deaa583ebf6b3bd551e92d3fbfde9c3ad18.nq.gz
    ├── 6720c994e09a90c98f2301c8d9339248d2772662.nq.gz
    ├── 676058d1d2caf6571d6bb60438ce06a7453074b0.nq.gz
    ├── 6803d32e36a1921b37e8e3e6d2901b774cb1199a.nq.gz
    ├── 683bd609c8db00d99ae6069f8b55561369810b84.nq.gz
    ├── 68b1f4442f6c814cfccd8be26e03381e31faa59b.nq.gz
    ├── 68ecd810ca2c5c476aca8b484cc78ef9d851d57d.nq.gz
    ├── 6a10dcaedca1bbcedbe2a0b03d10e2a6a7eae104.nq.gz
    ├── 6a2032c04cc783e2aa4761a9c2076ee4ef750785.nq.gz
    ├── 6a82d11166f4bcd38f64c0415ee0d0a164ca5f1c.nq.gz
    ├── 6a8f46a4404461554ebdf5beb1a4a85999878c4e.nq.gz
    ├── 6c51f30b70136c1ced2b8a297e1906974eb2fa0b.nq.gz
    ├── 6d06991e785c0c14e7abf058cb4f47c03daaa3a8.nq.gz
    ├── 6d13aa12b5cdaf5ddc11f823b65924a5ac7ee05c.nq.gz
    ├── 6d9fa72161443413301fe32fa286cd178a6088cd.nq.gz
    ├── 6e6f859dcf65075ca8a74d6c2b228afee70d03ba.nq.gz
    ├── 6f4c16ddaff47b26222e67f224b3657a6e5e904f.nq.gz
    ├── 6f6e809bc2b1af53fbb15571220e8ff771a4ad3e.nq.gz
    ├── 6fa4a41e8be0f00c066c6dd6c9a681a493dfb1f1.nq.gz
    ├── 6fb8ecd75c7d48c11069f5a571c31e278c3ba9ea.nq.gz
    ├── 71c48cc87a6901cfc124eef9c5e7f1f31cc51dd0.nq.gz
    ├── 72238353c4432f762346eef66b0538a261e38a27.nq.gz
    ├── 722e3dd6d871781c8feca60d4085777d9f0446bc.nq.gz
    ├── 72804d02a12ed524724730780d073cbfd5283e98.nq.gz
    ├── 72af1aedc0e112e6fc23d17314924f9e9088a779.nq.gz
    ├── 7507fb50e068acffcdd6d3ab684bec6089f07fb6.nq.gz
    ├── 76115617a1446b700d14371fcf0ff8f6319aca9b.nq.gz
    ├── 78061335817217288c478919dfa43aef0383fdd0.nq.gz
    ├── 7896e9e3991a32e5c91f485358bae506c51c2a6d.nq.gz
    ├── 7a072fbda3e74a6a420f11f9e329df8ac3487b6a.nq.gz
    ├── 7ab00f7b4b833ea184e8e6a613e82f2eb2ab3687.nq.gz
    ├── 7ae14bf1832feaf4903817f66800afcf2325a144.nq.gz
    ├── 7b4fc9c0eefca49e3cfa6867b492a4dece126e8a.nq.gz
    ├── 7b698aa9396325343f8f85e013ef81013fa3639d.nq.gz
    ├── 7c7b9605e113bf4dc5d2973d3fd0b89c6a21d7ff.nq.gz
    ├── 7da5d63cba631748d20f2300e453b1a9dc28fb3b.nq.gz
    ├── 7e279783f8988f17db9d594a7ebe123ddee7a3c8.nq.gz
    ├── 7e3bb8506c3b76defd606c34d897dee18faae903.nq.gz
    ├── 7f19480f2e888cbcbb1d29b7e8641aa427538fb2.nq.gz
    ├── 8027d988c98a4fbfd7c5bfcd1dcb4558fd6c085b.nq.gz
    ├── 84f18152676fe004ae2d72be17954f9667093800.nq.gz
    ├── 8604de66c868328ad7ba5e1ef0fe87979b6d9004.nq.gz
    ├── 872df028a6c97f3475345e81174c2a15bcdcbf4e.nq.gz
    ├── 87cf6c8ff7773c9e884c285e79767d2b5a02cabf.nq.gz
    ├── 87f371b4e2f7b6647722ef656986752a78316b37.nq.gz
    ├── 8855937741b7ce96b2938b356962a2ac8fdca936.nq.gz
    ├── 8925e41b812486e40a90d411ffdc23dfb876440a.nq.gz
    ├── 8aa27ee62d21e9e58b77847b1ee3b5c82bf436db.nq.gz
    ├── 8af6624d6bdf75d0f19bff7847cb163fab10d4e4.nq.gz
    ├── 8c5d4661de8cfe9300f9728dd74714128e27740f.nq.gz
    ├── 8eb226b42d6a35f39e896124407ba93f2010c74b.nq.gz
    ├── 8edac10aaf05b395681d3f7338fb728a5756b401.nq.gz
    ├── 91f0b609e2bcd1214b2a22b3af50a32fb0a3a2b6.nq.gz
    ├── 923b4420f0c9f53e867b3c67519d275499f55587.nq.gz
    ├── 925b27fd08c70624f10038e755b87f59b8749ebd.nq.gz
    ├── 9306f239565f904c3f9b8ac78446f79bd087f7d8.nq.gz
    └── 93951889496dfd1ecb2f7c5a426611dab1a7baa4.nq.gz

9 directories, 200 files
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

[tower-rs/tower](https://github.com/tower-rs/tower)

---
*Parsed on 2026-09-07 by [repolex](https://repolex.ai)*
