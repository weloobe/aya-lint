<a name="readme-top"></a>

<div align="center">

<img height="120" src="https://registry.npmmirror.com/@ayahub/assets-logo/1.0.0/files/assets/logo-3d.webp">
<img height="120" src="https://gw.alipayobjects.com/zos/kitchen/qJ3l3EPsdW/split.svg">
<img height="120" src="https://registry.npmmirror.com/@ayahub/assets-emoji/1.3.0/files/assets/triangular-ruler.webp">

<h1>Aya Lint</h1>

ESlint config, Prettier config, Remark config for AyaHub

[Changelog](./CHANGELOG.md) · [Report Bug][issues-link] · [Request Feature][issues-link]

<!-- SHIELD GROUP -->

[![][npm-release-shield]][npm-release-link]
[![][discord-shield]][discord-link]
[![][npm-downloads-shield]][npm-downloads-link]
[![][github-releasedate-shield]][github-releasedate-link]
[![][github-action-test-shield]][github-action-test-link]
[![][github-action-release-shield]][github-action-release-link]<br/>
[![][github-contributors-shield]][github-contributors-link]
[![][github-forks-shield]][github-forks-link]
[![][github-stars-shield]][github-stars-link]
[![][github-issues-shield]][github-issues-link]
[![][github-license-shield]][github-license-link]

</div>

