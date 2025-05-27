---
title: MathBox
second_title: Aspose.Sildes for .NET API 参考
description: 指定数学元素的逻辑包装（打包）。例如，一个被包装的对象可以作为一个运算符模拟器，可带或不带对齐点，作为换行点，或被分组以不允许内部换行。例如，"==" 运算符应该被包装以防止换行。
type: docs
weight: 8370
url: /zh/aspose.slides.mathtext/mathbox/
---

## MathBox 类

指定数学元素的逻辑包装（打包）。例如，一个被包装的对象可以作为一个运算符模拟器，可带或不带对齐点，作为换行点，或被分组以不允许内部换行。例如，"==" 运算符应该被包装以防止换行。

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | 使用指定的元素初始化 MathBox 作为参数 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | 当为 true 时，此运算符模拟器作为对齐点；也就是说，其他方程中的指定对齐点可以与之对齐。默认值：false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | 基础参数 |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | 当为 true 时，盒子充当微分（例如，积分中的 𝑑𝑥），并接收适当的水平间距用于数学微分。默认值：false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | 明确断开指定在 Box 对象开始时是否存在换行，以使行在盒子对象的开始处换行。指定用于当前数学文本行的对齐点的上一个数学文本行中运算符的数量，可能的值：1..255 默认值：0（无明确断开） |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | 不可断开 此属性指定对象盒子的“不可断开”属性。当为 true 时，盒子内部不能发生换行。对于由多个二元运算符组成的运算符模拟器，这一点可能很重要。当未指定该元素时，盒子内可能会发生换行。默认值：true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | 运算符模拟器。当为 true 时，盒子及其内容作为一个单独的运算符并继承运算符的属性。这意味着，例如，字符可以作为换行点并可以与其他运算符对齐。当一个或多个字形组合形成一个运算符时，运算符模拟器常常被使用，例如 '=='。默认值：false |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 设置一个重音符号（在此元素顶部的字符） |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 将此实例作为参数传递给指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 将此实例作为参数传递给指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 将此实例作为参数传递给指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 将此实例作为参数传递给指定函数和指定的额外参数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 将此实例作为参数传递给指定函数和指定的额外参数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 使用此分子和指定的分母创建一个分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 使用此分子和指定的分母创建一个分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 将数学元素包含在括号中 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 使用指定的字符如括号或其他字符作为框架将数学元素包含在内 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 使用此实例作为函数名传递一个参数的函数 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 使用此实例作为函数名传递一个参数的函数 |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | 获取子元素 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 使用底部大括号将此元素放入组中 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 使用分组字符（如底部大括号或其他）将此元素放入组中 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 获取不带限的积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 获取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 获取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 获取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 获取积分 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 连接一个数学元素并形成一个数学块 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 连接一个数学文本并形成一个数学块 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 创建一个 N-叉运算符 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | 创建一个 N-叉运算符 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在此元素顶部设置一个横线 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定给定参数的数学根。本身的度数。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定给定参数的数学根。 |
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
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 将此元素放入一个非可视盒子（逻辑分组）中，用于分组方程的组件或其他数学文本实例。被包装的对象可以（例如）作为带或不带对齐点的运算符模拟器，作为换行点，或被分组以不允许内部换行。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 放入垂直数组 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在此元素底部设置一个横线 |

### 示例

示例：

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### 参见

* 类 [MathElementBase](../mathelementbase)
* 接口 [IMathBox](../imathbox)
* 命名空间 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->