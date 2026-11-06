# Repolex Knowledge Graph of ansible-community/awx-tui

RDF knowledge graph data for [ansible-community/awx-tui](https://github.com/ansible-community/awx-tui), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-community/awx-tui
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7875fc3b72cc0362589f55d299159e5cdbe8f7b9
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7875fc3b72cc0362589f55d299159e5cdbe8f7b9
│           └── chunk-001.nq.gz
├── blob
│   ├── 01459903260bc34fd8e1c64ba2e9774c4100e441.nq.gz
│   ├── 04827e59c5908dfc4a14e0c75d0f439b29f73c84.nq.gz
│   ├── 0b5b8f4dcdbd6f8cf6e591831547fc3e56da0a7e.nq.gz
│   ├── 0c7dc0a393fa4a612ad368a828e46355859bffbf.nq.gz
│   ├── 0ccdc1d1ba60c6c0010b9623e3af4e639e997716.nq.gz
│   ├── 0e47024dff3942344ee851fc55343196dfcf6720.nq.gz
│   ├── 0efbaea6d773280f60aeaa511556833bf7fb8575.nq.gz
│   ├── 108f486a3165d3b9c075ae074bb494e8e49697cc.nq.gz
│   ├── 110e004254475de1af34fde8eea874518c8cf003.nq.gz
│   ├── 16b1f578571ae31df14ecacbc30b1c3ae1595545.nq.gz
│   ├── 170cccf67cedede085c3720ee20974642a68db90.nq.gz
│   ├── 189b85221a345abf693b91d691a2afabe68b8be8.nq.gz
│   ├── 1ab00597e157f60936a0f1bb4b24e0ea1afd9f1b.nq.gz
│   ├── 1b33a02c0e4137d307e5b861cfb5e8296f7c5083.nq.gz
│   ├── 1f83cb473224af5aa50b7a7269ec20bc1dd40e74.nq.gz
│   ├── 20944ac3b25c39ea8a01e5b3e51b6afad4410868.nq.gz
│   ├── 20a110910304d7dfd89b24cf91633401108a7583.nq.gz
│   ├── 245a13d59c2864ccaf915325db771d885e939a98.nq.gz
│   ├── 24ac7c2b26442d061b604bb460c7a304e28181a0.nq.gz
│   ├── 26fa47c6c8a7123ee87f65d9e7240f8e379f1863.nq.gz
│   ├── 2a15584f922382537c51642cfab66499ae80ceda.nq.gz
│   ├── 2a73066f1bd1870a5417cc6b30a4f5925d57f393.nq.gz
│   ├── 2df593317d6ea07037067507fd693c72313bde59.nq.gz
│   ├── 2e336552738bfe2d6248010f3e88ca3ba931a73d.nq.gz
│   ├── 31368dcb706b75bcac97144613cf8c5b6bfe7002.nq.gz
│   ├── 32e885e29bdb55d61f672751726bcd3510d20c8a.nq.gz
│   ├── 384ad754bae25d642299b7c09a2457ce70e66c49.nq.gz
│   ├── 3c4d8f37df27dee71d7ebfa96185535045daa66e.nq.gz
│   ├── 3d734a2885b32c0bbb31727d7220f24015712304.nq.gz
│   ├── 3dd7dff284551d4eb82373f788857847bbd48e82.nq.gz
│   ├── 421d8bf2fdf391d0fa9f78182b2c7f4a4319d2b6.nq.gz
│   ├── 43b1b397c83171e0e76bececdd74231a695370e5.nq.gz
│   ├── 43fdd43fe368e45ff4e402582b840553c2f0187a.nq.gz
│   ├── 4530c866d9253f54c73138eed75afd857d6d482a.nq.gz
│   ├── 48e6fae0a5d6f91abc34b38416b1011088781a95.nq.gz
│   ├── 4b6353cdf92faccb01e5f85c55f32009c73b022e.nq.gz
│   ├── 4c295b90cdd44fa82472b4846f1397e793e6a813.nq.gz
│   ├── 4d9646eb4633cf716274f6265f22075cb9d35574.nq.gz
│   ├── 50be28985cd4b46e858ed7cbd005769bdc6f1bb7.nq.gz
│   ├── 5a247a12623ca0d60c85a14d713d0ed1e461383e.nq.gz
│   ├── 5ee0afc0605859aaeabb2a010a57773694df1551.nq.gz
│   ├── 5f1ddf385af11a74864d737a17395c0c3d4fb8d4.nq.gz
│   ├── 5f5796f18c3273856ce267918e520944684a5db1.nq.gz
│   ├── 62d5b7460a3827fea6ba34e64ce81144d158375d.nq.gz
│   ├── 6516ac4deaebab91da2efe96d0fc4da5dfb5a106.nq.gz
│   ├── 65848803a82ad1ffcf9bb353583f333c54f37765.nq.gz
│   ├── 66db7890fc58c24186071ea03954e56e38f1e224.nq.gz
│   ├── 675858327d41d133301e21f74312067383fbffe1.nq.gz
│   ├── 67f59762195b4ea7c7e5bbfa89d58b5efc9e529a.nq.gz
│   ├── 6d3e765bb3f8a9983c71941e88d16d4effefc458.nq.gz
│   ├── 73fe37673756b2b24f6db56f45d39fb82d562cf0.nq.gz
│   ├── 7676b809c05d1b639ee83a1c8a4e81feb74fc187.nq.gz
│   ├── 77c5ad257cb2897990036997a1551df56ea8c74b.nq.gz
│   ├── 7821984e37fd649d905ea17473f21c2f230fd2b5.nq.gz
│   ├── 7de57f51c315e75cef9838922eb80d52a1276bfd.nq.gz
│   ├── 89254cda48d9b14fb39d0d96e297ff8cb1d759c2.nq.gz
│   ├── 8d3fda576d88e509b48c940b2e66b1b09df8b331.nq.gz
│   ├── 8ea9e70dcc119a5aea715fcf12771f2626c6a4a6.nq.gz
│   ├── 8ed6e894d18d9a6a9f99550874e7936098e39460.nq.gz
│   ├── 901fabf30deda67f510b10fa93c1367901d0727f.nq.gz
│   ├── 90328d89e6f06e3a05f11025300689c00d2d2e34.nq.gz
│   ├── 9243c76d9736a4a8f16c9aa9107a7d8a3f894e81.nq.gz
│   ├── 947be45b48394682d1c7a27211f2dc2510f743d5.nq.gz
│   ├── 96350fb9a03440976603bf52737953bf4bf51b4a.nq.gz
│   ├── 9920d23db6017a27063c0f25b18247e3dfe6b80c.nq.gz
│   ├── 9c91cfa22890ebdf16075477e81aa5b9b3e3cca8.nq.gz
│   ├── 9d15a849959778573dbeb228b73e704ea58fbd0e.nq.gz
│   ├── a08afa27b77038e05b60536928f2fd5b7992d59f.nq.gz
│   ├── a412fee768589764731d816e1027c1024125806b.nq.gz
│   ├── a5e1a38ff295d297c52e085afc947e34de5720ab.nq.gz
│   ├── a60f88605c115a0e3eb12aab5554cdca8266ac53.nq.gz
│   ├── a64fcb44c3a49e651772a2822d2f5bcdd3457c05.nq.gz
│   ├── a71d3f8786ea1f950db36e0ad306241530823948.nq.gz
│   ├── a98c9a4443f8b21050f2f34d631037c23ba4f5bf.nq.gz
│   ├── a98cec744e504c1ff1a10d041a43460f69380374.nq.gz
│   ├── b04420fe6ee5e436d8e49ea28a9fa7409d1f80b2.nq.gz
│   ├── b4d90790223b95552556ea895ac541a489a7379d.nq.gz
│   ├── b4ff6dc842c743d5c1da976fad1df51779862cef.nq.gz
│   ├── ba7063d969db92f2cdbc2907d963148d967bf657.nq.gz
│   ├── bd839027d414b3e4f130039a1cb2e5818eb91cb4.nq.gz
│   ├── c18f688fde2c67a0f3a0a555a04821ae7d65722a.nq.gz
│   ├── c3403339a9d3d993e25cae9faecf7078f94dccdf.nq.gz
│   ├── c4f467413532c47f73698cb015b2d06b60ce7930.nq.gz
│   ├── c720cd30b02d81eceb249f1ece10378e9488db2f.nq.gz
│   ├── cb38ba5b0f904a941747b182aaaa5c961193e0c0.nq.gz
│   ├── cb58c0c4d8ef9aec581d99395d86768030a4b317.nq.gz
│   ├── cd7b84495a3603c5e6ba093f8fabb4a9694ce112.nq.gz
│   ├── cef030fe054010929bfcc91ee90d8bc4eaa72b0e.nq.gz
│   ├── cf3517a203809eee4da55d81ce9e9a5602a89132.nq.gz
│   ├── d53f1f42e5ad79a2924d15f53cd7c1a32ade5915.nq.gz
│   ├── d5a7eb56c1df33ddf367918332a607ccca9faa33.nq.gz
│   ├── d6509f05fe32355f28d703db76705fe0e7ebbd87.nq.gz
│   ├── da038686ae5676605a99c26ab1c3f2c63793fc27.nq.gz
│   ├── db995f7da57badc38341c401d077c2f9545b9dd9.nq.gz
│   ├── dbfcea87b9cf7dc769a71e97ddc510c8f35bbad7.nq.gz
│   ├── dd6d4c8f442ed0e3248c222f372302f722d18561.nq.gz
│   ├── dd7b9fe2f72de27c0247f4ff697d7f139251ff5f.nq.gz
│   ├── de863ea2a6838b4a9200c682cfb266302bde7035.nq.gz
│   ├── dfc7815a09483edbb9cc79b5b477de82295cef6e.nq.gz
│   ├── dfcde81b9e0feee6822e38e7fc048bd4ab1a8cf4.nq.gz
│   ├── e0cddc3926e5aa274eb403ff9f3558c829f90e7f.nq.gz
│   ├── e4048b6722c433c932196e5dfe26d9fa6a10b047.nq.gz
│   ├── e4484d08edb58382ee079f83f46a096641232737.nq.gz
│   ├── e518f6cad3414c54027c22ee4eeea657f8215b58.nq.gz
│   ├── e602d03e9d46d61a205d6032a04d7ab100fa3b97.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6dc113f65e92e94cbb28df1b28cca5083f0346f.nq.gz
│   ├── e75b04051f77a25a1d31c7c072a4a324b237d2fa.nq.gz
│   ├── e8fd8d4c3eefe85b97435daa92e31e87c5752082.nq.gz
│   ├── e9611a051c5a485e4da96fad99b74ebd818ddb50.nq.gz
│   ├── eeee9dc2dd046c929ea5c29049e4074966b528ee.nq.gz
│   ├── f0e02155b61d987554b7f1ef3569308167925c0e.nq.gz
│   ├── f29f1c6751f440f85d3e8588a767fd21566b088d.nq.gz
│   ├── f873ceec14cb026a446a9a7bc34b16a8739d477e.nq.gz
│   ├── f8dd34dbbe2ac7130714ec10163cbcda8e8897b0.nq.gz
│   └── fca59ee97781238293d78efbd32f54b17f60fd2f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 7875fc3b72cc0362589f55d299159e5cdbe8f7b9.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 124 files
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

[ansible-community/awx-tui](https://github.com/ansible-community/awx-tui)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
