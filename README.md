# Repolex Knowledge Graph of nipy/nilabels

RDF knowledge graph data for [nipy/nilabels](https://github.com/nipy/nilabels), parsed by [repolex](https://repolex.ai).

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
rlex download nipy/nilabels
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4a61cd95e6bfb3644a3724461502d7cf69f5615d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4a61cd95e6bfb3644a3724461502d7cf69f5615d
│           └── chunk-001.nq.gz
├── blob
│   ├── 07f1bf205b55319f31b3f224851be0ad0f6c6cbd.nq.gz
│   ├── 0a7661fe8a5acddaa4690b3890b0d7a54e5eaf30.nq.gz
│   ├── 1423e4bb3b200a153670fc4a1bff7b8dacad3688.nq.gz
│   ├── 17f8792145f7de8b0156b73c3afc5690ab7514a7.nq.gz
│   ├── 224a415292bf04a71388b4958228b78a875c97da.nq.gz
│   ├── 236656fdcefd7f9c22e0988adb942a5a534f0fd3.nq.gz
│   ├── 25dfe7811ef3ae72add73a28386269a7159918d2.nq.gz
│   ├── 36e8f2baf1fab9cad05bc24b0ea6c6c4b46d3073.nq.gz
│   ├── 3a02add9c868b3545e9944d287479e8486f8d9bb.nq.gz
│   ├── 3ad108175f9bcff4d74707a4b680daceca27cb58.nq.gz
│   ├── 3f32f8e8470dbbfa8eb13e3a7bfc37645d22e9dc.nq.gz
│   ├── 433ba828fd87a16c68e23039542fd81389eace71.nq.gz
│   ├── 44938d561b5f0ec32058490c5b79bb1f68e702bd.nq.gz
│   ├── 45f52d2a073aa67f2a780c3ed8ba41668f27a7c5.nq.gz
│   ├── 4bad86f0c495fb259e6c8f4b2c3e4ddef0440ecc.nq.gz
│   ├── 4be0a0105b5065c719351f2334536d0acf35bbef.nq.gz
│   ├── 50b3f32380716b0c9c9e6060d613c7963ef3d4d4.nq.gz
│   ├── 51a9eb12ab8298f058ca6e43286d6d99b9fec330.nq.gz
│   ├── 51ea3089b65b4aadaeeb772d4edd3092cf234f25.nq.gz
│   ├── 54289334d0751150b926ed9f05d94e3f5454b4f4.nq.gz
│   ├── 55d99b618ac05377ac3c0f6884269bb37f40a84c.nq.gz
│   ├── 5b2c23ac61775d3fe74484be225a18cfdf435e56.nq.gz
│   ├── 5ba0b58aa36643a5123e2531f7c17c9d1c74748a.nq.gz
│   ├── 5ba721d0c9feff18a82f647cb1842625c5ffc740.nq.gz
│   ├── 5bf608151af5a439ada08062c0ad072fa35c59a8.nq.gz
│   ├── 5c237ddbad0e4597d147e3f64e6eaa7d16dbc3af.nq.gz
│   ├── 5cbcb75bc9fec5d3b5567e78191bfc0cf3f0d420.nq.gz
│   ├── 5d7f24232dd660e4af2750f34b654bda2ec0dedc.nq.gz
│   ├── 5f15c24f17fa12770111b686d12b02279b8ba763.nq.gz
│   ├── 5f6f4c782dc3978f7ce3bddea0a2106329d23619.nq.gz
│   ├── 61973f27a110c274e74518457c8b805a6e96ded9.nq.gz
│   ├── 62a3622dc4b7e0878539f294915d38e0afaaa3b3.nq.gz
│   ├── 639f5c7019e3e95501d5b5d63748bb145cc8d89f.nq.gz
│   ├── 66f1041a3f2763c3a3ae6718af10e3af9b69da71.nq.gz
│   ├── 6d41e4ab88177f45a8573365d0698545449635dc.nq.gz
│   ├── 7228cdb1c46decc4cb4207348b2e2ae95f988117.nq.gz
│   ├── 73533f058bb789bb211cd8b7f4e2cd4a6b04c85d.nq.gz
│   ├── 7688e48940f2c2949432f2163004130441228e6f.nq.gz
│   ├── 77a660ceb2453512eb16f30c020e0c9a92098078.nq.gz
│   ├── 784128918eb6361d137efd595643bd7de8a6c0b3.nq.gz
│   ├── 789f24ce8771cf55b26615a5070c3beba36ca5d6.nq.gz
│   ├── 7b2b0c290f78df949dc29e08a4f075352f915041.nq.gz
│   ├── 817adcc7c286084da3c2ac4476dcb4c5a29f779c.nq.gz
│   ├── 84f78ed2ea0d0426419f99f3b0182555db63efe6.nq.gz
│   ├── 86b1f439c5b0128c58fe4740c321465e06005f42.nq.gz
│   ├── 872554c036c838e96f616a7aa39a7c34f7a30637.nq.gz
│   ├── 8e9d127b275d892237bf15b05daaca7e8d5909cb.nq.gz
│   ├── 940bab1d4e13307e22fb2ab1b4dda5ae1f4b4f3a.nq.gz
│   ├── 9bf25c164159342d6d7ed0cd88cdef57b1639869.nq.gz
│   ├── a131b38074473fbbc7e1b2f97abd50dfee2d3bb1.nq.gz
│   ├── a248141dde3aa59659ea0706cb0d900dc2c2295f.nq.gz
│   ├── a7a31053a44506a8faa598ee5c80fa8c0e0a3ddd.nq.gz
│   ├── a8c7e72ad962dcb30fc6ed850ab9e3907ef90bdd.nq.gz
│   ├── b0129a4e4246be8562165ad2bba22271f1be5fa2.nq.gz
│   ├── b29c3e49717455d9566b8aae76a9ec039e261933.nq.gz
│   ├── b6f3968934e953394e90dbf6679be4a8c6f5d2fb.nq.gz
│   ├── b748e9a1bca85a8548a259f48f77113fb1ebe313.nq.gz
│   ├── bb8735e5f1ce411feb1bf08bce030da4a5803ba5.nq.gz
│   ├── bc186cb571250dc4cd280f699f9c37214e4d222d.nq.gz
│   ├── bdaab28a48d6b2941815b3490922e36514ff4cd0.nq.gz
│   ├── c16711336e11a88713bd81a5a65e2e37c11c9d9b.nq.gz
│   ├── c2972ced74d308e940f5bd76b08d606aa1607be6.nq.gz
│   ├── c5b85d3afa7e3b3d37832d49d8120fa8b97a4b41.nq.gz
│   ├── c60c6200d9affba10b5060ca490400716c38ddd6.nq.gz
│   ├── c75748d14a06aa8d4c6bf7e3782b89866d6275ee.nq.gz
│   ├── ca9ffd6748e116d4fe34d6b80a9edf7c8993c9cd.nq.gz
│   ├── cc6c69ae7da585b1a7a415005f1873b63a1b7c83.nq.gz
│   ├── ce1b31665d17d04104bc848fa684cca77626c7d0.nq.gz
│   ├── d135596b185406c59513c9aeda54a89ae8f0ff22.nq.gz
│   ├── d19750662a7a8328e8a0ff8000ce1f1078a345fe.nq.gz
│   ├── d68925e490844bb8694c85ac2af585d913533251.nq.gz
│   ├── d85f840c9cc92297df21fb0daf32bdd44e65ab4c.nq.gz
│   ├── dd3310a2ff91c8174d8a8fec67feef48b3f52f2d.nq.gz
│   ├── ddd03d693ebae7834bfc3ff3f9d2e8c7ece248ca.nq.gz
│   ├── e0c0248f2c10d1a1e2b1f47393a8d00d492a06de.nq.gz
│   ├── e1083bdb0a6ef8abeb74f53deda69763b608e7d3.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f0aa068530afb52b809543b2484bba4c484fb6df.nq.gz
│   ├── f2d4ecc4fa0c153beb9779f37fd46fe6f7653016.nq.gz
│   ├── f465431f4ff8b210893f9b37807590026724b02f.nq.gz
│   ├── f4e69f10b288993f2aae269e1b3e49c85d742940.nq.gz
│   ├── f788de1977772bc52cddd5c45fa422190047b48d.nq.gz
│   ├── f9a59b5f6c79dea0347537a337bfac41700dec12.nq.gz
│   ├── fb94e1a8f318ce9936482a71602f827aa4c4b515.nq.gz
│   ├── fd6da98a2d0aba348acb87616e8930c8b6d84ef3.nq.gz
│   ├── feb48698d3999fa3e03138e36364742ae68d1699.nq.gz
│   └── feba72a79568727a038776fe4c8eefafb4146717.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4a61cd95e6bfb3644a3724461502d7cf69f5615d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 95 files
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

[nipy/nilabels](https://github.com/nipy/nilabels)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
