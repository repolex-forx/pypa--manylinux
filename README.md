# Repolex Knowledge Graph of pypa/manylinux

RDF knowledge graph data for [pypa/manylinux](https://github.com/pypa/manylinux), parsed by [repolex](https://repolex.ai).

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
rlex download pypa/manylinux
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 57bd9a6e8f11b7ac7e7a26c0757782eb60bda143
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 57bd9a6e8f11b7ac7e7a26c0757782eb60bda143
│           └── chunk-001.nq.gz
├── blob
│   ├── 00d16fcf718b0b795b25bcaddf21cf8ae79ece51.nq.gz
│   ├── 00ef3b43c9e14380daad85a05f458610beae17f7.nq.gz
│   ├── 01ad2198f156be63ba4c22899509b69a64408702.nq.gz
│   ├── 0352128455ac785b522b2578f757aa78b9f382f9.nq.gz
│   ├── 09692214b3c70422758df504f2551b1178304f56.nq.gz
│   ├── 0cb8fad5c2463a33e03db6b6594b038be84c9b45.nq.gz
│   ├── 12d151617a283db69ae22b433cf9aeefb141860f.nq.gz
│   ├── 1589d0ff0fabdaef78a440c8dc9a9e485e35ea40.nq.gz
│   ├── 17e7670ef0df0b9cfef91d89384bd973e5fc4b1b.nq.gz
│   ├── 1b8e87a5265d8407a65374b7dfe756fea5defa12.nq.gz
│   ├── 1dbd6ef20470082093a4f502b7ec2913a3f08968.nq.gz
│   ├── 1e817f4e9a1cf9ff9d2e10ac93e1ef387f968740.nq.gz
│   ├── 273c9cdf9cf0d00c80c6349de790d23d0abe1860.nq.gz
│   ├── 273df419fdd803be953c765fc2034018f44dbb4c.nq.gz
│   ├── 31ed2dbc3503c3bb4fb4ac74cffea2777752bbb3.nq.gz
│   ├── 33caba731b8969b530dbb1b364b7245aeee5e60b.nq.gz
│   ├── 366926300bb9cc277295a7fd2b2f157ab89b8f0c.nq.gz
│   ├── 3831d8b48c7573a08f057108a19e3768d03a21c9.nq.gz
│   ├── 38cd6b436e863a4e12c1bfddd5f72cf68e4384b0.nq.gz
│   ├── 4023d6948a208fb561077028a803bbc8901e05f9.nq.gz
│   ├── 455bec708d72b4b76ffaa8a82784c04e441f1f51.nq.gz
│   ├── 4a51e0e51e2b523bd86bc6526a62eff3845ec551.nq.gz
│   ├── 4c65d26a466aba3ed2456be5021bef20429632c7.nq.gz
│   ├── 4d217b1879677a79441e0a52bbe47178050067fa.nq.gz
│   ├── 54a4099f422916b21bf0ac8d6cec2c2231eec337.nq.gz
│   ├── 55cf897e883a5120999a26f2bb294c9b156abb28.nq.gz
│   ├── 569cc4c75b998e68506016d8a83e4cff84f17f20.nq.gz
│   ├── 5f21013bed1a718dce3a82c8cc2eb77f1cc751f7.nq.gz
│   ├── 632bcf9a034dff9c37cff66a990911d82a705932.nq.gz
│   ├── 668eaf43a0d47ebdf557d37d86d45af341162d54.nq.gz
│   ├── 6a655fb52977bdd2209f13dde56c9e6eb38520fb.nq.gz
│   ├── 6c535deb5e4afb859ca2a3e1f3dc58ad73275eb7.nq.gz
│   ├── 70586eafef472154fca8e6f393ab44faa48e1c60.nq.gz
│   ├── 7d8f7841a619794a19426e42b779567a68314439.nq.gz
│   ├── 7e6cd40f1e47d7764a8811ba0a54878d1873f7b8.nq.gz
│   ├── 7ebabdfbcfd2a45b6bd0929a81f151b70f9efa0b.nq.gz
│   ├── 8254e2d45f36e6afd2d955feedcc143543deaf39.nq.gz
│   ├── 86f35b7ac3c46468b26f4534464259c7abaefd2e.nq.gz
│   ├── 8735588b5deff98e4f20a7c5723eaf6dfd713c02.nq.gz
│   ├── 877ebee013a80642528b06edee9bc3058f21f156.nq.gz
│   ├── 8af882e34d0a2ad61a45e7ace95097de2c545866.nq.gz
│   ├── 8c01ff0910e633cbaed206e6b7f82a1a3029dab4.nq.gz
│   ├── 916960982f258158578b60f78b4379f55172bb11.nq.gz
│   ├── 91ab1df8798fb254dee87f5e2201bc76e69bff42.nq.gz
│   ├── 94f6d41bfb606c0da6395442064bb370182907f7.nq.gz
│   ├── 9772051376fdacae5121c1a54e520c8dcdbd2b61.nq.gz
│   ├── 982f8030975f3a08cef55fa5c3912151109e93ee.nq.gz
│   ├── 9c11ff078bdeff18d0f2d4ceddf85e612d8c8dd1.nq.gz
│   ├── 9e055a9d6e6913d564f2eb30124b02f18ee70d96.nq.gz
│   ├── 9e75e830d5c0c74624ddd615004ae83d154f247e.nq.gz
│   ├── 9ee14414b9a7dc254d148150b51918bb623830ef.nq.gz
│   ├── a6a86cf999354631d46ef121b2a0d93082c6b95a.nq.gz
│   ├── a77099ca91bb613d5cbe6764f57bd488f7b7d674.nq.gz
│   ├── a84b1ffab452576aaac83182fb6fe3338be8c198.nq.gz
│   ├── ac2e96c225fab60900e18edf7a58595474ecb31c.nq.gz
│   ├── af0298a38fe2786f632512cdd2af5df23b8451f6.nq.gz
│   ├── ba22ea62a5d330a72a2e1b2164c71804017f6c4d.nq.gz
│   ├── c47ba8cbc490a3f904264cb00ccfbb3bce44e61f.nq.gz
│   ├── c74f773325749567f5d39edfc94635279a734c07.nq.gz
│   ├── c8fc176368484ba4545f3a70b0ef6dec0d0e43be.nq.gz
│   ├── cd6b651dfa12f31d49b1946926906c5419229a6b.nq.gz
│   ├── cfc8a2294e03228b5c0faf499130fd82b8bbf678.nq.gz
│   ├── d7054e480b063cdc607b8ae075b91cf46b814c27.nq.gz
│   ├── d96d0593b11c115b5ed94b94d2c0c60ea1ee80e2.nq.gz
│   ├── da11f4c4c3cc373c68031fb0a7e631c3f88b22e7.nq.gz
│   ├── e1289aca47f2ef9eef022a22283ccf8ae64e17c5.nq.gz
│   ├── e315a40f8a781389aeceea9abf99de6e65821263.nq.gz
│   ├── e39daf90eb007489ec2ba82cb218d340467dc9b7.nq.gz
│   ├── e49434037cf4d3a9611f8ab03b62ab44112bac45.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea5f62345327b6ae1c50d49006bf1789b742af8c.nq.gz
│   ├── eb69f33798dc8f2ebdfe44416709075b18858d4e.nq.gz
│   ├── f40a654efab9d8833ac179d521157796952a9131.nq.gz
│   ├── f97a57d745f8a360717d0b2f7e75cf4e447dfe82.nq.gz
│   ├── fb58799c31243a7bcd63b00fd954d3d2cd91852d.nq.gz
│   ├── fd06df837b9f33ef004a31f87f29206efd2aef78.nq.gz
│   ├── fdcaf32dec4572fc8f499c92a86a27521095774e.nq.gz
│   ├── fed528d4a7a148fd0bf0b0198a6461f8c91b87e9.nq.gz
│   └── ffac3a5188e52f5b0f8dd57b00b5b7f913abc593.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 57bd9a6e8f11b7ac7e7a26c0757782eb60bda143.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 87 files
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

[pypa/manylinux](https://github.com/pypa/manylinux)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
