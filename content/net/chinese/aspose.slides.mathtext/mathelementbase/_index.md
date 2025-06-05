---
title: MathElementBase
second_title: Aspose.Sildes for .NET API Reference
description: IMathElement 的基类，包含所有继承类共有的一些方法的实现，仅供内部使用。继承类必须是 IMathElement。
type: docs
weight: 8420
url: /zh/aspose.slides.mathtext/mathelementbase/
---

## MathElementBase class

IMathElement 的基类，包含所有继承类共有的一些方法的实现，仅供内部使用。继承类必须是 IMathElement。

```csharp
public abstract class MathElementBase : IMathElement
```

## Methods

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 设置一个重音符（位于此元素顶部的字符） |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction)(IMathElement) | 使用此实例作为参数来获取指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | 使用此实例作为参数来获取指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_4)(string) | 使用此实例作为参数来获取指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | 使用此实例作为参数和指定的附加参数来获取指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | 使用此实例作为参数和指定的附加参数来获取指定函数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide)(IMathElement) | 使用此分子和指定的分母创建一个分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_2)(string) | 使用此分子和指定的分母创建一个分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_1)(IMathElement, MathFractionTypes) | 使用指定类型的分母和此分子创建一个分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_3)(string, MathFractionTypes) | 使用指定类型的分母和此分子创建一个分数 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose#enclose)() | 将数学元素括在括号内 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose#enclose_1)(char, char) | 将数学元素用指定字符括起来，例如括号或其他字符作为框架 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function#function)(IMathElement) | 使用此实例作为函数名称获取参数的函数 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function#function_1)(string) | 使用此实例作为函数名称获取参数的函数 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group#group)() | 使用底部花括号将此元素放入一个组中 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | 使用分组字符（如底部花括号或其他）将此元素放入一个组中 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral)(MathIntegralTypes) | 获取不带限的积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | 获取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_3)(MathIntegralTypes, string, string) | 获取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 获取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | 获取积分 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join#join)(IMathElement) | 连接数学元素，形成数学块 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join#join_1)(string) | 连接数学文本，形成数学块 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 创建 N-ary 运算符 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary#nary_1)(MathNaryOperatorTypes, string, string) | 创建 N-ary 运算符 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在此元素的顶部设置一条横线 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical#radical)(IMathElement) | 从指定的参数指定给定程度的数学根。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical#radical_1)(string) | 从指定的参数指定给定程度的数学根。 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit#setlowerlimit)(IMathElement) | 获取下限 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit#setlowerlimit_1)(string) | 获取下限 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript#setsubscript)(IMathElement) | 创建下标 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript#setsubscript_1)(string) | 创建下标 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | 在左侧创建下标和上标 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | 在左侧创建下标和上标 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | 在右侧创建下标和上标 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | 在右侧创建下标和上标 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript#setsuperscript)(IMathElement) | 创建上标 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript#setsuperscript_1)(string) | 创建上标 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit#setupperlimit)(IMathElement) | 获取上限 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit#setupperlimit_1)(string) | 获取上限 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox#toborderbox)() | 将此元素放入边框盒中 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | 将此元素放入边框盒中 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 将此元素放入一个非视觉盒中（逻辑分组），用于分组方程式或其他数学文本实例的组件。一个被框住的对象可以（例如）充当操作符模拟器，有或没有对齐点，充当换行点，或分组以禁止其中的换行。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 放入一个垂直数组 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在此元素的底部设置一条横线 |

### See Also

* interface [IMathElement](../imathelement)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->