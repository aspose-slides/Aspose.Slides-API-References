---
title: MathDelimiter
second_title: Aspose.Sildes for .NET API Reference
description: 指定由开合字符（如括号、花括号、方括号和竖线）组成的分隔符对象，和内部由指定字符分隔的一个或多个数学元素。示例：2 2x7C2
type: docs
weight: 8390
url: /zh/aspose.slides.mathtext/mathdelimiter/
---

## MathDelimiter 类

指定分隔符对象，由开合字符（如括号、花括号、方括号和竖线）组成，以及内部由指定字符分隔的一个或多个数学元素。示例：（𝑥2）； [𝑥2&#x7C;𝑦2]

```csharp
public sealed class MathDelimiter : MathElementBase, IMathDelimiter
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MathDelimiter](mathdelimiter)(IMathElement) | 用指定元素初始化 MathDelimiter，作为单一基础参数 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/mathdelimiter/arguments) { get; } | 由分隔符字符分隔的一个或多个数学元素 |
| [BeginningCharacter](../../aspose.slides.mathtext/mathdelimiter/beginningcharacter) { get; set; } | 分隔符开始字符指定开始或开口分隔符字符。数学分隔符是如括号、方括号和花括号等包围字符。默认值：'('。 |
| [DelimiterShape](../../aspose.slides.mathtext/mathdelimiter/delimitershape) { get; set; } | 指定分隔符对象中的分隔符形状。当为 MathDelimiterShape.Centered 时，分隔符围绕数学文本的数学轴居中，并且仍可被调整以适应其内容的整个高度。当为 MathDelimiterShape.Match 时，其高度和形状会被修改以完全匹配其内容。 |
| [EndingCharacter](../../aspose.slides.mathtext/mathdelimiter/endingcharacter) { get; set; } | 分隔符结束字符指定结束或关闭分隔符字符。数学分隔符是如括号、方括号和花括号等包围字符。默认值：')'。 |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathdelimiter/growtomatchoperandheight) { get; set; } | 指定 BeginningCharacter、SeparatorCharacter、EndingCharacter 的增长。当为 true 时，分隔符垂直生长以匹配其操作数的高度。默认值为 true |
| [SeparatorCharacter](../../aspose.slides.mathtext/mathdelimiter/separatorcharacter) { get; set; } | 分隔符分隔字符指定在分隔符对象中分隔参数的字符。默认值：'&#x7C;'。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 设置一个音调符号（该元素顶部的字符） |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 以此实例作为参数接受指定的函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 以此实例作为参数接受指定的函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 以此实例作为参数接受指定的函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 以此实例作为参数和指定的附加参数接受指定的函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 以此实例作为参数和指定的附加参数接受指定的函数 |
| [Delimit](../../aspose.slides.mathtext/mathdelimiter/delimit)(char) | 使用指定的分隔符字符对参数进行分隔 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 以此分子和指定分母创建分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 以此分子和指定分母创建分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 以此分子和指定类型的分母创建分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 以此分子和指定类型的分母创建分数 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 用括号封闭一个数学元素 |
| override [Enclose](../../aspose.slides.mathtext/mathdelimiter/enclose#enclose_1)(char, char) | 用指定的字符（如括号或其他框架字符）封闭一个数学元素 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 以此实例作为函数名称接受参数的函数 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 以此实例作为函数名称接受参数的函数 |
| [GetChildren](../../aspose.slides.mathtext/mathdelimiter/getchildren)() | 获取子元素 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 使用底部花括号将此元素置于一组中 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 使用分组字符（如底部花括号或其他）将此元素置于一组中 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 进行无极限的积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 进行积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 进行积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 进行积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 进行积分 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 连接一个数学元素并形成一个数学块 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 连接一个数学文本并形成一个数学块 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 创建一个 N-元操作符 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | 创建一个 N-元操作符 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在此元素顶部设置一个横线 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定来自指定参数的给定度数的数学根。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定来自指定参数的给定度数的数学根。 |
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
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | 将此元素放置在边框框中 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | 将此元素放置在边框框中 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 将此元素放置在非视觉框中（逻辑分组），用于对方程的组件或其他数学文本的实例进行分组。一个盒状对象可以（例如）作为操作符模拟器（有或没有对齐点），作为换行点，或者被分组以防止换行。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 放置在垂直数组中 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在此元素底部设置一个横线 |

### 示例

示例：

```csharp
[C#]
IMathElement element = new MathematicalText("x");
MathDelimiter delimiter = new MathDelimiter(element);
```

### 另请参阅

* 类 [MathElementBase](../mathelementbase)
* 接口 [IMathDelimiter](../imathdelimiter)
* 命名空间 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->