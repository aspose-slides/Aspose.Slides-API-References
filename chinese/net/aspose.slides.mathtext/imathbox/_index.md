---
title: IMathBox
second_title: Aspose.Slides for .NET API 参考
description: 指定数学元素的逻辑装箱包装 例如装箱的对象可以用作带有或不带有对齐点的操作员模拟器 用作换行点或者被分组以不允许换行内 例如运算符应该被装箱以防止换行
type: docs
weight: 7480
url: /zh/net/aspose.slides.mathtext/imathbox/
---
## IMathBox interface

指定数学元素的逻辑装箱（包装）。 例如，装箱的对象可以用作带有或不带有对齐点的操作员模拟器， 用作换行点，或者被分组以不允许换行内。 例如，“==”运算符应该被装箱以防止换行。

```csharp
public interface IMathBox : IMathElement
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/imathbox/alignmentpoint) { get; set; } | 当为真时，此运算符模拟器用作对齐点；即 其他方程中指定的对齐点可以与之对齐。 默认值:假 |
| [AsIMathElement](../../aspose.slides.mathtext/imathbox/asimathelement) { get; } | 允许获取基础 IMathElement 接口 [`IMathElement`](../imathelement) |
| [Base](../../aspose.slides.mathtext/imathbox/base) { get; } | 基本参数 |
| [Differential](../../aspose.slides.mathtext/imathbox/differential) { get; set; } | 差分。 当为真时，该框充当微分（例如，被积函数中的𝑑𝑥），并为数学微分接收适当的 水平间距。 默认值:假 |
| [ExplicitBreak](../../aspose.slides.mathtext/imathbox/explicitbreak) { get; set; } | 显式换行指定 Box 对象的开头是否有换行符， 使得换行在盒子的开头目的。 指定前一行数学文本上的运算符编号，该编号应 用作当前数学文本行的对齐点 可能值:1..255 默认值:0（无显式中断） |
| [NoBreak](../../aspose.slides.mathtext/imathbox/nobreak) { get; set; } | 没有中断。 此属性指定对象框上的“牢不可破”属性。如果为 true，则框内不会出现换行符。 这对于由多个二元运算符组成的运算符模拟器可能很重要。 如果未指定此元素，则框内可能会出现中断。 默认值:true |
| [OperatorEmulator](../../aspose.slides.mathtext/imathbox/operatoremulator) { get; set; } | 操作员模拟器。 当为 true 时，框及其内容表现为单个运算符并继承运算符的属性。 这意味着，例如，字符可以用作换行符，并且可以与其他运算符对齐。 Operator Emulators 通常在一个或多个字形组合形成一个运算符时使用，例如'=='。 默认值:假 |

### 例子

示例:

```csharp
[C#]
IMathBox box = new MathematicalText("==").ToBox();
```

### 也可以看看

* interface [IMathElement](../imathelement)
* 命名空间 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->