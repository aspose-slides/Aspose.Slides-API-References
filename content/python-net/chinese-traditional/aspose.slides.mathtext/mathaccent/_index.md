---
title: MathAccent class
second_title: Aspose.Slides 於 Python 的 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.mathtext/mathaccent/
---
## MathAccent 類別

指定重音功能，由基底與組合附加記號組成  
範例：𝑎́

**繼承:**[`MathAccent`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent) → [`MathElementBase`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase)

MathAccent 類型公開以下成員：

## 建構子

| 建構式 | 說明 |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/__init__/#imathelement) | 建立一個套用於指定數學元素，使用預設重音字元值的數學重音 |
| [`__init__(self, element, accent_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/__init__/#imathelement-char) | 建立一個套用於指定數學元素的數學重音 |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`base`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/base/) | 已套用重音的參數 |
| [`character`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/character/) | 重音字元<br/>            值應在 (U+0300–U+036F) 或 (U+20D0–U+20EF) 範圍內<br/>            預設值：結合型抑揚符號 (U+0302) |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/join/#imathelement) | 將數學元素結合並形成數學區塊 |
| [`join(self, math_text)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/join/#str) | 將數學文字結合並形成數學區塊 |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/divide/#imathelement) | 使用此分子與指定分母建立分數 |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/divide/#str) | 使用此分子與指定分母建立分數 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/divide/#imathelement-mathfractiontypes) | 使用此分子與指定分母，依指定類型建立分數 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/divide/#str-mathfractiontypes) | 使用此分子與指定分母，依指定類型建立分數 |
| [`enclose(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/enclose/#) | 將數學元素置於括號內 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/enclose/#char-char) | 將數學元素以指定字元（例如括號或其他字元）包圍 |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/function/#imathelement) | 以此實例作為函式名稱，取得參數的函式 |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/function/#str) | 以此實例作為函式名稱，取得參數的函式 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/as_argument_of_function/#imathelement) | 使用此實例作為參數，取得指定函式 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/as_argument_of_function/#str) | 使用此實例作為參數，取得指定函式 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsofoneargument) | 使用此實例作為參數，取得指定函式 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 使用此實例作為參數，並帶入指定的額外參數，取得指定函式 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 使用此實例作為參數，並帶入指定的額外參數，取得指定函式 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/set_subscript/#imathelement) | 建立下標 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/set_subscript/#str) | 建立下標 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/set_superscript/#imathelement) | 建立上標 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/set_superscript/#str) | 建立上標 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_right/#imathelement-imathelement) | 在右側建立下標與上標 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_right/#str-str) | 在右側建立下標與上標 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_left/#imathelement-imathelement) | 在左側建立下標與上標 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_left/#str-str) | 在左側建立下標與上標 |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/radical/#imathelement) | 指定從給定參數取得指定次方的數學根號。 |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/radical/#str) | 指定從給定參數取得指定次方的數學根號。 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/set_upper_limit/#imathelement) | 取得上限 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/set_upper_limit/#str) | 取得上限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/set_lower_limit/#imathelement) | 取得下限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/set_lower_limit/#str) | 取得下限 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/nary/#mathnaryoperatortypes-imathelement-imathelement) | 建立 N 元運算子 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/nary/#mathnaryoperatortypes-str-str) | 建立 N 元運算子 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 取得積分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-imathelement-imathelement) | 取得積分 |
| [`integral(self, integral_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes) | 取得無上下限的積分 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-str-str-mathlimitlocations) | 取得積分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-str-str) | 取得積分 |
| [`group(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/group/#) | 使用底部大括號將此元素放入群組 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/group/#char-mathtopbotpositions-mathtopbotpositions) | 使用群組字元（例如底部大括號或其他）將此元素放入群組 |
| [`to_border_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/to_border_box/#) | 將此元素放入邊框盒 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 將此元素放入邊框盒 |
| [`to_math_array(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/to_math_array/#) | 放入垂直陣列 |
| [`accent(self, accent_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/accent/#char) | 設定重音標記（此元素上方的字元） |
| [`overbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/overbar/#) | 在此元素上方設定橫線 |
| [`underbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/underbar/#) | 在此元素下方設定橫線 |
| [`to_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/to_box/#) | 將此元素放入非可視盒（邏輯分組） <br/>            用於將方程式或其他數學文字的組件分組。<br/>            例如，盒化物件可以作為具有或不具有對齊點的運算子模擬器，<br/>            作為換行點，或以不允許內部換行的方式分組。 |
| [`get_children(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent/get_children/#) | 取得子元素 |

### 另請參閱
* 類別 [`MathAccent`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathaccent)
* 類別 [`MathElementBase`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase)
* 模組 [`aspose.slides.mathtext`](/slides/python-net/zh-hant/aspose.slides.mathtext)
* 函式庫 [`Aspose.Slides`](/slides/python-net)