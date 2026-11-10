# Repolex Knowledge Graph of RedApparat/Fotoapparat

RDF knowledge graph data for [RedApparat/Fotoapparat](https://github.com/RedApparat/Fotoapparat), parsed by [repolex](https://repolex.ai).

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
rlex download RedApparat/Fotoapparat
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9454f3e4d1d222799049b00f3d84b274c3e02ee6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9454f3e4d1d222799049b00f3d84b274c3e02ee6
│           └── chunk-001.nq.gz
└── blob
    ├── 0068bfcdfc9f54f9789bd4c3d01a6c11c0b945dc.nq.gz
    ├── 0154359f1dbebddaba9e0118c439b4f096997e53.nq.gz
    ├── 01a964aaa20e1861676373c5276ae8f1f049b549.nq.gz
    ├── 0201cc8b03bd0087377970bb3f1c55624ba2b15f.nq.gz
    ├── 026fd946db9df1344051f5a9f48787a2d40c369f.nq.gz
    ├── 02bb6a80d6a415040d3ea075d52743d478ec2f6c.nq.gz
    ├── 033307bdb761082336cd8004a4e00512f40f9544.nq.gz
    ├── 0347d20c858ece70f9331ed2d5167fd6896dd27e.nq.gz
    ├── 039cb88befcf57e24aa93d99bcc593c55ffe701f.nq.gz
    ├── 0410994b47daef9353292d9245767fc8d46cb251.nq.gz
    ├── 04f89312e351a3f31575ae6f53b53e82985fce45.nq.gz
    ├── 06217ae65fe703316c43d650cdbbda05009402b2.nq.gz
    ├── 062c6fb927df6a98ab74aa1220906c2754440c1e.nq.gz
    ├── 06ec520aee6a9aeba9a887af7e80ed92150228c1.nq.gz
    ├── 07f4d074d39de492ed06e61ac223933974b8f651.nq.gz
    ├── 0830e686223baef0374a7a21be7bb11fc3020a5f.nq.gz
    ├── 0aa3a330c5cecdf8cfb0750fe159ecabb7d2e6ab.nq.gz
    ├── 0ac8ad342e57479f156c2f8b4b071fe2a6b35545.nq.gz
    ├── 0b724db0b5487fa5a582aa521ace5d48616d0b1d.nq.gz
    ├── 0bd0198be2c92cf606749ed080e926f90a5585a6.nq.gz
    ├── 0d54652e80742c6d60ce2ea86e56e742f33599bf.nq.gz
    ├── 0d9c241b93d365f45954ef6c25d53a0a35993dfc.nq.gz
    ├── 0e95acbed3dca7bae96df9e517982aa253a15747.nq.gz
    ├── 11864e5845e84e4bd4f9765aada1f57cac3d483a.nq.gz
    ├── 125338338ba5d31d6ade2d6eb77cd92157309304.nq.gz
    ├── 18fdfc1ffd3de41d7e978d939aa37d8e68ad5f75.nq.gz
    ├── 1bb3a89c4e9539ce6a711841325e385b642bff28.nq.gz
    ├── 1bcc9bcbaa1fa63782f06908eaaaddca493e5f9b.nq.gz
    ├── 1c79362cc45699106afb8dfb95fe17cbafb78589.nq.gz
    ├── 1cce898c6ebc8002816a71d5c03ffb397fc8fe82.nq.gz
    ├── 1cfda1430c7d14547148406e7fadadd27f2ee850.nq.gz
    ├── 1d534b0370180bd952a4114ee75a23023b04586c.nq.gz
    ├── 1e20b673aea56afaf9c59a0cfc951af0dade37e0.nq.gz
    ├── 1edce4c4694181a4f9e35ef15618d17e01d65454.nq.gz
    ├── 1f1f06c0f4261535e625f20b1f8328caaf53028b.nq.gz
    ├── 210190cdef8974c3e1ce552feda9b39bf484683e.nq.gz
    ├── 214c6bea71205494f2af8275ce7a01a8c25a4e60.nq.gz
    ├── 22398ba64d0686e4dec07aea4fb9fdd1e08e1789.nq.gz
    ├── 2353fd3fa85bd6b27d1bc21fa7517a926083fb52.nq.gz
    ├── 2357fc4495737cdc18dfda18533bc2d9a8919280.nq.gz
    ├── 25a321df4f6af9797952dac77611ca7637cf0099.nq.gz
    ├── 2644e3918f89bc72e1f30fb7f59ddf4642845d95.nq.gz
    ├── 27126a03693930d3819f05113c7bf72eee95cbba.nq.gz
    ├── 2757a1fcac64c7dfa2e12dbec83355d3f1dd66d2.nq.gz
    ├── 29953ea141f55e3b8fc691d31b5ca8816d89fa87.nq.gz
    ├── 2ca117effa56dc841af50f2d823f10adb9e624ba.nq.gz
    ├── 30eb1cd89ca4f4509a611a346d2ad900f176c402.nq.gz
    ├── 31a774a6b9ea74081c92c746e98165346eeac781.nq.gz
    ├── 322cb44e45828066b94ea20b6b786e0504355fee.nq.gz
    ├── 332212848ae6ceec8b1de5938d9bfef97436c063.nq.gz
    ├── 3342b3aafe55ce5b5759e7eb8ecd7accc3de6640.nq.gz
    ├── 33e3fe6562bae49fb3636c94259d8dbf16e2d65b.nq.gz
    ├── 33ec28f84bfa72188c639aec224ac549983e5264.nq.gz
    ├── 34556751f0d208deca93709e1e104ee3475cae9b.nq.gz
    ├── 34e183371bedd355b2ae79a59ec9d124fde93ea9.nq.gz
    ├── 388a8905ec2d9406657f0a0bc08f26da95ebef8d.nq.gz
    ├── 3996270fdbd358b82c0380c0b26427b3f8a26820.nq.gz
    ├── 39c5ad26461004f9a83267d1864577456dcc4123.nq.gz
    ├── 3a0138a202a335db36fe3e16fc2dbf16f41635ac.nq.gz
    ├── 3ab3e9cbce07f7cdc941fc8ba424c05e83ed80f0.nq.gz
    ├── 3e5ecf321048457ad7176bac5b48c714784f4a46.nq.gz
    ├── 3f775cdf5a3acb9ba7b9999773d482a060bc74af.nq.gz
    ├── 422ba874d3b733924af8aa330730168eb9549535.nq.gz
    ├── 4251671020e00c306b37dbb1824883eed7de9ecf.nq.gz
    ├── 4420a9bce20d5e1517667fe44d538e2261d2a7c6.nq.gz
    ├── 44796f79891338ffa3a16bdca993ee33699c0113.nq.gz
    ├── 452a89302f9b2b678e56136388978c984c06f964.nq.gz
    ├── 470e7583ba8a018b2c621b762d6fcba0abf3cf0c.nq.gz
    ├── 47506d04e5aa80d70e7072605801046392dc6b18.nq.gz
    ├── 4795208c89100dcdc3d8bae857946dcd25ab51b9.nq.gz
    ├── 48349547ac2b26495b7abdec1e8d750b7b21218d.nq.gz
    ├── 4a1972114b23541c019d45e894b1473b10643b19.nq.gz
    ├── 4a779797bfa0e480983e729a89cfee3adae471d0.nq.gz
    ├── 4d4096c5560911487f8a418bed8120fe8ae3bdae.nq.gz
    ├── 4de3ad67b328fc4d8db97ca041bc862a7df43872.nq.gz
    ├── 55ede2f0be4bbe4dfd8d628d529be020c9c1b3b6.nq.gz
    ├── 5606d07f58f123250c6fc7a2519a42db40f475f3.nq.gz
    ├── 57b5256bfef5408e7adec1c21284c56d222b7bda.nq.gz
    ├── 5887a0d29d5ebeae19ed3cc27295c64a5aa74c2a.nq.gz
    ├── 58cb0b490b2fa3bd15d02f440cc3a180af94b02b.nq.gz
    ├── 58eec1fe79d376c6be66ba4d0415cc681b7382b4.nq.gz
    ├── 5950dd127aee1036fcf485e6900d32433ded2d27.nq.gz
    ├── 5a39210d2e09ccd5976fd8fe218eb05e2ca54b34.nq.gz
    ├── 5e995df57207d365fb691881b71ef26cade7b1ee.nq.gz
    ├── 5edd827e1dde467f98f615a5fb2958e6e0f6f5b4.nq.gz
    ├── 5f028bde5000a8b841cf8bfca4224858be5b8986.nq.gz
    ├── 60f189effd586a311ce0788d7787dab2e086e86e.nq.gz
    ├── 628043e706146f72332edb93b29064d5bbcc788c.nq.gz
    ├── 62bdf94b33434b10043756eefee989e2ddbd7c64.nq.gz
    ├── 632f67fa7c30a5f746da37835ef342b9e334aadc.nq.gz
    ├── 65b80bfdd0d804536f62ae2f02cb95c938b80812.nq.gz
    ├── 67de6ea5977083f8bb5ab7ed0e7eb39a0749a866.nq.gz
    ├── 6831bd5875ae09344e1e0d788fa5e06c8a96ae52.nq.gz
    ├── 69d26ee025ce293efcf7f4a15dc8760c93152382.nq.gz
    ├── 6b0be96d6394f7039253043ffcad64d2636ce4d5.nq.gz
    ├── 6cb4bc1fd506ab197570d8da15cc8d44ce551e60.nq.gz
    ├── 6d09c27dc6367d9407c70b2c9b79d6e6a2cdc8b9.nq.gz
    ├── 6e6ab425db59e2c03c028d086cfadc49ece01882.nq.gz
    ├── 6f4807976eb39984764807cab78a11b73bb8f63d.nq.gz
    ├── 6f78d729937984e1ab9b9443a9409dc9da2c4bed.nq.gz
    ├── 72b7fc77d271de310b155ebbdb628affc2e19337.nq.gz
    ├── 73dbf7911935337702a92567eb8ce1e0b16320dc.nq.gz
    ├── 745b2b31841fcc06b97a105cc0092ddfc62cb220.nq.gz
    ├── 753d6b576960dc227e06f2bac882fe3b59dcf2fc.nq.gz
    ├── 7731251ac7b3b386866f5132464aed11fa0c0cda.nq.gz
    ├── 795f705aa2171d4c84ddb7da9194b677202b1922.nq.gz
    ├── 796b96d1c402326528b4ba3c12ee9d92d0e212e9.nq.gz
    ├── 7c4c5a9c5dfffbf86811388b155b5008b108a0df.nq.gz
    ├── 7d5f59f9026737137a3430199aaa94c9abb82ca0.nq.gz
    ├── 7dccc3e31813cc9e85762e2e13d76c5c161f7a5b.nq.gz
    ├── 7ea8261c9d94232044a9cfd28e944f7028d1a35c.nq.gz
    ├── 80077dc83282148e64654b7f0d3f7ece7b688a53.nq.gz
    ├── 8251e8aaab8804f05409772e39ff62bede75d866.nq.gz
    ├── 868defdb76bf3ace114b697387c497e62167b307.nq.gz
    ├── 86c59c9d30165f28f39f0c50278d82f1c6784165.nq.gz
    ├── 8842b844865f9e9bb7580283a9a0596fa685331a.nq.gz
    ├── 88b90df9ec68f8cdd792650bcabe29fe270d7395.nq.gz
    ├── 89ed7d30438179c42eb033f47b9195408c5e53f0.nq.gz
    ├── 8a19c3bd6e7a52336acf930f8629b6f7370a1f3e.nq.gz
    ├── 8dada3edaf50dbc082c9a125058f25def75e625a.nq.gz
    ├── 8db8e5dae175ed64a1507eb25435bcfdd89fc094.nq.gz
    ├── 8e5ea8c3d3453c73d0e1555d4c7edbdd7b8fe91d.nq.gz
    ├── 8e78bd7e7b3046d4039b203a4cf84b6d90c65ffa.nq.gz
    ├── 8f0c47d46d78de28e65fc81cd26e8a150d09cbd1.nq.gz
    ├── 96c03c05ae340cd35508b20384b1dcd2d6948d87.nq.gz
    ├── 9849328ca82fefb6826d4d53637ac9b128b1e862.nq.gz
    ├── 988a18aa8474865c7345a090cdab2303479306b0.nq.gz
    ├── 9cca12bf2fd52c8f0261f369675ed232db3ee943.nq.gz
    ├── 9ead181d784ebe23226853567718a6b89aa24384.nq.gz
    ├── 9ee9b39f74ba316124e8b28915f3db36bdf494fe.nq.gz
    ├── a2257ef2810fdf209f2ab1793a92c0c61aff46dd.nq.gz
    ├── a2e2daf17b1409880bae436df3160e93a2890db5.nq.gz
    ├── a5297e4ab7358f6c6c01b93e14e79dacdee80e0a.nq.gz
    ├── a566504a47c51552f695f2e0fc51409b402e2349.nq.gz
    ├── a57bf0c0e3870cb15158dc60e20da417ebe1758f.nq.gz
    ├── a585a6b26cf79686e49f2bf7ce225c3eda3bd405.nq.gz
    ├── a6514c5adcc15c7ef954d2ff6d52404e5ae08699.nq.gz
    ├── a67ce1cd5379b4fd36b5adb31de9a2f560817e8e.nq.gz
    ├── a894bdee161dabb0169ccc8acd868a59694b43c8.nq.gz
    ├── ab6dad581a9ffa650ec8f65cfc6a54eed3aa32f7.nq.gz
    ├── b036ab35b82b4b2bf5461abe181f311f25f9e56a.nq.gz
    ├── b0e91f36b3fa6cc4b232e86b432d28217e8364ae.nq.gz
    ├── b1d4f6c0438ec55c113ee56c84857eb4fead4846.nq.gz
    ├── b36d3ef803f75b06f4a05ea77d73fd0585035b30.nq.gz
    ├── b3b2cb283bf9b8322cdcc001f6b3305f2399a910.nq.gz
    ├── b445be34fb4e40855206fce8935cbba5c698b54b.nq.gz
    ├── b49357ddaa54984004308899f1958c0d87283cda.nq.gz
    ├── b7b9a5224477b1ef6f1ed2295e923230a808da17.nq.gz
    ├── b871f13cfd73b89157b761d5fcfd40a313534828.nq.gz
    ├── b885b7264a3404a6e3c66e8c56ffed1728786766.nq.gz
    ├── b95f9f4c605112d6858bf90720340755ceb50c30.nq.gz
    ├── bbd23e4c2ab761361440bb8e2e57557dfe8733ae.nq.gz
    ├── bf1dd8b159c64293155ab3aa7dc390508c9b57ec.nq.gz
    ├── bf21d12ec687a1512aced7e319c94d57eace0e84.nq.gz
    ├── c1516dfc9454f3f1c067e5d3944284e525188167.nq.gz
    ├── c1999a058c95e203501f4552841659e2f9983103.nq.gz
    ├── c1d93bde6c0e4277d724f00b28c2b7194b56585f.nq.gz
    ├── c2366cd10be868cdfde1348bdfefe08735100d5a.nq.gz
    ├── c42818cb1f2ebbd2c4312a16913060a4379f34a2.nq.gz
    ├── c5c2c1c7fb7baef99f979a495bcd765cdfb68c95.nq.gz
    ├── c6377f047b8e6b436e6a4108d788416a1af74bb2.nq.gz
    ├── c6d544e44c3908b7cc97f8bb32f146aaaea1462d.nq.gz
    ├── c71d961a717932be20f9f76569aa6c170963d605.nq.gz
    ├── c74cf0b1f76236477db8ab4728c90bac01309ed8.nq.gz
    ├── c774b7e3212bd9172ee72b5c2ea0ccab773f2b38.nq.gz
    ├── caab280429f0441f5ae676eab015fcd1930061be.nq.gz
    ├── cc07f52fa0be0084cf979ec22c3565303f667e2c.nq.gz
    ├── cccdd3d517fc5249beaefa600691cf150f2fa3e6.nq.gz
    ├── cf2458949e94119df58dfc77161d28a8eae073de.nq.gz
    ├── cf4bd0d94607e0ab4409b125666f49abb6a3e6c4.nq.gz
    ├── d021fa3cd0517761747f6708258825ff36f606e0.nq.gz
    ├── d16de12db46cfaeb0b29c1f7b0d97af7f3d58fd0.nq.gz
    ├── d375f1a646d49448f26d4b6ace539c12b3df1ed9.nq.gz
    ├── d3c53ea5288f4c9b43022909b8c71dc71d1e9a91.nq.gz
    ├── d4246f6aa1316e95dc79b82f0fac2b5f353ea6ec.nq.gz
    ├── d48a8e35a8304964a04854c5880139aa2e22bef3.nq.gz
    ├── d6734193e71e38487413a08cbbb6cb6620bed377.nq.gz
    ├── d757f3d33fcc6837851eb73a6963eebcee23c282.nq.gz
    ├── d7cc654a77532f957f0ea055f9a01f55197bd819.nq.gz
    ├── d7e8ed16a259bf370a0ddc1693a794997c3ff23e.nq.gz
    ├── d8f92b3b56df500082966029c1462aa811b4bbf2.nq.gz
    ├── d9b2866aeb552ea4c2df93129025a38404b5754b.nq.gz
    ├── da33aa2587d1e0e0cc05614f8b7a2d9b48d0d8b2.nq.gz
    ├── daa57440fa8db2cd0ea6030ffc7ef7c80bc54dc2.nq.gz
    ├── dbc783e20a65655c3929da2e433d91e6325b4540.nq.gz
    ├── e01cbc5dc439ce92f46e7fe1632a050f8e425974.nq.gz
    ├── e1400a5a1378659bdb5a4219318accc3eff3fb2d.nq.gz
    ├── e1807fc500b070992e6e0e3d6632666c6ff9586f.nq.gz
    ├── e2616a38342956c4f416a270cb30b123a0f3ecd5.nq.gz
    ├── e8bfd202321e6f5ca220f50a1e540d907f45140a.nq.gz
    ├── e95643d6a2ca62258464e83c72f5156dc941c609.nq.gz
    ├── e9645547feb9d0cf77bd4eaadc7a179f6a7f4a98.nq.gz
    ├── ebb02f954fb1975ed29867feff3ed1231489f1cc.nq.gz
    ├── eca8b4f68f6881b410bdc6cf7699d7b08021ffcd.nq.gz
    ├── ed8ad5bb6d63e081cfa3030f5b98d866e8f77719.nq.gz
    ├── ee79caf1557a958871cdbfb2b08fe0919b3f797c.nq.gz
    ├── ef5c53e85f1dbc3248c6389693c90c08cf5b515f.nq.gz
    └── efd766dc3e952c8d0852cafbfd75c508d8da08df.nq.gz

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

[RedApparat/Fotoapparat](https://github.com/RedApparat/Fotoapparat)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
