<div align="center">
  <img src="https://raw.githubusercontent.com/vanduo-oss/.github/main/profile/vanduo-oss-animated.svg" alt="Vanduo OSS" width="220"/>
</div>

## About

**Vanduo** is an open-source foundation building a developer-focused design system, shipped as **perspective** — a standalone **Vue 3** design system with typed components and design tokens in a single package.

The original **legacy** line (a dual-engine Vanilla CSS/JS + Vue 3 system) was **retired on 2026-07-25**. Its repositories are archived and its documentation site is offline, but its packages remain published and installable on npm — deprecated, not removed. Nothing built on it breaks; it simply receives no further releases. See [legacy](#legacy--retired-2026-07-25) below.

## Projects

### perspective — the standalone Vue 3 line

> The only line under active development.

Typed components, a composable for every interaction, and design tokens in a single package. No runtime, no ceremony.

| Repository | npm | Description |
|---|---|---|
| [vd3](https://github.com/vanduo-oss/vd3) | [![npm](https://img.shields.io/npm/v/@vanduo-oss/vd3)](https://www.npmjs.com/package/@vanduo-oss/vd3) | The design system in one package — DTCG design tokens, the CSS tree, and typed `Vd*` components and composables. Sole peer dependency: `vue`. |
| [vd3-cbun](https://github.com/vanduo-oss/vd3-cbun) | [![npm](https://img.shields.io/npm/v/@vanduo-oss/vd3-cbun)](https://www.npmjs.com/package/@vanduo-oss/vd3-cbun) | Companion component bundle — charts, flowchart, hex-grid, and music-player as tree-shakeable Vue 3 subpath exports. |
| [vd3-docs](https://github.com/vanduo-oss/vd3-docs) | — | Documentation and live demos → [vanduo-oss.github.io/vd3-docs](https://vanduo-oss.github.io/vd3-docs/) |

### legacy — retired 2026-07-25

The original Vanduo: a zero-build Vanilla CSS/JS framework and first-class Vue 3 components on one framework-agnostic set of design tokens. **Archived and no longer developed.** Every package below stays published on npm at its final version and keeps working — retirement stopped development, not access.

**Migrating?** The [migration guide](https://vanduo-oss.github.io/vd3-docs/guides/migration) maps the old packages onto vd3. The short version: `vue` → `vd3`, the four add-ons → `vd3-cbun` subpaths, `core`'s tokens → inside `vd3`. **`framework` has no successor** — vd3 is Vue 3 only, so if you need a build-free drop-in, pin `@vanduo-oss/framework@1.7.1`.

| Repository | Final | Successor |
|---|---|---|
| [core](https://github.com/vanduo-oss/core) | `1.0.1` | tokens ship inside [`@vanduo-oss/vd3`](https://www.npmjs.com/package/@vanduo-oss/vd3) (`/css/core`, `/tokens.json`) |
| [framework](https://github.com/vanduo-oss/framework) | `1.7.1` | **none** — Vue 3 only from here; pin `1.7.1` for the vanilla engine |
| [vue](https://github.com/vanduo-oss/vue) | `0.3.1` | [`@vanduo-oss/vd3`](https://www.npmjs.com/package/@vanduo-oss/vd3) — closest to a drop-in |
| [charts](https://github.com/vanduo-oss/charts) | `0.2.0` | `@vanduo-oss/vd3-cbun/charts` |
| [flowchart](https://github.com/vanduo-oss/flowchart) | `1.1.0` | `@vanduo-oss/vd3-cbun/flowchart` |
| [hex-grid](https://github.com/vanduo-oss/hex-grid) | `1.1.0` | `@vanduo-oss/vd3-cbun/hex-grid` |
| [music-player](https://github.com/vanduo-oss/music-player) | `1.1.0` | `@vanduo-oss/vd3-cbun/music-player` |
| [vd2](https://github.com/vanduo-oss/vd2) | — | the legacy docs site — taken offline; source archived in the repo. Current docs: [vd3-docs](https://vanduo-oss.github.io/vd3-docs/) |

## Connect

- Website: [vanduo.dev](https://vanduo.dev)
- npm: [@vanduo-oss](https://www.npmjs.com/org/vanduo-oss)
- GitHub: [github.com/vanduo-oss](https://github.com/vanduo-oss)
