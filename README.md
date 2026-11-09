# Repolex Knowledge Graph of block/proto-fleet

RDF knowledge graph data for [block/proto-fleet](https://github.com/block/proto-fleet), parsed by [repolex](https://repolex.ai).

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
rlex download block/proto-fleet
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── cf88e5c31d3bcce18f55491fd3afaafbe3af3b9f
│   │   │   ├── chunk-001.nq.gz
│   │   │   ├── chunk-002.nq.gz
│   │   │   └── chunk-003.nq.gz
│   │   └── d6d3e97b24c27e4fe9cee942992dabb851973a13
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   ├── lsp
│   │   └── d6d3e97b24c27e4fe9cee942992dabb851973a13.nq.gz
│   └── repolex
│       └── cf88e5c31d3bcce18f55491fd3afaafbe3af3b9f
│           └── chunk-001.nq.gz
└── blob
    ├── 0047890d0420cea9d49f3ae58a4eded85eafbea0.nq.gz
    ├── 005273015aa1a4fa26fc737454675961c2561964.nq.gz
    ├── 00b2ec0f75c2b3b121471d0f704ce5ffb0053246.nq.gz
    ├── 00c5520c2142791a11e27ae98c9f22667809eff6.nq.gz
    ├── 0124c2d44c2f4966ba90d82bac6122f0b85fe890.nq.gz
    ├── 0163dec82ba803cc1435aa19d5553d1e3c490f17.nq.gz
    ├── 016ef88f986192afe776d3d7d0c33722c586085c.nq.gz
    ├── 019112b57e6503b199c9de2e542355b696b6df29.nq.gz
    ├── 01b0a3e9fdbc955b5042c62724b3d5c17184158a.nq.gz
    ├── 01cd5c3a8c477313b7d73004016cd17accc61545.nq.gz
    ├── 01cd773b4b25075c4a140071c0238223beb2a276.nq.gz
    ├── 01d48e3305d15390b4fea501962a08482879fd82.nq.gz
    ├── 01eeffc346d763fab5e0cab4d7b25291d477b28d.nq.gz
    ├── 020c6580df1cfa55157bf1b5bcff73b5d561170f.nq.gz
    ├── 0210757d005aff4d3c7465a9d1f1565fd0c37b2c.nq.gz
    ├── 0251ce86c29fe0c948c026d4e96f270d839c81db.nq.gz
    ├── 02ade75cd3ce60c18863835145ae3657316005f8.nq.gz
    ├── 02b1cea737e3f24704c2bdd4adde27bbc1085e14.nq.gz
    ├── 02b97f3f82efcbc53536392675e3188a74cfdda7.nq.gz
    ├── 02bf690b9c790921ad36f222c3960df68f806509.nq.gz
    ├── 02c0087dfb38bb08ff284615e25edf0ff1aa3703.nq.gz
    ├── 02ce76f5ddea1beb7b82b615bd0952a1e6e05f80.nq.gz
    ├── 02f9dc21ceaf974b903b36802c00e6c64cfcb3b6.nq.gz
    ├── 031b37dcb1459e834df8a559c1768c63a8666e2e.nq.gz
    ├── 033ad1c2c2fc7c345b33226425f28883f09b0f1b.nq.gz
    ├── 0361e83f2b4ba35b6595c4a67a0cb3b70852aca6.nq.gz
    ├── 0381d7b64a18fb29b9d8f83704c61ca63f3c5763.nq.gz
    ├── 03c8a29c827c05c298e480f352b3786cd06cfc3b.nq.gz
    ├── 0414694113425cce02f3fbb031e2405f3fa876db.nq.gz
    ├── 04a31a6c38fadfa49c631a06197d2898fdf02c29.nq.gz
    ├── 056ad165ec9432c27074612b81fc18e1dfbfd06d.nq.gz
    ├── 05accf9f7971f39537881c58c96c00f134d878fe.nq.gz
    ├── 05c3eb9b69a1b223500625bf18add3315b3494b4.nq.gz
    ├── 05d3f3d0c5c5c6712630b082ab3b17b224e799dd.nq.gz
    ├── 05df8ad3746d376f0d8551a255c4db057bfac02b.nq.gz
    ├── 05f233800f1681ee3a0e3a03b5cacfb3a9715c48.nq.gz
    ├── 05fdbd6cb97cb1de300ff7940c3387e9edcadd74.nq.gz
    ├── 060d36ff049edb9784c87c06bc3c87097f1c94da.nq.gz
    ├── 061117079115950cdc22996600f406e6a5e252cc.nq.gz
    ├── 061818696da67cb95cba319cdff635443a9a7086.nq.gz
    ├── 061bc3cefe4dc93857fd5ed0c088c967e0d280f2.nq.gz
    ├── 06343d319dd1c0b4f4aaa00214202a3349474047.nq.gz
    ├── 065334fa259dc68ab9e555d418e5d15153dad124.nq.gz
    ├── 0675ac32aa2a6961bda3a7e6b6b00c352418b8c6.nq.gz
    ├── 067e6df29ea3492da0f02c61eb3250b4190982f9.nq.gz
    ├── 068019072728cf9d9e63e5f6179464cb37317035.nq.gz
    ├── 06f45cf52867341a38fbd1e8a6982d6f111608e6.nq.gz
    ├── 073ff69073fdc416f1f0520d7e23e8a5366a7ea2.nq.gz
    ├── 074e7818e1e63a437abca203733554a76d8ddc18.nq.gz
    ├── 075a4900959741494d9a00277f0bcaaf37fa8335.nq.gz
    ├── 07aaaedb65eca12a54cb967564204633f1e68595.nq.gz
    ├── 07b183ea6e34f0bd6fdac879016430c60a2db7af.nq.gz
    ├── 07d33ca13cf33c8fc4068e3961933a1912513d77.nq.gz
    ├── 07e919ebc8668fe36708cb9d8d26384d418b6674.nq.gz
    ├── 082103baefd56dc207f22a3bfe4ce6088946c322.nq.gz
    ├── 0866c557bd4b1c97a4bffb0f9783bb01a840bc17.nq.gz
    ├── 0868f4d63111bf6af1ec4b826a4d65f3e0092924.nq.gz
    ├── 0903b37c4aecf09f4495114e16dd081a690273d2.nq.gz
    ├── 09686f43575203573a707239537063f644396bc7.nq.gz
    ├── 0984edb4204d8d6b4f43ef215c506e29547199cf.nq.gz
    ├── 09ff9dfeb2c9387f8ef408fb22147f21a2ede2c3.nq.gz
    ├── 0a1615f0d87e4c00df43c8bfa2f256af5c198598.nq.gz
    ├── 0a59f5dd72bcaa72926d24967b7ce20ccca1dab7.nq.gz
    ├── 0a64d3422d64c58fbd60d3b4b859d6f7d26f7643.nq.gz
    ├── 0a86243ff28d7746db0abe136167c5fabca01400.nq.gz
    ├── 0afde71ff36370d592160d68835a2d0657537271.nq.gz
    ├── 0b223851bb94d4b22c6a8760f82b5ce4a5de660d.nq.gz
    ├── 0b774931c8e48b7f363719a45fefd02590b518c5.nq.gz
    ├── 0b8291f7e38479ef677ed07ea7dcd5d2ad66f2fb.nq.gz
    ├── 0b9132a4d8ca2f481ef70a1a3963223169564693.nq.gz
    ├── 0bdc37518eae0145907f27ec341e37590ff049fd.nq.gz
    ├── 0bfb2ad0695b610e692c6fd861bfe0114c67ea09.nq.gz
    ├── 0c04c900dbe4c5572693356e48fde8cdd89a6463.nq.gz
    ├── 0c1b5e1aa78e8cb3e0d2ff4bfe8f58cb2e063322.nq.gz
    ├── 0c3bc9a9329a92f9df6df568a37882eda4bedf13.nq.gz
    ├── 0c4ce973a2b7d89ddc124bebf79a096b505acb6f.nq.gz
    ├── 0cb603d211ecee2fa69bae1b9735de6b50dc46e0.nq.gz
    ├── 0cb7fc0a3cb0de51fe01625eec3138f70e268567.nq.gz
    ├── 0cd1acb96fba8b8940e1ac9064f5b62fad9c7c76.nq.gz
    ├── 0d3788af176ea041cc2e153362803f82621f0faa.nq.gz
    ├── 0d5f3c0c138dcebacc0b5ec420974513dd68c10b.nq.gz
    ├── 0d87fe12958cda5c47f399335c9bc638f492d291.nq.gz
    ├── 0d8f424f74a2baaecf620b50023cd85c66b0a798.nq.gz
    ├── 0d907b0f3a0b36716bea3788a630367a142f14cd.nq.gz
    ├── 0dc71f917beaa1301610ee00c3c8c87b8d359171.nq.gz
    ├── 0deb7b0ca07c8c9314491a29c10edfa0ab148291.nq.gz
    ├── 0df8ea401dcf4de9f718aeebd9dccfc3f7ce7a0a.nq.gz
    ├── 0e13026703f6749156b6faea3940822e102be470.nq.gz
    ├── 0e1551289bca06a55bff517d88e81410ed669c95.nq.gz
    ├── 0e2adec16392b9ff3509885652e165a6b09af9e1.nq.gz
    ├── 0e3f1bf41beb8f62a223d559085b4635822e7ff7.nq.gz
    ├── 0e7928787baca5684e4ff39ab3bd59688644e8f9.nq.gz
    ├── 0e8bac91aecade9d65da8541fb6352ad3a6e0da6.nq.gz
    ├── 0ec7b68199bda9be5c3169e73382743f3664d157.nq.gz
    ├── 0ed1ad2e8e15afb2c9fab6601254137e3f918533.nq.gz
    ├── 0ed81b0e81418a7d1908ad3317a8476bb912ae50.nq.gz
    ├── 0f0b971aece094eec8383150574cc37149efc09d.nq.gz
    ├── 0f3e12b3582612f518d44c007a4a9683a2357c6c.nq.gz
    ├── 0f62182270eb1d70f3cce8fcd4d4694331588f51.nq.gz
    ├── 0fa0ff2502f441b91b9383aea8b8d6808d97f2e7.nq.gz
    ├── 0fc1e6e303de20a8821d2e9a9fd83bafae91547b.nq.gz
    ├── 101bf10d0ed6f24f3bfc3ed5177342c692807f04.nq.gz
    ├── 10369aef9674a07826865dcc9c1c5d013743f5ce.nq.gz
    ├── 1041d7dacb641cc525fc421ca965ca3894ecbb30.nq.gz
    ├── 10a1ce83e5acf465e4f6f0736261683457972eb1.nq.gz
    ├── 10d7c8e0b3c40cf1806eaec227435bd97116b55e.nq.gz
    ├── 10fe326039b0fd1d9aad4c8f3fd0078b3bd6c57d.nq.gz
    ├── 11005bed671691b5e41492c25bda75c17c9addba.nq.gz
    ├── 11169072e9e61df780d61a7cb5ea9658e66cc548.nq.gz
    ├── 112ab3bac3b158be587962a4e941544ae28306d7.nq.gz
    ├── 113beb4d6997fb75251d8118b5c5174a795b85a7.nq.gz
    ├── 114acc5835f399db004adc6480ef4bfec7db9b24.nq.gz
    ├── 1157d620c0b70775fd591488c92c508b11e51d98.nq.gz
    ├── 115f070b069da77b302754eac476f5ff29188699.nq.gz
    ├── 122119a8e6aea556d5dff6d73df203a2e47b3293.nq.gz
    ├── 122bc5b80995e5f003e7ceb86555cd0468bd6752.nq.gz
    ├── 123a25eb0d6b2449fa698e64ad3bb84be2b7fbed.nq.gz
    ├── 12577c820247c06003363b76c00475960c83b6d1.nq.gz
    ├── 12691250701b3f3ae801432ed415d0eedcafc28b.nq.gz
    ├── 126feb7e763659479847f68190c2486edb6f025b.nq.gz
    ├── 1293e6745626725ed4449a1e4130c78c566ad68d.nq.gz
    ├── 12eda73da13300356584abd2fe4d42b657eca763.nq.gz
    ├── 12fa091507ba423b6073c52118fe80f1683c6676.nq.gz
    ├── 131c326f6144844219012b4416c956b69466e6f8.nq.gz
    ├── 132f9731ed11d313e138f477327a366a5794ce3c.nq.gz
    ├── 135214ecf8dc131c969ba5252e5bc68cdede912a.nq.gz
    ├── 1383b2f2b2ca0b8e1d8be3fd315e1f4a94277edc.nq.gz
    ├── 13f21114a37810235e4570c6ea217f83d805f43e.nq.gz
    ├── 1409629c5b3249048dc741fc447b4c8369f89bf3.nq.gz
    ├── 14636d9329b21b88e0d44a5a21218e346aa1650b.nq.gz
    ├── 147434a1b9a8a70b9dfd4ae87fc7e59519dbb3f7.nq.gz
    ├── 14bce92bde0623eb8dafe9e36867d1924a0a2052.nq.gz
    ├── 14d7ba415984cc85b950b9f19e30c30dc05831b2.nq.gz
    ├── 14f5441cfe499fddc0097920f10275ff1aa0d050.nq.gz
    ├── 15133d49e8319c0fc0120345fccaa867acdc610b.nq.gz
    ├── 153adc80988a02045ae7164325d3a829a5a5eec6.nq.gz
    ├── 156ec9fcdd41710919f69414f9a28735a9901974.nq.gz
    ├── 158177998a127b050e67fd6fe6321b3375f4272c.nq.gz
    ├── 15862414966b53440ad3ba3939e70f9b5080ed81.nq.gz
    ├── 15990f4ffc323603bfddb7c3e4cd08d7c8ece7a2.nq.gz
    ├── 15b99d2eb2389677735fa52b9dc74150c9656b2e.nq.gz
    ├── 164ab87892869a9bbd62678489fa9e20cf4c6a47.nq.gz
    ├── 164d68ec2e8b273e5dc3261f9ebf1faf62edfc1f.nq.gz
    ├── 16993a2dfe26b18168e4574098bb1ba54f579ef7.nq.gz
    ├── 16c241a42e02d69a44e29b5288afb73a44c832fe.nq.gz
    ├── 172cbf393fb116841500e416867f30cee3450056.nq.gz
    ├── 173ebe8d0fb6d4daaf42af606ff2994465708c81.nq.gz
    ├── 176b901dac4c01b42ae1e89645edbc6c6cd9d653.nq.gz
    ├── 17cc531af1613e5b466baa07f3a3ff1eb8e7a401.nq.gz
    ├── 1802cd2de4b3d426a18fe38c38db28507b10c68b.nq.gz
    ├── 1808da451fd9aae2dafee9b05f9b1c61b63ebc40.nq.gz
    ├── 18110944b8a4c892e1038406fcdd40c3fbbe89c0.nq.gz
    ├── 181814dc8c41137ee12163c48c00ca3619cdf878.nq.gz
    ├── 1835e3dbb0798fc0dd6af8967a7ab2a11be383dd.nq.gz
    ├── 187a16575e7706768fbb13fe314d8c8c3381480a.nq.gz
    ├── 188204da669b61833c2dba420f4350784acd3783.nq.gz
    ├── 189e0edfb5f311f5b2e06ed6fa8ca92a6b7d8d8c.nq.gz
    ├── 18a955ca0b80d767dac01e0a765482da1021eec1.nq.gz
    ├── 18c11024fddce8aa8f958d541a72d31100120386.nq.gz
    ├── 18db1f0729e87eeaf864f42cdc8f5e9bf845a0e3.nq.gz
    ├── 19902786a328a87a1677aecc513cfd345e8c62fe.nq.gz
    ├── 19b478d09ee43b25cfd1818f6c9d451336bd30c0.nq.gz
    ├── 19da5dd0022e475dd74433ecc44281b085506933.nq.gz
    ├── 1a63b8a88e1a15b609353e8e80af5b02826ba116.nq.gz
    ├── 1a8f3e86c2ae56d5a2382b0eec2956d2595552ab.nq.gz
    ├── 1ab698271cdd0cb706d624b60bdafbef302ddb28.nq.gz
    ├── 1aca6232b348962cecb031407c2b37692836efac.nq.gz
    ├── 1aeac3e48b258718d4f354c373862dc556a7739d.nq.gz
    ├── 1b2e2e3d1df078375ff2e2dead6b63dba48f5e3b.nq.gz
    ├── 1b35c97930d28eeb41f32aee3bde6b907eab80a9.nq.gz
    ├── 1b69d7279a5ba812588d826d3f5167207c2b09c7.nq.gz
    ├── 1b871edb799c5ea385b53ef7a0d712d93aec3f71.nq.gz
    ├── 1b91f29676a9cf8133ae171e6d26d3a97d2dbd7c.nq.gz
    ├── 1b9e30190d7618889f4d61868e7074a1556d543f.nq.gz
    ├── 1bf589aabbc8e3d3dc16a8a6f390c4f9dc0637d2.nq.gz
    ├── 1c3fe6a1716cada5a8945636e632eba08a007291.nq.gz
    ├── 1c6f6410379fa740e984db81b773898f8772ef2f.nq.gz
    ├── 1cb6e2f178af5455ac53ac518e4fdb34f1c416d4.nq.gz
    ├── 1cda07128837d85708c5da0e70095ec4c248b8c9.nq.gz
    ├── 1ceeb4035094535e9653650e9b743ca99c52fe7a.nq.gz
    ├── 1cfeeea3730bbfbe3fa25fc9c0b4282772d732c4.nq.gz
    ├── 1d3f5158cc84b11f76f13fae3f38c183cc4e8bb3.nq.gz
    ├── 1d4beab87044d5b164cf6ce9a4558e61b509e8a5.nq.gz
    ├── 1d5505ca5a6500ff8ca1898fbb39dcd30ab9fe96.nq.gz
    ├── 1dbba00ab72ff16c719923d0727ee5844a48a200.nq.gz
    ├── 1de3be6687215dbf17befb0779a1d4f821b5013d.nq.gz
    ├── 1e356dee0703e6e534ffb2fcf9ecc4678a129c90.nq.gz
    ├── 1e3e50445b34c6fb4e0fe99394e6aecee616fb2a.nq.gz
    ├── 1e57a563dee80c6d7d6890e6b6952349e3d88347.nq.gz
    ├── 1e929c3c79848859ddbd804de6a938e979e088e9.nq.gz
    ├── 1eab5cbc65bac2be28b3ab45bbb79a9eb675b69b.nq.gz
    ├── 1ecb89b7ff5fd509c8c74c5f58433f51e2fe2c9d.nq.gz
    └── 1f1c42b22b6e0285a0a8b0ad8e7590b7360a317f.nq.gz

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
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[block/proto-fleet](https://github.com/block/proto-fleet)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
