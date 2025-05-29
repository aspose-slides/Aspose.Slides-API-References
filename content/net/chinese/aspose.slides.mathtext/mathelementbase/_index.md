---
title: MathElementBase
second_title: Aspose.Slides for .NET API Reference
description: IMathElement 的基类，包含一些所有继承类共有方法的实现，仅供内部使用。继承类必须是 IMathElement。
type: docs
weight: 8420
url: /zh/aspose.slides.mathtext/mathelementbase/
---

## MathElementBase 类

IMathElement 的基类，包含一些所有继承类共有方法的实现，仅供内部使用。继承类必须是 IMathElement。

```csharp
public abstract class MathElementBase : IMathElement
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 设置一个重音符号（此元素顶部的一个字符） |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction)(IMathElement) | 以此实例作为参数获取指定的函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | 以此实例作为参数获取指定的函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_4)(string) | 以此实例作为参数获取指定的函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | 以此实例作为参数和指定的额外参数获取指定的函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | 以此实例作为参数和指定的额外参数获取指定的函数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide)(IMathElement) | 创建一个以此分子和指定分母的分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_2)(string) | 创建一个以此分子和指定分母的分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_1)(IMathElement, MathFractionTypes) | 创建一个以此分子和指定分母的指定类型的分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_3)(string, MathFractionTypes) | 创建一个以此分子和指定分母的指定类型的分数 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose#enclose)() | 将一个数学元素用括号括起来 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose#enclose_1)(char, char) | 将一个数学元素用指定字符如括号或其他字符括起来 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function#function)(IMathElement) | 以此实例作为函数名称获取一个参数的函数 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function#function_1)(string) | 以此实例作为函数名称获取一个参数的函数 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group#group)() | 使用底部大括号将此元素放置在一个组中 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | 使用分组字符如底部大括号或其他字符将此元素放置在一个组中 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral)(MathIntegralTypes) | 取无界限的积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | 取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_3)(MathIntegralTypes, string, string) | 取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | 取积分 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join#join)(IMathElement) | 连接数学元素并形成数学块 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join#join_1)(string) | 连接数学文本并形成数学块 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 创建一个 N 叉运算符 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary#nary_1)(MathNaryOperatorTypes, string, string) | 创建一个 N 叉运算符 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在此元素顶部设置一条横线 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical#radical)(IMathElement) | 从指定参数中指定给定程度的数学根。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical#radical_1)(string) | 从指定参数中指定给定程度的数学根。 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit#setlowerlimit)(IMathElement) | 取下限 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit#setlowerlimit_1)(string) | 取下限 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript#setsubscript)(IMathElement) | 创建下标 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript#setsubscript_1)(string) | 创建下标 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | 在左侧创建下标和上标 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | 在左侧创建下标和上标 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | 在右侧创建下标和上标 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | 在右侧创建下标和上标 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript#setsuperscript)(IMathElement) | 创建上标 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript#setsuperscript_1)(string) | 创建上标 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit#setupperlimit)(IMathElement) | 取上限 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit#setupperlimit_1)(string) | 取上限 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox#toborderbox)() | 将此元素放置在边框框内 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | 将此元素放置在边框框内 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 将此元素放置在一个非视觉的框中（逻辑分组），用于分组方程的组件或其他数学文本实例。一个框的对象可以（例如）作为带有或不带有对齐点的运算符仿真器，作为换行点，或者被分组以不允许在其中换行。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 放在一个垂直数组中 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在此元素底部设置一条横线 |

### 另请参阅

* 接口 [IMathElement](../imathelement)
* 命名空间 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
