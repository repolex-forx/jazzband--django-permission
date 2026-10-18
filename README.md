# Repolex Knowledge Graph of jazzband/django-permission

RDF knowledge graph data for [jazzband/django-permission](https://github.com/jazzband/django-permission), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-permission
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7f23ceb00affee3219350832b361a01c658e3981
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7f23ceb00affee3219350832b361a01c658e3981
│           └── chunk-001.nq.gz
├── blob
│   ├── 002a6597c56f0ea5a5dae2b2b2a7cdc127fa027e.nq.gz
│   ├── 03ca1b34c8ee13e6f83c228f5037a003d5d590af.nq.gz
│   ├── 0baa815a4dee659a268a5f71860bce7a170bf19f.nq.gz
│   ├── 0ce9678d2ed4cb9b765e7ef8bc934fad961b2999.nq.gz
│   ├── 0d1a4439199c9ef84e882067c41f55f763548eaa.nq.gz
│   ├── 0de265a3ce7cdf96b4500d50f6a638b64fa81afc.nq.gz
│   ├── 0f4eb81fdc83108b604111e38bce901353f05d14.nq.gz
│   ├── 19d55504cf8d9ada11aa62830182e643f93eccc8.nq.gz
│   ├── 1e9c657740a97f9e4c7497e301d20e4b5d6914cd.nq.gz
│   ├── 1fe76addb1dc8d71082b96fabf998e1d0c5be591.nq.gz
│   ├── 27930fd9e4152239630fd7e50f9b62a8a446fc97.nq.gz
│   ├── 2a2cf607e61d28f113ffe4a135b5106f80303d9a.nq.gz
│   ├── 2e34245c57ea4d1f49cbc5b126041ffa5301df84.nq.gz
│   ├── 2e818adad0d2f0830022365eca419b4cf6a53085.nq.gz
│   ├── 314e4c89836cd29b798dbe4171be65417ce8ecd2.nq.gz
│   ├── 338c9bf15c0479e769447495748859ce44998327.nq.gz
│   ├── 3c45d4579179fdb3176d0afd8a6a94309802805d.nq.gz
│   ├── 3f9b92263a740a05f85029307511838252225c7b.nq.gz
│   ├── 3ff4649275a686830e4827f526d806023bb927df.nq.gz
│   ├── 438b7b1911b21092b7bb30fba0c5afd237e08071.nq.gz
│   ├── 47e4e4cee4f43d26317ca53429c81778b71e33c8.nq.gz
│   ├── 481a7a57ff9f8590c521b3c078b80464a7a0b2e9.nq.gz
│   ├── 49bbc8adf258b2ea723df869e18e0790565d7e06.nq.gz
│   ├── 4d96ebad48a73e8bd8a6483e46a3d789e5d7ce2c.nq.gz
│   ├── 4dc8e13bb1a16751ad31299d11c6c266b85ec9bf.nq.gz
│   ├── 5463d8f1f8ad5406baae3d7e85f23d99508199ec.nq.gz
│   ├── 562a848dba1b55e4c54502cb113754e7a68f8449.nq.gz
│   ├── 5a08af4f9fb958bb1bcda017158595b7b14a6993.nq.gz
│   ├── 5def8117c0fa31d35f88ca79c9ec40070cd35721.nq.gz
│   ├── 60a5eff969e2c9744210030ede92ba15c909845d.nq.gz
│   ├── 67e5f063b73082b041d0d68095c64f658ad8e5fa.nq.gz
│   ├── 68ca2655466d49d76fa261966e49b41fa5cfbef4.nq.gz
│   ├── 6937f445098f485744918e7629b7a9c835d010e2.nq.gz
│   ├── 6e0a5c39d0bfb35e07471407e6cd4c93b7547340.nq.gz
│   ├── 7b18b641c00144857419e718dad11f2ff92a37ab.nq.gz
│   ├── 8360f68efe2db2194d0efc12d94576b09698be20.nq.gz
│   ├── 8612f020303d83d38b80a18c941486a7e776b5f7.nq.gz
│   ├── 8902129de5353e17caf3abaab62e72c48b483049.nq.gz
│   ├── 895a1f054d4471ce6ea8d86c618f69f8b87f492a.nq.gz
│   ├── 8b7f5d75d1d0b386d43455dfbdd77646cbbf8556.nq.gz
│   ├── 8ca152860bb8598453c40b7628e4a47309885258.nq.gz
│   ├── 8d188f6e940a1837e323f4d45e70bc6f035e379f.nq.gz
│   ├── 93f63cbdcee114507f5d2d1dfa415e973bba7a5f.nq.gz
│   ├── 94cd883461087dcf7761c0fd5d0d63417c75d1ef.nq.gz
│   ├── 94e65d1b2c1cf95919abe7a3f42055312d101fb5.nq.gz
│   ├── 971cab3d727f8cdb84b56a56ab9c1cfae599c51f.nq.gz
│   ├── 9b6f6bf8016bbf754cfe783e902ec5e44307e592.nq.gz
│   ├── 9e91a9e455b305b5d728f87166e809884729b221.nq.gz
│   ├── a3180139efb65b5f99ebfdedccfb0cb15c77a6c3.nq.gz
│   ├── a59b4c0c74af2c9e1847fa6a9a12a55f0c0837d5.nq.gz
│   ├── a74bd6302d75c5b58e5e7fbd01772160186d6c49.nq.gz
│   ├── a85f798220d99ced87231c88d14224478d95c5c9.nq.gz
│   ├── a8f750610df2b15134043b445583a2b3ea6298b8.nq.gz
│   ├── b542371d5de49a382fc0b21e10ea5b19918822f2.nq.gz
│   ├── b61147f481e15d24ef202e7910da1bbd54830326.nq.gz
│   ├── b858158ae538854f2f6a1d92b8e667b85809f4ab.nq.gz
│   ├── b9a72441b73eefe2e521db4f8d1634cca9e1148b.nq.gz
│   ├── bdb0e0af7edbfd0f8847efd15ab1b4bc2c17cffd.nq.gz
│   ├── c0e6060db0960b4088072359f78b74818b9266d9.nq.gz
│   ├── c3ffd8f29bb3cecca1bfdd35e1c5f82f7f125cbc.nq.gz
│   ├── c89d8832e79523d7900cea1b28ca96167eb08b88.nq.gz
│   ├── c945eb24019e952cf8af33f7b321a625c756f708.nq.gz
│   ├── cbf1e3658e6aa8a22988927b510080a973450f52.nq.gz
│   ├── d3283134dbeea982782543f01dd0bb2df3dab48c.nq.gz
│   ├── d41198bbc03182cd8b5327b04884b4071cf14b68.nq.gz
│   ├── d52422efd89a23235b656868cc34ff84a2e6b5b6.nq.gz
│   ├── d5996bbec7028a20fcca1c5802a827a062fd1f4e.nq.gz
│   ├── d72a5a421099dc0af85db1b7262d0d5ce6aa242a.nq.gz
│   ├── d85a9f2acc2c33a23265353679ea4a396418ccdb.nq.gz
│   ├── da706881adf2a5c7a24c9bbfe30450bc1fbe976e.nq.gz
│   ├── db19037ea642c383a02d41bcefb81fdb36db58fc.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eacb0c1f7da6abb262a7e4d0af5b3d12f304632f.nq.gz
│   ├── f363485f3f07ef1cc3a5286f144e6b9ba319bad1.nq.gz
│   ├── f3b3eb282e309a284fa11246ad2826e3d97fece9.nq.gz
│   ├── f6412c75c2d210876a77f885457fdcd26865f551.nq.gz
│   ├── faba3802362dd590f77d00fb09e72d02fe7d31fd.nq.gz
│   └── fbfa00c113781fc9b7bcbdc628face0239508e14.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 7f23ceb00affee3219350832b361a01c658e3981.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 86 files
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

[jazzband/django-permission](https://github.com/jazzband/django-permission)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
