---
title: MathDelimiter class
second_title: Aspose.Slides 供 Python 使用的 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter 類別

指定分隔符物件，由開啟與關閉字元組成（例如括號、花括號、方括號與垂直線），以及內部一個或多個以指定字元分隔的數學元素。範例：(𝑥2)；[𝑥2|𝑦2]

**繼承:**[`MathDelimiter`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter) → [`MathElementBase`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase)

MathDelimiter 類型公開以下成員：

## 建構函式

| 建構函式 | 說明 |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/__init__/#imathelement) | Initializes MathDelimiter with the specified element as single base argument |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`arguments`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/arguments/) | 由分隔符字元分隔的一個或多個數學元素 |
| [`beginning_character`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/beginning_character/) | Delimiter Beginning Character 指定起始（或開啟）分隔符字元。<br/>數學分隔符是包圍字元，例如括號、方括號與花括號。<br/>預設值：'('。 |
| [`separator_character`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/separator_character/) | Delimiter Separator Character 指定在分隔符物件中分隔引數的字元。<br/>預設值：'\|'. |
| [`ending_character`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/ending_character/) | Delimiter Ending Character 指定結束（或關閉）分隔符字元。<br/>數學分隔符是包圍字元，例如括號、方括號與花括號。<br/>預設值：')'。 |
| [`grow_to_match_operand_height`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/grow_to_match_operand_height/) | 指定 BeginningCharacter、SeparatorCharacter、EndingCharacter 的成長方式。<br/>當為 true 時，分隔符會垂直伸長以符合其操作數的高度。<br/>預設值為 true。 |
| [`delimiter_shape`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/delimiter_shape/) | 指定分隔符物件中分隔符的形狀。<br/>當為 MathDelimiterShape.Centered 時，分隔符會以數學文字的數學軸為中心，並調整以符合其內容的整體高度。<br/>當為 MathDelimiterShape.Match 時，分隔符的高度和形狀會被調整以完全匹配其內容。 |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/join/#imathelement) | 將數學元素連接起來並形成數學區塊 |
| [`join(self, math_text)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/join/#str) | 將數學文字連接起來並形成數學區塊 |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/divide/#imathelement) | 以此分子和指定的分母建立分數 |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/divide/#str) | 以此分子和指定的分母建立分數 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/divide/#imathelement-mathfractiontypes) | 以此分子和指定的分母建立指定類型的分數 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/divide/#str-mathfractiontypes) | 以此分子和指定的分母建立指定類型的分數 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/enclose/#char-char) | 以指定的字元（如括號或其他字元）將數學元素包圍起來作為框架 |
| [`enclose(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/enclose/#) | 將數學元素包圍於括號中 |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/function/#imathelement) | 以此實例作為函式名稱，取得參數的函式 |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/function/#str) | 以此實例作為函式名稱，取得參數的函式 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#imathelement) | 以此實例作為參數，取得指定的函式 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#str) | 以此實例作為參數，取得指定的函式 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) | 以此實例作為參數，取得指定的函式 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 以此實例作為參數，並使用指定的額外參數，取得指定的函式 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 以此實例作為參數，並使用指定的額外參數，取得指定的函式 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/set_subscript/#imathelement) | 建立下標 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/set_subscript/#str) | 建立下標 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/set_superscript/#imathelement) | 建立上標 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/set_superscript/#str) | 建立上標 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) | 在右側建立下標與上標 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#str-str) | 在右側建立下標與上標 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) | 在左側建立下標與上標 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#str-str) | 在左側建立下標與上標 |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/radical/#imathelement) | 指定從指定參數計算給定次方的數學根 |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/radical/#str) | 指定從指定參數計算給定次方的數學根 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#imathelement) | 取得上限 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#str) | 取得上限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#imathelement) | 取得下限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#str) | 取得下限 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) | 建立 N 元運算子 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-str-str) | 建立 N 元運算子 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 取得積分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) | 取得積分 |
| [`integral(self, integral_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes) | 取得無上下限的積分 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) | 取得積分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str) | 取得積分 |
| [`group(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/group/#) | 使用底部大括號將此元素放入群組 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) | 使用分組字元（如底部大括號或其他）將此元素放入群組 |
| [`to_border_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/to_border_box/#) | 將此元素放入邊框盒中 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 將此元素放入邊框盒中 |
| [`to_math_array(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/to_math_array/#) | 放入垂直陣列 |
| [`accent(self, accent_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/accent/#char) | 設定重音符號（位於此元素上方的字元） |
| [`overbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/overbar/#) | 在此元素上方設定橫線 |
| [`underbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/underbar/#) | 在此元素下方設定橫線 |
| [`to_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/to_box/#) | 將此元素放入非視覺盒（邏輯分組）<br/>用於將方程式或其他數學文字的組件分組。<br/>盒狀物件例如可以作為具有或不具有對齊點的運算子模擬器，<br/>作為換行點，或被分組以防止內部換行。 |
| [`delimit(self, separator_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/delimit/#char) | 使用指定的分隔符字元分隔參數 |
| [`get_children(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/get_children/#) | 取得子元素 |

### 另請參閱
* 類別 [`MathDelimiter`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter)
* 類別 [`MathElementBase`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase)
* 模組 [`aspose.slides.mathtext`](/slides/python-net/zh-hant/aspose.slides.mathtext)
* 函式庫 [`Aspose.Slides`](/slides/python-net)