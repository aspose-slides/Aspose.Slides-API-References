---
title: MathMatrix
second_title: Aspose.Sildes for .NET API Reference
description: 指定由一个或多个行和列排列的子元素组成的 Matrix 对象。重要的是要注意，矩阵没有内置的分隔符。要将矩阵放入括号中，您应该使用分隔符对象 IMathDelimiter。可以使用空参数在矩阵中创建间隙。
type: docs
weight: 8590
url: /zh/aspose.slides.mathtext/mathmatrix/
---

## MathMatrix class

指定由一个或多个行和列排列的子元素组成的 Matrix 对象。重要的是要注意，矩阵没有内置的分隔符。要将矩阵放入括号中，您应该使用分隔符对象 (IMathDelimiter)。可以使用空参数在矩阵中创建间隙。

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## Constructors

| 名称 | 描述 |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | 初始化 MathMatrix 类的新实例。 |

## Properties

| 名称 | 描述 |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | 指定与周围文本的垂直对齐方式。可能的值有 top、bottom 和 center。默认值：Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | 矩阵中的列数 |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | 矩阵列之间的水平间距的值；如果 ColumnGapRule 设置为 3 ("Exactly")，则单位解释为 twips (1/20 的点)；如果 ColumnGapRule 设置为 4 ("Multiple")，则单位解释为 0.5 em 的增量。在其他情况下将被忽略。默认值：0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | 矩阵列之间的水平间距的类型；水平间距单位可以是 ems 或 points (以 twips 存储)。默认值：SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | 隐藏空矩阵元素的占位符。默认值：false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | 矩阵的元素 |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | 以 twips (1/20 的点) 表示的最小列宽。间隙间距（也称为 “Column Gap” 或 “Gap Width”）将加到 MinColumnWidth 上以确定总矩阵列间距（不同列相同边缘之间的距离）。默认值：0。 |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | 矩阵中的行数 |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | 矩阵行之间的垂直间距的值；如果 RowGapRule 设置为 3 ("Exactly")，则单位解释为 twips (1/20 的点)；如果 RowGapRule 设置为 4 ("Multiple")，则单位解释为半行。默认值：0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | 矩阵行之间的垂直间距的类型；垂直间距单位可以是行或点（以 twips 存储）。默认值：SingleSpacingGap (0) |

## Methods

| 名称 | 描述 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 设置一个重音符号（位于该元素顶部的字符） |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 使用此实例作为参数接受指定的函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 使用此实例作为参数接受指定的函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 使用此实例作为参数接受指定的函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 使用此实例作为参数和指定的额外参数接受指定的函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 使用此实例作为参数和指定的额外参数接受指定的函数 |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | 删除指定的列 |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | 删除指定的行 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 创建一个带有该分子和指定分母的分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 创建一个带有该分子和指定分母的分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 创建一个具有指定类型的分数，分子为该值，分母为指定值 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 创建一个具有指定类型的分数，分子为该值，分母为指定值 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 将数学元素用括号括起来 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 使用指定字符（例如括号或其他字母）将数学元素括起来 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 使用该实例作为函数名称接受参数的函数 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 使用该实例作为函数名称接受参数的函数 |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | 获取子元素 |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | 获取指定列的水平对齐方式 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 使用底部花括号将此元素放入组中 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 使用如底部花括号或其他的分组字符将此元素放入组中 |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | 在指定列后插入新列。新列中的所有元素最初都为null。 |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | 在指定列前插入新列。新列中的所有元素最初都为null。 |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | 在指定行后插入新行。新行中的所有元素最初都为null。 |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | 在指定行前插入新行。新行中的所有元素最初都为null。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 接受没有限制的积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 接受积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 接受积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 接受积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 接受积分 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 连接数学元素并形成数学块 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 连接数学文本并形成数学块 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 创建一个 N-ary 操作符 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | 创建一个 N-ary 操作符 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在该元素的顶部设置一条横线 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定从指定参数获得给定度数的数学根。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定从指定参数获得给定度数的数学根。 |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | 设置指定列的水平对齐方式 |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | 设置指定列的水平对齐方式 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | 接受下限 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | 接受下限 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | 创建下标 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | 创建下标 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | 在左侧创建下标和上标 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | 在左侧创建下标和上标 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | 在右侧创建下标和上标 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | 在右侧创建下标和上标 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | 创建上标 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | 创建上标 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | 接受上限 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | 接受上限 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | 将此元素放入边框框中 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | 将此元素放入边框框中 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 将此元素放入一个不可见的框（逻辑分组），用于将方程的组件或其他数学文本实例分组。一个框定的对象可以（例如）作为一个操作员模拟器，不论是否有对齐点，充当换行点，或者被分组以防止换行。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 放入一个垂直数组 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在该元素的底部设置一条横线 |

### Examples

示例:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### See Also

* class [MathElementBase](../mathelementbase)
* interface [IMathMatrix](../imathmatrix)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->