![](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<details>
<summary><kbd>Table of contents</kbd></summary>

#### TOC

- [📦 Installation](#-installation)
- [🤯 Usage](#-usage)
  - [.npmrc](#npmrc)
  - [ESlint](#eslint)
  - [Stylelint](#stylelint)
  - [Commitlint](#commitlint)
  - [Changelog](#changelog)
  - [Remark](#remark)
  - [Prettier](#prettier)
  - [Semantic Release](#semantic-release)
- [⌨️ Local Development](#️-local-development)
- [🤝 Contributing](#-contributing)

####

</details>

## 📦 Installation

To install Aya Lint, run the following command:

[![][bun-shield]][bun-link]

```bash
$ bun add @ayahub/lint -D
```

To use template ignore files, run the following command:

```bash
$ curl -O https://raw.githubusercontent.com/weloobe/aya-lint/master/.eslintignore
$ curl -O https://raw.githubusercontent.com/weloobe/aya-lint/master/.gitignore
$ curl -O https://raw.githubusercontent.com/weloobe/aya-lint/master/.prettierignore
```

<div align="right">

[![][back-to-top]](#readme-top)

</div>

## 🤯 Usage

### .npmrc

```text
public-hoist-pattern[]=*@umijs/lint*
public-hoist-pattern[]=*changelog*
public-hoist-pattern[]=*commitlint*
public-hoist-pattern[]=*eslint*
public-hoist-pattern[]=*postcss*
public-hoist-pattern[]=*prettier*
public-hoist-pattern[]=*remark*
public-hoist-pattern[]=*semantic-release*
public-hoist-pattern[]=*stylelint*
```

### ESlint

config can be found at [`.eslintrc.js`](/src/eslint/index.ts)

```js
module.exports = require('@ayahub/lint').eslint;
```

### Stylelint

config can be found at [`.stylelintrc.js`](/src/stylelint/index.ts)

```js
module.exports = require('@ayahub/lint').stylelint;
```

### Commitlint

config can be found at [`.commitlintrc.js`](/src/commitlint/index.ts)

```js
module.exports = require('@ayahub/lint').commitlint;
```

### Changelog

config can be found at [`.changelogrc.js`](/src/changelog/index.ts)

```js
module.exports = require('@ayahub/lint').changelog;
```

### Remark

config can be found at [`.remarkrc.js`](/src/remarklint/index.ts)

```js
module.exports = require('@ayahub/lint').remarklint;
```

### Prettier

config can be found at [`.prettierrc.js`](/src/prettier/index.ts)

```js
module.exports = require('@ayahub/lint').prettier;
```

### Semantic Release

config can be found at [`.releaserc.js`](/src/semantic-release/index.ts)

```js
module.exports = require('@ayahub/lint').semanticRelease;
```

<div align="right">

[![][back-to-top]](#readme-top)

</div>

## ⌨️ Local Development

You can use Github Codespaces for online development:

[![][codespaces-shield]][codespaces-link]

Or clone it for local development:

```bash
$ git clone https://github.com/weloobe/aya-lint.git
$ cd ayahub/lint
$ bun install
$ bun start
```

<div align="right">

[![][back-to-top]](#readme-top)

</div>

## 🤝 Contributing

Contributions of all types are more than welcome, if you are interested in contributing code, feel free to check out our GitHub [Issues][github-issues-link] to get stuck in to show us what you’re made of.

[![][pr-welcome-shield]][pr-welcome-link]

[![][contributors-contrib]][contributors-url]

<div align="right">

[![][back-to-top]](#readme-top)

</div>

---

#### 📝 License

Copyright © 2023 [AyaHub][profile-link]. <br />
This project is [MIT](./LICENSE) licensed.

<!-- LINK GROUP -->

[back-to-top]: https://img.shields.io/badge/-BACK_TO_TOP-151515?style=flat-square
[bun-link]: https://bun.sh
[bun-shield]: https://img.shields.io/badge/-speedup%20with%20bun-black?logo=bun&style=for-the-badge
[codespaces-link]: https://codespaces.new/weloobe/aya-lint
[codespaces-shield]: https://github.com/codespaces/badge.svg
[contributors-contrib]: https://contrib.rocks/image?repo=ayahub/aya-lint
[contributors-url]: https://github.com/weloobe/aya-lint/graphs/contributors
[discord-link]: https://discord.gg/DQ5VwFpR4p
[discord-shield]: https://img.shields.io/discord/1127171173982154893?color=5865F2&label=discord&labelColor=black&logo=discord&logoColor=white&style=flat-square
[github-action-release-link]: https://github.com/weloobe/aya-lint/actions/workflows/release.yml
[github-action-release-shield]: https://img.shields.io/github/actions/workflow/status/weloobe/aya-lint/release.yml?label=release&labelColor=black&logo=githubactions&logoColor=white&style=flat-square
[github-action-test-link]: https://github.com/weloobe/aya-lint/actions/workflows/test.yml
[github-action-test-shield]: https://img.shields.io/github/actions/workflow/status/weloobe/aya-lint/test.yml?label=test&labelColor=black&logo=githubactions&logoColor=white&style=flat-square
[github-contributors-link]: https://github.com/weloobe/aya-lint/graphs/contributors
[github-contributors-shield]: https://img.shields.io/github/contributors/weloobe/aya-lint?color=c4f042&labelColor=black&style=flat-square
[github-forks-link]: https://github.com/weloobe/aya-lint/network/members
[github-forks-shield]: https://img.shields.io/github/forks/weloobe/aya-lint?color=8ae8ff&labelColor=black&style=flat-square
[github-issues-link]: https://github.com/weloobe/aya-lint/issues
[github-issues-shield]: https://img.shields.io/github/issues/weloobe/aya-lint?color=ff80eb&labelColor=black&style=flat-square
[github-license-link]: https://github.com/weloobe/aya-lint/blob/master/LICENSE
[github-license-shield]: https://img.shields.io/github/license/weloobe/aya-lint?color=white&labelColor=black&style=flat-square
[github-releasedate-link]: https://github.com/weloobe/aya-lint/releases
[github-releasedate-shield]: https://img.shields.io/github/release-date/weloobe/aya-lint?labelColor=black&style=flat-square
[github-stars-link]: https://github.com/weloobe/aya-lint/network/stargazers
[github-stars-shield]: https://img.shields.io/github/stars/weloobe/aya-lint?color=ffcb47&labelColor=black&style=flat-square
[issues-link]: https://github.com/weloobe/aya-lint/issues/new/choose
[npm-downloads-link]: https://www.npmjs.com/package/@ayahub/lint
[npm-downloads-shield]: https://img.shields.io/npm/dt/@ayahub/lint?labelColor=black&style=flat-square
[npm-release-link]: https://www.npmjs.com/package/@ayahub/lint
[npm-release-shield]: https://img.shields.io/npm/v/@ayahub/lint?color=369eff&labelColor=black&logo=npm&logoColor=white&style=flat-square
[pr-welcome-link]: https://github.com/weloobe/aya-chat/pulls
[pr-welcome-shield]: https://img.shields.io/badge/🤯_pr_welcome-%E2%86%92-ffcb47?labelColor=black&style=for-the-badge
[profile-link]: https://github.com/weloobe
