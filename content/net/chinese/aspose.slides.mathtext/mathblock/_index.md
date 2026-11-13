---
title: MathBlock
second_title: Aspose.Sildes for .NET API 参考
description: 指定一个包含在 MathParagraph 中并在单独一行开始的数学文本实例。所有数学区域，包括等式、表达式、等式或表达式数组以及公式，都由数学块表示。
type: docs
weight: 8610
url: /zh/aspose.slides.mathtext/mathblock/
---
## MathBlock 类

指定一个包含在 MathParagraph 中并在单独一行开始的数学文本实例。所有数学区域，包括等式、表达式、等式或表达式数组以及公式，都由数学块表示。

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MathBlock](mathblock#constructor)() | 初始化 MathBlock 类的新实例。 |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | 创建一个新的数学块并将指定的元素放入其中。 |
| [MathBlock](mathblock#constructor_1)(IMathElement) | 创建一个新的数学块并将指定的元素放入其中。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | 获取集合中实际包含的子数学元素数量。只读 Int32。 |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | 返回 false，因为子元素集合可以被修改。 |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | 获取或设置指定索引处的 IMathElement。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 设置一个重音符号（此元素顶部的字符）。 |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | 在集合末尾添加一个数学元素。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 使用此实例作为参数调用指定的函数。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 使用此实例作为参数调用指定的函数。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 使用此实例作为参数调用指定的函数。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 使用此实例作为参数并使用指定的附加参数调用指定的函数。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 使用此实例作为参数并使用指定的附加参数调用指定的函数。 |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | 从集合中移除所有元素。 |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | 确定集合是否包含特定值。 |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | 复制到指定的数组。 |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | 使用分隔字符（不含括号）分隔子元素。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 使用此分子和指定的分母创建分数。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 使用此分子和指定的分母创建分数。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 使用此分子和指定的分母创建指定类型的分数。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 使用此分子和指定的分母创建指定类型的分数。 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 将数学元素用括号括起。 |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | 使用指定字符（如括号或其他字符）将此块的子元素括起来。 |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | 使用指定字符（如括号或其他）将此块的子元素括起来，并使用分隔字符分隔。 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 使用此实例作为函数名，对参数调用函数。 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 使用此实例作为函数名，对参数调用函数。 |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | 获取子元素。 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 使用底部大括号将此元素放入组中。 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 使用诸如底部大括号或其他分组字符将此元素放入组中。 |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | 确定集合中特定数学元素的索引。 |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | 在指定索引处向集合中插入一个 MathElement。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 获取无上下限的积分。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 获取积分。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 获取积分。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 获取积分。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 获取积分。 |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | 将数学元素与此数学块连接。 |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | 将数学文本与此数学块连接。 |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | 将另一个数学块与此块连接。 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 创建 N 元运算符。 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | 创建 N 元运算符。 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在此元素顶部设置一条横线。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定给定次数的数学根，从指定参数计算。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定给定次数的数学根，从指定参数计算。 |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | 从集合中移除首次出现的特定对象。 |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | 移除集合中指定索引处的元素。 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | 获取下限。 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | 获取下限。 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | 创建下标。 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | 创建下标。 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | 在左侧创建下标和上标。 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | 在左侧创建下标和上标。 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | 在右侧创建下标和上标。 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | 在右侧创建下标和上标。 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | 创建上标。 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | 创建上标。 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | 获取上限。 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | 获取上限。 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | 将此元素放入边框盒中。 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | 将此元素放入边框盒中。 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 将此元素放入非可视盒（逻辑分组），用于对方程或其他数学文本实例的组件进行分组。盒状对象可以（例如）作为带或不带对齐点的运算符仿真器，作为换行点，或被分组以不允许内部换行。 |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | 将子元素排列成垂直数组。 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在此元素底部设置一条横线。 |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | 将此 [`MathBlock`](../mathblock) 的内容保存为 MathML。 |

### 示例

示例：

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### 另请参见

* 类 [MathElementBase](../mathelementbase)
* 接口 [IMathBlock](../imathblock)
* 命名空间 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->