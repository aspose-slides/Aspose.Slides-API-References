---
title: MathMatrix
second_title: Aspose.Slides for .NET API 参考
description: 指定 Matrix 对象由排列在一个或多个行和列中的子元素组成 重要的是要注意矩阵没有内置分隔符 要将矩阵放在括号中您应该使用分隔符对象IMathDelimiter Null 参数可用于在矩阵中创建间隙
type: docs
weight: 8130
url: /zh/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix class

指定 Matrix 对象，由排列在一个或多个行和列中的子元素组成。 重要的是要注意矩阵没有内置分隔符。 要将矩阵放在括号中，您应该使用分隔符对象（IMathDelimiter）。 Null 参数可用于在矩阵中创建间隙。

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | 初始化 MathMatrix 类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | 指定相对于周围文本的垂直对齐方式。 可能的值是顶部、底部和中心。 默认值:中心 |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | 矩阵中的列数 |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | 矩阵列之间的水平间距值； 如果 ColumnGapRule 设置为 3（“精确”），则单位被解释为缇（点的 1/20） 如果 ColumnGapRule 设置为 4（ "Multiple")，则单位被解释为 0.5 em 增量的数量。 在其他情况下忽略。 默认值:0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | 矩阵列之间的水平间距类型； 水平间距单位可以是 em 或点（存储为缇）。 默认值:SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | 隐藏空矩阵元素的占位符 默认值:false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | 矩阵元素 |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | 最小列宽，以缇为单位（点的 1/20） 间隙间距（也称为“列间隙”或“间隙” Width”）添加到 MinColumnWidth 以确定总矩阵列间距 （不同列的相同边缘之间的距离）。 默认值:0。 |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | 矩阵中的行数 |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | 矩阵行之间的垂直间距值； 如果 RowGapRule 设置为 3（“精确”），则单位被解释为缇（点的 1/20） 如果 RowGapRule 设置为 4（ "Multiple")，则单位被解释为半行。 默认值:0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | 矩阵行之间的垂直间距类型； 垂直间距单位可以是线或点（存储为缇）。 默认值:SingleSpacingGap (0) |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | 设置重音符号（此元素顶部的字符） |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | 以使用此实例作为参数的指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | 以使用此实例作为参数的指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | 以使用此实例作为参数的指定函数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | 将使用此实例的指定函数作为参数并指定附加参数 |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | 将使用此实例的指定函数作为参数并指定附加参数 |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | 删除指定列 |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | 删除指定行 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | 使用此分子和指定分母创建分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | 使用此分子和指定分母创建分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | 使用此分子和指定分母创建指定类型的分数 |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | 使用此分子和指定分母创建指定类型的分数 |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | 将数学元素括在括号中 |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | 将数学元素括在指定字符中，例如括号或其他字符，作为框架 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | 使用该实例作为函数名的参数的函数 |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | 使用该实例作为函数名的参数的函数 |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | 获取子元素 |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | 获取指定列的水平对齐方式 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | 使用底部大括号将此元素放在组中 |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | 使用分组字符（例如下大括号或另一个 |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | 在指定的列之后插入一个新列 最初新列中的所有元素都是空的。 |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | 在指定的列之前插入一个新列 最初新列中的所有元素都是空的。 |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | 在指定行之后插入一个新行 最初新行中的所有元素都为空。 |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | 在指定行之前插入新行 最初新行中的所有元素都为空。 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | 无限制地取积分 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | 取整数 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | 取整数 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | 取整数 |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | 取整数 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | 连接一个数学元素并形成一个数学块 |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | 连接数学文本并形成数学块 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | 创建 N 元运算符 |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | 创建 N 元运算符 |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | 在此元素顶部设置一个栏 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | 根据指定参数指定给定度数的数学根。 |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | 根据指定参数指定给定度数的数学根。 |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | 设置指定列的水平对齐方式 |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | 设置指定列的水平对齐方式 |
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
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | 将此元素放置在边框中 |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | 将此元素放在边框中 |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | 将此元素置于非可视框（逻辑分组） 用于对方程的组件或其他数学文本实例进行分组. 装箱对象可以（例如）用作带有或不带有对齐点的操作员模拟器， 用作换行点，或者被分组以不允许换行内破。 |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | 放入垂直数组 |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | 在此元素的底部设置一个栏 |

### 例子

示例:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### 也可以看看

* class [MathElementBase](../mathelementbase)
* interface [IMathMatrix](../imathmatrix)
* 命名空间 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
