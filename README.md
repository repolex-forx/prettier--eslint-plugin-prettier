# Repolex Knowledge Graph of prettier/eslint-plugin-prettier

RDF knowledge graph data for [prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier), parsed by [repolex](https://repolex.ai).

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
lexq download prettier/eslint-plugin-prettier
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e2c154a7214d4548dad225a56ee1e333d6389b66
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── e2c154a7214d4548dad225a56ee1e333d6389b66.nq.gz
│   └── repolex
│       └── e2c154a7214d4548dad225a56ee1e333d6389b66
│           └── chunk-001.nq.gz
├── blob
│   ├── 02cbfc1a37163227ce26fbccda999c16a071d209.nq.gz
│   ├── 1451209f44b626ef3e6f0b8c3e719db99fb791f8.nq.gz
│   ├── 1595da216fdb03fc316dcf8788016f4c55435019.nq.gz
│   ├── 1903de421465e6bed7485a6c7556af5d31e02f41.nq.gz
│   ├── 1ca87ab7d8af25af84fa99e86561a75ba4c62a58.nq.gz
│   ├── 2433bcf21a7d28b773ebd8f62efc5453b0fe4645.nq.gz
│   ├── 2478a32abae641f32a9d5b18d2dff185768626de.nq.gz
│   ├── 26864ebf2b104771fe669f7d2559bdb1a7c5859b.nq.gz
│   ├── 27732fcc410b64c6af5c35facc789010dd1f1edf.nq.gz
│   ├── 2bd5a0a98a36cc08ada88b804d3be047e6aa5b8a.nq.gz
│   ├── 3658f9a4d1777bf18d5d5aad105167d08e07b4b0.nq.gz
│   ├── 3696a6d53518c4e7a0a1c112f790c0a51da2ef43.nq.gz
│   ├── 38117f6b84d33963b85c8f727bf704bef376b7ea.nq.gz
│   ├── 4175101fdb240814896100333bc5cf35111f29e9.nq.gz
│   ├── 434147a1c4f45f6d5aa5a527eb84b93628cf3438.nq.gz
│   ├── 4376ed4a37ca825ab1c4b31652d6afbb82dedc51.nq.gz
│   ├── 47a9ac4a4e9a51f7af57ab823cf97f356cdb525d.nq.gz
│   ├── 48ce7d30ee2887df3b35a72e8ac1d349f8d25eb8.nq.gz
│   ├── 4ab8063b0d5c4e2c154f901c7fdf00264e3a81d9.nq.gz
│   ├── 4ba52ba2c8df6758685c8f65f490306b5c44eb76.nq.gz
│   ├── 4ea8c5ebc5eed33449f76b7dccc7fac0a68d261f.nq.gz
│   ├── 4f26b6caa4101e4469d20a7204a9d49c1167da51.nq.gz
│   ├── 542cd300963de3b7760771f39f6640a1c28711e8.nq.gz
│   ├── 544138be45652abc7bc3873341deacd3f4f90c61.nq.gz
│   ├── 5e38ab980ecf84d9a4686512c6443175cf768fe5.nq.gz
│   ├── 6313b56c57848efce05faa7aa7e901ccfc2886ea.nq.gz
│   ├── 6a62e01a0fb3a3afd8265286374d963a21dac0ac.nq.gz
│   ├── 6b07ceb03fb88616d23d7417075e245d419b2168.nq.gz
│   ├── 6bc12623d1b69a98af0ca80fc457abd838eb8151.nq.gz
│   ├── 71a847ac6b51f459ff1178b8b4dd88ebd33114c3.nq.gz
│   ├── 770f20c361c4fc15ff8dd0d443fe37de3b2654dd.nq.gz
│   ├── 798f6331b65c0f9451410f1e48ee21b18d8a24ea.nq.gz
│   ├── 7a6ecedaf60013f14308f636dfc031e0647fe099.nq.gz
│   ├── 7d037f756d46ebbebae3bae57671c9d07e42b82e.nq.gz
│   ├── 8044e88b256d0ff304d974657ac2c6e3578ecd7f.nq.gz
│   ├── 80de1e61ab150958cace07ad5ea7932a7efe754e.nq.gz
│   ├── 8368378fb0769327bb2d556012fe8cbadb6f9ba5.nq.gz
│   ├── 874276faa305449eb6e9e3f07913aa5ddba91015.nq.gz
│   ├── 87a572089c4200076febc2feadb2096b59b4ca8b.nq.gz
│   ├── 889f570f596dadf3c001fd3a928ca80847b949d6.nq.gz
│   ├── 8a61ef1aea05bcdb9cd8985f95686db684705e69.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 98ddcba4a0e989927cd3a69c13eb7e0025371cbe.nq.gz
│   ├── 9b5d7d858471d0ca655b6ba243c967a142a8ae5c.nq.gz
│   ├── 9bf67b5d95e18fbb66ba66b10daa3d8807b18d40.nq.gz
│   ├── a9e93973e28b317b22fa81c03b524fd4d9dd50ef.nq.gz
│   ├── aaaa7a4baa810b35ead481330c05f4d6833b5384.nq.gz
│   ├── b27f64f8fd6f2434fefd1549e3cdb3c3ba1800be.nq.gz
│   ├── b852772d55fa67d85e24884dbacc07987480e57e.nq.gz
│   ├── bb557390fcf9f49bd11c95ad5c8045235959f8db.nq.gz
│   ├── c1df518445c2cde2102703be9a091a02470d4a3a.nq.gz
│   ├── cba4cf4ef9ecbf019d2ac1c7fb17cb80c07b4edd.nq.gz
│   ├── cc5ee1c138f31cce804f4ead81f5d81905bdb1be.nq.gz
│   ├── cce31b08c1ba9bde73e97cda8f16c7f1d090d491.nq.gz
│   ├── cce9d3c0801773cf33a36f6e57afe78a06eebb89.nq.gz
│   ├── cdfc47a6be9d8c488f9dcb349f5372f584f013ae.nq.gz
│   ├── d76c6c50f40d1c7613691097d4ec913887ab0886.nq.gz
│   ├── dc72ac94da6cb5e9d144babb6b00b14754c9725c.nq.gz
│   ├── e4b1d416da2d421e9c8d8b4fbe25e902a1209929.nq.gz
│   ├── e4c37f6a396d48c45c7bb4958b97511aa8430138.nq.gz
│   ├── e4ebd54cb460d3e80a1899f64d21dbd36d51b97f.nq.gz
│   ├── e5b6d8d6a67ad0dca8f20117fbfc72e076882d00.nq.gz
│   ├── eafdb4a18e8b260aae8ddfa122a48d60cea65f83.nq.gz
│   ├── ee81827e283f13b7de2ceb93ebef8bb601c14520.nq.gz
│   ├── efc556c011d75d3a0a4723d9b17e5fd74c221c99.nq.gz
│   ├── f088a64cca35c7f36db6791958c0bafdb9c701e7.nq.gz
│   ├── f33b21a4d8e398cbd490074dc1e8d431a1c95a0f.nq.gz
│   ├── f953c02959dceb9627a20209c96e0e6a60f70bbe.nq.gz
│   └── f97a86d2ec14d57b77200c34c75e012bfc651dc4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── e2c154a7214d4548dad225a56ee1e333d6389b66.nq.gz
├── filetree
│   └── e2c154a7214d4548dad225a56ee1e333d6389b66.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 79 files
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

[prettier/eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier)

---
*Parsed on 2026-04-17 by [repolex](https://repolex.ai)*
