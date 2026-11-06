# Repolex Knowledge Graph of wolph/portalocker

RDF knowledge graph data for [wolph/portalocker](https://github.com/wolph/portalocker), parsed by [repolex](https://repolex.ai).

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
rlex download wolph/portalocker
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6dbcbb2b3e428cf6064dcd7dc279503059a5299a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6dbcbb2b3e428cf6064dcd7dc279503059a5299a
│           └── chunk-001.nq.gz
├── blob
│   ├── 00da1804ffb2f29dce1a03518c400f0e406eb10a.nq.gz
│   ├── 09e410592d4c26c74f073d8b8f7247dac453b799.nq.gz
│   ├── 0cf9a7f9b2c594b0a0f38a82638dbeb37030cdf1.nq.gz
│   ├── 0f2b28208a1d01d909cf54d457eeed408544628a.nq.gz
│   ├── 0f900f68a06556e37ecf08e9bd60947aef9da6fd.nq.gz
│   ├── 143d7399b3f33c1d5bbc49455e79c1f4f20992cb.nq.gz
│   ├── 22bd89b96403c7ed4400f39691f1fa1a1cb7d869.nq.gz
│   ├── 26670ec9ad50d812bd0232b7e4496085442c981e.nq.gz
│   ├── 26d28a7c0259a13733f0b37719cd879625c78c9d.nq.gz
│   ├── 297bca88259938f60804501a62350b0c381a4da4.nq.gz
│   ├── 2a38360d3e638bbce2ce23c87c5cee1d77a17f72.nq.gz
│   ├── 349c2419fd174e4580463dd192481abc2fd0d9b7.nq.gz
│   ├── 35043354485cf12cde0465262b068fca3b7e2c3b.nq.gz
│   ├── 38bbb0d34148c28ccc97e292f473422695e6aa21.nq.gz
│   ├── 39c9021e2fa4e54dad5a666c1e893967725a06b4.nq.gz
│   ├── 41fad59a148f285cef175e09c46a5ddaa2ff367f.nq.gz
│   ├── 42016a7b180a6ebea08608aeb1e48bd01886b51d.nq.gz
│   ├── 425a06f8b8d4e3005f33c1f0765378555363af75.nq.gz
│   ├── 438487bdda1f9e1e8395199c2b7ac1a1637fd909.nq.gz
│   ├── 44066559f1a30c3014d6e78824ea2cc9857d70e8.nq.gz
│   ├── 49dff246504aaaa4f13a4db6c227396138b69ced.nq.gz
│   ├── 4b052771f582bb24dfec5a8373abcb43552f22be.nq.gz
│   ├── 4de03af31303a9f74b6205d9660e492bff7653e7.nq.gz
│   ├── 50752796ff82a4b72e11db1d8ddd884b09b7ad68.nq.gz
│   ├── 55b158475efb7f18308164450de30a7470989fb5.nq.gz
│   ├── 5d48d8b6d7acf2176c7e99af8599a70e863acef2.nq.gz
│   ├── 5dc205f7fe103993bc0a1300b2718f95044af440.nq.gz
│   ├── 5f319b35ef7b2a8949155a22a99001bbb1a5516f.nq.gz
│   ├── 62a32bf733df2435c88a15b0b17857b8feea5fd4.nq.gz
│   ├── 63f9865593ca392439774db4b79025cee43267b0.nq.gz
│   ├── 65342de12172d80d023c8d0825e1da575d34f16e.nq.gz
│   ├── 68f17e8d95bcf46d9d8e99ea6920ec71250c2f09.nq.gz
│   ├── 69fed0806a28f33450edb6d9d5f24bad5c7a12dd.nq.gz
│   ├── 6af0a5beab400eb54cef3c5a25a4a2502ab3c81a.nq.gz
│   ├── 6bbccc4787a10e372d552e52e800cd161dfa0464.nq.gz
│   ├── 7269087209db1971bee5a49d46e3c1624a4ea5f1.nq.gz
│   ├── 77631dc12459a9efcf4022bdc5c5c826cd89600a.nq.gz
│   ├── 79793f74a1258a38fb8a8dc275ef28e0c2b53d55.nq.gz
│   ├── 7a079552a1a5538d324687945d005c4e4e906909.nq.gz
│   ├── 7f1603aff4ce272d3786e1bde1d437c722d88d58.nq.gz
│   ├── 7f87f4e89d66604d5df865d2f37d9116bb139cca.nq.gz
│   ├── 830885fed9e595ea09e57f16b9f445b0de7fc769.nq.gz
│   ├── 84c23c9ded66b85bb94708b11e682b253e9ab244.nq.gz
│   ├── 8815ef0f759292c2eb9aa4928b49fd1704dad0f3.nq.gz
│   ├── 8968cb3f1997234ad7afce3ffd30d10e9d91fc8f.nq.gz
│   ├── 8a637f653bc271840089ccd9bfadf9a965126057.nq.gz
│   ├── 8f3cf1fb7bcd7c0b4461f0bda1841b90ff8c1a49.nq.gz
│   ├── 9360863df4b34edac3120effd77a1af11c49d556.nq.gz
│   ├── 952045948a4ce47a4fd23d53d899653aa2c75222.nq.gz
│   ├── 9d392da6b079d694939ba08875cd8c5d7102c9d6.nq.gz
│   ├── 9dbc537810e87abcfab005e52f0485eceb265a0c.nq.gz
│   ├── 9f8d44d44ae5ed94f4d86a49eb809c69680c83b1.nq.gz
│   ├── a12cf298e2bdbc22e1c391c7b60fafbb07c5d761.nq.gz
│   ├── a1bb4906451b29dbb6b1603c07a7a08274b7f211.nq.gz
│   ├── a5289497894bff728523469f746e40d1d888d0a9.nq.gz
│   ├── a65902bee13ddc45808ba2117d14a6f5bca8e4fd.nq.gz
│   ├── a9f5fda450f950081ae20bf40979014d3c701d29.nq.gz
│   ├── ac7290db434c3575884ab4c799edb7704cc3227d.nq.gz
│   ├── ace701d54dd37e40a519d8c5bf3007a6835219b2.nq.gz
│   ├── ad5d6c21d9c10337b4c34d7dd8a428d2967ff3f3.nq.gz
│   ├── b1a940ccf6f8c2b91bf9f92a73aa53a7aba3dfce.nq.gz
│   ├── b3224bb9e5285b720f1699330feccba4c78af7a6.nq.gz
│   ├── b4557b74cd27e4dd6b0c923e320db99d6a19e25b.nq.gz
│   ├── b638bda0d3b793bf3c52b37c9ea1f5b6dc0ce98b.nq.gz
│   ├── b73cc362a169c862bc5730321cdc8335acf66fd7.nq.gz
│   ├── b98a5c2227a1ac0f118c719b16f26951c7008a09.nq.gz
│   ├── ba3e3d54e07161c5f5002054655e6689882b3b72.nq.gz
│   ├── c220f61e0e525ba7263ed03b3fd8da024de85f39.nq.gz
│   ├── c3ca0f1c34c6002b8eab3fefbad7777a794cbe09.nq.gz
│   ├── c7eb71463c8c0f8a4f0b0c9f380fc26b7088baf1.nq.gz
│   ├── ca83dcfd5ba4a5ea3e7c192220960d9ceb5abd1a.nq.gz
│   ├── cc228bd6852c332eab9c2a9365986062111e5741.nq.gz
│   ├── d030891a776993388809451915635c107464d09a.nq.gz
│   ├── d6a70b971cfff3066de92ddf62683f80c640d5df.nq.gz
│   ├── df9db11ccc47e062d7b5657d099dc98fbb4ebd0b.nq.gz
│   ├── e084503adce28ef2d1ef17509f272dc4fc5e5eda.nq.gz
│   ├── e26cde216497e8470870f98fe2240c7682fa20f5.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8ae17eeffa89c1d5a9ccf77d4db5bf15d5c1de5.nq.gz
│   ├── e9c306cfe9d52b84b4f3acf16eb7e0939f0582ed.nq.gz
│   ├── ec44cfb689321f849f781914136397cc0c8a713a.nq.gz
│   ├── eebfe6fbee9113f660adc820e8e934bf40b70dbe.nq.gz
│   ├── eecffbff249f2ef464fa50d970620fd3f146ae6a.nq.gz
│   ├── f291a01f6160708b2ee3ffa461f7fa9f59f8b95d.nq.gz
│   ├── f40e8aac37d43e7187af541d85673d6e9e3075dd.nq.gz
│   ├── f44891345435e07ad7734875582c2c20c73f54d2.nq.gz
│   ├── f44e7d8c4a315e3594e8fbc3975403df75b58cff.nq.gz
│   ├── fa73ad08e311519ec96713c1b25ffde30ab46bdc.nq.gz
│   ├── fb9aa91b49fb97fcf9193225114c6acee71ebb06.nq.gz
│   └── fe593ba2d332758b8e45ad051d409e98f7f90444.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6dbcbb2b3e428cf6064dcd7dc279503059a5299a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 98 files
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

[wolph/portalocker](https://github.com/wolph/portalocker)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
