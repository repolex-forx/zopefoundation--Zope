# Repolex Knowledge Graph of zopefoundation/Zope

RDF knowledge graph data for [zopefoundation/Zope](https://github.com/zopefoundation/Zope), parsed by [repolex](https://repolex.ai).

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
lexq download zopefoundation/Zope
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 358841b27f3e2a06c0632db52c001c78d5f6a554
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   ├── lsp
│   │   └── 358841b27f3e2a06c0632db52c001c78d5f6a554.nq.gz
│   └── repolex
│       └── 358841b27f3e2a06c0632db52c001c78d5f6a554
│           └── chunk-001.nq.gz
└── blob
    ├── 003689b3eb91055607951e6eb27ffce1cc2b20bc.nq.gz
    ├── 003714e96f5854db53350f0ae5b57ecb10f7dfd3.nq.gz
    ├── 003b689909673812818843b9ce7f9811515bb08b.nq.gz
    ├── 005644a177f033c23ef4414d081b3fbb17811fd8.nq.gz
    ├── 00719162c1a255dc1714368098dd98dcd9477198.nq.gz
    ├── 007cf46af4bc064ee6031ed8588abd1cc90361f9.nq.gz
    ├── 008753cd8c61f27d2f420e36d8b6bcac20f6da37.nq.gz
    ├── 00c5ab6d4c9a6cb4b79e6342cbb7ad8e899d0b58.nq.gz
    ├── 00fdd126367960eee12574da833ec9566034be8a.nq.gz
    ├── 0105a4a613435a3bcc53b55b9ddb0a10cb14a0d8.nq.gz
    ├── 0122d2f9bc0e72c478411193a99cf07bdaa2b497.nq.gz
    ├── 0141355a725ecc1138fe65bfd61a06e41b524a48.nq.gz
    ├── 016d82eb65f43daefcf2fe416cbc8effda794a73.nq.gz
    ├── 0196ca22cc7c384eef54bba843164a0139244955.nq.gz
    ├── 019b2e11876576bae63d4d250a9ddb2aa970c32e.nq.gz
    ├── 01b72defceff780ff616120aaebe6c4bee98f5b7.nq.gz
    ├── 01c4e5180b16827fe8bda851bcf0c9e0b76a113c.nq.gz
    ├── 01ee0fa7b84c75cde912076a5ff7b6fe89a9f6e3.nq.gz
    ├── 0214a4da581fc2b39df1f2cfbf52a46f0f6160f7.nq.gz
    ├── 02255d5c3902f9430b151fd498c24e8ba61f530f.nq.gz
    ├── 022af385cb83009335d0879d4c7d96cb0ba0e8c7.nq.gz
    ├── 0247c8ebc63f04471580ed61a14ca420d4478998.nq.gz
    ├── 027150db180029ad77bcd5cd0658e1371896c70b.nq.gz
    ├── 0273c3cc4b1d7937f9b8c5d0baacb08b3ce2c4c4.nq.gz
    ├── 0289c258eb6a4cf0c1eebfcd610f8aa88d070eed.nq.gz
    ├── 028f76ebe0e1ce191c20e8644b37c14e05dd4d2e.nq.gz
    ├── 02995a3c24a43fd89f31e1027e20fd0880bb3040.nq.gz
    ├── 02d6526b0cd0bfdc6cae0fdc683d4db38a761542.nq.gz
    ├── 02ee264117a8d123c895f98fe6085d0250dd34fa.nq.gz
    ├── 030ba538832246f5afa258983ff783730bba519e.nq.gz
    ├── 033c1dcc46f0cffc8fbc7169e9f1e663026382e8.nq.gz
    ├── 03c67287d5ceecd7c79121f9754f98ffa2267355.nq.gz
    ├── 03d5bf0a920fe70d92d87b74b6fb6e025d6b88a4.nq.gz
    ├── 03fafac1016cf8d297898e878720fe1adf6b38d8.nq.gz
    ├── 041831e7e07c7070232826f61ebbd131fd20a26f.nq.gz
    ├── 041c28fb39b4960c99e04539a8c15f10d482e2a6.nq.gz
    ├── 042afe885aba2bb3ebc698f38341d412e4a25af5.nq.gz
    ├── 043347df6ee9890f6a4f0a4f60e34048efb837b6.nq.gz
    ├── 0449d3b090e42d2ee4ba04f2a2085f144ab670ef.nq.gz
    ├── 0482a3c15e14640472ac95c3a91c5cd9256301eb.nq.gz
    ├── 04b53d765788defa8ccd7533616d7c1464112ce9.nq.gz
    ├── 04cfb5b20748ec7f620943c52ec506aba0bf954e.nq.gz
    ├── 0517c5eda488e0dff47ff39e8c7916c9052aa394.nq.gz
    ├── 052ea9f15e9e4fae0a03c471eab758c71a73b070.nq.gz
    ├── 053cb2899e8b53d261be1946826709f154931937.nq.gz
    ├── 0551a5a6595d8c2af23fcba8cd46062ef8b0686d.nq.gz
    ├── 058485a0fdcecb778faa9726d00cdaefdc690fa5.nq.gz
    ├── 05e5939c4b6e16fd93a39c596347363c3f236a71.nq.gz
    ├── 062a3437b8a28e5d8f86caa165cea272111a36b1.nq.gz
    ├── 0639c38c3b6f0b19340a19711220b568d34e739c.nq.gz
    ├── 063cb2fa85fed4dcc6b04912801a80cfe8506d40.nq.gz
    ├── 06558939b04dc461d19e8ae5608292ca5a6119eb.nq.gz
    ├── 06a7087ba67017e069df79cf665ed5ed79e22f54.nq.gz
    ├── 06cfef2b7c2184849e787de7650d18a75b1d3a3c.nq.gz
    ├── 06e5373d94177ae456ae1ddb8b47813b6d70d616.nq.gz
    ├── 07efc86f66283444525b1920b449ab7c67a8e78a.nq.gz
    ├── 0811b0dba874631a3ec13e94ec4048fbd0055ab6.nq.gz
    ├── 081b76bcc09d73186856ddec5f60c9fd5b9890e9.nq.gz
    ├── 083afeb6284bcf5865b9a3b13149486d9629fd53.nq.gz
    ├── 083ffc75f1ff666c16b6483016900d276144eff7.nq.gz
    ├── 086be2a4f1dd55b4ded39b749bd23a1926c73bf9.nq.gz
    ├── 0880d14106deb06bb73b7d89c3957585bc403b6a.nq.gz
    ├── 09177bae92b2c7bd086d9896ab54769526569c24.nq.gz
    ├── 0939d033e765537e55ccd9785bc43990bf2d86a7.nq.gz
    ├── 09840a37f6e6eeca33d4eb7cc2ec9cecbaa4232d.nq.gz
    ├── 09852211485f813f5e36ef4caceb7d3b14fb590c.nq.gz
    ├── 099ab15ab92618d8eea26d3345a367994f8ac0a3.nq.gz
    ├── 09fe5a649db28ef6e0326c119538a19be6e84c0a.nq.gz
    ├── 09fedec1dd7b9d51161e68dcd1077c28cbb99079.nq.gz
    ├── 0a09ff9690f28341b3e4c42c185f83bec61c2d00.nq.gz
    ├── 0a313e2125cdc91ff86ad3eb9c4baf6ef1f4f57c.nq.gz
    ├── 0a5bd490b08f111bd308815c2f931adf6384ec39.nq.gz
    ├── 0a781757ad4c97887052fcf5cbefacc14c32c829.nq.gz
    ├── 0aa3d17fc63605fccc6b0d45adc57916e41a3569.nq.gz
    ├── 0aa8618e94ab3de6c3920bf2e62744d27e56b3fe.nq.gz
    ├── 0b291dbb74dd360adb33436b40b6148c659659bf.nq.gz
    ├── 0b68cc3adbbcfec997ceb121e53b4dbe095c4575.nq.gz
    ├── 0b8f9f630184bca6ea30c1c15c059a53aa3d24b2.nq.gz
    ├── 0bad2a313c1721b691b88a778b154c1ba2c89628.nq.gz
    ├── 0bb28f3ee129ad3bc44bee88c49ff17a54b1bee7.nq.gz
    ├── 0bc26917a3d37a365bdb504538ba9719bba10d9d.nq.gz
    ├── 0bebc6adf20237bf67a828f639a1e392d049f75c.nq.gz
    ├── 0bf9406325b4eb02ece863209a70ab1391750231.nq.gz
    ├── 0bfc6531979c0e2f80e972db23f213a77804ebb8.nq.gz
    ├── 0c2004524da72d3a9788c25ec7174e33be30bdfa.nq.gz
    ├── 0c2d71ab7fbc3375dc877a66b97a1f06b70a631b.nq.gz
    ├── 0c32d304b9d429e34dd1f5ee8afdce3120da9b1d.nq.gz
    ├── 0c3901ee32934e99926beb4938d309e0a8308cc3.nq.gz
    ├── 0c3e2e2f5b9251288f4122ca7d0ba3089a18f447.nq.gz
    ├── 0c5d8f37fa58c3e38ecda496777af2da6d9aeb98.nq.gz
    ├── 0c8eee50d401aa61a30c3b1f60764b9fde4161ae.nq.gz
    ├── 0c903c474054f18fe9d7d07ba8a2310e7359482e.nq.gz
    ├── 0d15b1ca621e3ca1ab5cd76d3645c9b1599cc12e.nq.gz
    ├── 0d30be0eaacc8597683b9cae43d55d2394bea687.nq.gz
    ├── 0d3ae5d2e3139aa75b9b93ba9570c19666a7982d.nq.gz
    ├── 0d88a57343f8a727924fd2fc1bad32c4ecb5b24d.nq.gz
    ├── 0d94c50ce9a80dad267a86935d0ca0de1eba3066.nq.gz
    ├── 0dc36140328b6a1b8a5180e53796b242392f9a53.nq.gz
    ├── 0ddd672717386087cd1028d3da82b285adf917ca.nq.gz
    ├── 0def586e0bd635139ddb8d8f0bd1f99599abcf36.nq.gz
    ├── 0dfdbbf346a94afa29f7ff627e9e8b5a7240d2c2.nq.gz
    ├── 0e307d5ae644fcd605dccee94a892897369d6f29.nq.gz
    ├── 0e450e726991be2dfbc7c2f5cd3caaf010f17f22.nq.gz
    ├── 0e5babc6021cff080a85e11f589ef83c8f348f8c.nq.gz
    ├── 0e857eff632551df31a7ec227a930e5095e0a6e7.nq.gz
    ├── 0ea553cf219856e4e514e9b214004e510c2c0abe.nq.gz
    ├── 0ec710211c7d32a2d2ed3709e83d9b107e9afa4f.nq.gz
    ├── 0ef7c731af6f1f6fcaf505f4fd7589cc839e4920.nq.gz
    ├── 0f06d960d86070b7b020bd872f3a8b056788915d.nq.gz
    ├── 0f18e9c8cc6506dec525528165a5646c20d3869f.nq.gz
    ├── 0f402007011bf4ecd4b127a8717c640afddb2919.nq.gz
    ├── 0f52b80ed96a0bee753a3db7e64237f1e48b9221.nq.gz
    ├── 0ffea758310506cfe97e0c2d0c87202ce81e7fc8.nq.gz
    ├── 10496138c22993e5e81249658918217f209f8ce7.nq.gz
    ├── 106f6c60289d099576201d2469788e9c7986fb53.nq.gz
    ├── 107a0033a59aa76d53e56f1e71253cbe015e0db0.nq.gz
    ├── 107b32b2cc9ae073512adb930df15757e0695784.nq.gz
    ├── 1080aea841f7ea3d951f973ded25c16ba72cf48f.nq.gz
    ├── 1084dc71c053b5df436584bdce2abf0be080c15b.nq.gz
    ├── 10c0bcc30591c1b3f1b7630e4a1f0197f3fb9778.nq.gz
    ├── 110bcb3388ca5f69f84f9374f0ab6892df11499f.nq.gz
    ├── 111601ae87fc0c139e428239b0398e72bc868c8f.nq.gz
    ├── 11241e23507308741032aaff6581d0a4bc99101b.nq.gz
    ├── 11246a95b0a1f1c03748cad66611ac7c2cc09154.nq.gz
    ├── 11272d6d28ae1e072eb53bdb085ea0d0321939ff.nq.gz
    ├── 112b393f151051dba7c87aa00842da88c9ef301c.nq.gz
    ├── 116a627d54fc704c471812386f3f6187f2a3f5bb.nq.gz
    ├── 117351acc4f73273925de24672c53e55b25e0119.nq.gz
    ├── 11839d02c613b256406889aba88156e0443f9621.nq.gz
    ├── 11a26bb89c3041ccaf19139492c64bdbbec1580b.nq.gz
    ├── 11f18d45b809a4774deabeb98aff4f3b6faf0c16.nq.gz
    ├── 122111376e2488e70c2974062b8e1e2ea870e6ef.nq.gz
    ├── 123fa0fb4ab54dadb1a2aabd1dbe27a7461ca665.nq.gz
    ├── 1253d5550aeb32461eaae728035e7079a5f0a138.nq.gz
    ├── 12bf11e0ec100f41ddd1bf0b41d5986a392641bc.nq.gz
    ├── 12e8ddd21def2c71494a2e61779659eb59a39dc6.nq.gz
    ├── 12fbf274562700a879389c658185ec5334d4ed57.nq.gz
    ├── 1334c5f04e8f4b00041f7a07b3f95abef8d587ea.nq.gz
    ├── 136daa26a668ab1baa1baf66c2388b4854cbd5c6.nq.gz
    ├── 1374f619607e98c2d37986bfa71f6804d363a2b7.nq.gz
    ├── 1379fc723d6a01cb83a23cb625076201c3bf49ec.nq.gz
    ├── 139dad72089476cbeb4ab5f95afc152f0c549100.nq.gz
    ├── 139ebd892287bd433cd0f89774265acfb46da4ff.nq.gz
    ├── 13a2dd152966391a499b2028be31dc67f35d4853.nq.gz
    ├── 13aee71d15dcc9e2a58343301dffe7b0fca2c17d.nq.gz
    ├── 13ca87e929fdc31a269759d3befbee0c4979424a.nq.gz
    ├── 13cda3a5d5673160bd968db5f8f2d04ab4b9b11a.nq.gz
    ├── 13e42a701b9f9017512b6535f8337ebf8c8d425d.nq.gz
    ├── 13f42cf9251620f6ad317265b5f3d383c78e6157.nq.gz
    ├── 13fb2bc20a161330aee0c5e149cb676918855ca9.nq.gz
    ├── 1411963daa376e511dce3cdd41c303eaf3184424.nq.gz
    ├── 1432b31c30be4519a57b799990a541590c1314c7.nq.gz
    ├── 143d908105e5191acd707cf3bf1cdbb62e71ec1a.nq.gz
    ├── 1448db544806064d30fbd25a2eb0ae85b8623480.nq.gz
    ├── 148104512ef2d4c14301a6cd8049df3980f4f253.nq.gz
    ├── 14a71dc327739070d79dbf20f466eeca430d51b2.nq.gz
    ├── 14c174dca02d8f2bf0ad51fb6d10f409086ec314.nq.gz
    ├── 14ce66b8f0082ea330f934d6b2f62a8de6dd7d6d.nq.gz
    ├── 151aa06c987c92f779a676ea9b8988f697c25f28.nq.gz
    ├── 15909719e2fcab9b843c72242a9a539b26e46077.nq.gz
    ├── 15c075c0b17ce79723c6d882ece9d7b6dfaa8d31.nq.gz
    ├── 15cb600089dd00af9311a64861d6ac0b11bd36a5.nq.gz
    ├── 160799787ff523daf7df3663c7b850b99650d2c0.nq.gz
    ├── 160c1a373e044e60ca9cdc9bddd70dd302a57477.nq.gz
    ├── 1651bdf4175644cb5930456190ba3b727ed1498f.nq.gz
    ├── 167f68443ef7f7a9029e72397122c3d95a970dd5.nq.gz
    ├── 173875229e5d58ecef78a225e0d6f44db8d5457f.nq.gz
    ├── 174056941f20e6ad095b793f8aa24287f2fc9456.nq.gz
    ├── 175067b3cd2eb6befbad00f29ce992c7662556d1.nq.gz
    ├── 175a95c427742551583c040f82ffef320ec2e56d.nq.gz
    ├── 1770f140424751bad76ffeae60f59ec607338623.nq.gz
    ├── 17719716e6284e1088d53fcb0f3a3143b398d68f.nq.gz
    ├── 17a72f3aa841684493502144c50b1272d5bb7f15.nq.gz
    ├── 184a554fb224cfaa6f964e62825ad3952eb55c1e.nq.gz
    ├── 184c5168498d1dd8b88212398fa1b812b66fd147.nq.gz
    ├── 1852ffd675db2ea92b338f5c4b88a321805285ff.nq.gz
    ├── 18819429ed8629f7a0d103a94e8cbe7d0c5f7ef7.nq.gz
    ├── 18a26e0bc0c3e47564a94471cce9d21ab0c2add7.nq.gz
    ├── 18c52004368f48988591466c170064d5390d3afc.nq.gz
    ├── 18e5f909ad512d34391535790fa1e95b9fddeb84.nq.gz
    ├── 1946ac94230ecc46537fbd344802765c948785d2.nq.gz
    ├── 198b9c1305a08562acab36c66df4a9d7f1c975c2.nq.gz
    ├── 199a55fbd44c97dfdf3045f763124b237ae44f4e.nq.gz
    ├── 199cb682901ce03cddac87b5e0e7a43a1c421383.nq.gz
    ├── 19aec163f926a4399f6b8b128ae3b991179f1fcf.nq.gz
    ├── 19b124dd10a5a03d97afd99df1ec8c7528006d6a.nq.gz
    ├── 19f746039c5391b07a967065bf3970f58345c63f.nq.gz
    ├── 1a1e26f2043cdbc14d90eafe7b46b65df3f73da1.nq.gz
    ├── 1a3def92b0788b8ad3b9841f32219ccd04785ecc.nq.gz
    ├── 1a5a763b73cb3b1b8f00733d82efc51e37fe2650.nq.gz
    ├── 1a6f093bc56b28e08b3e5a37ec1cd61175af8bd7.nq.gz
    ├── 1a8ecdf406e76de2834eb80f47e5eb92bc8d0706.nq.gz
    ├── 1a98b80e4ea746dcd23abaa2576566e715fdc3cd.nq.gz
    ├── 1ab3a8e4a0f0b35d55fc900e964484ccf0b8070c.nq.gz
    ├── 1ab8aeac3a7d5edfea63383ada2eed5374e8d864.nq.gz
    └── 1ad2ba75c4dd3892061aac7b791624f0a6e0503b.nq.gz

8 directories, 200 files
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

[zopefoundation/Zope](https://github.com/zopefoundation/Zope)

---
*Parsed on 2026-04-14 by [repolex](https://repolex.ai)*
