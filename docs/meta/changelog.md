## Change Log

### 7.1.1 (2015/09/15 20:13 +00:00)
- [96f80c6](https://github.com/maxogden/dat/commit/96f80c6c077     b99630076db74af72f0aec7791a6b) set deduplicate to false by default in cli (@karissa)
- [cb8e7da](https://github.com/maxogden/dat/commit/cb8e7da4f82     48aa0633936f6f03aa79eb0fdf56e) add 'dat' key with metadata to serve (@karissa)
### 7.1.0 (2015/09/11 20:13 +00:00)
- [7a2adf3](https://github.com/maxogden/dat/commit/7a2adf3976d0b71acfb0b8e8ed86553650c63f5a) Fix double prompt bug  on push pull and clone (@karissa)
- [11c4dfe](https://github.com/maxogden/dat/commit/11c4dfe280137c1deae234d14480d833b5d8f717) don't change status api before 1.0 (@karissa)
- [b11dc8a](https://github.com/maxogden/dat/commit/b11dc8a5d95eef721250603e9e51fb42d6dde0dc) Fix #355, properly exits on | head during aborts, closes #356 (@karissa)
- [dc8bea9](https://github.com/maxogden/dat/commit/dc8bea95787be87492fb21218cdc090bc969d4aa) Homogenize the response for dats to the outside (@karissa)
- [f03db07](https://github.com/maxogden/dat/commit/f03db07b92ea7199a921ac67dbe2f7ef22f4132f) Catch clone end-of-stream to fix edge linux bin failure (@karissa)
- [468816f](https://github.com/maxogden/dat/commit/468816f36f3b53e6b15808a061c9102f96e39e74) Push and pull will only print progress once progress has begun (@karissa)
- [04ba858](https://github.com/maxogden/dat/commit/04ba858f5575d9daa4e8073d64860faeadd431c5) move up 'module did not self-register' in readme (@karissa)
- [7783380](https://github.com/maxogden/dat/commit/7783380766bf1cbdd8639bb617cdfeac970cec19) Config should respect --path option (@karissa)
- [3a8da93](https://github.com/maxogden/dat/commit/3a8da930bdffc98ce18ef19fcff292dff84b1037) Replication authentication should only prompt once (@karissa)
- [bb5fff6](https://github.com/maxogden/dat/commit/bb5fff6e304413a1d9c40f34580e22abd32db0b8) Change diff order when only one is supplied (@karissa)
- [1916dc4](https://github.com/maxogden/dat/commit/1916dc405c6891bfa06eadf75258aa0e39d0d931) Allow users to get dat version from an http and ssh source (@karissa)
- [0d3cb9c](https://github.com/maxogden/dat/commit/0d3cb9c786495494c2f5df477546cfe7ebeb7db1) Fix weird clone progress indication (@karissa)
- [f3ecb68](https://github.com/maxogden/dat/commit/f3ecb68a4f33587732950ca5da521fc1bdc43b69) add forks to the status indicator (@karissa)
- [68bcb3e](https://github.com/maxogden/dat/commit/68bcb3e2f2351899791009da0f3737a8f3a37ddd) show errors when transport stream ends unexpectedly (@maxogden)
- [24ccbfb](https://github.com/maxogden/dat/commit/24ccbfbc279b67b2b4192833c15ba162d5354bbf) modularize the serve function into lib (@karissa)
- [1a25ef7](https://github.com/maxogden/dat/commit/1a25ef7bc2c0c0d6651db0c3bc4f9cd810243daa) the server should give metadata about the dat for discovery purposes (@karissa)
- [4cd4cf2](https://github.com/maxogden/dat/commit/4cd4cf232a3b1398ef57ce469b587b7f19d49c84) use dat-core 6.0 to fix speed issues with deduplication. fixes #391 (@mafintosh)
- [834faf7](https://github.com/maxogden/dat/commit/834faf7898c66ca2483a1bcf30b959d994fda3fd) support --live (@mafintosh)
- [b3e3ef7](https://github.com/maxogden/dat/commit/b3e3ef7e81d7dd0751535d65df0f9e0cd221d809) tcp nodelay (@maxogden)
- [d721fb0](https://github.com/maxogden/dat/commit/d721fb02b8ac3b8a3d92126a582a5746d2c5a39c) add fine grained debug logging to dat serve (@maxogden)

### v7.0.4 (2015/08/20 12:26 +00:00)
- [4e25286](https://github.com/maxogden/dat/commit/4e2528622560510a371466bdd9f0e0b9d74c4c3a) 7.0.4 (@maxogden)
- [5d8bfed](https://github.com/maxogden/dat/commit/5d8bfed4aa556d8c6a74171c6706b734cc5ca909) upgrade dat-core (@maxogden)
- [f2dd312](https://github.com/maxogden/dat/commit/f2dd31244f4f928952fe29cad20d9dd0990d8d80) use isArray instead of === 'object' (@karissa)
- [3420862](https://github.com/maxogden/dat/commit/342086286eba0ea1e1ff003647b795fcff8a5efb) Add compound keys to dat import (@karissa)
- [748990d](https://github.com/maxogden/dat/commit/748990dec1c57943cdcc9a24b13a1fe3feb3e419) config will ignore empty package.json files (@karissa)

### v7.0.3 (2015/08/06 18:40 +00:00)
- [bcc17ba](https://github.com/maxogden/dat/commit/bcc17bab29c7dbfaa5a03080fadf33ad1b9d9f0c) 7.0.3 (@karissa)
- [329b3ef](https://github.com/maxogden/dat/commit/329b3ef94a79aea65d491543659fa79dbfb441a4) pull parse-input-stream into its own module (@karissa)
- [32d6e91](https://github.com/maxogden/dat/commit/32d6e912bb72c5416c549caff22dc41ef1275fb7) Allow write from a url (@karissa)
- [75342e8](https://github.com/maxogden/dat/commit/75342e8085cb2dfe80f875dbc72d175f90fe2e49) Status should give the same # of datasets regardless of output type. fixes #367 (@karissa)
- [e3d7e12](https://github.com/maxogden/dat/commit/e3d7e121109fcea1ea6473c583af1c09b6b839ee) changed json to csv (@ArtskydJ)

### v7.0.2 (2015/07/27 18:40 +00:00)
- [754b1fc](https://github.com/maxogden/dat/commit/754b1fc40053ce9e6813567baaeecf7649e042a7) 7.0.2 (@mafintosh)
- [40af056](https://github.com/maxogden/dat/commit/40af056893788462639e16e6652fb5a8be2eeb62) force bump dat-core (@mafintosh)
- [e6bbb7b](https://github.com/maxogden/dat/commit/e6bbb7b0fd3a61b3308ee29b035546cc82ed71fe) upgrade transport-stream (@maxogden)

### v7.0.1 (2015/07/26 22:27 +00:00)
- [c6eeaa0](https://github.com/maxogden/dat/commit/c6eeaa0f99bb17be3daabbe8202d6230c6686f55) 7.0.1 (@mafintosh)
- [f71b385](https://github.com/maxogden/dat/commit/f71b385cb4e6cccb1d79583e5401287b60511e5f) key should always be a string (@mafintosh)
- [347f07c](https://github.com/maxogden/dat/commit/347f07c18e1869d75064a02340ddd651da3c2815) add no-prompt to init docs (@maxogden)
- [16950f1](https://github.com/maxogden/dat/commit/16950f191b9979f13391fb9ae58a3cbfacab5189) revert to finish event since it is the transport-stream (@mafintosh)
- [32a3257](https://github.com/maxogden/dat/commit/32a32570c0dd0705bfef245696033a947584ab9e) replication streams should use end and force flush (@mafintosh)
- [f0b18a9](https://github.com/maxogden/dat/commit/f0b18a97786fa515bf3058780ba14d15021c6bc0) upgrade transport-stream (@maxogden)
- [2d410d4](https://github.com/maxogden/dat/commit/2d410d4597fdf376af6f7d3135631cdde724afb9) fix premature close bug in clone (@mafintosh)
- [7edb51f](https://github.com/maxogden/dat/commit/7edb51ffa88512add02879485508a71333977f37) wait for pump end before calling cb (@mafintosh)
- [a2fbfdd](https://github.com/maxogden/dat/commit/a2fbfdd8a69b774fde67f75fb51b2034d2d7334d) Allow importing from a url (@karissa)
- [3ac22f9](https://github.com/maxogden/dat/commit/3ac22f96e6ea05e6c41d3e41780d3274d71587f3) key arg is not a boolean (@maxogden)

## v7.0.0 - BETA!