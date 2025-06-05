---
title: MathLimit
second_title: Aspose.Sildes for .NET API Reference
description: 指定由基线上的文本和其上方或下方紧接着的缩小文本组成的Limit对象。
type: docs
weight: 8560
url: /zh/aspose.slides.mathtext/mathlimit/
---

## MathLimit class

指定Limit对象，由基线上的文本和其上方或下方紧接着的缩小文本组成。

```csharp
public sealed class MathLimit : MathElementBase, IMathLimit
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MathLimit](mathlimit#constructor)(IMathElement, IMathElement) | 使用下限初始化MathLimit类的新实例 |
| [MathLimit](mathlimit#constructor_1)(IMathElement, IMathElement, bool) | 初始化MathLimit类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathlimit/base) { get; } | 基础参数 |
| [Limit](../../aspose.slides.mathtext/mathlimit/limit) { get; } | 极限参数 |
| [UpperLimit](../../aspose.slides.mathtext/mathlimit/upperlimit) { get; set; } | 指定上限或下限 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 设置一个重音标记（在此元素顶部的一个字符） |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 使用此实例作为参数取指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 使用此实例作为参数取指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 使用此实例作为参数取指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 使用此实例作为参数和指定的附加参数取指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 使用此实例作为参数和指定的附加参数取指定函数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 使用此分子和指定的分母创建一个分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 使用此分子和指定的分母创建一个分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 将数学元素放入括号中 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 将数学元素放入指定字符（如括号或其他字符）中 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 使用此实例作为函数名称取一个参数的函数 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 使用此实例作为函数名称取一个参数的函数 |
| [GetChildren](../../aspose.slides.mathtext/mathlimit/getchildren)() | 获取子元素 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 使用底部花括号将此元素放入组中 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 使用分组字符（如底部花括号或其他）将此元素放入组中 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 不带限制的取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 取积分 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 连接一个数学元素并形成一个数学块 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 连接一个数学文本并形成一个数学块 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 创建N元操作符 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | 创建N元操作符 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在此元素顶部设置一个横线 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定从指定参数给定度数的数学根。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定从指定参数给定度数的数学根。 |
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
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 将此元素放入一个非可视框（逻辑分组），用于分组方程的组件或其他数学文本实例。一个框对象可以（例如）充当带或不带对齐点的操作符仿真器，充当换行点，或被分组以禁止换行。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 放入一个垂直数组 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在此元素底部设置一个横线 |

### 示例

示例：

```csharp
[C#]
MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("𝑛→∞"));
```

### 另请参见

* class [MathElementBase](../mathelementbase)
* interface [IMathLimit](../imathlimit)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->