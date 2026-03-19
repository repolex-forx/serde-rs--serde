# Repolex Knowledge Graph of serde-rs/serde

RDF knowledge graph data for [serde-rs/serde](https://github.com/serde-rs/serde), parsed by [repolex](https://repolex.ai).

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
lexq download serde-rs/serde
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 1f65ce75ec9229a0088a9fbd32b4834ca8701dab.nq.gz
│   │   ├── 206e19edb40a8e3df29fc8d3862d92b02176f3dc.nq.gz
│   │   ├── 5d22be26d81d2661ad1d4980ccdf5937013492a8.nq.gz
│   │   ├── 60ab4942261ff8d52d9b46048a49e4279b4b4079.nq.gz
│   │   ├── 7511eeae7b95f2b4ba36ecb97e3a0b48fe346831.nq.gz
│   │   ├── 78e74886be410b9ef0709f5ef11a13f875e6ef0a.nq.gz
│   │   ├── a866b336f14aa57a07f0d0be9f8762746e64ecb4.nq.gz
│   │   ├── ae79451b7adfc530b3a997a1e0180b4310d485da.nq.gz
│   │   └── b6965ecde89bb28576bcaa0bd8b271d24a736570.nq.gz
│   ├── dataflow
│   │   ├── 1f65ce75ec9229a0088a9fbd32b4834ca8701dab.nq.gz
│   │   ├── 206e19edb40a8e3df29fc8d3862d92b02176f3dc.nq.gz
│   │   ├── 5d22be26d81d2661ad1d4980ccdf5937013492a8.nq.gz
│   │   ├── 60ab4942261ff8d52d9b46048a49e4279b4b4079.nq.gz
│   │   ├── 7511eeae7b95f2b4ba36ecb97e3a0b48fe346831.nq.gz
│   │   ├── 78e74886be410b9ef0709f5ef11a13f875e6ef0a.nq.gz
│   │   ├── a866b336f14aa57a07f0d0be9f8762746e64ecb4.nq.gz
│   │   ├── ae79451b7adfc530b3a997a1e0180b4310d485da.nq.gz
│   │   └── b6965ecde89bb28576bcaa0bd8b271d24a736570.nq.gz
│   ├── lsp
│   │   ├── 1f65ce75ec9229a0088a9fbd32b4834ca8701dab.nq.gz
│   │   ├── 206e19edb40a8e3df29fc8d3862d92b02176f3dc.nq.gz
│   │   ├── 5d22be26d81d2661ad1d4980ccdf5937013492a8.nq.gz
│   │   ├── 60ab4942261ff8d52d9b46048a49e4279b4b4079.nq.gz
│   │   ├── 7511eeae7b95f2b4ba36ecb97e3a0b48fe346831.nq.gz
│   │   ├── 78e74886be410b9ef0709f5ef11a13f875e6ef0a.nq.gz
│   │   ├── a866b336f14aa57a07f0d0be9f8762746e64ecb4.nq.gz
│   │   ├── ae79451b7adfc530b3a997a1e0180b4310d485da.nq.gz
│   │   └── b6965ecde89bb28576bcaa0bd8b271d24a736570.nq.gz
│   └── repolex
│       ├── 1f65ce75ec9229a0088a9fbd32b4834ca8701dab.nq.gz
│       ├── 206e19edb40a8e3df29fc8d3862d92b02176f3dc.nq.gz
│       ├── 5d22be26d81d2661ad1d4980ccdf5937013492a8.nq.gz
│       ├── 60ab4942261ff8d52d9b46048a49e4279b4b4079.nq.gz
│       ├── 7511eeae7b95f2b4ba36ecb97e3a0b48fe346831.nq.gz
│       ├── 78e74886be410b9ef0709f5ef11a13f875e6ef0a.nq.gz
│       ├── a866b336f14aa57a07f0d0be9f8762746e64ecb4.nq.gz
│       ├── ae79451b7adfc530b3a997a1e0180b4310d485da.nq.gz
│       └── b6965ecde89bb28576bcaa0bd8b271d24a736570.nq.gz
└── blob
    ├── 004bc341b29aeb8b44dbf5a288378ef34b94a90c.nq.gz
    ├── 00b07107e0da9890cad345aeb527fb31a146e9a2.nq.gz
    ├── 00c21892af3debfe9c915526868c05b49f7458f3.nq.gz
    ├── 00f32d68557a8b80c7c7d6779bae117122f38427.nq.gz
    ├── 0127feaa5a6c66dd539749a1f97afff5dbe3abb9.nq.gz
    ├── 016a0a022d6d65a7a4ab28b3d02e3d58fa5d7414.nq.gz
    ├── 024e62fb0beb6ec282abff2dc8d8cb2fcb2d5377.nq.gz
    ├── 027b665d671b69ecc5ddcac4706cba1d43e54058.nq.gz
    ├── 0297c8ac08c7149e19a0c864fd6a3f7211be9e64.nq.gz
    ├── 02c970e4b4945d6ed1a1d7b73f5b9214543d85c8.nq.gz
    ├── 0367df8b68c50503dda650843285badba3548967.nq.gz
    ├── 03dcdaa9d5cb8b2179c746c4da71a50d3da24265.nq.gz
    ├── 04bb8349deb48d6b38c1b29f3c48345b91ff1109.nq.gz
    ├── 04c69bdba26e471ee30693771f82e89f186a7e19.nq.gz
    ├── 05082363c6f9360cd1cda67a3e5e1a02b639d43e.nq.gz
    ├── 05bd0df7564d6595bc0a91951889d2133e667666.nq.gz
    ├── 061b4eb86446fffc85b9baf53c4fa44407928438.nq.gz
    ├── 06341b13ec592e1cb9c07c81eb5ee7cfbf2b1d75.nq.gz
    ├── 069d4f262b300fc609bb9b4c2e200a5fc8b191a3.nq.gz
    ├── 077fdccf1e81bcddc804fa4884cc0917236adc6a.nq.gz
    ├── 080e314e7fe103cbc353b986939372544c381e6e.nq.gz
    ├── 08292a15189430deb60e1042a7822d4a5c42ff74.nq.gz
    ├── 08337c0b30a501151df8bb772871be6cbaa210b6.nq.gz
    ├── 08953727b450c426e89c76283fd263905ff39d25.nq.gz
    ├── 08c9b1f9d2b5f74eecda62d7dbbdfae997e3a776.nq.gz
    ├── 08dd5d3cc0615f888215cb5e924459cb09e8f292.nq.gz
    ├── 08e89ee187b15c96138c823815dfc9c81fab2120.nq.gz
    ├── 08ee266635e6c4ce25bd1847d7c91e0e252f8d6e.nq.gz
    ├── 092d66a60befd4fb2fac74b37c93584127c759a1.nq.gz
    ├── 092f1a1fb62019fa280d9f9f94d332d14d7684bb.nq.gz
    ├── 0a50691ebdf67725a9b0b2eadf2811707dff76f6.nq.gz
    ├── 0a83a131225bcd7db6c21818a21764a65dc97a4c.nq.gz
    ├── 0a8804ab8d8f3f922556e8324dc7479a30a89e1c.nq.gz
    ├── 0afaf97f74468be4c10c11bf75f594ef383e8fdb.nq.gz
    ├── 0b2ebf7273fe1e7e6d39db1108a0d991446ace1c.nq.gz
    ├── 0bcdbc39eda0f3e093d5021a947810d9cdc91c02.nq.gz
    ├── 0bf6dd13159498623ae0818ec45cf743eb388fef.nq.gz
    ├── 0bffa22d4fd4dbce767b7d2c904e940cc02f4c51.nq.gz
    ├── 0c07c7af1570f7a3394258c50bacb54edf1d82f0.nq.gz
    ├── 0d15ef4db5cf95337f96d633882602773ad18aaf.nq.gz
    ├── 0ddf641a67b96bc2678392cbf2663c2f1fa45426.nq.gz
    ├── 0deaecb5b9ed10fca3499e70dd4a609d97b70d11.nq.gz
    ├── 0e286a91e061f665ea4fb462781ecdd3ec878050.nq.gz
    ├── 0e53d1a3f002d2006762b336c8c2cbde73c1a59a.nq.gz
    ├── 0e58ed4193b2d25492627f5c1c10aa5c21d78d5c.nq.gz
    ├── 0f37f5fa2df23b3fcc90bc90df2f67d8db1e2b01.nq.gz
    ├── 0f4cfa5997525b9ae6d36aa678e25181654178a1.nq.gz
    ├── 102a272b8efc775aaea94e30f0b79b6fd34f2821.nq.gz
    ├── 11a2eb2a040c5d72a937c3d9290dc2eacd8dfeaf.nq.gz
    ├── 11a8e9a67eaf77d5b1719cec7fcfc7e681aef308.nq.gz
    ├── 1203fed49e2345b11387c1bb995f83a1f576582c.nq.gz
    ├── 121dcd3db9a365bafe861646a055bdb41e80a700.nq.gz
    ├── 125b7262dcff9e10c877261c78d40a20301576b5.nq.gz
    ├── 125fe2d004d8b211962e5511d2a3a409d84f0ec8.nq.gz
    ├── 14e518605a135c9901bca65787b5bb7e3b781cf1.nq.gz
    ├── 16bdbb8eda48b82caf665d0fd6ebb9493ccf0de2.nq.gz
    ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
    ├── 181c4c616fbe94c6aec4330d099cb569287793dd.nq.gz
    ├── 18587b9e05a760010175522a60d11afc1b02f835.nq.gz
    ├── 18f155ec9bd5791abed0690759f46b5dd6392908.nq.gz
    ├── 190b862a210dc2b5360e56e1c74b600570023548.nq.gz
    ├── 19296f076071358d0787ff320274d6fec18d9ce6.nq.gz
    ├── 1961ee59e482b843c394ead4670a3be7ed53c17d.nq.gz
    ├── 1a76f67fe349ead9fc79f197c34d1cf0dddea047.nq.gz
    ├── 1a7b2d62007074301de1e0ea1d6979eb83b78ed5.nq.gz
    ├── 1b5ec8b78e237b5c3b3d812a7c0a6589d0f7161d.nq.gz
    ├── 1be136c88aa5989f05bb1feda9b63c50b6b7e6d9.nq.gz
    ├── 1c5e910d73249e6f76c9423d1bb83c7df1ac0c28.nq.gz
    ├── 1c806318486b68a3db8bd8a920b83e549579b2f8.nq.gz
    ├── 1c95e486563837a0a27b5dcdf87b9dfcc3997a5a.nq.gz
    ├── 1d6e205855f4f46e844c678f90773189bd6595df.nq.gz
    ├── 1e69da34499ed556d55f15a4d38dc6f0311c3c75.nq.gz
    ├── 1e8035291cfdca98c2133825178bbab6fce63c62.nq.gz
    ├── 1e869b38e0bedbaed8658d534e2ab4ce8f75f9ec.nq.gz
    ├── 1eac50ecdd104bd88250f6e05ce3fca7e88b805b.nq.gz
    ├── 1f7cf74010f2e1e74e329386b056ee7e3fba3288.nq.gz
    ├── 20bfa4eb886af71985fafbc5c5d0f8b8b425d382.nq.gz
    ├── 20f13dfc599d36afb536839dd215446e7ff917ba.nq.gz
    ├── 210b36b03b4534e30007799719facdf9a6d6bb01.nq.gz
    ├── 2360a1742362b1e0b31e0fd1f00e5246161851eb.nq.gz
    ├── 23b43ac7c45124cf2ad29ff74c3e2f0de799b3c7.nq.gz
    ├── 23e15383b03a1028fc69ab6509449458c427d997.nq.gz
    ├── 24508599f642af4e9639c7078ecd545982345073.nq.gz
    ├── 245ffdecaac38b711d765f392bc1071c42a1570d.nq.gz
    ├── 2473a812eefb5eabff160d15e026e196f2a3d34a.nq.gz
    ├── 24a6bf307724a287aefd5a36e620c7ca9251f88c.nq.gz
    ├── 2518ae68274a9888dd1c18e05d62a6191d3c86b0.nq.gz
    ├── 253be30e7741f6fccf0272c432ab1836cbba7920.nq.gz
    ├── 25705fad5761ff96f439ab62c1ebb0173912b368.nq.gz
    ├── 25cfb4f0babf6bda2e93731eb7ffc7e8468ebbd9.nq.gz
    ├── 27644f450b42b900faf99b4c34b967d87e1ea995.nq.gz
    ├── 276e176bb3761c543ae7eb0262dc2a338a082c64.nq.gz
    ├── 27c212b4d3df5ab3d1e3ea6ba62eea6f5d758015.nq.gz
    ├── 27fbc14667526059203daab16b992e10af972b8b.nq.gz
    ├── 280d427f8ff26c835c43545ac66e50476a47c064.nq.gz
    ├── 2814c5dda9d414a260ccdd073adc0c35cce6f627.nq.gz
    ├── 2845189cbc3c75307ac0f152390dc825105db303.nq.gz
    ├── 28e47d1bc1b53ee62ed3c1f9de50186f750d685f.nq.gz
    ├── 2927aad88fb17d1dcb8ef2ba68bc6f1f6646a7c0.nq.gz
    ├── 2941c164194469f88ec287357c748ae4d69a4e48.nq.gz
    ├── 295481c8e751d5219a13e8cf39007d2c1340e903.nq.gz
    ├── 29570ebd0b49713323c548f36ce61dee57857c32.nq.gz
    ├── 296512ff02f1a5305824e145f9021a7be1367730.nq.gz
    ├── 29668e8c0b123d7b5b4f5552a7dd8140d933ceaa.nq.gz
    ├── 29c229380e67aebb129f4f6309e7cf3737a4b203.nq.gz
    ├── 29f4330d4295964be4d751106c0a174c153bfeab.nq.gz
    ├── 2a8fc00f89f4edd4f8ada8e2f40d4696ada67c48.nq.gz
    ├── 2add149c1ace1b5f3c207ef76cf55a1d77c6670e.nq.gz
    ├── 2b83507b9befa5fc841a04577c067d24a6fa2cd1.nq.gz
    ├── 2bbb2a6ea4be4d4475cb2c5d042eb5e5c58bb31a.nq.gz
    ├── 2bc9a336a97f05ff6b03f357017c8d030da44770.nq.gz
    ├── 2be58104463ab362998b613eee37a77538ceae0b.nq.gz
    ├── 2bf7328da115e0505bac6281ced6f5ff431a69f1.nq.gz
    ├── 2c038ae8d6856c410681df8d5c39e3fc7f05cb68.nq.gz
    ├── 2cc07f0d931ec977ad0812c828187eb73505cfe2.nq.gz
    ├── 2cf75a40196a761e6666bd77358ac11e73be4fc5.nq.gz
    ├── 2d0d69fad4b676055e7d912b90862e17c2ed53f0.nq.gz
    ├── 2dec5e199b24b18c0e0ca73abf7bdf17f0a9beda.nq.gz
    ├── 2def40dc0aa9fef500a52c4701ccb4139a0c5380.nq.gz
    ├── 2e06cccccb49b04c413ce7e97abe8057c2255deb.nq.gz
    ├── 2e0fc86753619d21fb9a7d0317399a28ae7e1213.nq.gz
    ├── 2e80fbaf99b326b97faad6f2d750f78f04afd830.nq.gz
    ├── 2e8bccc6353de2b895dce10e43a3a1e309096fc1.nq.gz
    ├── 2efb786a410672524414c6739d18d023b64a4b5c.nq.gz
    ├── 2f028d3b2d0d2c66f6a68d553aad3bc61bdd6c25.nq.gz
    ├── 2f22cca8496f429605391a339775daed3ce14827.nq.gz
    ├── 2f2af797151fb09fed9d5705d9f354b23bf53863.nq.gz
    ├── 2f904a1fc5139f98231cdb22cad9bfcf7afab92a.nq.gz
    ├── 2f91b52ef1959f996f86a96f45e3b2723b9169b2.nq.gz
    ├── 2fe797a1d5f66260723355ba18602c8e088322f4.nq.gz
    ├── 2ff6521fe3f1a45b72953380afac3d73e5b8c96c.nq.gz
    ├── 31aa79387f27e730e33d871925e152e35e428031.nq.gz
    ├── 31d903eeaf7f003921a58e781f7a3327c4368b72.nq.gz
    ├── 3228799c113ef292abf13c30146e2b1ae1a93230.nq.gz
    ├── 32516303aa232f701bb05e75279af992200cfb3a.nq.gz
    ├── 32bc441509708527032d7b9849c5c68545d19716.nq.gz
    ├── 32c00054438c4374a298915eab835640014d91a3.nq.gz
    ├── 32d46ee883b58d6a383eed06eb98f33aa6530ded.nq.gz
    ├── 335344a2908cde83e0388cd3510d2e15086c474b.nq.gz
    ├── 345731a1ce4d414434d79df39cc0fce48dda4595.nq.gz
    ├── 358f9b22df02c4c3e7d340cf12634e98a1d93ad2.nq.gz
    ├── 37746ae5b9a6a31ee13afb41485e6a5dcc6572ad.nq.gz
    ├── 37df96e6bc11db8fb1c56e5010dc57f43d6450d8.nq.gz
    ├── 38953f5beb1c8112acd97b016ec8aa0d53fe5d70.nq.gz
    ├── 38f597a27607e3d45c589b20bd23391316a81c12.nq.gz
    ├── 3961ae4bc50fb67844f24d18faefdf2b57889c63.nq.gz
    ├── 3971495cdd170d63ecce1ffbac04e3777508444f.nq.gz
    ├── 39d4bdb5acd313c1a92dbeaa1c379aaf0596a315.nq.gz
    ├── 3a07ebc6363787868ab7a06046ba939c72919b79.nq.gz
    ├── 3a1922c0f5916b547ab5d9fd7d0f379f9ea91595.nq.gz
    ├── 3a3a3526099f03149c0d8c23c845ee5d890c3144.nq.gz
    ├── 3a45a9daa2c6a7de642af9650fcd40f986af4527.nq.gz
    ├── 3a5a57483520a456bbc36ef72f49208e986f15b3.nq.gz
    ├── 3abdc1b25e258c5a503a74d6e52b19ef764c5ee0.nq.gz
    ├── 3ac8f0ac39341cb02cdf8b7849fffeb584fc5ff1.nq.gz
    ├── 3c4527dae142f048f4862fcb6304f4c9e8d76c75.nq.gz
    ├── 3c5370b8e003e7c22645a75cf6e26520dc03d425.nq.gz
    ├── 3d4beae651b33f349ef547293637056f77937e71.nq.gz
    ├── 3d5475def127eb1daaeb0a4e991b07a4ee33867d.nq.gz
    ├── 3da197dfedcfda7a2127aea1cf50f3e4a71b44a4.nq.gz
    ├── 3db2c4ed933fc2c097ad0eb20c1be3f813aa0216.nq.gz
    ├── 3e15a0a5b6b8ef717ed247c4335fc4a99a09d6b7.nq.gz
    ├── 3eb4c766c0d83a7dc6615341fdefcd660f522ce3.nq.gz
    └── 3f02a61fc42b7c3380cb391a1b5306d3e76d34d8.nq.gz

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

## Source repository

[serde-rs/serde](https://github.com/serde-rs/serde)

---
*Parsed on 2026-03-19 by [repolex](https://repolex.ai)*
