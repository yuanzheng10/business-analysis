# business-analysis
35个经典商业分析框架，支持场景推荐、结构化分析、自审纠偏。适用于 Claude Code / Gemini CLI，也可将 `SKILL.md` 内容作为系统提示词接入任意 AI。

## 结构

```
business-analysis-skill/
├── SKILL.md              # Skill 入口，含完整工作流
└── references/
    ├── strategy.md       # 战略类（15个）：SWOT/PEST/五力/BCG 等
    ├── marketing.md      # 营销类（10个）：4P/STP/AIDA/安索夫 等
    ├── business_model.md # 商业模式（3个）：BMC/魏朱六要素/业务铁三角
    ├── organization.md   # 组织管理（4个）：RACI/Greiner/人才选育用留 等
    └── thinking_tools.md # 思维工具（6个）：麦肯锡七步/逻辑树/鱼骨图 等
```

## 使用方式

**Claude Code / Gemini CLI**：将 `business-analysis-skill/` 文件夹放入 skills 目录，自动识别。

**其他 AI（GPT / Gemini / DeepSeek）**：将 `SKILL.md` 中的内容复制为系统提示词使用。

## 核心功能

- **框架推荐**：描述业务场景，自动匹配 1-3 个最合适的框架
- **结构化分析**：按框架模板逐维度展开，输出分析报告
- **自审纠偏**：每次分析后执行 7 维度批判检查，修正偏差
