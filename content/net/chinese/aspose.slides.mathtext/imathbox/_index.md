---
title: IMathBox
second_title: Aspose.Sildes for .NET API Reference
description: 指定数学元素的逻辑包装（打包）。例如，盒对象可以作为运算符仿真器，与对齐点一起或不一起，作为换行点，或者被分组以不允许内部换行。例如，“==”运算符应该被包装以防止换行。
type: docs
weight: 7940
url: /zh/aspose.slides.mathtext/imathbox/
---

## IMathBox 接口

指定数学元素的逻辑包装（打包）。例如，盒对象可以作为运算符仿真器，与对齐点一起或不一起，作为换行点，或者被分组以不允许内部换行。例如，“==”运算符应该被包装以防止换行。

```csharp
public interface IMathBox : IMathElement
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/imathbox/alignmentpoint) { get; set; } | 当为 true 时，此运算符仿真器作为对齐点；即，其他方程中的指定对齐点可以与之对齐。默认值：false |
| [AsIMathElement](../../aspose.slides.mathtext/imathbox/asimathelement) { get; } | 允许获取基础 IMathElement 接口 [`IMathElement`](../imathelement) |
| [Base](../../aspose.slides.mathtext/imathbox/base) { get; } | 基础参数 |
| [Differential](../../aspose.slides.mathtext/imathbox/differential) { get; set; } | 微分。当为 true 时，盒子充当微分（例如，积分中的 𝑑𝑥），并接收适当的水平间距以适应数学微分。默认值：false |
| [ExplicitBreak](../../aspose.slides.mathtext/imathbox/explicitbreak) { get; set; } | 显式换行指定在盒子对象的开始位置是否有换行，即行在盒子对象的开始位置换行。指定上一个数学文本行中用于当前行数学文本的对齐点的运算符数量，可能的值：1..255 默认值：0（没有显式换行） |
| [NoBreak](../../aspose.slides.mathtext/imathbox/nobreak) { get; set; } | 无换行。此属性指定对象盒上的“不可换行”属性。当为 true 时，盒子内不能发生换行。这对于由多个二元运算符组成的运算符仿真器可能是重要的。当未指定此元素时，盒内可以发生换行。默认值：true |
| [OperatorEmulator](../../aspose.slides.mathtext/imathbox/operatoremulator) { get; set; } | 运算符仿真器。当为 true 时，盒子及其内容表现为单一运算符，并继承运算符的属性。这意味着，例如，字符可以作为换行点，并可以与其他运算符对齐。运算符仿真器通常用于一个或多个字形组合形成运算符时，例如 '=='。默认值：false |

### 示例

示例：

```csharp
[C#]
IMathBox box = new MathematicalText("==").ToBox();
```

### 另请参见

* 接口 [IMathElement](../imathelement)
* 命名空间 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->