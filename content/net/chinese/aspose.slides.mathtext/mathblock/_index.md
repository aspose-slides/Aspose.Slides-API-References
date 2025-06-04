---
title: MathBlock
second_title: Aspose.Sildes for .NET API Reference
description: 指定包含在 MathParagraph 中并独立起始于一行的数学文本实例。所有数学区域，包括方程、表达式、方程或表达式的数组以及公式，都通过数学块表示。
type: docs
weight: 8330
url: /zh/aspose.slides.mathtext/mathblock/
---

## MathBlock class

指定包含在 MathParagraph 中并独立起始于一行的数学文本实例。所有数学区域，包括方程、表达式、方程或表达式的数组以及公式，都通过数学块表示。

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
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | 获取或设置指定索引处的 IMathElement。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 设置一个重音符（此元素顶部的字符） |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | 将数学元素添加到集合的末尾。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 以此实例作为参数接受指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 以此实例作为参数接受指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 以此实例作为参数接受指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 以此实例作为参数接受指定函数和指定额外参数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 以此实例作为参数接受指定函数和指定额外参数 |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | 从集合中移除所有元素。 |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | 确定集合是否包含特定值。 |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | 复制到指定的数组。 |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | 用分隔字符（不带括号）定界子元素 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 创建一个以此为分子和指定分母的分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 创建一个以此为分子和指定分母的分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 创建一个指定类型的分数，以此为分子和指定分母 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 创建一个指定类型的分数，以此为分子和指定分母 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 将数学元素用括号括起来 |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | 将此块的子元素用指定字符（如括号或其他字符）括起来 |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | 将此块的子元素用指定字符（如括号或其他字符）括起来，并用分隔字符定界 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 以此实例作为函数名接受一个参数的函数 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 以此实例作为函数名接受一个参数的函数 |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | 获取子元素 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 使用底部大括号将此元素放入组中 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 使用分组字符如底部大括号或其他将此元素放入组中 |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | 确定集合中特定数学元素的索引。 |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | 在指定索引处将 MathElement 插入集合。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 不带限制地取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 取积分 |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | 将数学元素与此数学块连接 |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | 将数学文本与此数学块连接 |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | 将另一个数学块与此块连接 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 创建 N-元操作符 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | 创建 N-元操作符 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在此元素的顶部设置一条横杠 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定从指定参数计算的给定次数的数学根。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定从指定参数计算的给定次数的数学根。 |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | 从集合中移除特定对象的第一次出现。 |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | 移除集合中指定索引处的元素。 |
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
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 将此元素放入一个非可视框（逻辑分组），用于分组方程或其他数学文本实例的组件。一个框住的对象可以（例如）充当一个操作符仿真器，无论有无对齐点，充当换行点，或者被分组以禁止换行。 |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | 将子元素放入垂直数组 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在此元素的底部设置一条横杠 |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | 将此 [`MathBlock`](../mathblock) 的内容保存为 MathML |

### 示例

示例:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### 另请参阅

* class [MathElementBase](../mathelementbase)
* interface [IMathBlock](../imathblock)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
