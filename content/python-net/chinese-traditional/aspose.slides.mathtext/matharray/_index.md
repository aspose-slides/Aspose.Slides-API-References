---
title: MathArray class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.mathtext/matharray/
---
## MathArray 類別

指定垂直排列的方程式或任何數學物件的陣列

**繼承：**[`MathArray`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray) → [`MathElementBase`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase)

MathArray 類型公開以下成員：

## 建構函式

| 建構函式 | 說明 |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/__init__/#imathelement) | 建立一個數學陣列並將指定的元素放入其中 |
| [`__init__(self, elements)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/__init__/#iterableimathelement) |  |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`arguments`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/arguments/) | 陣列的項目集合 |
| [`base_justification`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/base_justification/) | 指定陣列相對於周圍文字的對齊方式<br/>            陣列外的文字可以與陣列物件的底部、頂部或中心對齊。<br/>            預設值：Center |
| [`maximum_distribution`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/maximum_distribution/) | 最大分配<br/>            設為 true 時，陣列的間距會延伸至包含元素（頁面、欄、儲存格等）的最大寬度。 |
| [`object_distribution`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/object_distribution/) | 物件分配<br/>            設為 true 時，陣列的內容會延伸至陣列物件的最大寬度。 |
| [`row_spacing_rule`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/row_spacing_rule/) | 陣列元素之間的垂直間距類型<br/>            預設：SingleLineGap |
| [`row_spacing`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/row_spacing/) | 陣列列之間的間距<br/>            僅在 RowSpacingRule 設為 3 Exactly 時使用，此時的測量單位為 points <br/>            或在 Multiple 時測量單位為半行。<br/>            預設：0 |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/join/#imathelement) | 將數學元素連接並形成數學區塊 |
| [`join(self, math_text)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/join/#str) | 將數學文字連接並形成數學區塊 |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/divide/#imathelement) | 以此分子和指定的分母建立分數 |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/divide/#str) | 以此分子和指定的分母建立分數 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/divide/#imathelement-mathfractiontypes) | 以此分子和指定的分母建立指定類型的分數 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/divide/#str-mathfractiontypes) | 以此分子和指定的分母建立指定類型的分數 |
| [`enclose(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/enclose/#) | 將數學元素置於括號中 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/enclose/#char-char) | 將數學元素用指定的字元（如括號或其他字元）框住 |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/function/#imathelement) | 以此實例作為函式名稱，取得帶有參數的函式 |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/function/#str) | 以此實例作為函式名稱，取得帶有參數的函式 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/as_argument_of_function/#imathelement) | 以此實例作為參數，取得指定函式 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/as_argument_of_function/#str) | 以此實例作為參數，取得指定函式 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsofoneargument) | 以此實例作為參數，取得指定函式 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 以此實例作為參數，取得指定函式並傳入額外參數 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 以此實例作為參數，取得指定函式並傳入額外參數 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/set_subscript/#imathelement) | 建立下標 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/set_subscript/#str) | 建立下標 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/set_superscript/#imathelement) | 建立上標 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/set_superscript/#str) | 建立上標 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#imathelement-imathelement) | 在右側建立下標與上標 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#str-str) | 在右側建立下標與上標 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#imathelement-imathelement) | 在左側建立下標與上標 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#str-str) | 在左側建立下標與上標 |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/radical/#imathelement) | 指定給定次方的數學根號，根據指定的參數 |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/radical/#str) | 指定給定次方的數學根號，根據指定的參數 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/set_upper_limit/#imathelement) | 取得上限 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/set_upper_limit/#str) | 取得上限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/set_lower_limit/#imathelement) | 取得下限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/set_lower_limit/#str) | 取得下限 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-imathelement-imathelement) | 建立 N 元運算子 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-str-str) | 建立 N 元運算子 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 取得積分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement) | 取得積分 |
| [`integral(self, integral_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/integral/#mathintegraltypes) | 取得無上下限的積分 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str-mathlimitlocations) | 取得積分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str) | 取得積分 |
| [`group(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/group/#) | 使用底部大括號將此元素放入群組 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/group/#char-mathtopbotpositions-mathtopbotpositions) | 使用分組字元（如底部大括號或其他）將此元素放入群組 |
| [`to_border_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/to_border_box/#) | 將此元素放入邊框框 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 將此元素放入邊框框 |
| [`to_math_array(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/to_math_array/#) | 放入垂直陣列 |
| [`accent(self, accent_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/accent/#char) | 設定重音符號（位於此元素之上的字元） |
| [`overbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/overbar/#) | 在此元素上方設定條線 |
| [`underbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/underbar/#) | 在此元素下方設定條線 |
| [`to_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/to_box/#) | 將此元素放入非視覺框（邏輯分組）<br/>            用於將方程式或其他數學文字的組件分組。<br/>            例如，方框物件可以作為有或無對齊點的運算子模擬器，<br/>            作為換行點，或被分組以避免內部換行。 |
| [`get_children(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray/get_children/#) | 取得子元素 |

### 另請參閱
* 類別 [`MathArray`](/slides/python-net/zh-hant/aspose.slides.mathtext/matharray)
* 類別 [`MathElementBase`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase)
* 模組 [`aspose.slides.mathtext`](/slides/python-net/zh-hant/aspose.slides.mathtext)
* 函式庫 [`Aspose.Slides`](/slides/python-net)