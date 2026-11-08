# Repolex Knowledge Graph of UKPLab/eacl2026-culturecare

RDF knowledge graph data for [UKPLab/eacl2026-culturecare](https://github.com/UKPLab/eacl2026-culturecare), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/eacl2026-culturecare
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ad950b84a8b2d4606a50c4f87c465976208be5a4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ad950b84a8b2d4606a50c4f87c465976208be5a4
│           └── chunk-001.nq.gz
├── blob
│   ├── 0ceddd8751dce64604d6331e4e0f0eac8e750c77.nq.gz
│   ├── 0d03bf268c448d14aeb9becbc045bcde4ae6c9b7.nq.gz
│   ├── 0d39a67c24f01c1af1e9cb675f380c3a1d1b2422.nq.gz
│   ├── 0d9360dc35d158ea1ccd025d9520994762579eec.nq.gz
│   ├── 120c6893b8af8f69dddc51b2734ed561b78c6091.nq.gz
│   ├── 15d5214aa8f46dfb016a6ca83de8b7f711c009ed.nq.gz
│   ├── 229edba242bb190698662cdce6bdacde9f0769fe.nq.gz
│   ├── 36af83e43fd35bd38318d67a9a989353915b5676.nq.gz
│   ├── 371b8db98c5098f090cdde515088fa3931931f17.nq.gz
│   ├── 3947918d999d8877071cf5a2ab7b982240326817.nq.gz
│   ├── 4228dbf3e3a9eba0659698c869ebe17eadbf8181.nq.gz
│   ├── 4494992e95a890d760734ccf84e8f96ba53b132e.nq.gz
│   ├── 45c94f6d8e39f3b7ace728febbb20e6294eff290.nq.gz
│   ├── 4b8e705a6d189f51828a67384b1e755d47aa44d3.nq.gz
│   ├── 4cef27e61ea9ac6f982e68a89dcb12432298bb71.nq.gz
│   ├── 4cf8d8fcc89e0577176b5ac7c22dff75c29aac4e.nq.gz
│   ├── 55f9a9e34c857e54b17e57e54895f5c3b3dcfdfa.nq.gz
│   ├── 580f54beb4252b47f9762acb22a5ebe91e6c43d1.nq.gz
│   ├── 5863948eacf22168b8d0ea993534a81b5134edcc.nq.gz
│   ├── 64a19929b54fed6b9a11c609557d21b224bf5d89.nq.gz
│   ├── 678dfb0bc919f16be757cf6bd72878faea2e6baf.nq.gz
│   ├── 6a171a558f6a2db926e56026b27c8a2cc3de9a48.nq.gz
│   ├── 6c3d9f87cbbe61fd9d74f1aa3c30e3e43ea4f184.nq.gz
│   ├── 776145655e67b45a6eb5504d5b9d1700827b3c03.nq.gz
│   ├── 77f885270000a88a5551e66b3a3b4069e35e3db9.nq.gz
│   ├── 829cafe545fbc5b6a622128620b975639019a6ef.nq.gz
│   ├── 841154e2f3505a93c2a875425521de035dcee3b9.nq.gz
│   ├── 8907f2b01382eb69fe8624289069f535b17e7885.nq.gz
│   ├── 89f79d04b69ed907c42ae436aa16e9cfa7cfd9bf.nq.gz
│   ├── 8a32ee34b1603953ed79a91dec01453f67fb93c4.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8d9f338e71a08898aee8a3e0fda49036eefb378b.nq.gz
│   ├── 8ecceb1741e2021ef4a3f7dde063eeb41941040f.nq.gz
│   ├── 9b3703a912d40f58fb0fb57d20742e53d9fe7671.nq.gz
│   ├── 9b9e7355f4688ffb8bec3da9dfdaa3d2dab35d88.nq.gz
│   ├── 9ccc7363dcc9155dec920e64a9820737d3fff0e3.nq.gz
│   ├── a173f085d537251174ce3edb335e732b0a964573.nq.gz
│   ├── ad62673dfff9473923c21ff39e793a861a7af574.nq.gz
│   ├── c08a79032592be8f5e7318991b0242323389469d.nq.gz
│   ├── c29c82157a8962e6cfa4aea56e7fe1da9d8f6dde.nq.gz
│   ├── c6718de5c5ae59d2c22141a147f5afba41af9cbb.nq.gz
│   ├── cc98b6933cd0df2705fd39225f24282258cd3685.nq.gz
│   ├── cd4b474a626af728d1f37d7886c7c9fe91559903.nq.gz
│   ├── d47e369517c7d67ef090b8fe2db7ca060ac6964e.nq.gz
│   ├── d62fc66df4b9acdd5381753fde4173a5775b1ddf.nq.gz
│   ├── da0f5ecf8515cb7801bdcfff836522de46e44c44.nq.gz
│   ├── e0cc7473d75f70aaf1c388f67a58c9b2dde3e29c.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea6d05ea8f9d193059c6b06318dbcc5229e7b33a.nq.gz
│   ├── eb8e7c128167a6e4e183ce0f2912335e17c31c3c.nq.gz
│   └── ed3a9d377ba3c30e6eb8b2a35e08e8dc814a0725.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ad950b84a8b2d4606a50c4f87c465976208be5a4.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 58 files
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

[UKPLab/eacl2026-culturecare](https://github.com/UKPLab/eacl2026-culturecare)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
