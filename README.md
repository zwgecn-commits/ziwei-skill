# 钦天门紫微斗数 SKILL · shixiong-ziwei-v7

> 排盘引擎见姊妹仓库 [zwgecn-commits/ziwei-chart](https://github.com/zwgecn-commits/ziwei-chart)；分析管线见 [zwgecn-commits/ziwei-pipeline](https://github.com/zwgecn-commits/ziwei-pipeline)。本仓库为其配套的**「知识层」**——一套面向 AI Agent 的紫微斗数结构化技法底座。

**v7.5.3 定版** · 主文档 `SKILL.md` + 11 份参考文档（`references/`）。

## 这是什么

写给大语言模型 / Agent 使用的紫微斗数技法知识底座：**不重算排盘、不做玄学承诺**，只解决一个问题——盘已排好，怎么读。

- **技法核**：定框架 / 叠宫 / 四化碰撞 / 应期四阶梯等结构化断法
- **工程层**：十二宫固定对宫、生年四化碰撞表、破财·离婚等可查表规则
- **排盘规范**：化曜定位、魁钺口诀、自化方向（↑向心 / ↓离心）、真太阳时、叠宫序——与引擎输出对齐
- **审查输出**：解释性输出规范（说全象、不铁口直断）
- **扩展参考（references/ ×11）**：十四主星十二宫、生年四化 48 条、宫位飞化全表、禄转忌与解忌、自化体系进阶、实战解盘专栏、六煞八吉十二宫、神煞长生等

> 版本履历（v7.3 → v7.5.3）见 `SKILL.md` 附录B。

## 使用方式

1. 将 `SKILL.md` 与 `references/` 放入你的 Agent 技能目录（Claude Code / Codex / OpenCode / 其他支持 skills 的 Agent 均可）
2. 排盘交给可靠引擎（推荐姊妹仓库 **ziwei-chart**；任何输出结构等价的引擎均可）
3. 建议工作流：**引擎排盘 → 本 SKILL 注入技法 → LLM 读象输出**
4. 与 **ziwei-pipeline** 配合：将其作为知识层挂载，参与「排盘 → 规则 → 闸门 → 渲染」全链

## 边界与原则

- **只查表，不推理**：对宫 / 叠宫 / 魁钺等结构性内容一律查表，禁止模型自行推导
- **定版边界**：不引入体用法 / 河图洛书等外体系；生死类断法不收录
- **来源标注**：断语标注来源层级；未标注者以「倾向性判例」对待
- **辅助定位**：本 SKILL 为分析辅助框架，输出供传统文化研究与娱乐参考，不构成医疗 / 法律 / 投资等专业建议

## 隐私

本仓库为**纯文档**项目：不含遥测、不上报数据、不收集任何信息。运行时产生的命盘数据完全留在使用者本地。

> 数据回流设计（若有）遵循姊妹项目 [ziwei-pipeline · docs/telemetry.md](https://github.com/zwgecn-commits/ziwei-pipeline/blob/main/docs/telemetry.md) 的「零遥测默认 · opt-in 同意 · 脱敏」三原则；本仓库当前**不启用任何通道**。

## License

[MIT](./LICENSE) —— 与 ziwei-chart / ziwei-pipeline 一致。技法文档为公开教学资料蒸馏整理 + 工程化改写，供学习研究。
