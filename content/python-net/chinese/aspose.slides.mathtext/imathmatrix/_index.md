---
title: IMathMatrix class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix 类

指定 Matrix 对象，由一个或多个行列中的子元素组成。  
重要的是矩阵没有内置分隔符。  
要将矩阵放在方括号中，应使用分隔符对象 (IMathDelimiter)。  
可以使用空参数在矩阵中创建间隙。

IMathMatrix 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`row_count`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/row_count/) | 矩阵中的行数 |
| [`column_count`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/column_count/) | 矩阵中的列数 |
| [`hide_placeholders`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/hide_placeholders/) | 隐藏空矩阵元素的占位符<br/>默认值: false |
| [`base_justification`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/base_justification/) | 指定相对于周围文本的垂直对齐方式。<br/>可能的值有 top、bottom 和 center。<br/>默认值: Center |
| [`min_column_width`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/min_column_width/) | 最小列宽，以 twips 为单位（1/20 点）<br/>间距（也称为“Column Gap”或“Gap Width”）加到<br/>MinColumnWidth 上以确定整个矩阵列间距<br/>（不同列相同边缘之间的距离）。<br/>默认值: 0. |
| [`column_gap_rule`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/column_gap_rule/) | 矩阵列之间水平间距的类型；<br/>水平间距单位可以是 ems 或 points（以 twips 存储）。<br/>默认值: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/column_gap/) | 矩阵列之间水平间距的数值；<br/>如果 ColumnGapRule 设置为 3（“Exactly”），则单位解释为 twips（1/20 点）<br/>如果 ColumnGapRule 设置为 4（“Multiple”），则单位解释为 0.5 em 增量的数量。<br/>其他情况忽略。<br/>默认值: 0 |
| [`row_gap_rule`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/row_gap_rule/) | 矩阵行之间垂直间距的类型；<br/>垂直间距单位可以是 lines 或 points（以 twips 存储）。<br/>默认值: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/row_gap/) | 矩阵行之间垂直间距的数值；<br/>如果 RowGapRule 设置为 3（“Exactly”），则单位解释为 twips（1/20 点）<br/>如果 RowGapRule 设置为 4（“Multiple”），则单位解释为 half-lines。<br/>默认值: 0 |

## 方法

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_column_alignment(self, column_index)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/get_column_alignment/#int) | 获取指定列的水平对齐方式 |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/set_column_alignment/#int-mathhorizontalalignment) | 设置指定列的水平对齐方式 |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | 设置指定列的水平对齐方式 |
| [`insert_row_before(self, row_index)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/insert_row_before/#int) | 在指定行之前插入新行<br/>新行中的所有元素最初为 None。 |
| [`insert_row_after(self, row_index)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/insert_row_after/#int) | 在指定行之后插入新行<br/>新行中的所有元素最初为 None。 |
| [`delete_row(self, row_index)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/delete_row/#int) | 删除指定行 |
| [`insert_column_before(self, column_index)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/insert_column_before/#int) | 在指定列之前插入新列<br/>新列中的所有元素最初为 None。 |
| [`insert_column_after(self, column_index)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/insert_column_after/#int) | 在指定列之后插入新列<br/>新列中的所有元素最初为 None。 |
| [`delete_column(self, column_index)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/delete_column/#int) | 删除指定列 |
| [`get_children(self)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/zh/aspose.slides.mathtext/imathmatrix/to_box/#) |  |

### 另请参阅
* 模块 [`aspose.slides.mathtext`](/slides/python-net/zh/aspose.slides.mathtext)
* 库 [`Aspose.Slides`](/slides/python-net)