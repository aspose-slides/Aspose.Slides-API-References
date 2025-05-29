---
title: MathFraction
second_title: Aspose.Sildes for .NET API Reference
description: 指定一个分数对象，由分子和分母组成，中间用一个分数线分隔。分数线可以是水平的或斜的，具体取决于分数属性。分数对象也用于表示堆叠功能，它将一个元素放在另一个元素上方，没有分数线。
type: docs
weight: 8430
url: /zh/aspose.slides.mathtext/mathfraction/
---

## MathFraction 类

指定分数对象，由分子和分母组成，中间用一个分数线分隔。分数线可以是水平的或斜的，具体取决于分数属性。分数对象也用于表示堆叠功能，它将一个元素放在另一个元素上方，没有分数线。

```csharp
public sealed class MathFraction : MathElementBase, IMathFraction
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MathFraction](mathfraction#constructor)(IMathElement, IMathElement) | 用指定的分子和分母初始化类型为 'Bar' 的 MathFraction |
| [MathFraction](mathfraction#constructor_1)(IMathElement, IMathElement, MathFractionTypes) | 用指定的分子、分母和类型初始化 MathFraction |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Denominator](../../aspose.slides.mathtext/mathfraction/denominator) { get; } | 分母 |
| [FractionType](../../aspose.slides.mathtext/mathfraction/fractiontype) { get; set; } | 分数类型 默认: Bar |
| [Numerator](../../aspose.slides.mathtext/mathfraction/numerator) { get; } | 分子 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 设置一个重音符号（一个字符在该元素的顶部） |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 以此实例作为参数使用指定的函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 以此实例作为参数使用指定的函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 以此实例作为参数使用指定的函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 以此实例作为参数使用指定的函数和指定的附加参数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 以此实例作为参数使用指定的函数和指定的附加参数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 使用此分子和指定的分母创建一个分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 使用此分子和指定的分母创建一个分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 用括号括住一个数学元素 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 用指定的字符（例如括号或其他字符）括住一个数学元素 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 以此实例作为函数名称使用一个参数的函数 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 以此实例作为函数名称使用一个参数的函数 |
| [GetChildren](../../aspose.slides.mathtext/mathfraction/getchildren)() | 获取子元素 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 使用底部大括号将此元素放入一个组 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 使用分组字符（例如底部大括号或其他）将此元素放入一个组 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 进行无界限的积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 进行积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 进行积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 进行积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 进行积分 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 连接一个数学元素并形成一个数学块 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 连接一个数学文本并形成一个数学块 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 创建一个 N-元操作符 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | 创建一个 N-元操作符 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在此元素的顶部设置一条线 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 从指定的参数中指定给定次数的数学根。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 从指定的参数中指定给定次数的数学根。 |
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
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | 将此元素放入边框盒中 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | 将此元素放入边框盒中 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 将此元素放入一个非可视盒（逻辑分组），用于对方程的组件或其他数学文本实例进行分组。一个盒子对象可以（例如）充当具有或不具有对齐点的操作符仿真器，充当换行点，或者分组不允许换行。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 放入一个纵向数组 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在此元素的底部设置一条线 |

### 示例

示例：

```csharp
[C#]
MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
```

### 另请参阅

* class [MathElementBase](../mathelementbase)
* interface [IMathFraction](../imathfraction)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->