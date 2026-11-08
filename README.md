# Repolex Knowledge Graph of PrefectHQ/marvin

RDF knowledge graph data for [PrefectHQ/marvin](https://github.com/PrefectHQ/marvin), parsed by [repolex](https://repolex.ai).

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
rlex download PrefectHQ/marvin
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── be92af1d777c2bddf6b06a18b8afef62b3a2a844
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── be92af1d777c2bddf6b06a18b8afef62b3a2a844
│           └── chunk-001.nq.gz
└── blob
    ├── 00199e9080aff7e66e332336ecc9f2ddfd1f2f00.nq.gz
    ├── 005c1426aa2aeef9c5a9624ba06f5f1930be382d.nq.gz
    ├── 0378ad9fb361743c270e17677b6dde571d545225.nq.gz
    ├── 03ded97d15b65bf19445f077ef3ad88dfc26a50c.nq.gz
    ├── 041e5780399917c469f7d096c90fcd10a8173b77.nq.gz
    ├── 0452dd14be294ffa166e7df827c5ee774cc47788.nq.gz
    ├── 059685ec78b3e07d0b2762c7b102faebf816d32f.nq.gz
    ├── 05a633ab350769f50c4f3eead81dca280148c8d7.nq.gz
    ├── 064e70554c298b5ec6df1cd61bb5267b4b8cabfd.nq.gz
    ├── 06588d81efb5f06a3fede3f7c24d2c1f1c17ada5.nq.gz
    ├── 06b6a6166db7df81af365d67ae62a304e45c2f39.nq.gz
    ├── 091d7d61bb7e666d3994b41bfbe176e44a810438.nq.gz
    ├── 0920d656748f2dcb9933b8342d580fde6d0e3abb.nq.gz
    ├── 09210918ddd4bc94ac0d0b4032e9faefe50be9d9.nq.gz
    ├── 094078f6938ebafa2470032ad06e811403ac126a.nq.gz
    ├── 094f4300f6f581857242e95a4cc6bcffec227f5e.nq.gz
    ├── 0a6caee9cd372a9683751ce7d7743158b4b151fa.nq.gz
    ├── 0aa33bce32eb279f3e52e02a84ff60313d29938c.nq.gz
    ├── 0aea3bcff6e0cc4239661e6ad06a15341fc5878f.nq.gz
    ├── 0caef4c17e2e03eb72a405d95f9d5cc026d6ade6.nq.gz
    ├── 0d5ac9925aee0e2f8bc01a8068982152626bfd5c.nq.gz
    ├── 0d9f3926a38daa28d636c97ed0bad16911d6cde0.nq.gz
    ├── 0e5ca3ed79f8f6a72577b7f594a148faf0898535.nq.gz
    ├── 0ee9b9981ba42c476a874ac45c2117ac43b62591.nq.gz
    ├── 0f13b4c0acb875092ccb748e3961fb7829df5897.nq.gz
    ├── 0f2a8ea7721d39211456d703e17e4fc8382e5a72.nq.gz
    ├── 0fc79a508d10f5db91acf6ed19817bc34ca139b0.nq.gz
    ├── 0fed36d55603f844ecf6239589725dcc5a004aff.nq.gz
    ├── 103311326f34a11eaf2aa3bee44156fea28dceac.nq.gz
    ├── 10d0d26a74a72233045a9124434cb3a90ea5f574.nq.gz
    ├── 11016cc86d3dba04285bef90a7b59f5cdd18f07c.nq.gz
    ├── 11e36da0f906e39313f98f415165d04dec8d057d.nq.gz
    ├── 1229c1bd8341298f3f90548f5f9aa865e659b86f.nq.gz
    ├── 12ab0ab4ee4ef7f883ac967094988aaf746ea367.nq.gz
    ├── 13ca957dc0290cdae6e489aeb5e3f4186e772d16.nq.gz
    ├── 14037cd4f5edb18fe7ae63ce54e5e7d411748c93.nq.gz
    ├── 161a0ff0074e15528044512e83119c05a76b1c22.nq.gz
    ├── 1631ba6b90650d08b257d8c5ccfaf68d81d82320.nq.gz
    ├── 169dafe7b19095255a3cbddc76ccc5a0174895aa.nq.gz
    ├── 16f858bf2a325324daa3315472fb9854d6f66bd3.nq.gz
    ├── 170b807c763eb9f95c06e4b9fb0938621a2ffd5a.nq.gz
    ├── 1729fd53c4e7b736a80d0c0c3ce9202e4fce5c90.nq.gz
    ├── 17d08c42ca3441f20bd0b6cdfdac0b523ccef403.nq.gz
    ├── 19e482940c6d026533ae977eb593f4bdf4cae9b5.nq.gz
    ├── 1a0ecc9ac2e9bee80418c48bd2c60e8fe554553c.nq.gz
    ├── 1bf5c7234f737259aeaa0c0fc4878fc47d58152b.nq.gz
    ├── 1ceb687811e1f065c36863042a9cd805683d55c4.nq.gz
    ├── 1ddb14204b20c1043f32e38a1837317ff15cb134.nq.gz
    ├── 1e07f119b9b567e9dea07ac3836c361f33863b4f.nq.gz
    ├── 1f94a9d697cbd6d3fc54641ff88c5f60aa9940f0.nq.gz
    ├── 1fc5b5632b44b83edf01b449ae953c5d7207f161.nq.gz
    ├── 2041f971a7230db0dfd995807e6a68b70ea52d01.nq.gz
    ├── 213967b89d5a43aeb40ca19c72954eed1432a04a.nq.gz
    ├── 21b764bc0902f05536317d46027c890a9dffbc16.nq.gz
    ├── 21e4e71893abdc05f51ac974690cb116e1cd0ca6.nq.gz
    ├── 2224ccc730f6b2772a20ac9207e94d2f5059d15c.nq.gz
    ├── 233d7713c2c33c281646c7fbee170a3c6528d095.nq.gz
    ├── 23e895af6043a4f4cd5f4e70c92372a14a14db56.nq.gz
    ├── 251a6da2695fb2e047679f2f94ed28738ab15f37.nq.gz
    ├── 259327f0d746daa0c60eb7066b90df32fbba9648.nq.gz
    ├── 25a9909e6c931737a0eaf085a700c320f4be2b50.nq.gz
    ├── 26d2d1d7e676b62065a766c12c8243270d1d18a1.nq.gz
    ├── 28a9fa7b1d2ae2960b3cd5595ae2a9085ad5ab1c.nq.gz
    ├── 291ca71ab9071216c1f81de615d3ab92fb04d031.nq.gz
    ├── 2969d2179f3db9c8b047b0f526fb852bf85c8259.nq.gz
    ├── 29d6ca780db19921a97465edde5d6fa6439a9df3.nq.gz
    ├── 2b483cf32dbb6069b9ebad71950d856f4d24e24c.nq.gz
    ├── 2c3ddc609a6db4af19e53b5108f13ab761247857.nq.gz
    ├── 2c5e73ea2a91c6dd4bdfcdb1e461f7db294aba7b.nq.gz
    ├── 2ce5a853fc29ca2fdfc2485f42a182dc3fbbb6dc.nq.gz
    ├── 2dc68ad9d987359ebc5a28ec57cda3ac0be944ba.nq.gz
    ├── 2ddafa6cfc0a02a99e0979779dd4d2e5c7118f79.nq.gz
    ├── 2dfc9be7e97f0e8b48b64047d693a879151be042.nq.gz
    ├── 2e4d0214e4a0d8efaa45ff505330466f60d793f7.nq.gz
    ├── 2f6c356f852d45cc11c7da4a1e4297ba7e27a7c4.nq.gz
    ├── 2f93f020e7c69074fa3fa08d97db1bea7e6a00e9.nq.gz
    ├── 301bb51f5feba44905d2a810226018203181d617.nq.gz
    ├── 303645486781ab6671606096e4d2e9655ab165d7.nq.gz
    ├── 30ac42604cfe666ec36dad84c03faf360172163d.nq.gz
    ├── 32201451500698effd04e8fe66620382941cced5.nq.gz
    ├── 326c249d85a8ee04a9c9420c56d6dbef96a97d08.nq.gz
    ├── 32eb2588e5399542ddec52f0cf8227542eceb4f1.nq.gz
    ├── 343de47647f84fda05c697002bf67c2973c060f4.nq.gz
    ├── 345e1e39f64838d1f69b7aa75ae64a0adcb85465.nq.gz
    ├── 3800fce642392a1d8f18b38d1717f25cd18c06ed.nq.gz
    ├── 386358b26427511b197ec268882d218c6f8c949b.nq.gz
    ├── 39701e87a92c386150d086fce24fb353445d0d23.nq.gz
    ├── 39b1dd86e6fd5da184e77f6b10f125ad71a90539.nq.gz
    ├── 3a1cfbb89a4646f5cd865842bae3deef376b5503.nq.gz
    ├── 3b3346992970dc6b538545f531def25ae7b5de90.nq.gz
    ├── 3b5824efba2be6b1cacadc5e76eb75a4481d8ecd.nq.gz
    ├── 3c54a33874896c586139a798332ebf7faa04a648.nq.gz
    ├── 3d98ff37239cec95117c6dfdc74a5e5ffb3f1ba6.nq.gz
    ├── 3da3623c2d9e32e23b6831d60b36654cbb7585e8.nq.gz
    ├── 3ed2f95965d3823869f567e50dc05c05eb8d42f6.nq.gz
    ├── 406c61906fec3493f8e0d60fcad4a8db7db0d085.nq.gz
    ├── 40a24c08d0b919871f954b8380958b60994525e6.nq.gz
    ├── 41a43bc56a686c9115a158012d80984519ccb342.nq.gz
    ├── 41c2e728ff96fda23936a8956bfdf97ffd63bb81.nq.gz
    ├── 426c2c09077e5fa98e30451223b7967c27e01fac.nq.gz
    ├── 4328e668121fe77b70b30bb6b15bd02799704e99.nq.gz
    ├── 44ca2f2b2a1b49e68f68b062c764377925b0f9e9.nq.gz
    ├── 457329453e72a9cf8f9423dba3023902d158d1e7.nq.gz
    ├── 45a4e333f710673ad9f293c110008090523cf196.nq.gz
    ├── 472b159dd5caeb87f6a34e2ea9af2d15d202e286.nq.gz
    ├── 472f5fd89f04d9ab687fbf55af0a5e141d60db54.nq.gz
    ├── 47e362b9a013168059ebde40d18df5ceb66333ce.nq.gz
    ├── 494b21f38448e6b3358c7a3b60eba9388fc554bf.nq.gz
    ├── 49e6622ba81bf2e111d6eac74b9371967832ddb0.nq.gz
    ├── 49f419fcb1b14358c2a017c715cdd479a52d07fc.nq.gz
    ├── 4b13723975c51e4edb054ab4e23117dcd360c3a5.nq.gz
    ├── 4ba792a85f175f1dbd99e0b896c1fae1122cb976.nq.gz
    ├── 4c9e709cde861ff629fa980f2818995359d08d00.nq.gz
    ├── 4e3d104a30f73ccfd16f6083c90992a7273b0a22.nq.gz
    ├── 4e863d251042abd14222265273dc19992f64a586.nq.gz
    ├── 4efe4cf727969ae30c0c7c2971f2fd0e54bf92b8.nq.gz
    ├── 4f4b035b2d0dc4c7d43085cee1bfd61788e1039d.nq.gz
    ├── 505bac52fa782c20aa40ddbdca966c51db1c5bc8.nq.gz
    ├── 50b5c7847297b54acc82a7f4d464618bae948797.nq.gz
    ├── 50f2d908dc9a157eb6eec8b1468ae2a99f3c11c6.nq.gz
    ├── 52474c6a6c9d6f827ccd027acbcd92816fe76ff0.nq.gz
    ├── 53aa5736df0af2107acf7bd22234ffc0a982569a.nq.gz
    ├── 5414f81abe18d921c338ed8ba2bd5142bd21e7b5.nq.gz
    ├── 55e306aad5116dd71acc3d3c211e2d22f7498c5a.nq.gz
    ├── 55fd18d1a846d04205f51f8d2c331bd2a7bc9b85.nq.gz
    ├── 57dce946e0dde6cb4df567664b92b89def42fbfd.nq.gz
    ├── 58ae54c09e2d8f04429b1c0d7d9e303500051b89.nq.gz
    ├── 5a1dbfe3942ad66b00e9f751c43c9929d905542a.nq.gz
    ├── 5a3de6b21ecbea1c3582547b05c78cc27dd7bbb2.nq.gz
    ├── 5a7273e0acc46f4a6c2aafb459c50cdd6dbe1774.nq.gz
    ├── 5aa42b53faa7d654534e4c8fd525301f7016154a.nq.gz
    ├── 5ac97edfffc9bc6556389a7eee96e768a4610161.nq.gz
    ├── 5aeaa3e71f87287da1b9b33a3363adc9e658d878.nq.gz
    ├── 5b11a053ea6d9b584f3d0ceec60697a4afc6caf9.nq.gz
    ├── 5b7020fa563664241bc1abd66652e7ad627d13c8.nq.gz
    ├── 5b8123f20ea29e4f7a70a050a06acc9d06fdada4.nq.gz
    ├── 5d58c0c3c6f441a94a99adc1d4fee3893089a79b.nq.gz
    ├── 5d7eaaff00fe50ae7e011f46a158c051bb1d47a2.nq.gz
    ├── 5e1bdeade04d1142eab1ee243578eac48a461aec.nq.gz
    ├── 5e995db37737d6faf57410e8a81f59832945ae74.nq.gz
    ├── 5ecabed7968e5466fd8f4086ce5cd5911019a5da.nq.gz
    ├── 5f073100a371dbc7120501bb0fe104b7d530f520.nq.gz
    ├── 5f5fc01f953db0a1561807e430dfce6253ad1a35.nq.gz
    ├── 61633e57e242501ae1a927f5906d68eb961bc86b.nq.gz
    ├── 6244a861259c9b8dd9cd23f0ac5753c5d2641177.nq.gz
    ├── 65d83dfa29a87449995872d28e8a00ea032ab980.nq.gz
    ├── 673c998e19b365023dde8149e83acb37f6473ee5.nq.gz
    ├── 6aa7ec15ce9a82fd35166d8bda785fd0076f5486.nq.gz
    ├── 6adc5effbc7c0bc9ff3934081d6f8545ac49e010.nq.gz
    ├── 6b9e72e085e27089323fa6e2eef1657bcac0f22e.nq.gz
    ├── 6be8a96a79190856219953ab692e895493374784.nq.gz
    ├── 6cf68e20009ebe49fc33343d5aaf05aa5ffd7606.nq.gz
    ├── 6d8b5bcc7e8438c802419075cdb16cb30023efd2.nq.gz
    ├── 6d9b054cfa4b74f3ec753e4c9e6d85a025f6cd10.nq.gz
    ├── 6da9eb79b5a590505e6be5789c36f4b957ecea7c.nq.gz
    ├── 6dafbb27344949e508654fc07972073b4964c1b3.nq.gz
    ├── 6e90311ef12103ab0fe4d9bdb398ae011d641386.nq.gz
    ├── 6e9f2e18b0ccd83d74f8bf276da2680d3f4cbdf7.nq.gz
    ├── 70913c5b5cb74af059e31745a22c25e63706a39c.nq.gz
    ├── 71ed12058c0cc8a7200a035846bb4f53feb93a49.nq.gz
    ├── 7504b51402150791e2acd65995621396d8545b35.nq.gz
    ├── 753777f4a3175eb2adbabfb00cff47b3eec7bdb5.nq.gz
    ├── 75c196d5f1d9402a8eb1241b1f8f8a2a296ba213.nq.gz
    ├── 7852fb8ffc791d03d5f6cc1e0ab6e288639c761d.nq.gz
    ├── 78cebe9930665f203efb082dad101ef860fdd388.nq.gz
    ├── 796d4eff1d5e9dd183eecebc770ec39a984aadef.nq.gz
    ├── 7a16b73d5d78ca4eb50d6a2c617237375433b268.nq.gz
    ├── 7a94f124d17cc8ab6cc5046db106259e372067d8.nq.gz
    ├── 7cf4f9d3eb241c7936e420593e7d854b0190d703.nq.gz
    ├── 7ea8a5572882458b594983258c7375ffbe8f7847.nq.gz
    ├── 7f9a8ae64103d729a734281222201fb424766436.nq.gz
    ├── 80729ea431b35b0befa54a5a64b9fc25ed5119c9.nq.gz
    ├── 80c51d740054c9022353a06ff6bc717c7474394b.nq.gz
    ├── 8152ea32927096587fdd75fd9d4f8c34c53e303d.nq.gz
    ├── 8156302615564c548fb2d9d593da92aa41497b16.nq.gz
    ├── 83470036120ecd331e28a218aaf61a84e37c9320.nq.gz
    ├── 83ef6d0ed4d017e6c7f5520127758677cf3a4586.nq.gz
    ├── 84026dcf061be99a88ecb923ee67b817d3ade9d7.nq.gz
    ├── 85eb167ed1df440eeb3015b9cdecafbb1ac24e10.nq.gz
    ├── 86bf10633b794a64cb434b9f72d6a1938355e657.nq.gz
    ├── 87d8659b35c4541f4678e871b2011082bf78066f.nq.gz
    ├── 885958989fba3d810bab288100ac072873d6f26a.nq.gz
    ├── 88f0e3b863877a8a174b68f9cdd01b787d809bf6.nq.gz
    ├── 89cfb65adc685073f217b03da10c24c42d24deee.nq.gz
    ├── 8aaf10aef4af6e265bbbf5e43e3b04017fdeb8db.nq.gz
    ├── 8b446eeb2293521e9a56f8d945990b70f7de7b95.nq.gz
    ├── 8b5bd7c0be1f8461f6d63b8a4afaa40c8019a6d0.nq.gz
    ├── 8b60735e0ea0db1f5fdaf9c9b824ff26639fb0f6.nq.gz
    ├── 8bc16a36153e1c1e2536e9e13b74ef179ecfc1b5.nq.gz
    ├── 8c01d7e38d43ae20b73534d52056727cf29d30a5.nq.gz
    ├── 8fdc3dde370d9c407133cf9dfd6018650118b9a0.nq.gz
    ├── 906dfb85239e943e8acd9072e7992bb9a12b5d5c.nq.gz
    ├── 92ac87a5cc0de92d7b4cbb5d864d2dc42ac0fc91.nq.gz
    ├── 93cc4185b9c7ad634b4cc7370b858115fe0789f6.nq.gz
    ├── 93dae458502cbadd10660a3a329a3a162daf7c43.nq.gz
    ├── 9528c64e6e315b4a57f2f768217a5fa24378ef27.nq.gz
    ├── 962a3b4ff18ad37e32b5baa0a6eb27529e4bca02.nq.gz
    └── 983b5f21497623c0cd946ae8196ce1ac1a848583.nq.gz

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

[PrefectHQ/marvin](https://github.com/PrefectHQ/marvin)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
