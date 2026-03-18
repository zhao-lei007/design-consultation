# design-consultation

一个用于**设计咨询（design consultation，设计顾问式协作）**的 Skill。

## 这个 Skill 是干什么的
它不是让 Agent 机械地列选项，而是让 Agent 先理解产品背景、用户类型与行业语境，再给出一套成体系的设计建议，包括：
- aesthetic（审美方向，整体气质）
- typography（字体系统）
- color palette（色板）
- layout（布局方式）
- motion（动效倾向）

它更像“设计顾问”，而不是“表单填写器”。

## 什么时候用
适合这些场景：
- 你刚开始做一个产品，想先定设计方向
- 你有产品想法，但视觉系统还没成型
- 你想让 Agent 先给出一套 coherent system（一致性的设计系统）
- 你需要把设计判断沉淀成 `DESIGN.md`

## 核心输出
通常会产出这些内容：
- 产品设计方向判断
- 一套完整的设计系统建议
- 风险与保守项（safe / risk）的对比
- 预览页或 `DESIGN.md`

## 不适合的场景
它不适合：
- 只想做一次简单视觉挑刺
- 已经有成型页面，只想做 QA
- 只想修一个按钮、一个间距、一个颜色的小问题

这些更适合交给 `design-review` 或 `qa`。

## 相关 Skills
- `design-review`：看已做出来的页面，做设计审查
- `plan-design-review`：对“计划”做设计层审查
- `review`：偏代码／结构层的 pre-landing review

