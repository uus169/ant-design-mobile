---
category: Components
type: Data Entry
title: Stepper
---

用作增加或者减少当前数值。

### 规则
- 当想要对数值进行小幅度调整时，可以使用 Stepper，eg：将年化收益从 4.00% 调整到 4.05%。

## API

Support WEB, React-Native.

Properties | Descrition | Type | Default
-----------|------------|------|--------
| min     | 最小值   | Number | -Infinity        |
| max     | 最大值       | Number      | Infinity           |
| value     | 当前值       | Number      |            |
| step     | 每次改变步数，可以为小数  | Number or String      |  1      |
| defaultValue     | 初始值       | Number      |            |
| onChange     | 变化时回调函数      | (): void      |            |
| disabled     | 禁用       | Boolean      |      false      |
| readOnly     | input 只读       | Boolean      |      false      |
| showNumber(`web only`)    | 是否显示数值，默认不显示  | Boolean      |      false      |
| styles(`rn only`)    | react native 组件样式  | ReactNative StyleSheet      |  -   |
