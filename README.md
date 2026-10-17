# Repolex Knowledge Graph of EleutherAI/lm-evaluation-harness

RDF knowledge graph data for [EleutherAI/lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness), parsed by [repolex](https://repolex.ai).

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
rlex download EleutherAI/lm-evaluation-harness
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d6de81643928d653435c431bae19945d41d32520
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d6de81643928d653435c431bae19945d41d32520
│           └── chunk-001.nq.gz
└── blob
    ├── 000108f77ea1a0b578c1ca980ed0d74490f24fdf.nq.gz
    ├── 00981bb20ba25a7881c19c31cd174636d4fc3e3c.nq.gz
    ├── 00ecf8ad181aed62a1e987d0abfc6d5c21ea15de.nq.gz
    ├── 0112ad99f9033990bbe6a7177d109ab4c9e54f9b.nq.gz
    ├── 011884f9016fea8be1de21f1d5730f51f194094e.nq.gz
    ├── 01820da52cbd3b30dfe1c65a052b47ce1af0c7c0.nq.gz
    ├── 02278d9ed2be936369a80a706b041f30aa5fba09.nq.gz
    ├── 02349797ed1c73110d2a828d47adfdbdbee518ac.nq.gz
    ├── 02681e0e0ace6c4f8ace4d29e70b2d892612c517.nq.gz
    ├── 03484acba2f48f75f89e8feadf74001449d82150.nq.gz
    ├── 04ce343642b8af545083b1dc21ad269f512d2c94.nq.gz
    ├── 04ed670d5498a7e7dca60d7f9c0f7f09a2e52b06.nq.gz
    ├── 053b911a6f7c17cab1447dd8a9feefdbb9a0d902.nq.gz
    ├── 05c31a4670a9300c1175dc2f7e109c024b146301.nq.gz
    ├── 05f8f0ec9d19841e37416b5343134df1a1db4c7a.nq.gz
    ├── 062dce0a3c9a77fe91e9a4a5c45d8446d58aef25.nq.gz
    ├── 063d111ac4aa0c8625d8615e7b13c1d10ac906fb.nq.gz
    ├── 068d2a9f183a63c7ff89d985fd882381fd610240.nq.gz
    ├── 0705a250288610ebd7162a6a730dd1fef58973c3.nq.gz
    ├── 07f96b7574d1df62b1e560305fb0b572f2648d76.nq.gz
    ├── 0832c633b740ea5174f877023cbb5002de8eb1d5.nq.gz
    ├── 085f4246ea731a39ed605aee5d5d482619c70e48.nq.gz
    ├── 0878c4e03e985eced95c234fa079c3d92999a982.nq.gz
    ├── 09d311e5a13746d41e5e2bcf7ce63fc905b4c72e.nq.gz
    ├── 09f3c11d6d928b6dcb6bb67eea4dec4c8ee64828.nq.gz
    ├── 0a0488295249513408b1d33de3a246b663cc523a.nq.gz
    ├── 0a08c8e3a98efcc19a3f48ec4dc46d220fd7a9ab.nq.gz
    ├── 0a10a5e9899385317282a3205be8de64a2d13687.nq.gz
    ├── 0a22ab84293fdcdf9991cbca6ec33c70094615d3.nq.gz
    ├── 0a5c8c25de23ec78396b97b16c16f1ea3d279375.nq.gz
    ├── 0bd52a493929ca7c2242524e83116e1b8e26e8c3.nq.gz
    ├── 0c01f548806c747150690d942f7def8b2d98f2a2.nq.gz
    ├── 0c4afb7a88bf2ca81ad619b2de402159c7f0fbce.nq.gz
    ├── 0cfd1dff148cedd50a3125222ea2076d5afe48aa.nq.gz
    ├── 0dd336f8b3cbeb85d5854beb923578f215f91632.nq.gz
    ├── 0f06c0655595ae81b985266e4e629b080d49130c.nq.gz
    ├── 0fe4b6bb731b68b084b50e77b17392c5db3fba1c.nq.gz
    ├── 104ecaa442b2bbd1030f140d68b0cfd27e134579.nq.gz
    ├── 1091d840f5a13837b25df4030bec2ea3922bee7c.nq.gz
    ├── 10a5becd284b71460f44d9c00caaf0d42831ba67.nq.gz
    ├── 10dadc008401647e1e9c58e034937abb5b918f4f.nq.gz
    ├── 115796d5276b8739efb6fccfb9064b5f4bb6a27e.nq.gz
    ├── 11653e6059e51d71b48e722abd1c519ddd956d00.nq.gz
    ├── 11668a5f0b10e588e86da989e40863e4d31c6e32.nq.gz
    ├── 11a057d8ed756f0d2e697c459be49f22b57dde94.nq.gz
    ├── 11acf5635c5559884c8c965cd1c4b614777611f8.nq.gz
    ├── 11b8df7f8739d9e4a459636640af6ebb2b7b868a.nq.gz
    ├── 129f0bbd695bfad6a3994936aeaafe309f6d87c0.nq.gz
    ├── 14d6fb2eeab1ed245fc6f8255947c961568fdf6b.nq.gz
    ├── 15375f9f0756d185c588cfd92abd58811df57dea.nq.gz
    ├── 169496aba379d254203e2aa02afbf0edfff86f04.nq.gz
    ├── 16be6060b7700a43fb4f1084fd753e72d370b20e.nq.gz
    ├── 17340fa490f0350e6e532b2c67f8c81fa63bfb3a.nq.gz
    ├── 17d8f3ebfcbae471a4c7d4a852efb489be4bbd18.nq.gz
    ├── 180c7143b75b5c8a0a4929e43a0c42f6e4443011.nq.gz
    ├── 180f3b25e44a21d081d8efd4bbaf9754766e0841.nq.gz
    ├── 192a1f2c0da7c395e2f6f99b08e3e6bcdf822f94.nq.gz
    ├── 195876998160addea6184dbc4d3375192068aec5.nq.gz
    ├── 198f227b893a3758d463ac50d867e6ee3355b76c.nq.gz
    ├── 1a29143d979ef6c0c7d3f38806e1bab6d020f2a8.nq.gz
    ├── 1a2d9f232ea875d57ae57b8a0ccff9742e1a0849.nq.gz
    ├── 1aba318a13c6b67c0934c15312de7ecdf9497171.nq.gz
    ├── 1aed1e5ac7954377f0e594e5e2f3b8260d140c62.nq.gz
    ├── 1b26cbee762ba972b44d9404f421e975ee285487.nq.gz
    ├── 1cc9fde75cd042f62adda200d8dbd667cbc31bc3.nq.gz
    ├── 1d5509c412e8227af5c863888338942d8fca2bbc.nq.gz
    ├── 1d7df52b09b2fb43f64c54fa1c45949f8dd0ac5f.nq.gz
    ├── 1d938cba1e0ab35c3e6b3f53c0a9f995cd8466b4.nq.gz
    ├── 1dac1c345da7ba4971d9b90b0bbecf0ba814aa07.nq.gz
    ├── 1dc93c0d67bc3c43eb589360247aeb25a19477a8.nq.gz
    ├── 1dd277c50074145809f998dd81ef4befbbca280f.nq.gz
    ├── 1de3bcc3c25ad1b26a4daa5c9b0bb0a567768bf5.nq.gz
    ├── 1e997578893b0bd98fff5ebb2696e4e759a032ca.nq.gz
    ├── 1eac952c9e44e97a7678c648c5b917502c9ba185.nq.gz
    ├── 1ec4f58e3675b456e3ebedaa36c49ce45f9a4560.nq.gz
    ├── 1ec9e102fc7668af46af9d9bc375a50d8bf9ab67.nq.gz
    ├── 1ed095bf4193d57d69d450bcf3f494ffdbef90f1.nq.gz
    ├── 1fc0ef01550f3ee2a0aaa74ece9ce2b733f3157b.nq.gz
    ├── 2176ca5faf02ea8078a56991d8e2f8ffccd2a421.nq.gz
    ├── 21d9fc0e71589cb2e1c832a6b82e6d8fb5288b89.nq.gz
    ├── 22bc47943f0f66614f79cd0de5e7614afa1f08d5.nq.gz
    ├── 22de9a1444cc4a4677e42924ea91134277feee45.nq.gz
    ├── 231ee38af9a07d0c83b08833e4f87b492c18b9bd.nq.gz
    ├── 24680e2dbfb841086a49469a56b25d32e8efa1ef.nq.gz
    ├── 257a8df8a2e2eddfa6d33ba67e0414cd6f1fa28c.nq.gz
    ├── 26fe1db5ac3039018f02bfa55e118cbba1db4ed8.nq.gz
    ├── 278884741d6639dfda1072ea0564baf63937dfc6.nq.gz
    ├── 293a76c27a9bfbf7beec22805d06f44310cf143c.nq.gz
    ├── 2a46a242b0adf0edd769de12f81f30dcbe2e52aa.nq.gz
    ├── 2ac14a0c04b362f925e578a30a9eb615a6bc1fed.nq.gz
    ├── 2b8389f1212c727eec6e899279dab85b296beda2.nq.gz
    ├── 2c1c9d41e9b2495490e671f3bec8de893cac8353.nq.gz
    ├── 2c960b75f60dcfef53fac9f5cff333baeeb00ef2.nq.gz
    ├── 2cb24d965dd586f1bf74bef55ce2bb4a165460ba.nq.gz
    ├── 2db9f196a33172f01c47d0ffa5337407d5107f88.nq.gz
    ├── 2dba35cfcc6dc0b8b039a47e6cbe9164bf773cb7.nq.gz
    ├── 2e1ee51ae39475693de41fff1a0da13cb10ac466.nq.gz
    ├── 2e90cf8c00b51667cb09c0ba2857e54277ee46e4.nq.gz
    ├── 2f7ae185dff1e0108d5d4b6d0bd5fa318c3c182b.nq.gz
    ├── 303272745cdbdbe32c83a2d3ceba85b02e59974a.nq.gz
    ├── 3204b902c7d8457abfa4f1eb24fa34f08001cc95.nq.gz
    ├── 3230d00a677fe3628bc4b682db025feb8cf1e7af.nq.gz
    ├── 33169fe8280f4cde96756cac4580984d7741cb53.nq.gz
    ├── 338f080950aa736aac2d7b1ff63d990dd4a467fa.nq.gz
    ├── 34033c55b88be89f49997de2820f88eb689d2e2d.nq.gz
    ├── 369b9ea1dd73f6e7b3bd3398c2a6c86161b272e8.nq.gz
    ├── 37f611a1b7804755d15290516e3321155dcc655c.nq.gz
    ├── 391e0800d878fa613edac0d02b497a6e3c7ea92b.nq.gz
    ├── 394c1d77e553a24820ba5db934bfa8fd95a8a269.nq.gz
    ├── 39b365418eda1be6e4c344d4e32717045d2eafda.nq.gz
    ├── 3be22efe269d48fefd05a7921c9e30e796b11a4c.nq.gz
    ├── 3c0f045d8825b6a6e778211f0aead037b628b907.nq.gz
    ├── 3ceb0df221f7902668c81f71093f8a9a310da063.nq.gz
    ├── 3d4dd34ff212178d2ea1414d219262edc5e646c0.nq.gz
    ├── 3d6465da7416b7bc3c23ef44482d125e0e6fb9ea.nq.gz
    ├── 3d6ce3efcc06da61779af071de70a7ce093a5dca.nq.gz
    ├── 3d7510dfc80d4e52db0cc020f5f2abcdf9952795.nq.gz
    ├── 3de752a10fdbdd1d10217f12cdd20618d8bd7908.nq.gz
    ├── 3e3a8ec6f710ac92bf836ad6dc406108e69af26d.nq.gz
    ├── 3e735e2deb1f9c53152c072615aebe8ba3acb90b.nq.gz
    ├── 3f28488a9028fed32a088de9a2e8c0fac4fd12de.nq.gz
    ├── 3fa1380df4b219fae78d9af94069a3becc256832.nq.gz
    ├── 428b1c5f8731a4e8533035dd624c8fd66549deea.nq.gz
    ├── 461958de5f6cbcb236b23ee50381d3a97767ba66.nq.gz
    ├── 46cb3f1bc10ed1119d3485456763a28868940c06.nq.gz
    ├── 475a71fdbbeb22532ef620ceda4bc70d03445948.nq.gz
    ├── 475eaf91a5d3f3287e06a62bf94accc3dbb61b30.nq.gz
    ├── 47e49ded46082847d73fce85e2db37556fafa877.nq.gz
    ├── 480b29e19197670dacf177788da96f9d973f8ae4.nq.gz
    ├── 48261c60b28fa4c157b511153b609c840fea80e8.nq.gz
    ├── 483a8fd6fd14575ab2bc2a87ae4767d6aa194480.nq.gz
    ├── 48e590213417ddbf4fcd72df0ce04b000e0e9081.nq.gz
    ├── 4b7cb5e7318fe73422c66e88ed3a64025c65d0e8.nq.gz
    ├── 4b94a2c13dae19e6ed50ab49a321b1f73d326a97.nq.gz
    ├── 4b9f49af669e777d6b133a1380725cbc021b01d3.nq.gz
    ├── 4bbc19d54eaf88a6208e5dace07880e27ef637fe.nq.gz
    ├── 4d03bdafc44d8335e05a79ecd45ef66fb3c82e37.nq.gz
    ├── 4d5020a5ab95397d71b30b8b9a00df137c01280b.nq.gz
    ├── 4df4ffc582991ccbc5c6949cfc61035eddc63fc0.nq.gz
    ├── 4e2a1ef6bb72384cde74496d940088b4871d9dd6.nq.gz
    ├── 4e318de321992583381378b2e3fc8b7c02704932.nq.gz
    ├── 4eba7f6994b577b4769b6b74a2848ecc0b3b0fb0.nq.gz
    ├── 4fae66a7c5ecef3de82fef9fb280c3a3c2c3ca14.nq.gz
    ├── 508a63a9452874109cd949f5d5a5e00ad5f66b36.nq.gz
    ├── 5094c2d3633ffadb9ca94c358c11df444e8b3855.nq.gz
    ├── 515a40f0c063d440b1bb230ceaebfae8c1938fde.nq.gz
    ├── 51e7dd9e92f19f1c849b839f30fa78522254ed14.nq.gz
    ├── 51ff436ba4e0fd6d30c9cccccc1d7efbc19f6f1a.nq.gz
    ├── 520bcdf3faaf5b395c266496092e51d09d0f30f0.nq.gz
    ├── 52156c85072e4f1a829345a4b9eef7af2c2ca059.nq.gz
    ├── 5234b7a0b60b0d06001c150faa0ea30da2762382.nq.gz
    ├── 52947adf6b6819c5af4abae69ab994603bc38ce4.nq.gz
    ├── 52c92423e7159ddeed225b000a50a1cb28ec8236.nq.gz
    ├── 54fce1f8da44e9b2c889e71e8a8d9f5eea4b3ef7.nq.gz
    ├── 550834257a69f7054ae397a403c6dc00d15c8888.nq.gz
    ├── 55099c6f16febd89270ad022abe181bf8ccd708e.nq.gz
    ├── 5528016f47710cbd8618a61ea0df2910b5b26a40.nq.gz
    ├── 564d86565f8aa47d9944d3a5aedc9555ca29c9a8.nq.gz
    ├── 5727b785993c98fad6b2bd630c8dbd076ff60c45.nq.gz
    ├── 580d538517936505bdb7e435e8e6b3d6096d4876.nq.gz
    ├── 58cc172092b5268fab5142766dd5caa6679ff0cc.nq.gz
    ├── 58fdc83f0294d00ceb4e67bad0171f444dbb2622.nq.gz
    ├── 591d506d023654e1bf3fe06fce92c895f28548e5.nq.gz
    ├── 59d26a1a22e441ad9c7303920d93b67ae552d8db.nq.gz
    ├── 5ab84a8b5dcaf181c72b1db050f53281eeb26600.nq.gz
    ├── 5b3955a93e27cee34ab96ad17ab688eb22418043.nq.gz
    ├── 5e68e101d53cb1f166ccb93824dba9332a09e49c.nq.gz
    ├── 5ea2914d41f6be70127e56ba1285dcabd723f094.nq.gz
    ├── 5ee91f710cf4372f01de5d0ea60749707d2c8e5f.nq.gz
    ├── 5f340addd59d21e74d72d3a3ea1c064320cbff36.nq.gz
    ├── 5fc59ee24bb455dff7cb77cfdb73ad11b7f1f572.nq.gz
    ├── 5fd86105df589b16c08f9c8abfdfc7eca6cbf712.nq.gz
    ├── 61172788f96865300020c3ed3269627fc8a60191.nq.gz
    ├── 61359149c5df8d3a56cd6efb600de7cf2a7b1b51.nq.gz
    ├── 61521c91da4d5597aa1c31450e1b18a0115f9771.nq.gz
    ├── 618bb77e629524eefa58419fd9533af20ad29871.nq.gz
    ├── 61e717f46056322c32772a15c49b4e92efe5cec3.nq.gz
    ├── 6240db295f2e63697de85e0e5e6baa0d7020352d.nq.gz
    ├── 62a197c0eba0a301c435c9ed68e1f108c3716022.nq.gz
    ├── 62a570f00cb8a457ce0b23917ac897b5e77acc70.nq.gz
    ├── 62ad6c00f7568b54d39dc2da0bafa30e45a9835e.nq.gz
    ├── 62b5b80e7c26335f304f7ed9673dd9f1c94ef970.nq.gz
    ├── 6302b417e70c09a831aa7ae1124ddf559fca01fa.nq.gz
    ├── 630a90a56f8a0b2a48ef75d0a4b6e6b17471682e.nq.gz
    ├── 630e0b2298157f3072dc706e74362ee128513a41.nq.gz
    ├── 63be26d6c98dfd1c004e5eba68464c20dd498027.nq.gz
    ├── 642aa1830753a18d84bc8df8c6cce3a926419760.nq.gz
    ├── 64665de31fe9f4e80b33917bab1812553b52527f.nq.gz
    ├── 64c0f9c67414c1da011073a377cc05a87255e8f9.nq.gz
    ├── 6527b811c6a01fca3361f217e0444f2874c30536.nq.gz
    ├── 65bb7cf4596c8973ae7dd2efc60e366c65bc4800.nq.gz
    ├── 6612a3cf79bf293ab646ceec7b872f5451f67af3.nq.gz
    ├── 6625c9ce5a2501aa607cacf148531e0c3220652b.nq.gz
    ├── 663946766a66de190961e49ad9329cfcd3ceca62.nq.gz
    ├── 6728c95422089a3a2eb330a2679765e7b3367c22.nq.gz
    ├── 678ee0d4c308b9e1c3cb492e088f6b7fd881af14.nq.gz
    ├── 68969870744501788d6eeb43d844610a37d5a69b.nq.gz
    └── 6acd743a77e5b04b5df5ddf8861984f206697542.nq.gz

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

[EleutherAI/lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
