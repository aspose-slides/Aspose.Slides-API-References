---
title: MathAccent
second_title: Aspose.Sildes for .NET API Reference
description: 指定由基底和组合音调符号组成的音调函数示例 ́
type: docs
weight: 8270
url: /zh/aspose.slides.mathtext/mathaccent/
---

## MathAccent class

指定音调函数，由基底和组合音调符号组成示例: 𝑎́

```csharp
public sealed class MathAccent : MathElementBase, IMathAccent
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MathAccent](mathaccent#constructor)(IMathElement) | 创建一个应用于指定数学元素的数学音调，使用默认音调字符值 |
| [MathAccent](mathaccent#constructor_1)(IMathElement, char) | 创建一个应用于指定数学元素的数学音调 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathaccent/base) { get; } | 应用音调的参数 |
| [Character](../../aspose.slides.mathtext/mathaccent/character) { get; set; } | 音调字符，值应在 (U+0300–U+036F) 或 (U+20D0–U+20EF) 范围内，默认值: 组合抑扬音调 (U+0302) |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 设置音调符号（此元素顶部的字符） |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 使用此实例作为参数获取指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 使用此实例作为参数获取指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 使用此实例作为参数获取指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 使用此实例作为参数和指定额外参数获取指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 使用此实例作为参数和指定额外参数获取指定函数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 使用此分子和指定分母创建一个分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 使用此分子和指定分母创建一个分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 使用此分子和指定分母创建指定类型的分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 使用此分子和指定分母创建指定类型的分数 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 将数学元素用括号括起来 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 用指定字符（如括号或其他框架字符）将数学元素括起来 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 使用此实例作为函数名称获取一个参数的函数 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 使用此实例作为函数名称获取一个参数的函数 |
| [GetChildren](../../aspose.slides.mathtext/mathaccent/getchildren)() | 获取子元素 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 使用下部大括号将此元素放入一个组中 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 使用分组字符（如下部大括号或其他）将此元素放入一个组中 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 取无限制的积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 取积分 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 连接数学元素并形成数学块 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 连接数学文本并形成数学块 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 创建 N 叉算子 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | 创建 N 叉算子 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在此元素的顶部设置一条线 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定来自指定参数的给定程度的数学根。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定来自指定参数的给定程度的数学根。 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | 取下限 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | 取下限 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | 创建下标 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | 创建下标 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | 在左侧创建下标和上标 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | 在左侧创建下标和上标 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | 在右侧创建下标和上标 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | 在右侧创建下标和上标 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | 创建上标 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | 创建上标 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | 取上限 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | 取上限 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | 将此元素放入边框框中 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | 将此元素放入边框框中 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 将此元素放入一个非视觉框（逻辑分组），用于分组方程或其他数学文本实例的组件。一个框定的对象可以（例如）作为操作符模拟器使用，有无对齐点，作为换行点，或者以不允许在其中换行的方式分组。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 放入垂直数组 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在此元素的底部设置一条线 |

### 示例

示例:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("x");
MathAccent accent = new MathAccent(baseElement, '~');
```

### 另请参阅

* class [MathElementBase](../mathelementbase)
* interface [IMathAccent](../imathaccent)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->