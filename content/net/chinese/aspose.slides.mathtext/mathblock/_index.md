---
title: MathBlock
second_title: Aspose.Slides for .NET API Reference
description: 指定一个包含在 MathParagraph 中并单独换行的数学文本实例。所有的数学区域包括方程、表达式、方程或表达式的数组，以及公式都由数学块表示。
type: docs
weight: 8330
url: /zh/aspose.slides.mathtext/mathblock/
---

## MathBlock 类

指定一个包含在 MathParagraph 中并单独换行的数学文本实例。所有的数学区域，包括方程、表达式、方程或表达式的数组，以及公式都由数学块表示。

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MathBlock](mathblock#constructor)() | 初始化 MathBlock 类的新实例。 |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | 创建一个新的数学块并将指定元素放入其中 |
| [MathBlock](mathblock#constructor_1)(IMathElement) | 创建一个新的数学块并将指定元素放入其中 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | 获取集合中实际包含的子数学元素的数量。只读 Int32。 |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | 返回 false，因为子元素集合可以被修改。 |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | 获取或设置指定索引的 IMathElement。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 设置一个重音符号（位于该元素顶部的字符） |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | 将数学元素添加到集合的末尾。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 将指定的函数与此实例作为参数使用 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 将指定的函数与此实例作为参数使用 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 将指定的函数与此实例作为参数使用 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 将指定的函数与此实例作为参数使用，并指定额外参数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 将指定的函数与此实例作为参数使用，并指定额外参数 |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | 从集合中移除所有元素。 |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | 确定集合是否包含特定值。 |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | 复制到指定数组。 |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | 用分隔符字符（不带括号）分隔子元素 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 创建一个分数，以此作为分子和指定的分母 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 创建一个分数，以此作为分子和指定的分母 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 创建一个指定类型的分数，以此作为分子和指定的分母 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 创建一个指定类型的分数，以此作为分子和指定的分母 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 将数学元素包围在括号中 |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | 将此块的子元素包围在指定字符中，如括号或其他字符作为框架 |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | 将此块的子元素包围在指定字符中，如括号或其他字符作为框架，并用分隔符字符分隔 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 将一个参数的函数以此实例作为函数名 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 将一个参数的函数以此实例作为函数名 |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | 获取子元素 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 使用底部花括号将此元素放入一个组中 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 使用分组字符（如底部花括号或其他）将此元素放入一个组中 |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | 确定集合中特定数学元素的索引。 |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | 将 MathElement 插入集合中指定索引处。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 获取没有限制的积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 获取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 获取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 获取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 获取积分 |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | 将数学元素与此数学块连接 |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | 将数学文本与此数学块连接 |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | 将另一个数学块与此块连接 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 创建一个 N-元运算符 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | 创建一个 N-元运算符 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在此元素的顶部设置一个横线 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定从指定参数得到的给定度数的数学根。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定从指定参数得到的给定度数的数学根。 |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | 从集合中移除特定对象的第一次出现。 |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | 移除集合中指定索引的元素。 |
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
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 将此元素放入一个非视觉框（逻辑分组），用于分组方程的组成部分或其他数学文本实例。一个框对象可以（例如）作为运算符模拟器，有或没有对齐点，作为换行点，或者分组，以禁止在其中换行。 |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | 将子元素放入垂直数组 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在此元素的底部设置一个横线 |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | 将此 [`MathBlock`](../mathblock) 的内容保存为 MathML |

### 示例

示例:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### 另见

* 类 [MathElementBase](../mathelementbase)
* 接口 [IMathBlock](../imathblock)
* 命名空间 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->