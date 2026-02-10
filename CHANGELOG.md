# Changelog

## [0.13.0](https://github.com/wangsu/cc_companion/compare/the-vibe-companion-v0.12.1...the-vibe-companion-v0.13.0) (2026-02-10)


### Features

* Add permission & plan approval E2E tests ([#6](https://github.com/wangsu/cc_companion/issues/6)) ([8590a68](https://github.com/wangsu/cc_companion/commit/8590a68657f0a06e94795a179ad4bbedae782c63))
* add release-please for automated npm publishing ([#24](https://github.com/wangsu/cc_companion/issues/24)) ([93b24ee](https://github.com/wangsu/cc_companion/commit/93b24ee4a12b3f32e81f59a348b25e89aaa86dce))
* allow dev server access over Tailscale/LAN ([#33](https://github.com/wangsu/cc_companion/issues/33)) ([9599d7a](https://github.com/wangsu/cc_companion/commit/9599d7ad4e2823d51c8fa262e1dcd96eeb056244))
* claude.md update ([7fa4e7a](https://github.com/wangsu/cc_companion/commit/7fa4e7adfdc7c409cfeed4e8a11f237ff0572234))
* e2e permissions plans ([#9](https://github.com/wangsu/cc_companion/issues/9)) ([53b38bf](https://github.com/wangsu/cc_companion/commit/53b38bfd4e773454492a3fea10e8db7ffd3fd768))
* protocol conformance fixes and improved E2E tests ([#14](https://github.com/wangsu/cc_companion/issues/14)) ([51b13b9](https://github.com/wangsu/cc_companion/commit/51b13b9d647de6c92881b1abb61161f39152e0ef))
* Redesign README as a landing page with API-first documentation ([#7](https://github.com/wangsu/cc_companion/issues/7)) ([a59e1b4](https://github.com/wangsu/cc_companion/commit/a59e1b4604baf87faa32af7d62e4846afae49dbe))
* simplified claude() API, unified endpoints, and landing page README ([#12](https://github.com/wangsu/cc_companion/issues/12)) ([aa2e535](https://github.com/wangsu/cc_companion/commit/aa2e535fe0a83b726ff2a2c08359e55973a9136b))
* The Vibe Companion complete web UI rewrite + npm package ([#23](https://github.com/wangsu/cc_companion/issues/23)) ([0bdc77a](https://github.com/wangsu/cc_companion/commit/0bdc77a81b21cd9d08ba29ea48844e73df3a1852))
* trigger release for statusline capture ([#19](https://github.com/wangsu/cc_companion/issues/19)) ([cedc9df](https://github.com/wangsu/cc_companion/commit/cedc9dfb7445344bdb43a1a756f1d2e538e08c76))
* **web:** add Clawd-inspired pixel art logo and favicon ([#70](https://github.com/wangsu/cc_companion/issues/70)) ([b3994ef](https://github.com/wangsu/cc_companion/commit/b3994eff2eac62c3cf8f40a8c31b720c910a7601))
* **web:** add component playground and ExitPlanMode display ([#36](https://github.com/wangsu/cc_companion/issues/36)) ([e958be7](https://github.com/wangsu/cc_companion/commit/e958be780f1b6e1a8f65daedbf968cdf6ef47798))
* **web:** add git worktree support for isolated multi-branch sessions ([#64](https://github.com/wangsu/cc_companion/issues/64)) ([fee39d6](https://github.com/wangsu/cc_companion/commit/fee39d62986cd99700ba78c84a1f586331955ff8))
* **web:** add permission suggestions and pending permission indicators ([10422c1](https://github.com/wangsu/cc_companion/commit/10422c1464b6ad4bc45eb90e6cd9ebbc0ebeac92))
* **web:** archive sessions instead of deleting them ([#56](https://github.com/wangsu/cc_companion/issues/56)) ([489d608](https://github.com/wangsu/cc_companion/commit/489d6087fc99b9131386547edaf3bd303a114090))
* **web:** enlarge homepage logo as hero element ([#71](https://github.com/wangsu/cc_companion/issues/71)) ([18ead74](https://github.com/wangsu/cc_companion/commit/18ead7436d3ebbe9d766754ddb17aa504c63703f))
* **web:** git fetch on branch picker open ([#72](https://github.com/wangsu/cc_companion/issues/72)) ([f110405](https://github.com/wangsu/cc_companion/commit/f110405edbd0f00454edd65ed72197daf0293182))
* **web:** git info display, folder dropdown fix, dev workflow ([#43](https://github.com/wangsu/cc_companion/issues/43)) ([1fe2069](https://github.com/wangsu/cc_companion/commit/1fe2069a7db17b410e383f883c934ee1662c2171))
* **web:** git worktree support with branch picker and git pull ([#65](https://github.com/wangsu/cc_companion/issues/65)) ([4d0c9c8](https://github.com/wangsu/cc_companion/commit/4d0c9c83f4fe13be863313d6c945ce0b671a7f8a))
* **web:** named environment profiles (~/.companion/envs/) ([#50](https://github.com/wangsu/cc_companion/issues/50)) ([eaa1a49](https://github.com/wangsu/cc_companion/commit/eaa1a497f3be61f2f71f9467e93fa2b65be19095))
* **web:** persist sessions to disk for dev mode resilience ([#45](https://github.com/wangsu/cc_companion/issues/45)) ([c943d00](https://github.com/wangsu/cc_companion/commit/c943d0047b728854f059e26facde950e08cdfe0c))


### Bug Fixes

* add web/dist to gitignore ([#2](https://github.com/wangsu/cc_companion/issues/2)) ([b9ac264](https://github.com/wangsu/cc_companion/commit/b9ac264fbb99415517636517e8f503d40fe3253d))
* always update statusLine settings on agent spawn ([#21](https://github.com/wangsu/cc_companion/issues/21)) ([71c343c](https://github.com/wangsu/cc_companion/commit/71c343cfd29fff3204ad0cc2986ff000d1be5adc))
* auto-accept workspace trust prompt and handle idle in ask() ([#16](https://github.com/wangsu/cc_companion/issues/16)) ([ded31b4](https://github.com/wangsu/cc_companion/commit/ded31b4cf9900f7ed8c3ff373ef16ae8f1e8a886))
* checkout selected branch when worktree mode is off ([#68](https://github.com/wangsu/cc_companion/issues/68)) ([500f3b1](https://github.com/wangsu/cc_companion/commit/500f3b112c5ccc646c7965344b5774efe1338377))
* remove vibe alias, update repo URLs to companion ([#30](https://github.com/wangsu/cc_companion/issues/30)) ([4f7b47c](https://github.com/wangsu/cc_companion/commit/4f7b47cba86c278e89fe81292fea9b8b3e75c035))
* scope permission requests to their session tab ([#35](https://github.com/wangsu/cc_companion/issues/35)) ([ef9f41c](https://github.com/wangsu/cc_companion/commit/ef9f41c8589e382de1db719984931bc4e91aeb11))
* show pasted images in chat history ([#32](https://github.com/wangsu/cc_companion/issues/32)) ([46365be](https://github.com/wangsu/cc_companion/commit/46365be45ae8b325100ed296617455c105d4d52e))
* track all commits in release-please, not just web/ ([#27](https://github.com/wangsu/cc_companion/issues/27)) ([d49f649](https://github.com/wangsu/cc_companion/commit/d49f64996d02807baf0482ce3c3607ae59f78638))
* use correct secret name NPM_PUBLISH_TOKEN in publish workflow ([e296ab0](https://github.com/wangsu/cc_companion/commit/e296ab0fabd6345b1f21c7094ca1f8d6f6af79cb))
* use correct secret name NPM_PUBLISH_TOKEN in publish workflow ([#26](https://github.com/wangsu/cc_companion/issues/26)) ([61eed5a](https://github.com/wangsu/cc_companion/commit/61eed5addd6e332fac360d9ae8239f1b0f93868e))
* **web:** chat scroll and composer visibility in plan mode ([#55](https://github.com/wangsu/cc_companion/issues/55)) ([4cff10c](https://github.com/wangsu/cc_companion/commit/4cff10cde297b7142c088584b6dd83060902c526))
* **web:** isolate worktree sessions with proper branch-tracking ([#74](https://github.com/wangsu/cc_companion/issues/74)) ([764d7a7](https://github.com/wangsu/cc_companion/commit/764d7a7f5391a686408a8542421f771da341d5db))
* **web:** session reconnection with auto-relaunch and persist ([#49](https://github.com/wangsu/cc_companion/issues/49)) ([f58e542](https://github.com/wangsu/cc_companion/commit/f58e5428847a342069e6790fa7d70f190bc5f396))
* **web:** use --resume on CLI relaunch to restore conversation context ([#46](https://github.com/wangsu/cc_companion/issues/46)) ([3e2b5bd](https://github.com/wangsu/cc_companion/commit/3e2b5bdd39bd265ca5675784227a9f1b4f2a8aa3))

## [0.12.1](https://github.com/The-Vibe-Company/companion/compare/the-vibe-companion-v0.12.0...the-vibe-companion-v0.12.1) (2026-02-10)


### Bug Fixes

* **web:** isolate worktree sessions with proper branch-tracking ([#74](https://github.com/The-Vibe-Company/companion/issues/74)) ([764d7a7](https://github.com/The-Vibe-Company/companion/commit/764d7a7f5391a686408a8542421f771da341d5db))

## [0.12.0](https://github.com/The-Vibe-Company/companion/compare/the-vibe-companion-v0.11.0...the-vibe-companion-v0.12.0) (2026-02-10)


### Features

* **web:** git fetch on branch picker open ([#72](https://github.com/The-Vibe-Company/companion/issues/72)) ([f110405](https://github.com/The-Vibe-Company/companion/commit/f110405edbd0f00454edd65ed72197daf0293182))

## [0.11.0](https://github.com/The-Vibe-Company/companion/compare/the-vibe-companion-v0.10.0...the-vibe-companion-v0.11.0) (2026-02-10)


### Features

* **web:** add Clawd-inspired pixel art logo and favicon ([#70](https://github.com/The-Vibe-Company/companion/issues/70)) ([b3994ef](https://github.com/The-Vibe-Company/companion/commit/b3994eff2eac62c3cf8f40a8c31b720c910a7601))
* **web:** enlarge homepage logo as hero element ([#71](https://github.com/The-Vibe-Company/companion/issues/71)) ([18ead74](https://github.com/The-Vibe-Company/companion/commit/18ead7436d3ebbe9d766754ddb17aa504c63703f))


### Bug Fixes

* checkout selected branch when worktree mode is off ([#68](https://github.com/The-Vibe-Company/companion/issues/68)) ([500f3b1](https://github.com/The-Vibe-Company/companion/commit/500f3b112c5ccc646c7965344b5774efe1338377))

## [0.10.0](https://github.com/The-Vibe-Company/companion/compare/the-vibe-companion-v0.9.0...the-vibe-companion-v0.10.0) (2026-02-10)


### Features

* **web:** git worktree support with branch picker and git pull ([#65](https://github.com/The-Vibe-Company/companion/issues/65)) ([4d0c9c8](https://github.com/The-Vibe-Company/companion/commit/4d0c9c83f4fe13be863313d6c945ce0b671a7f8a))

## [0.9.0](https://github.com/The-Vibe-Company/companion/compare/the-vibe-companion-v0.8.1...the-vibe-companion-v0.9.0) (2026-02-10)


### Features

* claude.md update ([7fa4e7a](https://github.com/The-Vibe-Company/companion/commit/7fa4e7adfdc7c409cfeed4e8a11f237ff0572234))
* **web:** add git worktree support for isolated multi-branch sessions ([#64](https://github.com/The-Vibe-Company/companion/issues/64)) ([fee39d6](https://github.com/The-Vibe-Company/companion/commit/fee39d62986cd99700ba78c84a1f586331955ff8))

## [0.8.1](https://github.com/The-Vibe-Company/companion/compare/the-vibe-companion-v0.8.0...the-vibe-companion-v0.8.1) (2026-02-10)


### Bug Fixes

* **web:** chat scroll and composer visibility in plan mode ([#55](https://github.com/The-Vibe-Company/companion/issues/55)) ([4cff10c](https://github.com/The-Vibe-Company/companion/commit/4cff10cde297b7142c088584b6dd83060902c526))

## [0.8.0](https://github.com/The-Vibe-Company/companion/compare/the-vibe-companion-v0.7.0...the-vibe-companion-v0.8.0) (2026-02-10)


### Features

* **web:** archive sessions instead of deleting them ([#56](https://github.com/The-Vibe-Company/companion/issues/56)) ([489d608](https://github.com/The-Vibe-Company/companion/commit/489d6087fc99b9131386547edaf3bd303a114090))

## [0.7.0](https://github.com/The-Vibe-Company/companion/compare/the-vibe-companion-v0.6.1...the-vibe-companion-v0.7.0) (2026-02-10)


### Features

* **web:** named environment profiles (~/.companion/envs/) ([#50](https://github.com/The-Vibe-Company/companion/issues/50)) ([eaa1a49](https://github.com/The-Vibe-Company/companion/commit/eaa1a497f3be61f2f71f9467e93fa2b65be19095))

## [0.6.1](https://github.com/The-Vibe-Company/companion/compare/the-vibe-companion-v0.6.0...the-vibe-companion-v0.6.1) (2026-02-10)


### Bug Fixes

* **web:** session reconnection with auto-relaunch and persist ([#49](https://github.com/The-Vibe-Company/companion/issues/49)) ([f58e542](https://github.com/The-Vibe-Company/companion/commit/f58e5428847a342069e6790fa7d70f190bc5f396))
* **web:** use --resume on CLI relaunch to restore conversation context ([#46](https://github.com/The-Vibe-Company/companion/issues/46)) ([3e2b5bd](https://github.com/The-Vibe-Company/companion/commit/3e2b5bdd39bd265ca5675784227a9f1b4f2a8aa3))

## [0.6.0](https://github.com/The-Vibe-Company/companion/compare/the-vibe-companion-v0.5.0...the-vibe-companion-v0.6.0) (2026-02-10)


### Features

* **web:** git info display, folder dropdown fix, dev workflow ([#43](https://github.com/The-Vibe-Company/companion/issues/43)) ([1fe2069](https://github.com/The-Vibe-Company/companion/commit/1fe2069a7db17b410e383f883c934ee1662c2171))
* **web:** persist sessions to disk for dev mode resilience ([#45](https://github.com/The-Vibe-Company/companion/issues/45)) ([c943d00](https://github.com/The-Vibe-Company/companion/commit/c943d0047b728854f059e26facde950e08cdfe0c))

## [0.5.0](https://github.com/The-Vibe-Company/companion/compare/the-vibe-companion-v0.4.0...the-vibe-companion-v0.5.0) (2026-02-09)


### Features

* **web:** add permission suggestions and pending permission indicators ([10422c1](https://github.com/The-Vibe-Company/companion/commit/10422c1464b6ad4bc45eb90e6cd9ebbc0ebeac92))

## [0.4.0](https://github.com/The-Vibe-Company/companion/compare/the-vibe-companion-v0.3.0...the-vibe-companion-v0.4.0) (2026-02-09)


### Features

* **web:** add component playground and ExitPlanMode display ([#36](https://github.com/The-Vibe-Company/companion/issues/36)) ([e958be7](https://github.com/The-Vibe-Company/companion/commit/e958be780f1b6e1a8f65daedbf968cdf6ef47798))

## [0.3.0](https://github.com/The-Vibe-Company/companion/compare/the-vibe-companion-v0.2.2...the-vibe-companion-v0.3.0) (2026-02-09)


### Features

* allow dev server access over Tailscale/LAN ([#33](https://github.com/The-Vibe-Company/companion/issues/33)) ([9599d7a](https://github.com/The-Vibe-Company/companion/commit/9599d7ad4e2823d51c8fa262e1dcd96eeb056244))


### Bug Fixes

* scope permission requests to their session tab ([#35](https://github.com/The-Vibe-Company/companion/issues/35)) ([ef9f41c](https://github.com/The-Vibe-Company/companion/commit/ef9f41c8589e382de1db719984931bc4e91aeb11))

## [0.2.2](https://github.com/The-Vibe-Company/companion/compare/the-vibe-companion-v0.2.1...the-vibe-companion-v0.2.2) (2026-02-09)


### Bug Fixes

* remove vibe alias, update repo URLs to companion ([#30](https://github.com/The-Vibe-Company/companion/issues/30)) ([4f7b47c](https://github.com/The-Vibe-Company/companion/commit/4f7b47cba86c278e89fe81292fea9b8b3e75c035))
* show pasted images in chat history ([#32](https://github.com/The-Vibe-Company/companion/issues/32)) ([46365be](https://github.com/The-Vibe-Company/companion/commit/46365be45ae8b325100ed296617455c105d4d52e))

## [0.2.1](https://github.com/The-Vibe-Company/claude-code-controller/compare/the-vibe-companion-v0.2.0...the-vibe-companion-v0.2.1) (2026-02-09)


### Bug Fixes

* track all commits in release-please, not just web/ ([#27](https://github.com/The-Vibe-Company/claude-code-controller/issues/27)) ([d49f649](https://github.com/The-Vibe-Company/claude-code-controller/commit/d49f64996d02807baf0482ce3c3607ae59f78638))
* use correct secret name NPM_PUBLISH_TOKEN in publish workflow ([e296ab0](https://github.com/The-Vibe-Company/claude-code-controller/commit/e296ab0fabd6345b1f21c7094ca1f8d6f6af79cb))
* use correct secret name NPM_PUBLISH_TOKEN in publish workflow ([#26](https://github.com/The-Vibe-Company/claude-code-controller/issues/26)) ([61eed5a](https://github.com/The-Vibe-Company/claude-code-controller/commit/61eed5addd6e332fac360d9ae8239f1b0f93868e))
