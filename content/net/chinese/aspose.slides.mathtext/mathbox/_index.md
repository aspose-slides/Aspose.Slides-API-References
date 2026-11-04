---
title: MathBox
second_title: Aspose.Sildes for .NET API 参考
description: 指定数学元素的逻辑盒装包装。举例来说，盒装对象可以作为带或不带对齐点的运算符仿真器、作为换行点，或进行分组以防止内部换行。例如，运算符应进行盒装以防止换行。
type: docs
weight: 8650
url: /zh/aspose.slides.mathtext/mathbox/
---
## MathBox 类

指定数学元素的逻辑盒装（包装）。例如，一个盒装对象可以作为带或不带对齐点的运算符仿真器，作为换行点，或进行分组以防止内部换行。例如，"==" 运算符应进行盒装以防止换行。

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | 使用指定的元素作为参数初始化 MathBox |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | 当为 true 时，此运算符仿真器用作对齐点；即其他等式中指定的对齐点可以与其对齐。默认值: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | 基准参数 |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | 微分 当为 true 时，盒子作为微分符号（例如 integrand 中的 𝑑𝑥）使用，并获得适当的水平间距以呈现数学微分。默认值: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | 显式换行 指定 Box 对象开始处是否存在换行，从而在盒子对象起始处换行。指定前一行数学文本中的运算符编号，该编号将在当前行数学文本中用作对齐点。可能的取值范围: 1..255 默认: 0（无显式换行） |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | 不换行 此属性指定对象盒子的“不可换行”特性。当为 true 时，盒子内部不会出现换行。这对于由多个二元运算符组成的运算符仿真器尤为重要。当未指定此元素时，盒子内部可以换行。默认值: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | 运算符仿真器。当为 true 时，盒子及其内容表现为单个运算符并继承运算符的属性。这意味着，例如该字符可用作换行点并可与其他运算符对齐。当一个或多个字形组合形成运算符（如 '=='）时通常使用运算符仿真器。默认值: false |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 设置重音标记（元素顶部的字符） |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 以此实例作为参数调用指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 以此实例作为参数调用指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 以此实例作为参数调用指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 以此实例作为参数并使用指定的附加参数调用指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 以此实例作为参数并使用指定的附加参数调用指定函数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 使用此分子和指定的分母创建分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 使用此分子和指定的分母创建分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 用括号将数学元素包围 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 用指定字符（例如括号或其他字符）将数学元素框住 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 使用此实例作为函数名称，对参数调用函数 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 使用此实例作为函数名称，对参数调用函数 |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | 获取子元素 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 使用底部大括号将此元素放入组中 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 使用分组字符（例如底部大括号或其他）将此元素放入组中 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 求取无上下限的积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 求取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 求取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 求取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 求取积分 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 连接数学元素并形成数学块 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 连接数学文本并形成数学块 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 创建 N 元运算符 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | 创建 N 元运算符 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在此元素顶部设置横线 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定给定次数的数学根号，使用指定的参数 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定给定次数的数学根号，使用指定的参数 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | 获取下限 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | 获取下限 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | 创建下标 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | 创建下标 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | 在左侧创建下标和上标 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | 在左侧创建下标和上标 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | 在右侧创建下标和上标 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | 在右侧创建下标和上标 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | 创建上标 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | 创建上标 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | 获取上限 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | 获取上限 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | 将此元素放入边框盒中 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | 将此元素放入边框盒中 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 将此元素放入非可视盒（逻辑分组），用于对方程或其他数学文本的组件进行分组。盒子对象可以（例如）作为带或不带对齐点的运算符仿真器，作为换行点，或分组以防止内部换行 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 放入纵向数组 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在此元素底部设置横线 |

### 示例

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### 另见

* 类 [MathElementBase](../mathelementbase)
* 接口 [IMathBox](../imathbox)
* 命名空间 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->