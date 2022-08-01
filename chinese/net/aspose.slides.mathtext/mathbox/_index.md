---
title: MathBox
second_title: Aspose.Slides for .NET API 参考
description: 指定数学元素的逻辑装箱包装 例如装箱的对象可以用作带有或不带有对齐点的运算符模拟器 用作换行点或者被分组以不允许换行inside. 例如运算符应该被装箱以防止换行
type: docs
weight: 7910
url: /zh/net/aspose.slides.mathtext/mathbox/
---
## MathBox class

指定数学元素的逻辑装箱（包装）。 例如，装箱的对象可以用作带有或不带有对齐点的运算符模拟器， 用作换行点，或者被分组以不允许换行inside. 例如，“==”运算符应该被装箱以防止换行。

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | 使用指定元素作为参数初始化 MathBox |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | 当为真时，这个算子模拟器作为一个对齐点；即 其他方程中指定的对齐点可以与之对齐。 默认：false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | 基本参数 |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | Differential 当为真时，该框充当微分（例如，被积函数中的𝑑𝑥），并为数学微分接收适当的 水平间距。 默认值：false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | 显式断点指定在 Box 对象的开头是否有换行符， 使得该行在盒子对象的开头换行。 指定前一行数学文本上的运算符号 被使用作为当前数学文本行的对齐点 可能值：1..255 默认值：0（无显式中断） |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | 否 break 此属性指定对象框上的“不可破坏”属性。如果为 true，则框内不会出现换行符。 这对于包含多个二元运算符的运算符模拟器可能很重要。 如果未指定此元素，则框内可能会出现中断。 默认值：true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | Operator Emulator. 如果为 true，则框及其内容表现为单个运算符并继承运算符的属性。 这意味着，例如，该字符可以作为换行符的一个点，并且可以与其他运算符对齐。 运算符 当一个或多个字形组合形成一个运算符时，通常使用模拟器，例如“==” . 默认值：false |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 设置重音符号（此元素顶部的字符） |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 将使用此实例的指定函数作为参数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 将使用此实例的指定函数作为参数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 将使用此实例的指定函数作为参数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 将使用此实例的指定函数作为参数并指定附加参数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 将使用此实例的指定函数作为参数并指定附加参数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 用这个分子和指定的分母创建一个分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 用这个分子和指定的分母创建一个分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 使用此分子和指定分母创建指定类型的分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 使用此分子和指定分母创建指定类型的分数 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 用括号括起来一个数学元素 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 将数学元素括在指定字符中，例如括号或其他字符，如 framing |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 以使用此实例作为函数名的参数的函数 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 以使用此实例作为函数名的参数的函数 |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | 获取子元素 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 使用底部大括号将此元素放在组中 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 使用分组字符（例如下大括号或另一个）将此元素放在一个组中 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 无限制地取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 取积分 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 连接一个数学元素并形成一个数学块 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 加入数学文本并形成数学块 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 创建一个 N 元运算符 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | 创建一个 N 元运算符 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在此元素的顶部设置一个栏 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 根据指定参数指定给定度数的数学根。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 根据指定参数指定给定度数的数学根。 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | 取下限 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | 取下限 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | 创建下标 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | 创建下标 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | 在左边创建下标和上标 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | 在左边创建下标和上标 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | 在右边创建下标和上标 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | 在右边创建下标和上标 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | 创建上标 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | 创建上标 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | 取上限 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | 取上限 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | 将此元素放置在边框中 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | 将此元素放置在边框中 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 将此元素放置在非可视框（逻辑分组）中点， 用作换行点，或被分组以不允许换行。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 放入一个垂直数组 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在此元素的底部设置一个栏 |

### 例子

示例：

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### 也可以看看

* class [MathElementBase](../mathelementbase)
* interface [IMathBox](../imathbox)
* 命名空间 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
