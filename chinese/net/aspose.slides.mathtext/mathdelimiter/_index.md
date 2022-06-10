---
title: MathDelimiter
second_title: Aspose.Slides for .NET API 参考
description: 指定分隔符对象由开始和结束字符如圆括号 大括号方括号和竖线和一个或里面有更多的数学元素用指定的字符分隔 示例2 2x7C2
type: docs
weight: 7930
url: /zh/net/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter class

指定分隔符对象，由开始和结束字符（如圆括号、 大括号、方括号和竖线）和一个或里面有更多的数学元素，用指定的字符分隔。 示例:(𝑥2); [𝑥2&#x7C;𝑦2]

```csharp
public sealed class MathDelimiter : MathElementBase, IMathDelimiter
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [MathDelimiter](mathdelimiter)(IMathElement) | 使用指定元素作为单个基本参数初始化 MathDelimiter |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/mathdelimiter/arguments) { get; } | 一个或多个用分隔符分隔的数学元素 |
| [BeginningCharacter](../../aspose.slides.mathtext/mathdelimiter/beginningcharacter) { get; set; } | 分隔符开始字符指定开始或开始分隔符。 数学定界符是括起来的字符，例如圆括号、方括号和花括号。 默认值:'('。 |
| [DelimiterShape](../../aspose.slides.mathtext/mathdelimiter/delimitershape) { get; set; } | 指定分隔符对象中分隔符的形状。 什么时候是 MathDelimiterShape.Centered，分隔符以数学文本 的数学轴为中心，并且仍然适合其内容的整个高度。 什么时候是 MathDelimiterShape.Match，它们的高度和形状被改变以完全匹配它们的内容。 |
| [EndingCharacter](../../aspose.slides.mathtext/mathdelimiter/endingcharacter) { get; set; } | Delimiter Ending Character 指定结束或关闭分隔符。 数学定界符是括起来的字符，例如圆括号、方括号和花括号。 默认值:')'。 |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathdelimiter/growtomatchoperandheight) { get; set; } | 指定BeginningCharacter、SeparatorCharacter、EndingCharacter 当为真时，分隔符垂直增长以匹配其操作数高度。 默认值为真 |
| [SeparatorCharacter](../../aspose.slides.mathtext/mathdelimiter/separatorcharacter) { get; set; } | Delimiter Separator Character 指定分隔分隔符对象中的参数的字符。 默认值:'&#x7C;'。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 设置重音符号（此元素顶部的字符） |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 以使用此实例作为参数的指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 以使用此实例作为参数的指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 以使用此实例作为参数的指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 将使用此实例的指定函数作为参数并指定附加参数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 将使用此实例的指定函数作为参数并指定附加参数 |
| [Delimit](../../aspose.slides.mathtext/mathdelimiter/delimit)(char) | 使用指定的分隔符分隔参数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 使用此分子和指定分母创建分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 使用此分子和指定分母创建分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 使用此分子和指定分母创建指定类型的分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 使用此分子和指定分母创建指定类型的分数 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 将数学元素括在括号中 |
| override [Enclose](../../aspose.slides.mathtext/mathdelimiter/enclose#enclose_1)(char, char) | 将数学元素括在指定字符中，例如括号或其他字符，作为框架 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 使用该实例作为函数名的参数的函数 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 使用该实例作为函数名的参数的函数 |
| [GetChildren](../../aspose.slides.mathtext/mathdelimiter/getchildren)() | 获取子元素 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 使用底部大括号将此元素放在组中 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 使用分组字符（例如下大括号或另一个 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 无限制地取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 取整数 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 取整数 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 取整数 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 取整数 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 连接一个数学元素并形成一个数学块 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 连接数学文本并形成数学块 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 创建 N 元运算符 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | 创建 N 元运算符 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在此元素顶部设置一个栏 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 根据指定参数指定给定度数的数学根。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 根据指定参数指定给定度数的数学根。 |
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
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | 将此元素放置在边框中 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | 将此元素放在边框中 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 将此元素置于非可视框（逻辑分组） 用于对方程的组件或其他数学文本实例进行分组. 装箱对象可以（例如）用作带有或不带有对齐点的操作员模拟器， 用作换行点，或者被分组以不允许换行内破。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 放入垂直数组 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在此元素的底部设置一个栏 |

### 例子

示例:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
MathDelimiter delimiter = new MathDelimiter(element);
```

### 也可以看看

* class [MathElementBase](../mathelementbase)
* interface [IMathDelimiter](../imathdelimiter)
* 命名空间 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
