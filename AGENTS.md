# CODEBUDDY.md

This file provides guidance to CodeBuddy Code when working with code in this repository.

## 项目概述

本仓库是**量潮数字资产档案**，记录各类数字资产分类定义及平台账号资源管理。作为量潮工作档案的子模块，采用 Git 子模块架构。

## 目录结构

```
.
├── index.md           # 入口
├── README.md          # 项目说明
├── CHANGELOG.md       # 版本变更记录
├── category/          # 资产分类
│   └── profile/       # 工作档案
├── entity/            # 实体档案
│   └── founder/       # 创始人档案
├── platform/          # 平台资产
└── quanttide/         # 平台数据模型（schema.json）
```

骨架以外的档案内容归档于归档仓 `quanttide-archive-of-asset-management` 的 `profile/` 目录。

## 访问范围

| 位置 | 访问范围 |
|------|----------|
| GitHub | 公开 |
| 飞书知识库 | 内部 |

## 提交规范

使用 Conventional Commits 格式：

```
feat: 新增功能/内容
docs: 文档更新
refactor: 结构调整
fix: 修复问题
```

## 版本规范

遵循语义化版本（SemVer）：
- 修订号：错别字修正、格式调整
- 次版本：新增内容、新增板块
- 主版本：架构调整

## 发布流程

1. 更新 CHANGELOG.md
2. 提交所有变更
3. 推送到远程

## 相关文档

- 元数据信息位于主仓库 `meta/asset/`
- 父仓库工作指南见 `/Users/mac/repos/quanttide/asset/profile/AGENTS.md`
