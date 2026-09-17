---
title: MathMatrix class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix 类

指定矩阵对象，由一个或多个行和列中的子元素布局组成。需要注意的是，矩阵没有内置分隔符。要在括号中放置矩阵，应使用分隔符对象 (IMathDelimiter)。可以使用空参数在矩阵中创建间隙。

继承:[`MathMatrix`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix) → [`MathElementBase`](/slides/python-net/zh/aspose.slides.mathtext/mathelementbase)

MathMatrix 类型公开以下成员：

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self, row_count, column_count)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/__init__/#int-int) | 初始化 MathMatrix 类的新实例。 |

## 属性

| 属性 | 描述 |
| :- | :- |
| [`row_count`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/row_count/) | 矩阵中的行数 |
| [`column_count`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/column_count/) | 矩阵中的列数 |
| [`hide_placeholders`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/hide_placeholders/) | 隐藏空矩阵元素的占位符<br/>            默认: false |
| [`base_justification`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/base_justification/) | 指定相对于周围文本的垂直对齐方式。<br/>            可能的取值为 top、bottom 和 center。<br/>            默认: Center |
| [`min_column_width`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/min_column_width/) | 以 twip 为单位的最小列宽 (1/20 点)<br/>            列间距（也称为 “Column Gap” 或 “Gap Width”）会加到 MinColumnWidth 上，以确定矩阵列间的总间距<br/>            （不同列相同边缘之间的距离）。<br/>            默认: 0. |
| [`column_gap_rule`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/column_gap_rule/) | 矩阵列之间的水平间距类型；<br/>            水平间距单位可以是 em 或点（以 twip 存储）。<br/>            默认: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/column_gap/) | 矩阵列之间的水平间距值；<br/>            如果 ColumnGapRule 设置为 3 (“Exactly”，则单位解释为 twip (1/20 点)<br/>            如果 ColumnGapRule 设置为 4 (“Multiple”，则单位解释为 0.5 em 的增量数。<br/>            其他情况忽略。<br/>            默认: 0 |
| [`row_gap_rule`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/row_gap_rule/) | 矩阵行之间的垂直间距类型；<br/>            垂直间距单位可以是行或点（以 twip 存储）。<br/>            默认: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/row_gap/) | 矩阵行之间的垂直间距值；<br/>            如果 RowGapRule 设置为 3 (“Exactly”，则单位解释为 twip (1/20 点)<br/>            如果 RowGapRule 设置为 4 (“Multiple”，则单位解释为半行。<br/>            默认: 0 |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/join/#imathelement) | 将数学元素连接并形成数学块 |
| [`join(self, math_text)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/join/#str) | 将数学文本连接并形成数学块 |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/divide/#imathelement) | 使用此分子和指定的分母创建分数 |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/divide/#str) | 使用此分子和指定的分母创建分数 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/divide/#imathelement-mathfractiontypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/divide/#str-mathfractiontypes) | 使用此分子和指定的分母创建指定类型的分数 |
| [`enclose(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/enclose/#) | 用括号将数学元素括起来 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/enclose/#char-char) | 用指定字符（如括号或其他字符）将数学元素框住 |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/function/#imathelement) | 使用此实例作为函数名，对参数执行函数 |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/function/#str) | 使用此实例作为函数名，对参数执行函数 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#imathelement) | 使用此实例作为参数，调用指定函数 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#str) | 使用此实例作为参数，调用指定函数 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsofoneargument) | 使用此实例作为参数，调用指定函数 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 使用此实例作为参数，调用指定函数并附加额外参数 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 使用此实例作为参数，调用指定函数并附加额外参数 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/set_subscript/#imathelement) | 创建下标 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/set_subscript/#str) | 创建下标 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/set_superscript/#imathelement) | 创建上标 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/set_superscript/#str) | 创建上标 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) | 在右侧创建下标和上标 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#str-str) | 在右侧创建下标和上标 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) | 在左侧创建下标和上标 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#str-str) | 在左侧创建下标和上标 |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/radical/#imathelement) | 指定给定次数的数学根，基于指定的参数。 |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/radical/#str) | 指定给定次数的数学根，基于指定的参数。 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/set_upper_limit/#imathelement) | 取上限 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/set_upper_limit/#str) | 取上限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/set_lower_limit/#imathelement) | 取下限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/set_lower_limit/#str) | 取下限 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) | 创建 N 元运算符 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-str-str) | 创建 N 元运算符 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 取积分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement) | 取积分 |
| [`integral(self, integral_type)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes) | 取无上下限的积分 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) | 取积分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str) | 取积分 |
| [`group(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/group/#) | 使用底部花括号将此元素放入组中 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) | 使用分组字符（如底部花括号或其他字符）将此元素放入组中 |
| [`to_border_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/to_border_box/#) | 将此元素放入边框盒中 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 将此元素放入边框盒中 |
| [`to_math_array(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/to_math_array/#) | 放入垂直数组 |
| [`accent(self, accent_character)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/accent/#char) | 设置重音符号（位于此元素顶部的字符） |
| [`overbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/overbar/#) | 在此元素顶部设置横线 |
| [`underbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/underbar/#) | 在此元素底部设置横线 |
| [`to_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/to_box/#) | 将此元素放入非可视盒（逻辑分组）<br/>            用于对方程式或其他数学文本实例的组件进行分组。<br/>            盒装对象可以（例如）充当带或不带对齐点的运算符仿真器，<br/>            充当换行点，或分组以防止其中出现换行。 |
| [`get_column_alignment(self, column_index)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/get_column_alignment/#int) | 获取指定列的水平对齐方式 |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/set_column_alignment/#int-mathhorizontalalignment) | 设置指定列的水平对齐方式 |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | 设置指定列的水平对齐方式 |
| [`insert_row_before(self, row_index)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/insert_row_before/#int) | 在指定行之前插入新行<br/>            新行中的所有元素初始为 None。 |
| [`insert_row_after(self, row_index)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/insert_row_after/#int) | 在指定行之后插入新行<br/>            新行中的所有元素初始为 None。 |
| [`delete_row(self, row_index)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/delete_row/#int) | 删除指定行 |
| [`insert_column_before(self, column_index)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/insert_column_before/#int) | 在指定列之前插入新列<br/>            新列中的所有元素初始为 None。 |
| [`insert_column_after(self, column_index)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/insert_column_after/#int) | 在指定列之后插入新列<br/>            新列中的所有元素初始为 None。 |
| [`delete_column(self, column_index)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/delete_column/#int) | 删除指定列 |
| [`get_children(self)`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix/get_children/#) | 获取子元素 |

### 另见
* 类 [`MathElementBase`](/slides/python-net/zh/aspose.slides.mathtext/mathelementbase)
* 类 [`MathMatrix`](/slides/python-net/zh/aspose.slides.mathtext/mathmatrix)
* 模块 [`aspose.slides.mathtext`](/slides/python-net/zh/aspose.slides.mathtext)
* 库 [`Aspose.Slides`](/slides/python-net)