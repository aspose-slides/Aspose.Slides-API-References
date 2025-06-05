---
title: MathBorderBox
second_title: Aspose.Sildes for .NET API Reference
description: 在 IMathElement 周围绘制矩形或其他边框。
type: docs
weight: 8350
url: /zh/aspose.slides.mathtext/mathborderbox/
---

## MathBorderBox class

在 IMathElement 周围绘制矩形或其他边框。

```csharp
public sealed class MathBorderBox : MathElementBase, IMathBorderBox
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MathBorderBox](mathborderbox#constructor)(IMathElement) | 创建具有矩形边框的 MathBorderBox 元素 |
| [MathBorderBox](mathborderbox#constructor_1)(IMathElement, bool, bool, bool, bool, bool, bool, bool, bool) | 创建 MathBorderBox 元素 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathborderbox/base) { get; } | 基础参数 |
| [HideBottom](../../aspose.slides.mathtext/mathborderbox/hidebottom) { get; set; } | 隐藏底边（默认是 false）- 指定边框框底边的隐藏或显示状态。 |
| [HideLeft](../../aspose.slides.mathtext/mathborderbox/hideleft) { get; set; } | 隐藏左边（默认是 false）- 指定边框框左边的隐藏或显示状态。 |
| [HideRight](../../aspose.slides.mathtext/mathborderbox/hideright) { get; set; } | 隐藏右边（默认是 false）- 指定边框框右边的隐藏或显示状态。 |
| [HideTop](../../aspose.slides.mathtext/mathborderbox/hidetop) { get; set; } | 隐藏顶部（默认是 false）- 指定边框框顶部的隐藏或显示状态。 |
| [StrikethroughBottomLeftToTopRight](../../aspose.slides.mathtext/mathborderbox/strikethroughbottomlefttotopright) { get; set; } | 从底左到顶右的删除线（默认是 false）。指定从边框框底左角到顶右角的删除线的隐藏或显示状态。 |
| [StrikethroughHorizontal](../../aspose.slides.mathtext/mathborderbox/strikethroughhorizontal) { get; set; } | 水平删除线（默认是 false）- 指定水平删除线的隐藏或显示状态。 |
| [StrikethroughTopLeftToBottomRight](../../aspose.slides.mathtext/mathborderbox/strikethroughtoplefttobottomright) { get; set; } | 从顶左到底右的删除线（默认是 false）。指定从边框框顶左角到底右角的删除线的隐藏或显示状态。 |
| [StrikethroughVertical](../../aspose.slides.mathtext/mathborderbox/strikethroughvertical) { get; set; } | 垂直删除线（默认是 false）- 指定垂直删除线的隐藏或显示状态。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 设置一个重音符号（此元素上方的字符） |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 使用此实例作为参数接受指定的函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 使用此实例作为参数接受指定的函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 使用此实例作为参数接受指定的函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 使用此实例作为参数和指定的额外参数接受指定的函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 使用此实例作为参数和指定的额外参数接受指定的函数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 创建具有此分子和指定分母的分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 创建具有此分子和指定分母的分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 创建具有此分子和指定分母的指定类型的分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 创建具有此分子和指定分母的指定类型的分数 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 将数学元素用括号括起来 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 用指定字符（如括号或其他字符）将数学元素括起来 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 使用此实例作为函数名接受一个参数的函数 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 使用此实例作为函数名接受一个参数的函数 |
| [GetChildren](../../aspose.slides.mathtext/mathborderbox/getchildren)() | 获取子元素 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 使用底部大括号将此元素放入组中 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 使用分组字符（如底部大括号或其他）将此元素放入组中 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 进行不带限制的积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 进行积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 进行积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 进行积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 进行积分 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 连接数学元素并形成数学块 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 连接数学文本并形成数学块 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 创建 N-元运算符 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | 创建 N-元运算符 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在此元素上方设置一条横线 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定从指定参数得出的给定度数的数学根。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定从指定参数得出的给定度数的数学根。 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | 接受下限 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | 接受下限 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | 创建下标 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | 创建下标 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | 在左侧创建下标和上标 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | 在左侧创建下标和上标 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | 在右侧创建下标和上标 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | 在右侧创建下标和上标 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | 创建上标 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | 创建上标 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | 接受上限 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | 接受上限 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | 将此元素放入边框框中 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | 将此元素放入边框框中 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 将此元素放入一个非视觉箱中（逻辑分组），用于分组方程或其他数学文本实例的组件。一个盒状对象可以（例如）作为运算符仿真器，有或没有对齐点，作为换行点，或者被分组以不允许换行。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 放入垂直数组 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在此元素底部设置一条横线 |

### 示例

示例：

```csharp
[C#]
MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
```

### 另请参阅

* class [MathElementBase](../mathelementbase)
* interface [IMathBorderBox](../imathborderbox)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->