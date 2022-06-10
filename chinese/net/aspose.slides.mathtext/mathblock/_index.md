---
title: MathBlock
second_title: Aspose.Slides for .NET API 参考
description: 指定包含在 MathParagraph 中并在其自己的行上开始的数学文本实例 所有数学区域包括方程式表达式方程式或表达式的数组以及公式都由数学块表示
type: docs
weight: 7870
url: /zh/net/aspose.slides.mathtext/mathblock/
---
## MathBlock class

指定包含在 MathParagraph 中并在其自己的行上开始的数学文本实例。 所有数学区域，包括方程式、表达式、方程式或表达式的数组以及公式都由数学块表示。

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [MathBlock](mathblock#constructor)() | 初始化 MathBlock 类的新实例。 |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | 创建一个新的数学块并将指定的元素放入其中 |
| [MathBlock](mathblock#constructor_1)(IMathElement) | 创建一个新的数学块并将指定元素放入其中 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | 获取集合中实际包含的子数学元素的数量。 只读Int32。 |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | 返回 false，因为可以修改子元素集合。 |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | 获取或设置指定索引处的 IMathElement。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 设置重音符号（此元素顶部的字符） |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | 将数学元素添加到集合的末尾。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 以使用此实例作为参数的指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 以使用此实例作为参数的指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 以使用此实例作为参数的指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 将使用此实例的指定函数作为参数并指定附加参数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 将使用此实例的指定函数作为参数并指定附加参数 |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | 从集合中删除所有元素。 |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | 确定集合是否包含特定值。 |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | 复制到指定数组。 |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | 用分隔符分隔子元素（不带括号） |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 使用此分子和指定分母创建分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 使用此分子和指定分母创建分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 使用此分子和指定分母创建指定类型的分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 使用此分子和指定分母创建指定类型的分数 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 将数学元素括在括号中 |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | 将此块的子元素括在指定的字符中，例如括号或其他字符作为框架 |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | 将此块的子元素括在指定字符中，例如括号或其他作为框架 并用分隔符分隔 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 使用该实例作为函数名的参数的函数 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 使用该实例作为函数名的参数的函数 |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | 获取子元素 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 使用底部大括号将此元素放在组中 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 使用分组字符（例如下大括号或另一个 |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | 确定集合中特定数学元素的索引。 |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | 将 MathElement 插入到集合中指定索引处。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 无限制地取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 取整数 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 取整数 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 取整数 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 取整数 |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | 用这个数学块连接一个数学元素 |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | 用这个数学块连接一个数学文本 |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | 连接另一个数学块 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 创建 N 元运算符 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | 创建 N 元运算符 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在此元素顶部设置一个栏 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 根据指定参数指定给定度数的数学根。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 根据指定参数指定给定度数的数学根。 |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | 从集合中删除特定对象的第一个匹配项。 |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | 移除集合指定索引处的元素。 |
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
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | 将子元素放入垂直数组 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在此元素的底部设置一个栏 |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | 将此[`MathBlock`](../mathblock)的内容保存为 MathML |

### 例子

示例:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### 也可以看看

* class [MathElementBase](../mathelementbase)
* interface [IMathBlock](../imathblock)
* 命名空间 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
