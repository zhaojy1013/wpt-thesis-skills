# 无线充电硕士论文写作技能

两项可独立调用的 Codex 技能，面向无线电能传输、电池充电和系统参数优化方向的中文工科论文。

| 技能 | 用途 |
| --- | --- |
| [wpt-thesis-writing](skills/wpt-thesis-writing/SKILL.md) | 拟大纲、起草章节、润色和压缩正文，按需读取建模、优化和结果表达的参考材料。 |
| [wpt-thesis-claim-review](skills/wpt-thesis-claim-review/SKILL.md) | 专项核查科研主张、数学与物理依据、比较协议和证据边界，给出分级意见和可替换表述。 |

## 安装

将仓库中的两个技能目录复制到论文项目根目录的 .agents/skills/。保留目录名、SKILL.md 和 references/。在论文项目中开启新 Codex 会话，再按技能名称调用。

## 使用示例

- $wpt-thesis-writing 请根据所给模型假设和公式起草二阶 RC 等效电路小节，保留电流方向、单位和适用边界。
- $wpt-thesis-claim-review 请核查这段结论，逐项说明哪些主张得到表格支持，以及哪些仍需验证。

两个技能也可以直接处理用户提供的素材。独立计算、仿真与 Office 交付可分别交给已安装的 scientific-toolkit-skill 和 office-academic-skill。

## 许可与来源

两项技能的目录分别保留 MIT 许可证和上游版权声明。派生来源、固定提交和主要改动见各自的上游说明。

- [写作技能来源](skills/wpt-thesis-writing/UPSTREAM.md) · [MIT 许可](skills/wpt-thesis-writing/LICENSE)
- [审读技能来源](skills/wpt-thesis-claim-review/UPSTREAM.md) · [MIT 许可](skills/wpt-thesis-claim-review/LICENSE)
