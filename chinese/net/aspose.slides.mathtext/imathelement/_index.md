---
title: IMathElement
second_title: Aspose.Slides for .NET API 参考
description: 任何数学元素的基本接口 分数数学文本函数多元素表达式等
type: docs
weight: 7520
url: /zh/net/aspose.slides.mathtext/imathelement/
---
## IMathElement interface

任何数学元素的基本接口： 分数、数学文本、函数、多元素表达式等

```csharp
public interface IMathElement
```

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | 设置重音符号（此元素顶部的字符） |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | 将使用此实例的指定函数作为参数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | 将使用此实例的指定函数作为参数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | 将使用此实例的指定函数作为参数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | 将使用此实例的指定函数作为参数并指定附加参数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | 将使用此实例的指定函数作为参数并指定附加参数 |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | 用这个分子和指定的分母创建一个分数 |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | 用这个分子和指定的分母创建一个分数 |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | 使用此分子和指定分母创建指定类型的分数 |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | 使用此分子和指定分母创建指定类型的分数 |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | 用括号括起来一个数学元素 |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | 将此元素括在指定字符中，例如括号或其他字符，如 framing |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | 以使用此实例作为函数名的参数的函数 |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | 以使用此实例作为函数名的参数的函数 |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | 获取子元素 |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | 使用底部大括号将此元素放在组中 |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | 使用分组字符（例如下大括号或另一个）将此元素放在一个组中 |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | 无限制地取积分 |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | 取积分 |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | 取积分 |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 取积分 |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | 取积分 |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | 连接一个数学元素并形成一个数学块 |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | 加入数学文本并形成数学块 |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 创建一个 N 元运算符 |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | 创建一个 N 元运算符 |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | 在此元素的顶部设置一个栏 |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | 根据指定参数指定给定度数的数学根。 |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | 根据指定参数指定给定度数的数学根。 |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | 取下限 |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | 取下限 |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | 创建下标 |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | 创建下标 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | 在左边创建下标和上标 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | 在左边创建下标和上标 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | 在右边创建下标和上标 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | 在右边创建下标和上标 |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | 创建上标 |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | 创建上标 |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | 取上限 |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | 取上限 |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | 将此元素放置在边框中 |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | 将此元素放置在边框中 |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | 将此元素放置在非可视框（逻辑分组）中点， 用作换行点，或被分组以不允许换行。 |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | 放入一个垂直数组 |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | 在此元素的底部设置一个栏 |

### 例子

示例：

```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### 也可以看看

* 命名空间 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
