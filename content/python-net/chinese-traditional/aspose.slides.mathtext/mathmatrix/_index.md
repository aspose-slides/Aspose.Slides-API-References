---
title: MathMatrix class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix 類別

指定 Matrix 物件，由排列在一列或多列多欄的子元素組成。  
請注意，矩陣沒有內建的分隔符號。  
若要將矩陣放入括號中，應使用分隔符物件 (IMathDelimiter)。  
可使用 null 參數在矩陣中建立空白間隙。

**Inheritance:**[`MathMatrix`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix) → [`MathElementBase`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase)

The MathMatrix type exposes the following members:

## 建構子

| Constructor | Description |
| :- | :- |
| [`__init__(self, row_count, column_count)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/__init__/#int-int) | 初始化 MathMatrix 類別的新執行個體。 |

## 屬性

| Property | Description |
| :- | :- |
| [`row_count`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/row_count/) | 矩陣的列數 |
| [`column_count`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/column_count/) | 矩陣的欄數 |
| [`hide_placeholders`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/hide_placeholders/) | 隱藏空矩陣元素的佔位符<br/>            預設：false |
| [`base_justification`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/base_justification/) | 指定相對於周圍文字的垂直對齊方式。<br/>            可能的值有 top、bottom 和 center。<br/>            預設：Center |
| [`min_column_width`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/min_column_width/) | 最小欄寬，單位為 twips（1/20 點）<br/>            「間隙間距」（亦稱「欄間距」或「間距寬度」）會加到 MinColumnWidth，以決定整體矩陣欄間距<br/>            （不同欄位相同邊緣之間的距離）。<br/>            預設：0. |
| [`column_gap_rule`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/column_gap_rule/) | 矩陣欄之間的水平間距類型；<br/>            水平間距單位可以是 ems 或 points（以 twips 儲存）。<br/>            預設：SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/column_gap/) | 矩陣欄之間的水平間距值；<br/>            若 ColumnGapRule 設為 3（「Exactly」），則單位以 twips（1/20 點）解讀；<br/>            若 ColumnGapRule 設為 4（「Multiple」），則單位以 0.5 em 為增量的數量解讀。<br/>            其他情況則忽略。<br/>            預設：0 |
| [`row_gap_rule`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/row_gap_rule/) | 矩陣列之間的垂直間距類型；<br/>            垂直間距單位可以是 lines 或 points（以 twips 儲存）。<br/>            預設：SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/row_gap/) | 矩陣列之間的垂直間距值；<br/>            若 RowGapRule 設為 3（「Exactly」），則單位以 twips（1/20 點）解讀；<br/>            若 RowGapRule 設為 4（「Multiple」），則單位以半行為單位解讀。<br/>            預設：0 |

## 方法

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/join/#imathelement) | 將數學元素合併，形成數學區塊 |
| [`join(self, math_text)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/join/#str) | 將數學文字合併，形成數學區塊 |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/divide/#imathelement) | 以此分子與指定的分母建立分數 |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/divide/#str) | 以此分子與指定的分母建立分數 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/divide/#imathelement-mathfractiontypes) | 以此分子與指定的分母，建立指定類型的分數 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/divide/#str-mathfractiontypes) | 以此分子與指定的分母，建立指定類型的分數 |
| [`enclose(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/enclose/#) | 將數學元素括於圓括號中 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/enclose/#char-char) | 將數學元素以指定的字符（如圓括號或其他字符）框住 |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/function/#imathelement) | 以此實例作為函式名稱，取得參數的函式 |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/function/#str) | 以此實例作為函式名稱，取得參數的函式 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#imathelement) | 以此實例作為參數，取得指定的函式 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#str) | 以此實例作為參數，取得指定的函式 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsofoneargument) | 以此實例作為參數，取得指定的函式 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 以此實例作為參數，並加入指定的額外參數，取得指定的函式 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 以此實例作為參數，並加入指定的額外參數，取得指定的函式 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/set_subscript/#imathelement) | 建立下標 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/set_subscript/#str) | 建立下標 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/set_superscript/#imathelement) | 建立上標 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/set_superscript/#str) | 建立上標 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) | 在右側建立下標與上標 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#str-str) | 在右側建立下標與上標 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) | 在左側建立下標與上標 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#str-str) | 在左側建立下標與上標 |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/radical/#imathelement) | 指定從給定參數計算指定次方的數學根號 |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/radical/#str) | 指定從給定參數計算指定次方的數學根號 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/set_upper_limit/#imathelement) | 取得上限 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/set_upper_limit/#str) | 取得上限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/set_lower_limit/#imathelement) | 取得下限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/set_lower_limit/#str) | 取得下限 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) | 建立 N 元運算子 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-str-str) | 建立 N 元運算子 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 取得積分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement) | 取得積分 |
| [`integral(self, integral_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes) | 取得無上下限的積分 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) | 取得積分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str) | 取得積分 |
| [`group(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/group/#) | 使用底部大括號將此元素放入群組 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) | 使用分組字符（如底部大括號或其他）將此元素放入群組 |
| [`to_border_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/to_border_box/#) | 將此元素放入邊框盒中 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 將此元素放入邊框盒中 |
| [`to_math_array(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/to_math_array/#) | 放入垂直陣列 |
| [`accent(self, accent_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/accent/#char) | 設定重音符號（位於此元素上方的字元） |
| [`overbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/overbar/#) | 在此元素上方設定橫線 |
| [`underbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/underbar/#) | 在此元素下方設定橫線 |
| [`to_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/to_box/#) | 將此元素放入非視覺盒（邏輯分組）<br/>            用於將方程式或其他數學文字的組件分組。<br/>            盒子物件例如可以作為具有或不具對齊點的運算子模擬器，<br/>            作為換行點，或分組以避免內部換行。 |
| [`get_column_alignment(self, column_index)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/get_column_alignment/#int) | 取得指定欄的水平對齊方式 |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/set_column_alignment/#int-mathhorizontalalignment) | 設定指定欄的水平對齊方式 |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | 設定指定欄位的水平對齊方式 |
| [`insert_row_before(self, row_index)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/insert_row_before/#int) | 在指定列之前插入新列<br/>            新列中的所有元素初始為 None。 |
| [`insert_row_after(self, row_index)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/insert_row_after/#int) | 在指定列之後插入新列<br/>            新列中的所有元素初始為 None。 |
| [`delete_row(self, row_index)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/delete_row/#int) | 刪除指定的列 |
| [`insert_column_before(self, column_index)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/insert_column_before/#int) | 在指定欄之前插入新欄<br/>            新欄中的所有元素初始為 None。 |
| [`insert_column_after(self, column_index)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/insert_column_after/#int) | 在指定欄之後插入新欄<br/>            新欄中的所有元素初始為 None。 |
| [`delete_column(self, column_index)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/delete_column/#int) | 刪除指定的欄 |
| [`get_children(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix/get_children/#) | 取得子元素 |

### 另請參閱
* 類別 [`MathElementBase`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase)
* 類別 [`MathMatrix`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathmatrix)
* 模組 [`aspose.slides.mathtext`](/slides/python-net/zh-hant/aspose.slides.mathtext)
* 函式庫 [`Aspose.Slides`](/slides/python-net)