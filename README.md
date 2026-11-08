# Repolex Knowledge Graph of canonical/jenkins-k8s-operator

RDF knowledge graph data for [canonical/jenkins-k8s-operator](https://github.com/canonical/jenkins-k8s-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/jenkins-k8s-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── bae70e437c92ac58930308087e234be2b9ba504d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── bae70e437c92ac58930308087e234be2b9ba504d
│           └── chunk-001.nq.gz
├── blob
│   ├── 00f31c31fcca6d80340c52e02291cfda7a75c32b.nq.gz
│   ├── 0216ae2beee8a90ffbf73342cedb490bd12f8830.nq.gz
│   ├── 02361050a74f8c7508cc12ed3d26ae641a0352af.nq.gz
│   ├── 05a2357cbabb27aad9661a782c00e42eaa141f65.nq.gz
│   ├── 05bd46ea152de8da2e602c064c211abaf5a44cd7.nq.gz
│   ├── 073ccfceb10f2f5102059fff3aa22166c88f668d.nq.gz
│   ├── 0787646b750afed28151e334ac0cfd1fd2972324.nq.gz
│   ├── 08233f572e14e058e4b188c41006a9e908d641f8.nq.gz
│   ├── 0ab19524aaf63e055d16fc8a648180c6a524e360.nq.gz
│   ├── 0af532c40fe749853fb98f7c8aa2c48c60af8099.nq.gz
│   ├── 0b44a226b7e7eb6d5fda82ed03e636865961ec00.nq.gz
│   ├── 0bc332242de19250316b6b4c208c8f898e7252ae.nq.gz
│   ├── 1662082cb936e25b756584f77db6a239759daf9c.nq.gz
│   ├── 17c0ac0b5dc8e9a94bcb994201db7731683d570d.nq.gz
│   ├── 18ce6c1eb00bf9c1071b751ce9e4f07479ff0bb2.nq.gz
│   ├── 213ec01d15a4e63159e610b387073bf3c6028137.nq.gz
│   ├── 23438ebb51b3a008509fd2d657c3e028b66beec9.nq.gz
│   ├── 23832c0085d0706bb1acd8e1d68294a128a122b6.nq.gz
│   ├── 2513df62bb49ef025f4d626d8c9a8df9b7cc366f.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 26ac226df88c6bc3785214f437d30606702a7736.nq.gz
│   ├── 28df0ee71d4894137a83219463a9b4d7f6425116.nq.gz
│   ├── 28f15cf8eb127e93835944ae5e57be63f36257e7.nq.gz
│   ├── 2a1d76743ca79a66c082c02609187d73eb378dbe.nq.gz
│   ├── 2b6a8846721ef6997d81c06b5374963d93127fb3.nq.gz
│   ├── 2cdda9d818698aa83576ecf6207e21ba05f6a5a3.nq.gz
│   ├── 2db7f38922b53bd3323492fe2532042a05ed74cb.nq.gz
│   ├── 2ec1807eeb4841326db2022b58c76b77ba58ea88.nq.gz
│   ├── 3071b2d180ea44df8365da4f0a8e04d85f50c42a.nq.gz
│   ├── 32286ff4d8bd23fad62ed17b8754d3b8e0fa5499.nq.gz
│   ├── 3372cdf832ee05e9662c2b38bd09673703f18820.nq.gz
│   ├── 347b93daa39084680172e32b968bb0ca2f44ba03.nq.gz
│   ├── 350d969edb9e532c464817dc76bc145c2e282a05.nq.gz
│   ├── 38241f92ea27729903835ee632b2b4882a78593d.nq.gz
│   ├── 39a476b27fbd17f948f61e8f2a1e58643abccd8a.nq.gz
│   ├── 3d0925f9a8d4601d003e1ae4911a08a7cb2ed3a4.nq.gz
│   ├── 3f47d0dbd9c0c2a5e12d09c702620bef2195bf61.nq.gz
│   ├── 3fda8f365bfaedab225c3a372928b4365ff162c1.nq.gz
│   ├── 3fdc69c90454212514c3f118f22acfeec705a021.nq.gz
│   ├── 419e0382c1dddb03c9667bd5e80b51752fa40c93.nq.gz
│   ├── 4469e15ff6cd1e74ffc9c650c4350404b4f8ab5d.nq.gz
│   ├── 45f6674b20106d13e4ea3ed1ebc28cc5d96b3616.nq.gz
│   ├── 46f69e89a035161b647ee50ebf2581ed6e04bfda.nq.gz
│   ├── 497dbd502db0a7bb0d06aaf73d7ec7873e276018.nq.gz
│   ├── 49dd2c7be2d51e67874fb13a326ca8715d0dcd62.nq.gz
│   ├── 4a7015d08b8e842b2e4a31159c50b7659651047d.nq.gz
│   ├── 4b955aaa91ac8d26860c374c6d3a79ca1bbe7f66.nq.gz
│   ├── 4cc9464ae4c4008a453668e5108f51a6adc2ccad.nq.gz
│   ├── 4d03c786248a53358954d700658579e9205c730c.nq.gz
│   ├── 4f13f0380d610d4f0d7d0f6868fefe56d5f1841a.nq.gz
│   ├── 544f89c2a7cedb6f808cccc62f564d45f6987ac7.nq.gz
│   ├── 547bdaf45aced39ce5a21599d5852dea4475348a.nq.gz
│   ├── 55969d643048afbcfabdfa8a3314e271294fff2f.nq.gz
│   ├── 56a6051ca2b02b04ef92d5150c9ef600403cb1de.nq.gz
│   ├── 5747436128204b448f69c218c7443827d3b9b10c.nq.gz
│   ├── 575f60780efd9fd976ce00d58b9176556d47081e.nq.gz
│   ├── 57b60ff9020bd32e920ad3695e582f334458429d.nq.gz
│   ├── 59a13c364e2f65d6d8276b81b67e5a26af28ec38.nq.gz
│   ├── 5a2e4414cc2a554781156ed5fe9f0337ff2e5b9f.nq.gz
│   ├── 5cc50842fb8dedebf08605f972e0507fadc5b2fd.nq.gz
│   ├── 61176c8b8b2885dfad9758bf58c44dd65c7e26ad.nq.gz
│   ├── 64debaaef41793ef5fd27730ace52e21015ce7f6.nq.gz
│   ├── 66e50e976a5cb9e05e2380da7acbc640220c0979.nq.gz
│   ├── 67c7bc790cd28d40719926ac1b221552b960006a.nq.gz
│   ├── 68068624bc26bcfb7d0e8ff1ecaf4fcf45985611.nq.gz
│   ├── 722fcdd3852a3d74610c6d83c5a1e3be00a5cded.nq.gz
│   ├── 72915bf062db09d2d6ca963e40362328f268c500.nq.gz
│   ├── 734eb1802cdaad44c5321b9615ec3e2b5952d5dd.nq.gz
│   ├── 7572ff2cd42d68b69c6bc41aa8cd557e8a2e6c8b.nq.gz
│   ├── 76d4fa286db858f8ae1a037a179c3e8aa7516c65.nq.gz
│   ├── 792ef01e3950ca44b6dcad61eaf1c16cba388ad4.nq.gz
│   ├── 79cccaed7d15244c15efe3f071ab7f445c3a1e9d.nq.gz
│   ├── 7a5a9039f24ed85983183b5503580ce43b4f15c1.nq.gz
│   ├── 7ad9214abcda81bf51dbd97e08391aa0d9695bef.nq.gz
│   ├── 7b66b2854ad2ab82f7b3d3dba669bce2c48df436.nq.gz
│   ├── 7d0657843f5ac6d5d9f16b77c9505fe019ea7a27.nq.gz
│   ├── 7e52278ec15572639b0d5b1df9c590ae5ca83107.nq.gz
│   ├── 7ed021d904286063a5099fb3c80ef7c6a6c17e5c.nq.gz
│   ├── 887a994a8ba1a87e43d733080658c954fc51272a.nq.gz
│   ├── 890da226c101469fbaf52d4df24989f34ce99881.nq.gz
│   ├── 89f1b2b067418f118ff169c8f8c3d1a2558309c6.nq.gz
│   ├── 8a01fb07cd562c51b46e46fb3013067602cb40d3.nq.gz
│   ├── 8bcc80cd57891e9cbe43173ec90d91ef70af673d.nq.gz
│   ├── 8d3315fec7f152b037e42f5e021c892fb304e81f.nq.gz
│   ├── 92e715023cabfc13864bbedbb6c1cce19256b946.nq.gz
│   ├── 95b0e1a6f410b5e20761489f62d5e74e554b449e.nq.gz
│   ├── 97d9843d0054466171e505c2b2b82c7085e71d64.nq.gz
│   ├── 9832e7b13fde2e879589a506d6e180a9df86ac17.nq.gz
│   ├── 9886fc2b40dfc111e4cc7eb94e14591d5ee21aab.nq.gz
│   ├── 98cf245c3c48f889cf82cf44e271feb455a41bff.nq.gz
│   ├── 995253d1a0c726ada81305f182d8b86b77e5ab49.nq.gz
│   ├── 9c1bc090a9409fd314ada213e314b54ff14730b6.nq.gz
│   ├── 9ec0379bc5aa6325087f5b7f7a34e599d82b005b.nq.gz
│   ├── a296acfa8671f9eab935c6895dcabbafaaaed04c.nq.gz
│   ├── a69ac55f05f5875ddb73a0141f581bea23cc0a4b.nq.gz
│   ├── a6f5a3f297863f6b89c08ef59e24abf2f491810b.nq.gz
│   ├── abbfa0938863f98ffd414fac1b1abc9898538185.nq.gz
│   ├── b4880914f3d5ac4c3876dc68e14ad25535a66a24.nq.gz
│   ├── b74a9d8394502e69a85e068d556b7c82bbbfb755.nq.gz
│   ├── b77eb61caccf5738e25dc52736f4248622bb11d6.nq.gz
│   ├── b832499944900bbc48dddb3af25d1d6a38abbd81.nq.gz
│   ├── bab69997ece8a6d12e8c6e3a03e5c5d390897238.nq.gz
│   ├── bdbeafe6fa5daa81338b57ebf9663aa1f042613c.nq.gz
│   ├── bfa2c4644d5ce7e1667b8380a224e2ed13a88a70.nq.gz
│   ├── c04e6ec0a5a6f7ade4589fac1be2ffd99531319d.nq.gz
│   ├── c1a14512861fd651af9c52bc9c056f0fde8f45c4.nq.gz
│   ├── c4c600284cc4a0f8dbe4e566e0558c0ac2bb617d.nq.gz
│   ├── c51f8731433ae312f489f87b230c5aa38ef668fa.nq.gz
│   ├── c74fe8dc07d47e1590f6c8bad4f91db96d5b760e.nq.gz
│   ├── c7ce8a31fc807e8dc18777fc2ab352b20faa3129.nq.gz
│   ├── c9d4413ee972e852ffea5c7fa078c38c8bc6d872.nq.gz
│   ├── cbaa08d6d6de8d6dd11e3f42263ddde55265cd44.nq.gz
│   ├── ceb4c2f6cee8272f367fdc06dc7fa30eaf29cb17.nq.gz
│   ├── cf7444146b5c999d207c33d687b6e45f220a1f49.nq.gz
│   ├── cfef08841651bf0c5a262148d90b3da11473c69d.nq.gz
│   ├── d28431b05ab0579aaf937e58c4a567a6b0f66019.nq.gz
│   ├── d4485ea15defbb7e43d2dfaf59b31171d50fd963.nq.gz
│   ├── d7031890adec26b533a8d53ab56f851b32a2239b.nq.gz
│   ├── dc0acae748e997a3d8757e4bc0ff41d573810890.nq.gz
│   ├── de6f79441bec0bc505aaf706ac8e2a0c0758cc38.nq.gz
│   ├── df3778d621b8226b4eecd947a5dc3be7dbe9a82c.nq.gz
│   ├── df52ee27f537c69be8a66ddd8d9f0400ecfbdc36.nq.gz
│   ├── df541556b4c8b8d1d2040a3acdf1aa8872e9c1a7.nq.gz
│   ├── e0590f76a0f190f02d977471681852b4e4c965f7.nq.gz
│   ├── e0cb73264fcc8d1863b9278aafbde8d608093df7.nq.gz
│   ├── e0f8e89c336f5931f723609eb68f9ab5d25823e0.nq.gz
│   ├── e272e9fde973b9984501c168bc31e2fe21ad87f0.nq.gz
│   ├── e372b6d87ee647cb68b62da1bee015a14be65ed2.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e969aff1d315fb7cba18be7f32d3dbcd6c624eb1.nq.gz
│   ├── eb943824ba5a9bdfd4112cd59c90c3b4546e9e07.nq.gz
│   ├── ef0594ac691a97d8a6a754308aac0ce8bc9c9512.nq.gz
│   ├── ef2f11716363bd35b085fd347ab2b82d3deab313.nq.gz
│   ├── ef9f6f8420211fb0e6d01fc208f7952692073c82.nq.gz
│   ├── f21e04de09fdca1048eff7f1fa796b9bcdccc830.nq.gz
│   ├── f35647af608357679a9997806bc67a05352f28d1.nq.gz
│   ├── f3d2c85aed0e9ac5ec511c3bee69bd5ae2e9142b.nq.gz
│   ├── f826c8d085a5b90581609e53b18a95c07806e0da.nq.gz
│   ├── fc18b9fdffb3a14f91bb7956c25d13c4890e82d7.nq.gz
│   ├── fd7f77d3308ad32f92008b1c87df59eb14a673b9.nq.gz
│   ├── fe05f3f9e25fd7ee3d15960181616de815b0c7d3.nq.gz
│   ├── fe3518b0772aaeea4b156d5d8453f58c15b3ab96.nq.gz
│   ├── fe6468e8d0a1957aba024423c38b9eac57f996f6.nq.gz
│   └── ff52245c9cfaa5bcf811785450528ad234783e84.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── bae70e437c92ac58930308087e234be2b9ba504d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 152 files
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

[canonical/jenkins-k8s-operator](https://github.com/canonical/jenkins-k8s-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
