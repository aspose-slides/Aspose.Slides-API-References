---
title: MathFraction
second_title: Aspose.Sildes for .NET API Reference
description: 指定包含由分数线分隔的分子和分母的分数对象。分数线可以是水平或对角线，具体取决于分数属性。该分数对象还用于表示堆叠函数，该函数将一个元素放在另一个元素上方，而没有分数线。
type: docs
weight: 8430
url: /zh/aspose.slides.mathtext/mathfraction/
---

## MathFraction class

指定分数对象，由分子和分母组成，二者由分数线分隔。分数线可以是水平或对角线，具体取决于分数属性。该分数对象还用于表示堆叠函数，该函数将一个元素放在另一个元素上方，而没有分数线。

```csharp
public sealed class MathFraction : MathElementBase, IMathFraction
```

## Constructors

| Name | Description |
| --- | --- |
| [MathFraction](mathfraction#constructor)(IMathElement, IMathElement) | 使用指定的分子和分母初始化类型为 'Bar' 的 MathFraction |
| [MathFraction](mathfraction#constructor_1)(IMathElement, IMathElement, MathFractionTypes) | 使用指定的分子、分母和类型初始化 MathFraction |

## Properties

| Name | Description |
| --- | --- |
| [Denominator](../../aspose.slides.mathtext/mathfraction/denominator) { get; } | 分母 |
| [FractionType](../../aspose.slides.mathtext/mathfraction/fractiontype) { get; set; } | 分数类型 默认值: Bar |
| [Numerator](../../aspose.slides.mathtext/mathfraction/numerator) { get; } | 分子 |

## Methods

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 设置一个重音符号（一个位于该元素顶部的字符） |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 以该实例作为参数使用指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 以该实例作为参数使用指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 以该实例作为参数使用指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 以该实例作为参数使用指定函数和指定的其他参数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 以该实例作为参数使用指定函数和指定的其他参数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 创建一个具有该分子和指定分母的分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 创建一个具有该分子和指定分母的分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 使用该分子和指定分母创建指定类型的分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 使用该分子和指定分母创建指定类型的分数 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 将数学元素用括号括起来 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 使用指定字符（例如括号或其他字符）将数学元素括起来 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 使用该实例作为函数名获取一个参数的函数 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 使用该实例作为函数名获取一个参数的函数 |
| [GetChildren](../../aspose.slides.mathtext/mathfraction/getchildren)() | 获取子元素 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 使用底部花括号将该元素放入一个组中 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 使用分组字符（例如底部花括号或其他）将该元素放入一个组中 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 获取无界限的积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 获取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 获取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 获取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 获取积分 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 连接一个数学元素并形成一个数学块 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 连接一个数学文本并形成一个数学块 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 创建一个 N-元运算符 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | 创建一个 N-元运算符 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在该元素上方设置一条横线 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定来自指定参数的给定级数的数学根。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定来自指定参数的给定级数的数学根。 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | 获取下限 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | 获取下限 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | 创建下标 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | 创建下标 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | 在左侧创建下标和上标 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | 在左侧创建下标和上标 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | 在右侧创建下标和上标 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | 在右侧创建下标和上标 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | 创建上标 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | 创建上标 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | 获取上限 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | 获取上限 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | 将该元素放入边界框中 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | 将该元素放入边界框中 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 将该元素放入一个非视觉框（逻辑分组），用于分组方程或其他数学文本的组件。一个盒对象可以（例如）作为一个运算符仿真器，带有或不带有对齐点，作为换行点，或被分组以不允许换行。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 放入垂直数组 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在该元素底部设置一条横线 |

### Examples

示例:

```csharp
[C#]
MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
```

### See Also

* class [MathElementBase](../mathelementbase)
* interface [IMathFraction](../imathfraction)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->