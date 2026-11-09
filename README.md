# Repolex Knowledge Graph of diegoveloper/flutter-samples

RDF knowledge graph data for [diegoveloper/flutter-samples](https://github.com/diegoveloper/flutter-samples), parsed by [repolex](https://repolex.ai).

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
rlex download diegoveloper/flutter-samples
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── feb76b20167fe2686d6aaf3a922d645d216959ec
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── feb76b20167fe2686d6aaf3a922d645d216959ec
│           └── chunk-001.nq.gz
├── blob
│   ├── 00c8f9081e7730e20ec8b6a751f3e09a10dae8ef.nq.gz
│   ├── 0156fefa5575d5879ca2f8b0ca33db1dbcc91c0d.nq.gz
│   ├── 0293109801f99009f70cb71e95da336326a466e8.nq.gz
│   ├── 0760d4bf7e74be0e3980184dc73b87ae48eeacbf.nq.gz
│   ├── 09d4391482be68e9e4a07fab769b5de337d16eb1.nq.gz
│   ├── 09f8028cbe51f89499ff141ed876bb15647dac95.nq.gz
│   ├── 0afa7cbf72ccec8bb86d1318b8bbe480db77c7ee.nq.gz
│   ├── 0f0a6193ba5e040a88c639193d9806f4bf3f4780.nq.gz
│   ├── 12237c993d91ad5eabb05b14949acdf363f6ad68.nq.gz
│   ├── 1263ac84b1059dba93f788b61ec40796285dab40.nq.gz
│   ├── 13b235e604588c6dda1c18e9cb6fb179a52b19cd.nq.gz
│   ├── 15ea2599aba0afcf32aa0f3e660ba838c01ad9cb.nq.gz
│   ├── 17987b79bb8a35cc66c3c1fd44f5a5526c1b78be.nq.gz
│   ├── 18d981003d68d0546c4804ac2ff47dd97c6e7921.nq.gz
│   ├── 18f8cbf59298a1c490b5592aa1ca5e29cad49f7c.nq.gz
│   ├── 1908e46aa06c2f5968d7beaed3c6dc7d91dd55c3.nq.gz
│   ├── 1f7d5ad9cb3fb274aff01f62a42af73e11895fd6.nq.gz
│   ├── 203a44c7a79a63d0b04864e8147f4cd260e68f37.nq.gz
│   ├── 2068cb8b4271fd61def800e034f0952a364f7a1e.nq.gz
│   ├── 209db2cb55977164b85e1614177b854258bba668.nq.gz
│   ├── 21a3cc14c74e969ab1548274a8512ebfecc40f78.nq.gz
│   ├── 24337330111cea71eff45f4bbec00227aa3b4ed0.nq.gz
│   ├── 24c622c9f966488fba4fad0700d7752e33694f18.nq.gz
│   ├── 255529a4ce2f773344f28a43787e453730b8a2c1.nq.gz
│   ├── 264bbd2cab4f51ff69d8238578ac9bb9cdc7aec6.nq.gz
│   ├── 2683a262265c4a8ebe856cf0fe1307b649688c59.nq.gz
│   ├── 28c32aa8235c8c70665e7a1a132efb745bf0fc89.nq.gz
│   ├── 28c6bf03016f6c994b70f38d1b7346e5831b531f.nq.gz
│   ├── 2b2e31ec6d600329ea5ebe3173e02d7ac74bb4ef.nq.gz
│   ├── 2b6bebab3282976883b633e84680c65933b4cc7f.nq.gz
│   ├── 2c978b64d007195c3a5e864d18e527b4f8251ae7.nq.gz
│   ├── 2ccbfd967d9697cd4b83225558af2911e9571c9b.nq.gz
│   ├── 31a953b5df20507984e7d8431f4cb0192757bd26.nq.gz
│   ├── 31b3e2f885d6b76dce37738937bcf6f170afa652.nq.gz
│   ├── 349b655523ec9721e708e74fafd43e258df3e8bb.nq.gz
│   ├── 368d670316cb9947ffc1a9f4e116671e5014f7b0.nq.gz
│   ├── 36e21bbf9cf407bfa7968f28d35675da72c6c6c0.nq.gz
│   ├── 399e9340e6f617f68676161ad4a64edcbe483115.nq.gz
│   ├── 39dea7706bf58b02ddf37d435141b69fbaca1b22.nq.gz
│   ├── 3d43d11e66f4de3da27ed045ca4fe38ad8b48094.nq.gz
│   ├── 3ef03ae76bfca6eff6085e621786a806447680bc.nq.gz
│   ├── 4460cd5b95cd88f687563bc136bed55f9cfca1d9.nq.gz
│   ├── 45642ddb1c94ea95d3b58fda3527dd6b3ec7619f.nq.gz
│   ├── 49855b7f623689fba5f8c3ae3f8ccd7c27dc5618.nq.gz
│   ├── 4a5cbb7d49904961f46bba5da42b0260bd46f811.nq.gz
│   ├── 4ae170542049c8f859d9136dff542d6507960a6b.nq.gz
│   ├── 4cde12118dda48d71e01fcb589a74d069c5d7cb5.nq.gz
│   ├── 4d6372eebdb28e45604e46eeda8dd24651419bc0.nq.gz
│   ├── 4e4e51910479cae1d4eb190798027b657a642b7e.nq.gz
│   ├── 5590c3ba0f869a94f2519dbbe400492ba5702b3a.nq.gz
│   ├── 57b24d58c419a260b638b928234c56d5445d5592.nq.gz
│   ├── 5a2f14fb18f6e8b8c4308ff0f0dc187d9d27a5aa.nq.gz
│   ├── 5ad5329d3792d158fe69795d2722d101f774746d.nq.gz
│   ├── 5b2b73b83ea49a6d0c3c43c3e8de897676d83e5d.nq.gz
│   ├── 5b463c3d57ecb343bc2601d24855a0763b12f1c1.nq.gz
│   ├── 5c4087fd7445dab30a341d984878800182599211.nq.gz
│   ├── 5c98b5a8c55942610d6375ff1bf5607945e07a22.nq.gz
│   ├── 5e723256c97a12cd5ac6433a601ef720eaa552c8.nq.gz
│   ├── 5ecf4bae2d430e4a5049eb6db9f9a16b9d841853.nq.gz
│   ├── 5edd5b6e1cd29c3e2a4ed04c6e78b993a94379fe.nq.gz
│   ├── 5fee1f96c5edaab83981525addf3c9b29a75fa63.nq.gz
│   ├── 6329b5cfd3f7453f5c39c58286cbf810abc433dd.nq.gz
│   ├── 63ab3ae08f9e4c3ddbbac64e0c3aadee390f7c22.nq.gz
│   ├── 65b7315af1b601459e7f93940be2cad3462e2aa7.nq.gz
│   ├── 6a84f41e14e27f4b11f16f9ee39279ac98f8d5ac.nq.gz
│   ├── 6b5b6e37e771eb85bfa3eab6bd6625a9b17bc775.nq.gz
│   ├── 6de372893df43da11ae38e41d46aa5b4fdf28afd.nq.gz
│   ├── 6eb4475e7de1f9f69716b8c34eb9d774d36d0d5e.nq.gz
│   ├── 6fd65d8b8c16da30ebd470ac1b9e1426c6a339fa.nq.gz
│   ├── 70693e4a8c128fc4350b157416374ca599ac8c7b.nq.gz
│   ├── 718aaeb024d667cdf81f2de0e448199089053fdc.nq.gz
│   ├── 7335fdf9000cec1b6c1e3f506b196734e8a427ff.nq.gz
│   ├── 73f1d0bcae122b5a512e68882e00a39bacd45642.nq.gz
│   ├── 74857ea4a85d849a039888d6b6c7f048112a8a90.nq.gz
│   ├── 7523b406733f6ee71ed50b1906cb3af675f48dc4.nq.gz
│   ├── 75b2d164a5a98e212cca15ea7bf2ab5de5108680.nq.gz
│   ├── 7722c3e3fd689ff030dc3c2ecb48ec9d7f36efe7.nq.gz
│   ├── 77d221dc891dbcdb79fddbbb96b8420dd28a3de5.nq.gz
│   ├── 78ca24a2a1fa69d5ba0bd356388a8613758281fb.nq.gz
│   ├── 79cc4da802e98c076d3d5aa5ab24eacd64e715fb.nq.gz
│   ├── 7a0ed161b5ded357a733d7fd7e15294010ee273c.nq.gz
│   ├── 7afc8ca1ef669f7a52a081cce3f811e6d4841bbe.nq.gz
│   ├── 7bf5b89465c8e442b92e24b497a98b774acdb9f8.nq.gz
│   ├── 7e22241c0f91a8e189cb30cfd88b6782dfa8f2e9.nq.gz
│   ├── 80f2374b9041a59dcd63188f254fcce21d086bee.nq.gz
│   ├── 82403edb59b79bb9414a90e60dcccd43a3352b39.nq.gz
│   ├── 83e845df088d095e67d68886382c0cb87d02c58d.nq.gz
│   ├── 89c2725b70f1882be97f5214fafe22d27a0ec01e.nq.gz
│   ├── 89dfd22400cdf77741a466399c16d7a31f207320.nq.gz
│   ├── 8b168bd67ee2e9ed806649b2091e2a4cab4d5792.nq.gz
│   ├── 8cc48a10a0875ba85e039c4aacbf4fc9230c2226.nq.gz
│   ├── 8d8b3ea23642b3728eaad6f6ff3100200f3d58c6.nq.gz
│   ├── 8e0d5690b12e4c8eb45bb257e55f230cc15bb127.nq.gz
│   ├── 919434a6254f0e9651f402737811be6634a03e9c.nq.gz
│   ├── 9588d80bb67d625485fa7604534a165e2e82beeb.nq.gz
│   ├── 9adbeb3fb44bf86bc514193c662bd1781640a03b.nq.gz
│   ├── 9da19eacad3b03bb08bbddbbf4ac48dd78b3d838.nq.gz
│   ├── 9e28bdbf51232a59b662dec65097fc198142a48a.nq.gz
│   ├── 9efbe87f3e0fc2f4311f9ec6509370693cba7859.nq.gz
│   ├── a01bb887611078858ddbb56a7597492f5545c51d.nq.gz
│   ├── a076dd4c410f7e83a775c7472b057b29eae7564b.nq.gz
│   ├── a39f35016ec523fa5431f9e6657acb94a91b7d21.nq.gz
│   ├── a53449c380edf19fcdb3c051d6394098864aa898.nq.gz
│   ├── a5965ab8dced71464f52d81becbc8397b4610413.nq.gz
│   ├── a5dd86fd9a643dea0a59b66233d20d343295754f.nq.gz
│   ├── a6d6b8609df07bf62e5100a53a01510388bd2b22.nq.gz
│   ├── a843775cac444f39b01cf98fb85ce59827431344.nq.gz
│   ├── abb5db8a7fabc69f8ec6f50c728cc5580d29f91e.nq.gz
│   ├── aee8b3cb2706d00a75bccfdca65a21098e2fc393.nq.gz
│   ├── b0b8f739a597fb1dcd4d59be4c47caf535f1b626.nq.gz
│   ├── b0de641d8e9cc4f597dc4aca38e499b8c406d73d.nq.gz
│   ├── b38188be3f45ff7cdb6910e4a2cdbcba9c25fd79.nq.gz
│   ├── b5c9c6044ea26d431d71ad93ccf3583e5d0469eb.nq.gz
│   ├── bb2ac2957123bc65ceac1b7331f237b97958c62b.nq.gz
│   ├── bc37158387f333573bd1e952fb944af8a267e37c.nq.gz
│   ├── bd84b65642b39d27e10630593b36f9f78512cd3c.nq.gz
│   ├── bfd60c4868a4aa8313e4112929f7404521838797.nq.gz
│   ├── c18d8e2de8f7c5ec843d03a5d158d0790cbdad94.nq.gz
│   ├── c213beac9f5ace6abe1c7f3b6a34687a6b87f0ad.nq.gz
│   ├── c2a3a08944ba197fb02783de6e5b93548cfe0400.nq.gz
│   ├── c47306dd200d0d5c368a23d13eac470d4bcd3fd6.nq.gz
│   ├── c4df70d39da7941ef3f6dcb7f06a192d8dcb308d.nq.gz
│   ├── c8f9ed8f5cee1c98386d13b17e89f719e83555b2.nq.gz
│   ├── cb29018708727eb493215332b37ea9dc3eead0ca.nq.gz
│   ├── cb786c8cd4169057b20a13c025e06c9d96e61315.nq.gz
│   ├── cea23ecef0ace7dfbc38564fc016027de2c3b3d5.nq.gz
│   ├── d0e052fcd9850096df0c5e202a22031cb3afb2d3.nq.gz
│   ├── d0e1f58536026aebc4f1f70e481f6993c9ff088d.nq.gz
│   ├── d0ef06e7edb86cdfe0d15b4b0d98334a86163658.nq.gz
│   ├── d1fcfeb67bca21ca69a7ffbf7f123d50ba2e0f01.nq.gz
│   ├── d45644da07d46afea162459d86214684d952cf22.nq.gz
│   ├── d5f1c8d34e7a88e3f88bea192c3a370d44689c3c.nq.gz
│   ├── d97071652afbd47ac41616c252439cb24d60d552.nq.gz
│   ├── d9ef4779be292079c267eae708ff07a210fb1032.nq.gz
│   ├── da33b82c348f1a2d87059260af3fd36fa25bace4.nq.gz
│   ├── db77bb4b7b0906d62b1847e87f15cdcacf6a4f29.nq.gz
│   ├── dbac71fe4eb14e36b37c910e4f56b522ad3f2e67.nq.gz
│   ├── dcdc2306c28505ebc0b6c3a359c4d252bf626b9f.nq.gz
│   ├── de7cbd61df177236629a6411e563ef88b2af5e87.nq.gz
│   ├── dff6597e4513dcf90c13b17495c78dd1069cdb20.nq.gz
│   ├── e1c043552b5c090b94ff702ba99194081ff279f5.nq.gz
│   ├── e8efba114687be7d0e4e5d026a31f5efd04d20bf.nq.gz
│   ├── eaaa68332be7a63e2edba3aeeafa4963086293fc.nq.gz
│   ├── eac01579bd8d225c656490092a4be389cbe03695.nq.gz
│   ├── ecd1da6d7f28ca601a140d4a69a0665a9d3e8960.nq.gz
│   ├── efdf5466865b18946c38286a82878722ffa01a42.nq.gz
│   ├── f091b6b0bca859a3f474b03065bef75ba58a9e4c.nq.gz
│   ├── f2ae5d004e209e91d64fa0451444e32f397a9448.nq.gz
│   ├── f3c28516fb38e64d88cfcf5fb1791175df078f2f.nq.gz
│   ├── f4882ac8714738713be8b111966c2d43d9666ca2.nq.gz
│   ├── f9f35a1779131648f391228ba544b060a9925e15.nq.gz
│   ├── feb74e36111b567600b42d2d8eb3cc32b749f9da.nq.gz
│   └── fec61490bad396cdba36161f6955acd59afecea3.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── feb76b20167fe2686d6aaf3a922d645d216959ec.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 161 files
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

[diegoveloper/flutter-samples](https://github.com/diegoveloper/flutter-samples)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
