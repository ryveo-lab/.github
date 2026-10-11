# Contributing to RYVEO LAB

RYVEO LAB 的贡献指南。本文件是组织级默认约定，适用于旗下所有公开仓库；某个仓库如有更具体的规则，以该仓库内的 `CONTRIBUTING.md` 为准。

This is the organization-level contributing guide for RYVEO LAB. It applies to all public repositories by default; when a repository keeps its own, more specific rules, that repository's `CONTRIBUTING.md` is the source of truth.

## 欢迎 · Welcome

无论你来自哪里，你的第一个 issue、第一次 review、第一个 pull request，都受欢迎。参与即意味着你同意遵循[行为准则](CODE_OF_CONDUCT.md)。

Wherever you come from, your first issue, your first review, and your first pull request are all welcome. Participating means agreeing to follow the [Code of Conduct](CODE_OF_CONDUCT.md).

## 入门 · Getting started

1. **阅读 README** —— 了解项目做什么、当前处于什么阶段。
2. **找到方向** —— 从你关心的 issue 或讨论开始；标有 `good first issue` 的条目适合初次贡献。
3. **先讨论，后编码** —— 较大改动（新特性、破坏性变更、API 调整）先在 issue 或 Discussion 中与维护者对齐方向。

1. **Read the README** — understand what the project does and where it stands.
2. **Find a direction** — start with issues or discussions you care about; `good first issue` is a good place to begin.
3. **Discuss before coding** — for larger changes (features, breaking changes, API adjustments), align with maintainers in an issue or Discussion first.

## 提出 Issue · Opening issues

- 先搜索是否已有相同或相关的 issue。
- 标题简明描述问题或想法。
- 内容包含：复现步骤（若为缺陷）、预期行为、实际行为、运行环境；若是功能提议，说明用途与理由。
- 保持一个 issue 聚焦一件事。

- Search for an existing issue first.
- Use a concise title that describes the problem or idea.
- Include reproduction steps (for bugs), expected vs. actual behavior, and environment; for feature requests, explain the use case and rationale.
- Keep one issue focused on one thing.

## 提交 Pull Request · Submitting pull requests

1. **Fork 仓库** 并基于最新 `main`（或仓库约定的开发分支）创建特性分支，如 `feat/xxx`。
2. **遵循仓库约定**：运行仓库定义的检查与测试（lint / typecheck / test），保证通过后再提交。
3. **Commit 信息清晰**：一句话说明动机与影响；组织内建议 `类型(范围): 摘要` 格式，例如 `feat(core): add render cache`。
4. **PR 描述**：说明改了什么、为什么、如何验证；关联相关的 issue（`Closes #123`）。
5. **评审循环**：维护者与社区成员会评审并反馈，按要求迭代；CI 通过、至少一位维护者批准后合并。

1. **Fork** the repository and create a feature branch from the latest `main` (or the branch the repository specifies), e.g. `feat/xxx`.
2. **Follow the repository conventions**: run the checks and tests it defines (lint / typecheck / test) and make sure they pass.
3. **Write clear commits**: one sentence stating intent and impact. `type(scope): summary` is preferred, e.g. `feat(core): add render cache`.
4. **Describe the PR**: what changed, why, and how to verify; link related issues (`Closes #123`).
5. **Review loop**: maintainers and community members review and give feedback; iterate accordingly. The PR merges when CI passes and at least one maintainer approves.

## 行为准则 · Code of Conduct

所有交互遵循 [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)：友好、尊重、对事不对人。

All interaction follows [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md): be kind, be respectful, and argue about ideas, not people.

## 协议与许可 · License

在非特指仓库中，除非另有说明，代码部分按仓库指定的开源协议发布；内容与文档遵循相应许可。提交 PR 即表示你同意你的贡献按项目采用的许可条款发布。

Unless stated otherwise in a specific repository, code is released under the license the repository specifies; content and documentation follow their own licensing. By submitting a PR you agree that your contribution is released under the project's license terms.
