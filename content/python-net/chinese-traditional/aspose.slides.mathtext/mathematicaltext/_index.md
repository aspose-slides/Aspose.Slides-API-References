---
title: MathematicalText class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.mathtext/mathematicaltext/
---
## MathematicalText 類別

數學文字

**繼承:**[`MathematicalText`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext) → [`MathElementBase`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase)

MathematicalText 類型公開以下成員：

## 建構函式

| 建構函式 | 說明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/__init__/#) | 預設建構函式（建立 String.Empty 值） |
| [`__init__(self, math_symbol)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/__init__/#char) | 使用單一符號建立 MathText |
| [`__init__(self, math_text)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/__init__/#str) | 從文字建立 MathematicalText |
| [`__init__(self, math_text, portion_format)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/__init__/#str-iportionformat) | 從文字和格式設定建立 MathematicalText |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`value`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/value/) | 文字值 |
| [`format`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/format/) | 文字格式屬性 |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/join/#imathelement) | 將數學元素結合並形成數學區塊 |
| [`join(self, math_text)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/join/#str) | 將數學文字結合並形成數學區塊 |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/divide/#imathelement) | 以此分子和指定的分母建立分數 |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/divide/#str) | 以此分子和指定的分母建立分數 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/divide/#imathelement-mathfractiontypes) | 以此分子和指定的分母建立指定類型的分數 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/divide/#str-mathfractiontypes) | 以此分子和指定的分母建立指定類型的分數 |
| [`enclose(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/enclose/#) | 將數學元素括於括號內 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/enclose/#char-char) | 使用指定的字元（如括號或其他字元）將數學元素框起來 |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/function/#imathelement) | 將此實例作為函式名稱，取得參數的函式 |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/function/#str) | 將此實例作為函式名稱，取得參數的函式 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#imathelement) | 使用此實例作為參數，取得指定的函式 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#str) | 使用此實例作為參數，取得指定的函式 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsofoneargument) | 使用此實例作為參數，取得指定的函式 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 使用此實例作為參數，並加入指定的額外參數，取得指定的函式 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 使用此實例作為參數，並加入指定的額外參數，取得指定的函式 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/set_subscript/#imathelement) | 建立下標 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/set_subscript/#str) | 建立下標 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/set_superscript/#imathelement) | 建立上標 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/set_superscript/#str) | 建立上標 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_right/#imathelement-imathelement) | 在右側建立下標與上標 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_right/#str-str) | 在右側建立下標與上標 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_left/#imathelement-imathelement) | 在左側建立下標與上標 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_left/#str-str) | 在左側建立下標與上標 |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/radical/#imathelement) | 指定給定次方的數學根，根據指定的參數。 |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/radical/#str) | 指定給定次方的數學根，根據指定的參數。 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/set_upper_limit/#imathelement) | 取得上限 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/set_upper_limit/#str) | 取得上限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/set_lower_limit/#imathelement) | 取得下限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/set_lower_limit/#str) | 取得下限 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/nary/#mathnaryoperatortypes-imathelement-imathelement) | 建立 N 元運算子 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/nary/#mathnaryoperatortypes-str-str) | 建立 N 元運算子 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 取得積分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-imathelement-imathelement) | 取得積分 |
| [`integral(self, integral_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes) | 取得無上下限的積分 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-str-str-mathlimitlocations) | 取得積分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-str-str) | 取得積分 |
| [`group(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/group/#) | 使用底部大括號將此元素置於群組中 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/group/#char-mathtopbotpositions-mathtopbotpositions) | 使用分組字元（例如底部大括號或其他）將此元素置於群組中 |
| [`to_border_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/to_border_box/#) | 將此元素置於邊框盒中 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 將此元素置於邊框盒中 |
| [`to_math_array(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/to_math_array/#) | 放入垂直陣列 |
| [`accent(self, accent_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/accent/#char) | 設定重音符號（此元素之上方的字元） |
| [`overbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/overbar/#) | 在此元素上方設定橫線 |
| [`underbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/underbar/#) | 在此元素下方設定橫線 |
| [`to_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/to_box/#) | 將此元素置於非可視盒（邏輯群組）<br/>            用於將方程式或其他數學文字的組件群組起來。<br/>            例如，盒狀物件可作為有或無對齊點的運算子模擬器，<br/>            作為換行點，或被群組以避免其內部換行。 |
| [`get_children(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext/get_children/#) |  |

### 參見
* 類別 [`MathElementBase`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase)
* 類別 [`MathematicalText`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathematicaltext)
* 模組 [`aspose.slides.mathtext`](/slides/python-net/zh-hant/aspose.slides.mathtext)
* 函式庫 [`Aspose.Slides`](/slides/python-net)