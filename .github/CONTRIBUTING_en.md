# Contributing Guide

Thank you very much for your interest and contribution to BongoCat! Before you submit your contribution, please take some time to read the following guide to ensure your contribution proceeds smoothly.

## Transparent Development

All work is conducted publicly on GitHub. Whether it is a core team member or an external contributor, all Pull Requests must go through the same review process.

## Submitting Issues

We use [Github Issues](https://github.com/ayangweb/BongoCat/issues) for bug reports and new feature suggestions. Before submitting an issue, please make sure you have searched for similar issues, as they may have already been answered or are being fixed. For bug reports, please include complete steps to reproduce the problem. For new feature suggestions, please indicate the changes you want and the expected behavior.

## Submitting Pull Request

### Collaboration Process

- Claim an issue: Create an Issue on Github and claim it (or claim an existing Issue directly), informing everyone that you are fixing it to avoid duplicate work.
- Project Development: After completing the preparation work, carry out bug fixes or feature development.
- Submit PR.

### Preparation

- [Rust](https://v2.tauri.app/start/prerequisites/): Please install the rust environment according to the official website steps.
- [Node.js](https://nodejs.org/en/): Used to run the project.
- [Pnpm](https://pnpm.io/): This project uses Pnpm for package management.

### Download Dependencies

```shell
pnpm install
```

### Start Application

```shell
pnpm tauri dev
```

### Build Application

> If you need to debug after packaging, please add `--debug` after the following command

```shell
pnpm tauri build
```

## Commit Guide

Commit messages should follow the [conventional-changelog standard](https://www.conventionalcommits.org/en/v1.0.0/).

### Commit Types

The following is a list of commit types:

- feat: New feature or function
- fix: Bug fix
- docs: Documentation update
- style: Code style update
- refactor: Code refactoring, no new features or bug fixes introduced
- perf: Performance optimization
- chore: Other commits

We look forward to your participation, let's make BongoCat better together!
