---
title: MathMatrix
second_title: Aspose.Sildes for .NET API 参考
description: 指定矩阵对象，由一行或多行多列的子元素布局而成。需要注意的是矩阵没有内置分隔符。若要将矩阵放在括号中，应使用分隔符对象 IMathDelimiter。可以使用 null 参数在矩阵中创建空隙。
type: docs
weight: 8850
url: /zh/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix 类

指定 Matrix 对象，由一行或多行多列的子元素布局而成。需要注意的是矩阵没有内置分隔符。若要将矩阵放在括号中，应使用分隔符对象 (IMathDelimiter)。可以使用 null 参数在矩阵中创建空隙。

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## 构造函数

| 名称 | 说明 |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | 初始化 MathMatrix 类的新实例。 |

## 属性

| 名称 | 说明 |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | 指定相对于周围文本的垂直对齐方式。可能的取值有 top、bottom 和 center。默认值：Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | 矩阵中的列数 |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | 矩阵列之间的水平间距值；如果 ColumnGapRule 设置为 3 (“Exactly”), 则单位解释为 twips (1/20 点)；如果 ColumnGapRule 设置为 4 (“Multiple”), 则单位解释为 0.5 em 增量的数量。其它情况忽略。默认值：0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | 矩阵列之间的水平间距类型；水平间距单位可以是 ems 或 points（以 twips 存储）。默认值：SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | 隐藏空矩阵元素的占位符。默认值：false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | 矩阵元素 |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | 最小列宽（单位：twips，1/20 点）。列间距（亦称 “Column Gap” 或 “Gap Width”）会加到 MinColumnWidth 上，以确定总的矩阵列间距（不同列相同边缘之间的距离）。默认值：0。 |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | 矩阵中的行数 |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | 矩阵行之间的垂直间距值；如果 RowGapRule 设置为 3 (“Exactly”), 则单位解释为 twips (1/20 点)；如果 RowGapRule 设置为 4 (“Multiple”), 则单位解释为半行。默认值：0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | 矩阵行之间的垂直间距类型；垂直间距单位可以是 lines 或 points（以 twips 存储）。默认值：SingleSpacingGap (0) |

## 方法

| 名称 | 说明 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 设置此元素顶部的重音符号（字符）。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 使用此实例作为参数调用指定的函数。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 使用此实例作为参数调用指定的函数。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 使用此实例作为参数调用指定的函数。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 使用此实例作为参数并添加指定的附加参数调用指定的函数。 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 使用此实例作为参数并添加指定的附加参数调用指定的函数。 |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | 删除指定的列。 |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | 删除指定的行。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 使用此分子和指定的分母创建分数。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 使用此分子和指定的分母创建分数。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 使用此分子和指定的分母创建指定类型的分数。 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 使用此分子和指定的分母创建指定类型的分数。 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 用括号将数学元素括起来。 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 用指定字符（如括号或其他字符）将数学元素框住。 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 使用此实例作为函数名称，对参数调用函数。 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 使用此实例作为函数名称，对参数调用函数。 |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | 获取子元素。 |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | 获取指定列的水平对齐方式。 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 使用底部大括号将此元素放入组中。 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 使用分组字符（如底部大括号或其他字符）将此元素放入组中。 |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | 在指定列之后插入新列，初始时新列中的所有元素为 null。 |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | 在指定列之前插入新列，初始时新列中的所有元素为 null。 |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | 在指定行之后插入新行，初始时新行中的所有元素为 null。 |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | 在指定行之前插入新行，初始时新行中的所有元素为 null。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 创建无上下限的积分。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 创建积分。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 创建积分。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 创建积分。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 创建积分。 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 将数学元素连接并形成数学块。 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 将数学文本连接并形成数学块。 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 创建 N 元运算符。 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | 创建 N 元运算符。 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在此元素顶部添加横线。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 指定给定次数的数学根号，使用指定的参数。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 指定给定次数的数学根号，使用指定的参数。 |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | 设置指定列的水平对齐方式。 |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | 设置指定列的水平对齐方式。 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | 获取下限。 |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | 获取下限。 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | 创建下标。 |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | 创建下标。 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | 在左侧创建下标和上标。 |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | 在左侧创建下标和上标。 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | 在右侧创建下标和上标。 |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | 在右侧创建下标和上标。 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | 创建上标。 |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | 创建上标。 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | 获取上限。 |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | 获取上限。 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | 将此元素放入边框盒中。 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | 将此元素放入边框盒中。 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 将此元素放入非可视盒（逻辑分组），用于对方程或其他数学文本的组件进行分组。盒对象可以（例如）充当带或不带对齐点的运算符仿真器、作为换行点，或分组以防止在其中换行。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 放入垂直数组中。 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在此元素底部添加横线。 |

### 示例

示例：

```csharp
[C#]
IMMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### 另请参见

* class [MathElementBase](../mathelementbase)
* interface [IMathMatrix](../imathmatrix)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->