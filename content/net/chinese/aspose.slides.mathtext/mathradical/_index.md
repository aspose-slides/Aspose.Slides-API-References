---
title: MathRadical
second_title: Aspose.Sildes for .NET API Reference
description: 指定由基地和可选度组成的根函数。根对象的示例是。
type: docs
weight: 8670
url: /zh/aspose.slides.mathtext/mathradical/
---

## MathRadical class

指定根函数，由一个基数和一个可选的度数组成。根对象的示例是 √𝑥。

```csharp
public sealed class MathRadical : MathElementBase, IMathRadical
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MathRadical](mathradical)(IMathElement, IMathElement) | 初始化 MathRadical 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathradical/base) { get; } | 基数参数 |
| [Degree](../../aspose.slides.mathtext/mathradical/degree) { get; } | 度数参数 |
| [HideDegree](../../aspose.slides.mathtext/mathradical/hidedegree) { get; set; } | 隐藏度数 当为 true 时，度数不显示，如 √𝑥 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 设置此元素顶部的重音符号（字符） |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 使用此实例作为参数获取指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 使用此实例作为参数获取指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 使用此实例作为参数获取指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 使用此实例作为参数和指定的附加参数获取指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 使用此实例作为参数和指定的附加参数获取指定函数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 使用此分子和指定分母创建一个分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 使用此分子和指定分母创建一个分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 使用此分子和指定分母创建指定类型的分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 使用此分子和指定分母创建指定类型的分数 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 将数学元素用括号括起来 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 使用指定字符（如括号或其他字符）将数学元素括起来 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 使用此实例作为函数名称获取一个参数的函数 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 使用此实例作为函数名称获取一个参数的函数 |
| [GetChildren](../../aspose.slides.mathtext/mathradical/getchildren)() | 获取子元素 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 使用底部大括号将此元素放入组中 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 使用分组字符（例如底部大括号或其他）将此元素放入组中 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 获取无极限的积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 获取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 获取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 获取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 获取积分 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 连接一个数学元素并形成一个数学块 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 连接一个数学文本并形成一个数学块 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 创建一个 N-元运算符 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | 创建一个 N-元运算符 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在此元素的顶部设置一条横线 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定给定参数的指定度数的数学根。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定给定参数的指定度数的数学根。 |
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
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | 将此元素放入边框框中 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | 将此元素放入边框框中 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 将此元素放入一个非视觉框（逻辑分组），用于分组方程或其他数学文本的实例。一个框对象可以（例如）作为一个运算符仿真器使用，带或不带对齐点，作为换行点，或者被分组以不允许换行。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 放入垂直数组中 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在此元素的底部设置一条横线 |

### 示例

示例：

```csharp
[C#]
MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
```

### 另见

* class [MathElementBase](../mathelementbase)
* interface [IMathRadical](../imathradical)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->