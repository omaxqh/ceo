# ceo

> 商业智能外脑。审查你的想法，激发更大可能。

## 这是什么

一个"策略外脑"型 AI Skill，从商业、竞对、用户、产品、运营、体验等角度审查你的商业想法，并激发更多可能性。

剔除了工程化部分和发散能力，极致压缩 token 消耗，只聚焦 CEO 思考。

## 四种模式

| 模式 | 场景 |
|------|------|
| **SCOPE EXPANSION** | 梦想大一点 |
| **SELECTIVE EXPANSION** | 保持范围 + 挑选扩展 |
| **HOLD SCOPE** | 最大严谨 |
| **SCOPE REDUCTION** | 精简到本质 |

## 两个版本

| 文件 | 用途 |
|------|------|
| `SKILL.md` | IDE Skill 完整版，加载到 AI IDE 中使用 |
| `how-great-ceos-think.md` | LLM 加载版（18条CEO思维框架），直接丢到 GPT/Gemini 对话框 |

## 安装

### IDE Skill

| 平台 | 安装方式 | 只需 SKILL.md？ |
|------|----------|----------------|
| Qoder | 复制目录到 `~/.qoder/skills/ceo/` | 是 |
| Cursor | 复制目录到 `.cursor/skills/ceo/` | 是 |
| Codex | 整个目录原样放入 skills 目录 | 是 |
| Claude Code | 手动贴到 `CLAUDE.md` 或 `.claude/commands/`，或让 CC 帮你转格式 | 基本是 |

### LLM 加载版

直接把 `how-great-ceos-think.md` 丢到 GPT 或 Gemini 对话框：

```
使用这个 md 作为核心思考和方法论
```

然后把需要审核的方案发过去就行。

## 使用

```bash
/ceo
```

报告落盘位置：`skills/ceo/reviews/<project-slug>/report.md`

## 最佳实践

**想法已经清晰？**

直接把想法/规划/PRD/提案.md 扔进 CLI/IDE/LLM，接受评价。选择扩展模式时会激活 10X 场景讨论。

**想法还不清晰？**

先用 GPT/Gemini/Claude 整理创意原点，或用 office-hours、brainstorm 等 skill 发散，整理清楚后再交给 ceo 评审。

## License

MIT
