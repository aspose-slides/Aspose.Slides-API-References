---
title: MathSuperscriptElement
second_title: Aspose.Sildes for .NET API Reference
description: 指定由基底和位于上方和右侧的缩小尺寸的上标组成的上标对象
type: docs
weight: 8750
url: /zh/aspose.slides.mathtext/mathsuperscriptelement/
---

## MathSuperscriptElement class

指定由基底和位于上方和右侧的缩小尺寸的上标组成的上标对象

```csharp
public sealed class MathSuperscriptElement : BaseScript, IMathSuperscriptElement
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MathSuperscriptElement](mathsuperscriptelement)(IMathElement, IMathElement) | 初始化 MathSuperscriptElement 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Base](../../aspose.slides.mathtext/basescript/base) { get; } | 基底参数 |
| [Superscript](../../aspose.slides.mathtext/mathsuperscriptelement/superscript) { get; } | 上标 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 设置一个重音符号（该元素顶部的字符） |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 使用此实例作为参数获取指定的函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 使用此实例作为参数获取指定的函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 使用此实例作为参数获取指定的函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 使用此实例作为参数和指定的附加参数获取指定的函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 使用此实例作为参数和指定的附加参数获取指定的函数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 创建一个以此分子和指定分母的分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 创建一个以此分子和指定分母的分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 创建指定类型的分数，以此分子和指定分母 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 创建指定类型的分数，以此分子和指定分母 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 用括号包围数学元素 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 用指定字符（如括号或其他字符）包围数学元素 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 使用此实例作为函数名称获取一个参数的函数 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 使用此实例作为函数名称获取一个参数的函数 |
| [GetChildren](../../aspose.slides.mathtext/mathsuperscriptelement/getchildren)() | 获取子元素 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 使用底部大括号将此元素放入一个组中 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 使用分组字符（如底部大括号或其他）将此元素放入一个组中 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 获取不带限制的积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 获取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 获取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 获取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 获取积分 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 连接数学元素并形成数学块 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 连接数学文本并形成数学块 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 创建一个 N 叉运算符 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | 创建一个 N 叉运算符 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在此元素顶部设置一个条 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定给定参数的数学根。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定给定参数的数学根。 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | 获取下限 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | 获取下限 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | 创建下标 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | 创建下标 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | 创建左侧的下标和上标 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | 创建左侧的下标和上标 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | 创建右侧的下标和上标 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | 创建右侧的下标和上标 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | 创建上标 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | 创建上标 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | 获取上限 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | 获取上限 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | 将此元素放入边框框中 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | 将此元素放入边框框中 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 将此元素放入一个非视觉框（逻辑分组）中，该框用于将方程或其他数学文本的组件分组。一个框定的对象可以（例如）用作运算符模拟器，有或没有对齐点，作为换行点，或者被分组以防止其中之间的换行。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 放入垂直数组中 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在此元素底部设置一个条 |

### 示例

示例:

```csharp
[C#]
MathSuperscriptElement superscriptElement = new MathematicalText("N").SetSuperscript("i");
```

### 另请参见

* class [BaseScript](../basescript)
* interface [IMathSuperscriptElement](../imathsuperscriptelement)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
