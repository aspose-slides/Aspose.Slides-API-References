---
title: BaseScript
second_title: Aspose.Sildes for .NET API Reference
description: 数学脚本
type: docs
weight: 7820
url: /zh/aspose.slides.mathtext/basescript/
---

## BaseScript 类

数学脚本

```csharp
public abstract class BaseScript : MathElementBase
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Base](../../aspose.slides.mathtext/basescript/base) { get; } | 基础参数 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 设置重音符(放置在该元素顶部的字符) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 将指定的函数作为参数，使用此实例 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 将指定的函数作为参数，使用此实例 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 将指定的函数作为参数，使用此实例 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 将指定的函数作为参数，使用此实例和指定的附加参数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 将指定的函数作为参数，使用此实例和指定的附加参数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 创建一个具有该分子和指定分母的分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 创建一个具有该分子和指定分母的分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 创建一个具有该分子和指定分母的指定类型的分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 创建一个具有该分子和指定分母的指定类型的分数 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 将数学元素放在括号中 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 将数学元素用指定字符括起来，如括号或其他字符作为框架 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 使用此实例作为函数名，接受一个函数的参数 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 使用此实例作为函数名，接受一个函数的参数 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 使用底部大括号将此元素置于组中 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 使用分组字符（如底部大括号或其他）将此元素放在组中 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 无限制的积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 进行积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 进行积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 进行积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 进行积分 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 连接数学元素并形成数学块 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 连接数学文本并形成数学块 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 创建一个N元运算符 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | 创建一个N元运算符 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在该元素顶部设置横线 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 从指定参数中指定给定度数的数学根 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 从指定参数中指定给定度数的数学根 |
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
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | 将此元素放置在边框盒中 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | 将此元素放置在边框盒中 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 将此元素放在一个非可视框（逻辑分组）中，这用于对方程或其他数学文本实例的组件进行分组。一个被框的对象可以（例如）作为带或不带对齐点的运算符仿真器，作为换行点，或者被分组以防止行间断。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 放入垂直数组 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在该元素底部设置横线 |

### 另见

* 类 [MathElementBase](../mathelementbase)
* 命名空间 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->