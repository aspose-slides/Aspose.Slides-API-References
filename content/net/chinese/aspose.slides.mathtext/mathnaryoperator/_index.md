---
title: MathNaryOperator
second_title: Aspose.Sildes for .NET API Reference
description: 指定N元数学对象，例如求和和积分。它由一个运算符、一个基数（或操作数）以及可选的上限和下限组成。N元运算符的例子包括：求和、并集、交集、积分
type: docs
weight: 8610
url: /zh/aspose.slides.mathtext/mathnaryoperator/
---

## MathNaryOperator class

指定N元数学对象，例如求和和积分。它由一个运算符，一个基数（或操作数），以及可选的上限和下限组成。N元运算符的例子包括：求和、并集、交集、积分

```csharp
public sealed class MathNaryOperator : MathElementBase, IMathNaryOperator
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MathNaryOperator](mathnaryoperator#constructor)(char, IMathElement) | 初始化MathNaryOperator类的新实例。 |
| [MathNaryOperator](mathnaryoperator#constructor_1)(char, IMathElement, IMathElement) | 初始化MathNaryOperator类的新实例。 |
| [MathNaryOperator](mathnaryoperator#constructor_2)(char, IMathElement, IMathElement, IMathElement) | 初始化MathNaryOperator类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathnaryoperator/base) { get; } | 基数参数 |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathnaryoperator/growtomatchoperandheight) { get; set; } | 运算符字符在垂直方向上增长以匹配其操作数的高度 |
| [HideSubscript](../../aspose.slides.mathtext/mathnaryoperator/hidesubscript) { get; set; } | 隐藏下标 |
| [HideSuperscript](../../aspose.slides.mathtext/mathnaryoperator/hidesuperscript) { get; set; } | 隐藏上标 |
| [LimitLocation](../../aspose.slides.mathtext/mathnaryoperator/limitlocation) { get; set; } | 极限的位置（下标和上标） |
| [Operator](../../aspose.slides.mathtext/mathnaryoperator/operator) { get; set; } | N元运算符字符，例如：'∑'，'∫' |
| [Subscript](../../aspose.slides.mathtext/mathnaryoperator/subscript) { get; } | 指定下标参数，例如，在积分的情况下，设置下限 |
| [Superscript](../../aspose.slides.mathtext/mathnaryoperator/superscript) { get; } | 指定上标参数，例如，在积分的情况下，设置上限 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 设置一个重音标记（在此元素顶部的字符） |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 使用此实例作为参数提取指定的函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 使用此实例作为参数提取指定的函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 使用此实例作为参数提取指定的函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 使用此实例作为参数提取指定的函数，并指定附加参数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 使用此实例作为参数提取指定的函数，并指定附加参数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 使用此分子和指定分母创建一个分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 使用此分子和指定分母创建一个分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 使用此分子和指定分母创建指定类型的分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 使用此分子和指定分母创建指定类型的分数 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 将数学元素括在括号中 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 将数学元素括在指定字符中，例如括号或其他字符作为框架 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 使用此实例作为函数名称提取一个参数的函数 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 使用此实例作为函数名称提取一个参数的函数 |
| [GetChildren](../../aspose.slides.mathtext/mathnaryoperator/getchildren)() | 获取子元素 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 使用下方花括号将此元素放入组中 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 使用分组字符（如下方花括号或其他）将此元素放入组中 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 提取无极限的积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 提取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 提取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 提取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 提取积分 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 连接一个数学元素并形成一个数学块 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 连接一个数学文本并形成一个数学块 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 创建N元运算符 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | 创建N元运算符 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在此元素的顶部设置一个横线 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定来自指定参数的给定度的数学根。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定来自指定参数的给定度的数学根。 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | 提取下限 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | 提取下限 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | 创建下标 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | 创建下标 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | 在左侧创建下标和上标 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | 在左侧创建下标和上标 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | 在右侧创建下标和上标 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | 在右侧创建下标和上标 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | 创建上标 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | 创建上标 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | 提取上限 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | 提取上限 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | 将此元素放入边框盒中 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | 将此元素放入边框盒中 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 将此元素放入逻辑框（非可视框）中，用于分组方程的组件或其他数学文本的实例。一个框对象可以（例如）作为运算符仿真器，带或不带对齐点，作为换行点，或分组以不允许换行。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 放入垂直数组 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在此元素的底部设置一个横线 |

### 示例

示例：

```csharp
[C#]
IMathNaryOperator naryOperator = new MathematicalText("x").Nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```

### 另见

* class [MathElementBase](../mathelementbase)
* interface [IMathNaryOperator](../imathnaryoperator)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->