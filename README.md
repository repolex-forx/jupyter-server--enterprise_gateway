# Repolex Knowledge Graph of jupyter-server/enterprise_gateway

RDF knowledge graph data for [jupyter-server/enterprise_gateway](https://github.com/jupyter-server/enterprise_gateway), parsed by [repolex](https://repolex.ai).

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
rlex download jupyter-server/enterprise_gateway
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 880ab92b9a9124363a10acafd82daa42ecf402e1
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 880ab92b9a9124363a10acafd82daa42ecf402e1
│           └── chunk-001.nq.gz
└── blob
    ├── 00ab59528b8827cdfcf70d84d8320603665463e7.nq.gz
    ├── 00be1fccc039c98c504f8c500e79584045aeb293.nq.gz
    ├── 015dfb82cb04e59c0731216e60e04028255bb3c7.nq.gz
    ├── 01ad618d4137b662aedde03b88ec025b5d91f596.nq.gz
    ├── 02077d1fdd78dc0c9bae1ca02487592fae09a373.nq.gz
    ├── 02f5a3477980ddcfc14a3475a5de2e73e4caf5dd.nq.gz
    ├── 03040562cd06c8fbd9f40c4a8686c9b73aef0468.nq.gz
    ├── 0396bd60471459710d0673a3287c9fcbb85f0a34.nq.gz
    ├── 07e18822bdfb4b6d74af08530f3d42a98a030c93.nq.gz
    ├── 08ca808fcdf865a707d57ff6e36e6b88570744c9.nq.gz
    ├── 0b3ddeffe8e7a33158aaaf83ec09a278605ab640.nq.gz
    ├── 0b440382f61f0bb1683e5b15c2a00e4e398f9980.nq.gz
    ├── 0c3e5abb0b8e77655cec6ec020cebbccf5158690.nq.gz
    ├── 0c90eb5672b04fc66edcc99f003e15fc638e279c.nq.gz
    ├── 0cfd61d4a50815cc3908cda5aec1426f16a1baaf.nq.gz
    ├── 0d93be38e6539d9b3162600328e7849275269ca8.nq.gz
    ├── 0dad44510056b91bd566c2ba11fd346769c932d9.nq.gz
    ├── 0e78da600d6462135d4e76b0591c576b68cc4a49.nq.gz
    ├── 100ae568ed47c9c45f3ede317857c018660402dd.nq.gz
    ├── 10e85f41d551d420ed5cb9814dd50db2e15212b3.nq.gz
    ├── 110289f2f4b5260ce04dd035408961f1e4f2785b.nq.gz
    ├── 113a5061fc3d996751c8bd56143cb8d97aa02741.nq.gz
    ├── 114b5e37e0a7a4e144448f8eea2f7c22fb14be65.nq.gz
    ├── 1174bc98c425ee93a7e0a26d79659f1d58fac0ad.nq.gz
    ├── 11a0abac5892bb9e09db581dc2dd66a1c726e3da.nq.gz
    ├── 128cc958ea4a56a5d4c271de99dfda9be54eafab.nq.gz
    ├── 12e88e9dc3dbfa27cc12de47fb267725579963c4.nq.gz
    ├── 139c62e671dec059619530b7faabf515c39e6ad8.nq.gz
    ├── 1413fc609ab6f21774de0cb7e01360095584f65b.nq.gz
    ├── 14ac149dac820e31ea513aad89ee5b23984ec83c.nq.gz
    ├── 14f19053ab2a56c4734f3cefff3f455f12eb2343.nq.gz
    ├── 1557e4df1882bce899aacf9548b492b22f843e09.nq.gz
    ├── 16702a9f022a301c3098122d2dd1e4f5a8595679.nq.gz
    ├── 171c584dd8303f5ce4b0257ef49280016182f212.nq.gz
    ├── 174372db782e210067329f58acd2f6c82b09b002.nq.gz
    ├── 1780b7063fed7565f2d2ba6c3b59d9e2fafa7779.nq.gz
    ├── 178caf68d5a6c583431ec8612f5a4683b4c3e21d.nq.gz
    ├── 187805af66929715b59e8d408c88b0542c85d608.nq.gz
    ├── 189618f84aae50e75e1f39ae67331f3b28feace7.nq.gz
    ├── 18f2d223b86021eb86e0d02384642bd29f7b4c6f.nq.gz
    ├── 19314105d44c95c226d8b1ed46c6ffad49737c6e.nq.gz
    ├── 194488363cb6ebf1576fccacfd82b49ce7925b55.nq.gz
    ├── 19f568c3f9a0873ebc435f5203db45a688a04e31.nq.gz
    ├── 1a3690eac13bfb5a40e54f57815ec35b9d4b0f20.nq.gz
    ├── 1b25c83233cc53edbf0fc3a6f547c3ea7cbeb987.nq.gz
    ├── 1b7234ca214bdbe3c7d361f6a701ab2f7e16a3fb.nq.gz
    ├── 1c7be2fc1e8aeae89d3eed8e2c8f4dadd380a114.nq.gz
    ├── 1e350d8cf101146e874740ffaec3cca741106e2c.nq.gz
    ├── 1eca51a54c7ce074f547d8262a6766c324d532a8.nq.gz
    ├── 1f45c63d154692051135ff84c22d9be73542d9a7.nq.gz
    ├── 1f8336e6c01559ffa73b650ac54b02ff1e45dda7.nq.gz
    ├── 201047c154edc5e66c158306d561f29fd71b5dd0.nq.gz
    ├── 209ef10b1dc814d12abe14ea384fd54f36421c4b.nq.gz
    ├── 21a5c405f7a6c0648ebcb69f5eba597ad94d3627.nq.gz
    ├── 21c7ec5b1d4aaf705a1c838dfaad8c67cdfbdd31.nq.gz
    ├── 2355a07af85a323a7f969dc0ca5b9a74a4752d79.nq.gz
    ├── 248b8aea5700dd15b1eda503135e0c838382ed6c.nq.gz
    ├── 264fad331aee17f88f08acc24e4f234b7b6632dc.nq.gz
    ├── 270533aa1622a42bf556214dd39157050d70467b.nq.gz
    ├── 27557952ee041fc529a0b6972143894c20d41cf8.nq.gz
    ├── 27af6b680994f93bd65beda2135321805191bfe2.nq.gz
    ├── 291ce0f556183f47cfcd890ab9adab5c7fda2ab9.nq.gz
    ├── 29a7e9c9ec21691151390f8b90daac88dc0ac4cb.nq.gz
    ├── 2a388617f491a63c0c44d5773b63c25d03527060.nq.gz
    ├── 2a52b2af1047b1669af04052591681748c2d4778.nq.gz
    ├── 2a9783ff1e4d8171b19f15209cf77181d2ff4cce.nq.gz
    ├── 2ae8611a131e9c5d93636644ce02f2b1d6f51d02.nq.gz
    ├── 2ca755c677ed84ff4140d0910642dee89733754e.nq.gz
    ├── 2d3279be0fc7c9217ebb15aa498c5416507ac732.nq.gz
    ├── 2dcdc220722c85a5db777797657b94c50d98aff7.nq.gz
    ├── 2e2e167ab370fa781426ba1dc23bbfbb1a253c30.nq.gz
    ├── 2f51e4bb48d67639fb54837d87487d6d7c536b17.nq.gz
    ├── 300a6fbd0aff59a00acdb557812afbdbe1578f52.nq.gz
    ├── 30584f1cb55a7cf6ed313cc6f307d076eaa7debf.nq.gz
    ├── 30aee544d34fbd421ca160d22039b3bb700ca885.nq.gz
    ├── 32824866f12b850a61629188882cad96acd0a022.nq.gz
    ├── 3311d585145b1cc1b9581e914acbb32d8542b4f5.nq.gz
    ├── 33b2bb80055cc480e797de704925acaba4ba7d7d.nq.gz
    ├── 3402dd658f08014d01a48971819965996eb2efa6.nq.gz
    ├── 35e2148c61f64f1b8eff2eda5d807042bcca32f9.nq.gz
    ├── 362a054d66a06c8b833c5882d3ff60f54227837f.nq.gz
    ├── 36e09d2b112a1697d5fd3056fd306e8df99a9aa3.nq.gz
    ├── 380aaefe0d73d20acf580401b9b94d6f29697e2c.nq.gz
    ├── 3853fb09e50a3497366a332f1766fb9808097f7c.nq.gz
    ├── 388ac6b0cd6738cf09470583903708d28809762f.nq.gz
    ├── 38d5de9a40ba73156edc24eff02529312cbb855f.nq.gz
    ├── 3931b1699b55f2e07a78e3749ceacf0c9c1f16d9.nq.gz
    ├── 39c44ae4e53b6ae9e8232271ba49b0d77a7ef064.nq.gz
    ├── 3a5d08788c0d5ba6da677e99216d34d0015861dd.nq.gz
    ├── 3a62926eb6896e0df7907ab83b35dad09bbefb23.nq.gz
    ├── 3b83d6a46e6985c07ef585f60b565db48609976c.nq.gz
    ├── 3b9250f2595def1227767fe83c9745503e4f1e8a.nq.gz
    ├── 3dd3f0184f1128bf60127e68764570e5cf967b63.nq.gz
    ├── 3edc18762a4f47e36fd5a7bf36c650b21eb49846.nq.gz
    ├── 3ee61f1f7c301d8390c237cbd35190e37d93cb1c.nq.gz
    ├── 405adfbca77fab6b6f99ace170e8e08395bf8ae4.nq.gz
    ├── 4139b6fc3bb3c3243abcb8c1b72d4db424e86512.nq.gz
    ├── 41e9a8184aa287c5970cc8415e3c5a6310dc9f79.nq.gz
    ├── 42c0ace5693b9a1797edd37afd87eb7172b58b0d.nq.gz
    ├── 42d69573d78aaa18a2996e1491564159d64b51a8.nq.gz
    ├── 46481f392f8dc6c0247cd4f026c28a56011e4d51.nq.gz
    ├── 48dfc839d90878287fb5530d1f52ce20b2fe8917.nq.gz
    ├── 4b3da0ed14f9ebaf4469b7cf5801a0d640c38df1.nq.gz
    ├── 4cf93eca6ecd9c32c94216db5876eaa7f38ee634.nq.gz
    ├── 4e4f5fda8cb761b4ac605d785290947d1fc32490.nq.gz
    ├── 4ea7c812f0b32c54c8a5e16aa38c60d8ecee54c5.nq.gz
    ├── 4ed8b3b1be449caa632bdfccf624856693680b08.nq.gz
    ├── 4ee1c49f9094126965a22de8dd307bbd25dbb47f.nq.gz
    ├── 500530ccc55505b5bbd776a7f48f777e531555db.nq.gz
    ├── 51a70dbaf31a8cbd9c4e0d1e8c9678ebae65dfe0.nq.gz
    ├── 535f9d32bd4d9004aadf4677a1085ddfd0888c09.nq.gz
    ├── 54f24b5caa88bba9bf8b4435b8514f825f0bd362.nq.gz
    ├── 55fd2067209b7ad33777dc7aeef7526b8caa2e07.nq.gz
    ├── 57362b77930adaedaf10851805d696eba5cf0b03.nq.gz
    ├── 57b1deb4e7dc567f06e26e5e356e6d3ec16042f3.nq.gz
    ├── 58bef1d3b30b0108f954e8601cf3f2215575ac07.nq.gz
    ├── 596781bfd77f57a527a98d0677ea185fce6cc8f6.nq.gz
    ├── 59e482ae78f6e4518dbb2c24065bc9c6739e459b.nq.gz
    ├── 5a2db9d5612d028a6cc3d448262d3dee5f70f6a0.nq.gz
    ├── 5a6da397090a6febd078f9cb28347b9b8bd994ad.nq.gz
    ├── 5b4de94b21c4365f2031b398083846f436aab9d4.nq.gz
    ├── 5b603735993389714705acfc6d082bc865b2cbae.nq.gz
    ├── 5c8be927ea0cf5340cdafd31257395861e43a565.nq.gz
    ├── 5d317d950547c05920412ae595874a09105095a9.nq.gz
    ├── 60cf62729b1339c6ea4b4069ebef53b21fbd13c0.nq.gz
    ├── 62947a695f3ce68ab994a3f206bb59122e0bf137.nq.gz
    ├── 629ab95f499476d9a32f2d4db87549bd4e58bb6a.nq.gz
    ├── 62f2beabdd96b0cf09137f3fd088fc86722b6be1.nq.gz
    ├── 63faf2527beb9075b2214a256e88161e6724a81f.nq.gz
    ├── 64539b54c3751a6d9adb44c8e3a45ba5a73b77f0.nq.gz
    ├── 650ea5bf133776cddc65d76a14e7fcaf9d193836.nq.gz
    ├── 653e54f25ec923a743a31e3240d33d44bbe91979.nq.gz
    ├── 659b2763eb07858a4104db26203a9efe3d585af6.nq.gz
    ├── 65d0e4fc9589e25ea5b5f12a6e8240a747a38784.nq.gz
    ├── 668cb28f190afa630bade2e50ab4dc6cb2795873.nq.gz
    ├── 66ad52a5ba052ced428dcc7ec7016bc25438a2ca.nq.gz
    ├── 67286c8eab00f363b1be5ec11b58a2c0fd9fe972.nq.gz
    ├── 672f045eae8eea823057eb6526e49115542ed6b9.nq.gz
    ├── 6831b5d1bf0efe96e0b57c37f9f23dd300002536.nq.gz
    ├── 69eb0069b065bc009356f13066b9a35d98e7e9e3.nq.gz
    ├── 69fa4631ce389333e45851f1a765e6524e347fe1.nq.gz
    ├── 6b7f16093120f1f2245c16677687f30f5b95b7b7.nq.gz
    ├── 6bcf1b612d498290745161aa2d1821af8c610e55.nq.gz
    ├── 6c43f7f0243d46fb706fc39665b3ffa52ea16ae6.nq.gz
    ├── 6d91e8d7c992bdf6eb9bc0afa601ad3d4cff01bb.nq.gz
    ├── 6da52a96178ae4e25218cf74d65188c396ed68ec.nq.gz
    ├── 6ec46bb3cfc8f5cc71d55e621db0e440dd9f704d.nq.gz
    ├── 6f3d64c9557e40c8f3a66c3b6ed2d02b75e171dd.nq.gz
    ├── 7040bcd6290eccac2ee38f844ee5a646776e498c.nq.gz
    ├── 704c884e21d4271dfc8294e7d35078620e34fe48.nq.gz
    ├── 7149c15a6d6c2eeea7dc16ec424d9161a3bb622e.nq.gz
    ├── 725198872db62063877a800ecb79ae7f5a4b5a5a.nq.gz
    ├── 73c2694b3d558b73cc37b9445be4d081589fc5d5.nq.gz
    ├── 73e7c443b0df275cca947c48f14a2a6342420c3f.nq.gz
    ├── 74674060684e1910e6ffe576b0065dfbf6fae235.nq.gz
    ├── 756f00eff6eb69176a07ac53758d0f21b60e61c8.nq.gz
    ├── 76d91b54f914a190de9fa44e68cc6a3f33438e0b.nq.gz
    ├── 76f73fde61b20e6f2fd5d8d4f256b5a3835ee713.nq.gz
    ├── 78fce3f55be255a272f033c342ffed1d4a9d39e4.nq.gz
    ├── 7a6f069b1ea71eb7336c8be1ea3f9bb5594d270a.nq.gz
    ├── 7aebfeba649df5d7f2608c7ef04a91e3fd16eb14.nq.gz
    ├── 7cdede4d71e9666bc70253e69e0c0ad7e97df276.nq.gz
    ├── 7d1e4d54d6c293333eb638aa56feba7b62e15564.nq.gz
    ├── 7ed972645f0290a3d925c90f5b3e586d0c432633.nq.gz
    ├── 7fdc51f34abbfbaeff2085df124e900cc521a22e.nq.gz
    ├── 812471e8447114ae52b9ee1f6f37a37bb208d16a.nq.gz
    ├── 81c77afc81352e785033aeb242fc0a977f0f802e.nq.gz
    ├── 81fb0d2b9492f60ec38b2f559c79277306e77784.nq.gz
    ├── 828e9b05fd4c749ff2f4885e23880533bead640f.nq.gz
    ├── 8299cfbc018d9cf7d7202cae11344577a93463cc.nq.gz
    ├── 82c525ea4147fc370639a11cafac22e4080b725d.nq.gz
    ├── 86ac97193c80465b694a80d2477575d4a8bebaee.nq.gz
    ├── 88f9a4f1719cc5bd4a5ac738a0b675629c443831.nq.gz
    ├── 891f869be0384c703190ed2fd0fe6f0fbbda0d20.nq.gz
    ├── 8a020dbfff7822bf57c7217eafdaa4884b8aa943.nq.gz
    ├── 8a6240371fcd7fcbca559131b20ee864ccae2aa2.nq.gz
    ├── 8ac11d2c211cb9b7938e3ef9189b996e56df9fd7.nq.gz
    ├── 8b280b98fa2fa261aa4b0f8fd061f772073ef83e.nq.gz
    ├── 8c86998ff2bd6e4f77b205d5653218c17f3f125c.nq.gz
    ├── 8e4a16c5157057fc8da8039de539eb7b3f728e64.nq.gz
    ├── 8e9e65c23dcd8ed32df9c962c7522e282861813f.nq.gz
    ├── 9051a6fe8a4ca6a21f588211223603f319c69520.nq.gz
    ├── 9140caf19283017fade0d3fc3ceae42f6029c920.nq.gz
    ├── 91781f4f76c2825d89ab724528fa813a6e1cdaf0.nq.gz
    ├── 917b76c8e34fc33095af8058cb8c3c92f2c4400f.nq.gz
    ├── 9211e66597a0345e3faf1319b5c5f11c4e4e9c91.nq.gz
    ├── 93141aecbd8a5ff6c641aa4bd216e349398e4606.nq.gz
    ├── 93fe363d7dd0fb167e7d448f2ed5735a677fcfda.nq.gz
    ├── 9497227dfa32101707d43005cd687073d0844c0b.nq.gz
    ├── 972148ffce3df4b402e9035920bff3f9e1aaffa7.nq.gz
    ├── 97ba9cbcbf69c1e2c244b1ccb54c30687c06c730.nq.gz
    ├── 9c5c7d429743f8cac25fcfa62b7415856b6e9ee4.nq.gz
    ├── 9cc3235f8412d2f4b31f659e8e0302e3780c4c08.nq.gz
    ├── 9d3fdf3a0b477ffa6e9c1378bf7f0636c1f43c1e.nq.gz
    ├── 9d988a1da425de0b9a3b680edf84465b707cd89c.nq.gz
    ├── 9e571ab0b1e7b31fc30084752eb2cb9c83878890.nq.gz
    ├── 9e612858f802245ddcbf59788a0db942224bab35.nq.gz
    └── a2f2190e56a5393ef292898aafcac7b4cf5e9fc6.nq.gz

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

[jupyter-server/enterprise_gateway](https://github.com/jupyter-server/enterprise_gateway)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
