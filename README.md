# Repolex Knowledge Graph of hpcaitech/ColossalAI

RDF knowledge graph data for [hpcaitech/ColossalAI](https://github.com/hpcaitech/ColossalAI), parsed by [repolex](https://repolex.ai).

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
rlex download hpcaitech/ColossalAI
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 250c903c8212a65a8ae8c9af007ba08c7eff02b5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 250c903c8212a65a8ae8c9af007ba08c7eff02b5
│           └── chunk-001.nq.gz
└── blob
    ├── 000fce63f35f093ca638e79224e1152ebba0b841.nq.gz
    ├── 00455897ebb3cf9a64edcd23f0da339ded9210ea.nq.gz
    ├── 00721ca86ade2194269554c70b335092f6583adb.nq.gz
    ├── 00afcd775b0f0d7ff5b0da81d3044c4cf3d81df4.nq.gz
    ├── 0173f09644536b43128abca374b4b62e8a816460.nq.gz
    ├── 01e5cd217c5d9830551735c7d9e6d4087e038391.nq.gz
    ├── 0232cb90e677da6502e5f459483cac71881d07fe.nq.gz
    ├── 02ffadd9f6b091c2b0409d240026ac255c391ba1.nq.gz
    ├── 03679e66404a59983fc47ac541569d2b1247d3a7.nq.gz
    ├── 0369d9c0ab885f3e39151eb8803946393f20daa1.nq.gz
    ├── 03c8ac201049ece23f95fac25f28298330018cf3.nq.gz
    ├── 04a1296e60eb3f26d9316b4c65a51f54ce0de418.nq.gz
    ├── 050dc22b593584094f8f2baa5e5c1629ee0086b0.nq.gz
    ├── 054b709c92d02969c2aeb43ef1242cc911a489aa.nq.gz
    ├── 05dd24e8169e104a7f44c7060204ad6d7835bcaa.nq.gz
    ├── 06d57e4f05746e38ed96b30e7e4a619b285d827d.nq.gz
    ├── 0703a2a8cd7b5d064ac80ac5599e71c1dd2a3a85.nq.gz
    ├── 072ddbcfd2984a69c6fc056bd83e095418a5e1e0.nq.gz
    ├── 07f6cdb2d701e94e6856608f52d2c99920a5e85b.nq.gz
    ├── 080aa61e8e3a04128ff24d5f28f0231413b631f4.nq.gz
    ├── 0954e2be3eb1e28101ab032fb8b5dd74c915269e.nq.gz
    ├── 09c9b84a99075341a039de101edb298d34e128b7.nq.gz
    ├── 0b7c0eb746516adac2cb2a6119de3443be613a44.nq.gz
    ├── 0cb7968c81030782cfef8c94dbfeed84ba98fa0b.nq.gz
    ├── 0d94fe59f8aef275c4bae22a6ea29fa8ec0c1978.nq.gz
    ├── 0e6731db5a7763f82a9b124e2224c605ed3f4df8.nq.gz
    ├── 0ef75e13df9b762b1cc49a35b5c226740c820649.nq.gz
    ├── 0f2fbfa2ba440571bfd9f9ee7287fd470ddee3ff.nq.gz
    ├── 10239071fe1b387a7761939b94ca274b4d8cd67f.nq.gz
    ├── 107851b80d7c1a45744d0817dc36f18928eb1444.nq.gz
    ├── 110a42cf880e60c8364ac6371cc625e2fd00c73d.nq.gz
    ├── 11bd0c5954a28bfc3dd928b2364960f72d92d9a8.nq.gz
    ├── 11e204b504c5be370285bef9c5ea2a089e403376.nq.gz
    ├── 13f3281fbfb0c11e2c523cc7f61e02d39c20138b.nq.gz
    ├── 146dd267967d8b26c16d950245381c699e86c5ca.nq.gz
    ├── 14a8eabb42b1fb797230e0d11bf2b522cdfd781d.nq.gz
    ├── 152602774b52d9e195720dca39d45ad17b0dc6e1.nq.gz
    ├── 1539bc01d134c77727416b74f1b47e8f25c9cde4.nq.gz
    ├── 15a755b97c27df9cee3ea8d8d2cdc44f4514d939.nq.gz
    ├── 15cb2987489bf13183b8e6beb824768d94130c69.nq.gz
    ├── 168e554f93b18e792c27fdb4e040f4625d217035.nq.gz
    ├── 16fd385bad30c140eccd85a8f63eb05bc4f55564.nq.gz
    ├── 171d8876201f29568c2afab4b986bbae68c2f4c4.nq.gz
    ├── 1720aa58da2b0f2a36befa9c4270030194fb0c32.nq.gz
    ├── 1856a11100b07944d99d498e19f5cd8dda25d9d5.nq.gz
    ├── 1927159765ba1fbc4718ae431889ef25eab82738.nq.gz
    ├── 192aef7a4ba0388a817c8146b55c41311faa577a.nq.gz
    ├── 19c0e21d7c17637f4ad7956ce62e35f46328930d.nq.gz
    ├── 19d5265249cbe9ff6a06ff0adb4eb4ceb06f9aaf.nq.gz
    ├── 19dbaf5384de2a3ad96d372ad0598d78ec1df95b.nq.gz
    ├── 1a17c2d8740f16db283ea494a0e26993796c453e.nq.gz
    ├── 1b7c60e22861d2d519bab5debf032ef1f8477b47.nq.gz
    ├── 1c54dfe74f74abf03b3d6fbde0b90efb71ab2add.nq.gz
    ├── 1d362015fc8b8c8fcfbcf5985e459f1de0aaa5b9.nq.gz
    ├── 1d618a65f4919927d38e86cb005fe4e382c3b9f0.nq.gz
    ├── 1d691e5c8f976289d491a762f00ae55ce825ff38.nq.gz
    ├── 1dbc3ace85b659955bea6a9db5415ff8795fbf0f.nq.gz
    ├── 1e17c2bb584df4d03a915796ce441508f2a236d9.nq.gz
    ├── 1eb7dac2ea04b780971e8ad286cea7f4e76bd448.nq.gz
    ├── 1ee93e4e0d9fe2d6abfc192f8dbbd329b4aebe55.nq.gz
    ├── 1f8324a53ecbd3bb58f3fbbd72e286d6163c3530.nq.gz
    ├── 1fc7f613716b4cc895f10b61e9a5d0c91932a22e.nq.gz
    ├── 1ff2e330521c5b5ee41b7c5f9df98d20c4ef44d1.nq.gz
    ├── 200e282e7b2be9982ee2d772c5713995e61d9e3d.nq.gz
    ├── 202f3e3bf6f4aecdbe946f76af73fd0a498da974.nq.gz
    ├── 20f9ef31aae036743b52ba2f7f88771dc94e877b.nq.gz
    ├── 219c7ca416753fc2a531b3250b05d082a5a64e86.nq.gz
    ├── 21d769f3c49f9fe5cb5fc46d3c04157a105f152a.nq.gz
    ├── 21e5c5e7856bb76e607f43be4f91c4071518f03c.nq.gz
    ├── 220099f9ba32d06e90022a6eed569b0f1ab9a705.nq.gz
    ├── 22115a72c3e301e40b2b3c85720f5c29835dfc75.nq.gz
    ├── 235cefcbc6df6b24d261bb88431236c9a3e492b3.nq.gz
    ├── 23c0ccd811331dfc3115f97e563a821c6d35169b.nq.gz
    ├── 2426d8c32672cb01733fd10dc8901cf15bf0aa03.nq.gz
    ├── 25c5d4ef154ea89f43376d52c2230fb74c2de667.nq.gz
    ├── 2663076c6992555fac8273b597cb15bc6123fbf2.nq.gz
    ├── 26784f3a3411c5cf87b6dc239a00dd827a786b83.nq.gz
    ├── 271d55ae917a7dba977edd128424be9385839804.nq.gz
    ├── 27285f95ce52ca7d6e00eb38a2f100982411ed40.nq.gz
    ├── 277e75e6de5687f2f9fdef346e20dee7bfce93a6.nq.gz
    ├── 27afac9e95d3728368b16603134450d3ef31ae20.nq.gz
    ├── 27afe72c0db84f506aab3ba544e71937703b2a4c.nq.gz
    ├── 28ce72a18b31f347bb37267e5ec3d19f09f5977e.nq.gz
    ├── 2b4790884effd4dfe8781870fd2c4d58766a97fd.nq.gz
    ├── 2cbdb6e1b767dbcd8c88db09d98443f651c42d36.nq.gz
    ├── 2d7e4b05d217aa11a07cfb499d7860f59fe08a93.nq.gz
    ├── 2da9822dfc57be24a55d47e82ac7bb81976238fe.nq.gz
    ├── 2edca3b3e1c434c5e8d996a7b4503c81f78ce712.nq.gz
    ├── 2f638fa919e445ac4bc24c9b8904bfef27e608c5.nq.gz
    ├── 2feded7751ea0e451594789817acd0d731bdcc7e.nq.gz
    ├── 30063857ac30b5a66883215de9daea5311589a20.nq.gz
    ├── 33c6454ad92cbdb01b715bd11c0c4e3e8d0b7a2d.nq.gz
    ├── 33fb1ac5c5be779a5f65b44431e4ba84c878fab9.nq.gz
    ├── 34a7d2526fdad1fa1e3622d7b5f0a6bf419d9b50.nq.gz
    ├── 3776e0c6455263a9001546306cb496252701157b.nq.gz
    ├── 3782adaf718727afe588f207feff354ce44d7d71.nq.gz
    ├── 37e7bae419e89bc0cf9a8552aaa9187475f28d9d.nq.gz
    ├── 390eb9642907d99f8df30adfd73e6e9726b3f835.nq.gz
    ├── 3954b84ff1baa52477dd0aca33ef8fcdceb77c45.nq.gz
    ├── 3a1c2e57b4be605d2d3c5cae29cc9154b97fc6c5.nq.gz
    ├── 3a42e13645f6937c6a127b454868a5141a24eb0f.nq.gz
    ├── 3a782a6dd445bba4d8d6b392b4dc2bec5aa4a61a.nq.gz
    ├── 3aa09a95f3bc3337f151e9e35f9181258c1aa168.nq.gz
    ├── 3abe38968fec23cb64c045720b631f5520141f21.nq.gz
    ├── 3d91eb95b4097265f7e89e0598b6592b2da58848.nq.gz
    ├── 3e197ff96c0c0f718cc67effb9f27366b9b67c65.nq.gz
    ├── 3e94b7cfe993a5e9056f146adbdf92a7ef31a043.nq.gz
    ├── 3eefcb9dd5b38e2c1dc061052455dd97bcd51e6c.nq.gz
    ├── 409561b3a26b4a47a7d246319eb306c507afc29c.nq.gz
    ├── 40b4e368d384d4fdaec46acb8986b5fb4421fc8b.nq.gz
    ├── 412b14c7b28337e3ab0129714b808b0fee28d687.nq.gz
    ├── 420ea286fd0a1baed91992a65f01890e3386efd5.nq.gz
    ├── 42178b7b786e95493893a6464aedba7b10e9b34e.nq.gz
    ├── 427035d4e88b418386cb9eb97195a05962316693.nq.gz
    ├── 42b43bbc06f4b67a76972d00b14e6b7fe39831d2.nq.gz
    ├── 437713eb0b3dd7d85dd14e30b3e727ea3daab347.nq.gz
    ├── 43ccdc430ef1b8c674d39cec9e14f96bb0a967bc.nq.gz
    ├── 445b7e4cda2a6805c62cb5b3dd7e9875e5b8c73a.nq.gz
    ├── 448a3f031a29080e12a91a31347b5112e8ff4c56.nq.gz
    ├── 44d821a87fee894b9e07ca500cb64c1419f43a21.nq.gz
    ├── 44d859e48b1704bace74100b268b65f954ae2f2f.nq.gz
    ├── 44fa3678d621c3103ebf22413fdd98188c67d183.nq.gz
    ├── 450586d02f8f294730412be0ba0718b0146421bf.nq.gz
    ├── 4525dff3fe80d0a2445fee8354f511d2ba4a751c.nq.gz
    ├── 45aae2ea9d42dc53df907b547bfbf410c41c3769.nq.gz
    ├── 45b1056fdd5e3594f0fe9cbc3a0f673aa62f1893.nq.gz
    ├── 463a0704d0b73aa41550441747d3b6dfe40ab4de.nq.gz
    ├── 466914cc0d4d00c6e276f06af6ff720761d91e8d.nq.gz
    ├── 46d4222c4ac279ba4a8ff50539e42fdfd8480ab0.nq.gz
    ├── 471c23516e9a677733365371ced1263a07e3e571.nq.gz
    ├── 4735df7178822f0f8e920fe5e3d20aaefe0cda1a.nq.gz
    ├── 474fd4a2cb9c12655d9cd9f504103f1539732124.nq.gz
    ├── 47dfc8595e7436c1579481e84a32dd59e1b4b23a.nq.gz
    ├── 481efe98ac12e13c3d28f7386c494ce319bc9650.nq.gz
    ├── 48327e014adfa53dfe17a34afb21e61461a8705e.nq.gz
    ├── 4851f1b85817e23a679b8469395f499ac1b442bf.nq.gz
    ├── 48526b32bb3f2e9ff96bdd50d38c9745d0f7464e.nq.gz
    ├── 4a0f505826f13b46987ea1e0745c56c4c2c71448.nq.gz
    ├── 4a48f4c0ed3e8c91d43885fa0696f3f6bf5c5a0e.nq.gz
    ├── 4a50a78f2dbc5728f236f57d873ce7691d6445da.nq.gz
    ├── 4a840fea69ea280b43c451e033b131993fffd857.nq.gz
    ├── 4b297e6ff4fe0d34ce658c9b1e62003cc0ffc4bb.nq.gz
    ├── 4b6eea24d6ea49d06fe3aa222afc13db98f8d38a.nq.gz
    ├── 4babf7bc8a8e06135eaee0f351fd0ae48b13c3e7.nq.gz
    ├── 4d08d9941133b4521bdb895ca9eec98aabbb1d08.nq.gz
    ├── 4dbce7e09f379c1450c07ded7130686d2a94823f.nq.gz
    ├── 4e78b228eb4f56797bb1d861378d76ed5ca24fa7.nq.gz
    ├── 4e978542569a459fed8b5402f89efebe8e0fd35d.nq.gz
    ├── 4f3fe94f6b31354c1548edab32926c58d4b44098.nq.gz
    ├── 4fab5f7f05eb3ea4dcfeeb49a48ae8230acef97e.nq.gz
    ├── 5038714f754b8a39b859d935ecc3c5cfd4733834.nq.gz
    ├── 503981409ccaced2b6371b78c9a8e9bf77e41c06.nq.gz
    ├── 50742b850b24e13d19a044902a1e813d5063acf4.nq.gz
    ├── 5106d97cf4bc7441a2f7140f09d52d7c460d0357.nq.gz
    ├── 511873bde6862d953982a8e1150457adc891122e.nq.gz
    ├── 526e0f63221e18c1e5b835348b8f961b94016ae1.nq.gz
    ├── 534035cb5abf54fe33cb4361d2fb58fac2c7637d.nq.gz
    ├── 5361fe9a3bad098ef2fc89ff0a6a9ae15d649089.nq.gz
    ├── 5495282bcf22e27208600c7a2fcffa1cc7fe382b.nq.gz
    ├── 55303a164c89028b351a2c4071fe27d539ccf7ea.nq.gz
    ├── 56da2a9542255213e3772392b53a1acb98ae68d3.nq.gz
    ├── 56dd431f1e603fb9209d9ed4f95a3065bcd2ecef.nq.gz
    ├── 56fafa58b3f43decb7699b93048b8b87e0f695aa.nq.gz
    ├── 57076063cb3f8ece04dccbe7a9dd3579679f0b85.nq.gz
    ├── 588357d6b4bf7327079e5e443d1b5b77a0843b9a.nq.gz
    ├── 58941a5918ff30c8bcbc3a668a16c3a8ca61c197.nq.gz
    ├── 58a4811d9fdca28576e06437ee9c39a5cb6a4611.nq.gz
    ├── 58c9889ad98e24f5f163107f5095c07c8bf7f3a7.nq.gz
    ├── 58ca902bf3eb74840f5e0a463b21f2093e69f0e9.nq.gz
    ├── 58e585474b80b098f0c7d4379d2eef89f6b3847b.nq.gz
    ├── 58ff1e5bc0cc9bdcd1f9a58d82a4a1e5dae1d1cf.nq.gz
    ├── 59ec1c1a75c2bc96cbf5855d3f89076ba34e798a.nq.gz
    ├── 5ad59e83234ba116356aa272f773e7158b9edef2.nq.gz
    ├── 5ad5faf08b71e55d438b57401457fa1c7c4e9d82.nq.gz
    ├── 5af994a006651e42bf708d2ed067f1df8c64c5eb.nq.gz
    ├── 5b1e11c9f345addf2e1220d7c53d0eca2f685290.nq.gz
    ├── 5b66c016b3990468ed78722408987c1dd2d4643a.nq.gz
    ├── 5bdc08a09e50c8178e641a5da92cc0f2ea85b181.nq.gz
    ├── 5c22ac7bef117be918a1cfda03ae562e48741e19.nq.gz
    ├── 5c4c18989c179f860916d008b5cc14e0b7d2687e.nq.gz
    ├── 5cc5b310c27b92d66b274d71d7787dce49b2cefe.nq.gz
    ├── 5d651b202cc89b7fecdc2f9f48467480d0899e2c.nq.gz
    ├── 5d9b38e6fe983cdb290369f6dc89798f3bfbad10.nq.gz
    ├── 5e8d82922ddc4af2644cba1ef80479854c5db084.nq.gz
    ├── 5eaa4af4df78bc52a5711b54e0ddfb3d645c7077.nq.gz
    ├── 5f5e159a22fc93d827aee1ce083922c9294378df.nq.gz
    ├── 5f5e488f383e3846b428ff15a8c013ea4df07663.nq.gz
    ├── 5f745286a7197260d3dac31d2420c6f090d23651.nq.gz
    ├── 5fa0d07015be43bd625f48e237ed540591c39756.nq.gz
    ├── 5ffc227f979e7f5d96aecdd0aac91c0f8845ab53.nq.gz
    ├── 603b7b6fa3256842f7b29ea02d772f0cf62a95ca.nq.gz
    ├── 6091c4b6be2f85ca0aefeed6c6814a7b9da8f7c2.nq.gz
    ├── 609fc9c7b02211d30bbf9df25f4786d3f61d0450.nq.gz
    ├── 6171dd755a9d2c8b039edb4c6bceaf2cc1e08826.nq.gz
    ├── 619bbc98e3a0701cee28b8544002c007d89d5c01.nq.gz
    ├── 61c1d25f7b3d1d692c6dfe5b78a556b5ff45bc9f.nq.gz
    ├── 627aafb18e6155de9abed63b929ae5a0837f508f.nq.gz
    └── 63b5f2a75fa83b09fd22c2cd3f5d742ed3b4a9db.nq.gz

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

[hpcaitech/ColossalAI](https://github.com/hpcaitech/ColossalAI)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
