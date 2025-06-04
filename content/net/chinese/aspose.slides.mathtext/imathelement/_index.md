---
title: IMathElement
second_title: Aspose.Sildes for .NET API Reference
description: 任何数学元素的基础接口：分数、数学文本、函数、具有多个元素的表达式等
type: docs
weight: 7980
url: /zh/aspose.slides.mathtext/imathelement/
---

## IMathElement 接口

任何数学元素的基础接口：分数、数学文本、函数、具有多个元素的表达式等

```csharp
public interface IMathElement
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | 设置一个重音符号（该元素顶部的字符） |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | 使用此实例作为参数接受指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | 使用此实例作为参数接受指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | 使用此实例作为参数接受指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | 使用此实例作为参数接受指定函数和指定的附加参数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | 使用此实例作为参数接受指定函数和指定的附加参数 |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | 创建一个具有这个分子和指定分母的分数 |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | 创建一个具有这个分子和指定分母的分数 |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | 创建具有指定类型的分数，使用这个分子和指定分母 |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | 创建具有指定类型的分数，使用这个分子和指定分母 |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | 用括号封闭一个数学元素 |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | 用指定字符（如括号或其他字符）封闭此元素 |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | 使用此实例作为函数名称接受一个参数的函数 |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | 使用此实例作为函数名称接受一个参数的函数 |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | 获取子元素 |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | 使用底部大括号将此元素放入一个组中 |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | 使用分组字符（如底部大括号或其他）将此元素放入一个组中 |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | 接受无限制的积分 |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | 接受积分 |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | 接受积分 |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 接受积分 |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | 接受积分 |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | 连接一个数学元素并形成一个数学块 |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | 连接一个数学文本并形成一个数学块 |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 创建一个 N-元运算符 |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | 创建一个 N-元运算符 |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | 在此元素顶部设置一个横线 |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | 指定来自指定参数的给定度的数学根。 |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | 指定来自指定参数的给定度的数学根。 |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | 接受下限 |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | 接受下限 |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | 创建下标 |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | 创建下标 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | 在左侧创建下标和上标 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | 在左侧创建下标和上标 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | 在右侧创建下标和上标 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | 在右侧创建下标和上标 |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | 创建上标 |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | 创建上标 |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | 接受上限 |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | 接受上限 |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | 将此元素放入边框框中 |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | 将此元素放入边框框中 |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | 将此元素放入一个非视觉框（逻辑分组），用于对方程的组件或其他数学文本实例进行分组。一个框选对象可以（例如）作为一个运算符仿真器，带或不带对齐点，作为换行点，或被分组以不允许在其中换行。 |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | 放入垂直数组 |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | 在此元素底部设置一个横线 |

### 示例

示例：

```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### 另请参见

* 命名空间 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->