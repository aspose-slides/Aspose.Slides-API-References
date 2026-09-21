---
title: IMathMatrix class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix 類別

指定 Matrix 物件，由一或多列與多欄排列的子元素組成。  
重要的是矩陣本身不具備內建的分隔符號。  
若要將矩陣放入方括號中，應使用分隔符物件 (IMathDelimiter)。  
可使用 Null 引數在矩陣中建立空白。

IMathMatrix 型別公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`row_count`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/row_count/) | 矩陣的列數 |
| [`column_count`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/column_count/) | 矩陣的欄數 |
| [`hide_placeholders`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/hide_placeholders/) | 隱藏空矩陣元素的占位符<br/>            Default: false |
| [`base_justification`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/base_justification/) | 指定相對於周圍文字的垂直對齊方式。<br/>            可能的值有 top、bottom 和 center。<br/>            Default: Center |
| [`min_column_width`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/min_column_width/) | 以 twips 為單位的最小欄寬 (1/20 點)<br/>            欄間距 (亦稱 “Column Gap” 或 “Gap Width”) 會加到 <br/>            MinColumnWidth 以決定總矩陣欄間距<br/>            (不同欄位相同邊緣之間的距離)。<br/>            Default: 0. |
| [`column_gap_rule`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/column_gap_rule/) | 矩陣欄之間的水平間距類型；<br/>            水平間距單位可以是 ems 或 points (以 twips 存儲)。<br/>            Default: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/column_gap/) | 矩陣欄之間的水平間距值；<br/>            若 ColumnGapRule 為 3（「Exactly」），則此單位解釋為 twips（1/20 點）<br/>            若 ColumnGapRule 為 4（「Multiple」），則此單位解釋為 0.5 em 的增量數量。<br/>            其他情況則忽略。<br/>            Default: 0 |
| [`row_gap_rule`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/row_gap_rule/) | 矩陣列之間的垂直間距類型；<br/>            垂直間距單位可以是 lines 或 points (以 twips 存儲)。<br/>            Default: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/row_gap/) | 矩陣列之間的垂直間距值；<br/>            若 RowGapRule 為 3（「Exactly」），則此單位解釋為 twips（1/20 點）<br/>            若 RowGapRule 為 4（「Multiple」），則此單位解釋為半行。<br/>            Default: 0 |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_column_alignment(self, column_index)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/get_column_alignment/#int) | 取得指定欄的水平對齊方式 |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/set_column_alignment/#int-mathhorizontalalignment) | 設定指定欄的水平對齊方式 |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | 設定指定多個欄的水平對齊方式 |
| [`insert_row_before(self, row_index)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/insert_row_before/#int) | 在指定列之前插入新列<br/>            新列的所有元素起始為 None。 |
| [`insert_row_after(self, row_index)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/insert_row_after/#int) | 在指定列之後插入新列<br/>            新列的所有元素起始為 None。 |
| [`delete_row(self, row_index)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/delete_row/#int) | 刪除指定的列 |
| [`insert_column_before(self, column_index)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/insert_column_before/#int) | 在指定欄之前插入新欄<br/>            新欄的所有元素起始為 None。 |
| [`insert_column_after(self, column_index)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/insert_column_after/#int) | 在指定欄之後插入新欄<br/>            新欄的所有元素起始為 None。 |
| [`delete_column(self, column_index)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/delete_column/#int) | 刪除指定的欄 |
| [`get_children(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathmatrix/to_box/#) |  |

### 另見
* 模組 [`aspose.slides.mathtext`](/slides/python-net/zh-hant/aspose.slides.mathtext)
* 函式庫 [`Aspose.Slides`](/slides/python-net)