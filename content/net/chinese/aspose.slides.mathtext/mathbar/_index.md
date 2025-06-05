---  
title: MathBar
second_title: Aspose.Sildes for .NET API Reference  
description: 指定由基参数和上划线或下划线组成的条形函数
type: docs
weight: 8310  
url: /zh/aspose.slides.mathtext/mathbar/
---  

## MathBar class  

指定条形函数，由基参数和上划线或下划线组成  

```csharp  
public sealed class MathBar : MathElementBase, IMathBar  
```  

## 构造函数  

| 名称 | 描述 |  
| --- | --- |  
| [MathBar](mathbar#constructor)(IMathElement) | 用上划线（顶部位置）初始化 MathBar |  
| [MathBar](mathbar#constructor_1)(IMathElement, MathTopBotPositions) | 用指定的位置初始化 MathBar |  

## 属性  

| 名称 | 描述 |  
| --- | --- |  
| [Base](../../aspose.slides.mathtext/mathbar/base) { get; } | 基参数 |  
| [Position](../../aspose.slides.mathtext/mathbar/position) { get; set; } | 条形线的位置。默认: 顶部 |  

## 方法  

| 名称 | 描述 |  
| --- | --- |  
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 设置一个重音标记（位于此元素顶部的字符） |  
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 使用此实例作为参数，采用指定函数 |  
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 使用此实例作为参数，采用指定函数 |  
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 使用此实例作为参数，采用指定函数 |  
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 使用此实例作为参数和指定附加参数，采用指定函数 |  
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 使用此实例作为参数和指定附加参数，采用指定函数 |  
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 创建一个以此为分子的分数，并指定分母 |  
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 创建一个以此为分子的分数，并指定分母 |  
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 创建带有指定类型的分数，分子为此字符和指定分母 |  
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 创建带有指定类型的分数，分子为此字符和指定分母 |  
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 将数学元素用括号括起来 |  
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 用指定的字符（例如括号或其他字符）将数学元素括起来 |  
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 使用此实例作为函数名称，采用一个参数的函数 |  
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 使用此实例作为函数名称，采用一个参数的函数 |  
| [GetChildren](../../aspose.slides.mathtext/mathbar/getchildren)() | 获取子元素 |  
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 使用底部大括号将此元素放置在一个组中 |  
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 使用分组字符（例如底部大括号或其他字符）将此元素放置在一个组中 |  
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 采用不带限制的积分 |  
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 采用积分 |  
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 采用积分 |  
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 采用积分 |  
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 采用积分 |  
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 连接一个数学元素，形成一个数学块 |  
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 连接一个数学文本，形成一个数学块 |  
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 创建一个 N-ary 运算符 |  
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | 创建一个 N-ary 运算符 |  
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在此元素的顶部添加一条线 |  
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定给定度数的数学根，基于指定参数。 |  
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定给定度数的数学根，基于指定参数。 |  
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | 采用下限 |  
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | 采用下限 |  
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | 创建下标 |  
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | 创建下标 |  
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | 在左侧创建下标和上标 |  
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | 在左侧创建下标和上标 |  
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | 在右侧创建下标和上标 |  
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | 在右侧创建下标和上标 |  
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | 创建上标 |  
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | 创建上标 |  
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | 采用上限 |  
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | 采用上限 |  
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | 将此元素放置在边框盒中 |  
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | 将此元素放置在边框盒中 |  
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 将此元素放置在一个非视觉框中（逻辑分组），用于分组方程或其他数学文本的组件。一个被框住的对象可以（例如）作为运算符模拟器出现，带或不带对齐点，作为换行点出现，或者分组以避免内部换行。 |  
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 放入一个垂直数组 |  
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在此元素的底部添加一条线 |  

### 示例  

示例：  

```csharp  
[C#]  
MathBar mathBar = new MathBar(new MathematicalText("x"));  
```  

### 另见  

* class [MathElementBase](../mathelementbase)  
* interface [IMathBar](../imathbar)  
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)  
* assembly [Aspose.Slides](../../)  

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->  