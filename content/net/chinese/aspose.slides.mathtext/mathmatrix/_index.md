---
title: MathMatrix
second_title: Aspose.Sildes for .NET API Reference
description: 指定矩阵对象，由一个或多个行和列中的子元素构成。重要的是要注意，矩阵没有内置的分隔符。要将矩阵放在括号中，您应该使用分隔符对象 IMathDelimiter。可以使用空参数在矩阵中创建间隙。
type: docs
weight: 8590
url: /zh/aspose.slides.mathtext/mathmatrix/
---

## MathMatrix 类

指定矩阵对象，由一个或多个行和列中的子元素构成。重要的是要注意，矩阵没有内置的分隔符。要将矩阵放在括号中，您应该使用分隔符对象 (IMathDelimiter)。可以使用空参数在矩阵中创建间隙。

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | 初始化 MathMatrix 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | 指定相对于周围文本的垂直对齐。可能的值有顶部、底部和居中。默认值：居中 |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | 矩阵中的列数 |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | 矩阵列之间的水平间距值；如果 ColumnGapRule 设置为 3 ("Exactly")，则单位解释为 twips (1/20 分)；如果 ColumnGapRule 设置为 4 ("Multiple")，则单位解释为 0.5 em 的增量。在其他情况下被忽略。默认值：0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | 矩阵列之间的水平间距类型；水平间距单位可以是 em 或点（以 twips 存储）。默认值：SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | 隐藏空矩阵元素的占位符 默认值：false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | 矩阵元素 |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | 最小列宽，以 twips 为单位 (1/20 分)。间隔宽度（也称为“列间距”或“间隙宽度”）添加到 MinColumnWidth 中以确定总的矩阵列间距（不同列相同边缘之间的距离）。默认值：0。 |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | 矩阵中的行数 |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | 矩阵行之间的垂直间距值；如果 RowGapRule 设置为 3 ("Exactly")，则单位解释为 twips (1/20 分)；如果 RowGapRule 设置为 4 ("Multiple")，则单位解释为半行。默认值：0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | 矩阵行之间的垂直间距类型；垂直间距单位可以是行或点（以 twips 存储）。默认值：SingleSpacingGap (0) |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 设置一个重音符（位于该元素顶部的字符） |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 使用此实例作为参数，采用指定的函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 使用此实例作为参数，采用指定的函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 使用此实例作为参数，采用指定的函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 使用此实例作为参数，及指定的额外参数，采用指定的函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 使用此实例作为参数，及指定的额外参数，采用指定的函数 |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | 删除指定的列 |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | 删除指定的行 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 创建一个分数，以该分子和指定的分母 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 创建一个分数，以该分子和指定的分母 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 创建指定类型的分数，以该分子和指定的分母 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 创建指定类型的分数，以该分子和指定的分母 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 将数学元素放在括号内 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 将数学元素放在指定字符中，例如括号或其他字符作为框架 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 使用此实例作为函数名，采用一个参数的函数 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 使用此实例作为函数名，采用一个参数的函数 |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | 获取子元素 |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | 获取指定列的水平对齐 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 将此元素放在一个组中，使用底部花括号 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 使用分组字符将此元素放在一个组中，例如底部花括号 |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | 在指定列后插入新列，最初新列中的所有元素均为 null。 |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | 在指定列前插入新列，最初新列中的所有元素均为 null。 |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | 在指定行后插入新行，最初新行中的所有元素均为 null。 |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | 在指定行前插入新行，最初新行中的所有元素均为 null。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 进行不带限制的积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 进行积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 进行积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 进行积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 进行积分 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 连接数学元素并形成数学块 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 连接数学文本并形成数学块 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 创建 N-ary 运算符 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | 创建 N-ary 运算符 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在该元素顶部设置一个条 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定从指定参数的给定程度的数学根。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定从指定参数的给定程度的数学根。 |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | 设置指定列的水平对齐 |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | 设置指定列的水平对齐 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | 获取下限 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | 获取下限 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | 创建下标 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | 创建下标 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | 在左侧创建下标和上标 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | 在左侧创建下标和上标 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | 在右侧创建下标和上标 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | 在右侧创建下标和上标 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | 创建上标 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | 创建上标 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | 获取上限 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | 获取上限 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | 将此元素放置在边框框中 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | 将此元素放置在边框框中 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 将此元素放在一个非可视框中（逻辑分组），用于分组方程的组件或其他数学文本的实例。一个被框住的对象可以（例如）作为运算符仿真器，有或没有对齐点，充当换行点，或者被分组以不允许内部换行。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 放入一个垂直数组 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在该元素底部设置一个条 |

### 示例

示例：

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### 另请参阅

* 类 [MathElementBase](../mathelementbase)
* 接口 [IMathMatrix](../imathmatrix)
* 命名空间 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->