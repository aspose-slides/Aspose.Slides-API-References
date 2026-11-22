---
title: MathDelimiter class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter 類別

指定分隔符物件，由開啟與關閉字元組成（例如括號、大括號、方括號與直線），以及內部一個或多個以指定字元分隔的數學元素。範例：(𝑥2)； [𝑥2|𝑦2]

**Inheritance:**[`MathDelimiter`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter) → [`MathElementBase`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase)

MathDelimiter 類型公開以下成員：

## 建構子

| 建構子 | 描述 |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/__init__/#imathelement) | 使用指定的元素作為單一基礎參數來初始化 MathDelimiter |

## 屬性

| 屬性 | 描述 |
| :- | :- |
| [`arguments`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/arguments/) | 一個或多個由分隔字元分隔的數學元素 |
| [`beginning_character`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/beginning_character/) | Delimiter Beginning Character 指定開始或開啟的分隔字元。<br/>            數學分隔符是括號、方括號與大括號等包圍字符。<br/>            預設值：'('。 |
| [`separator_character`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/separator_character/) | Delimiter Separator Character 指定在分隔符物件中分隔參數的字元。<br/>            預設值：'\|'. |
| [`ending_character`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/ending_character/) | Delimiter Ending Character 指定結束或關閉的分隔字元。<br/>            數學分隔符是括號、方括號與大括號等包圍字符。<br/>            預設值：')'. |
| [`grow_to_match_operand_height`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/grow_to_match_operand_height/) | 指定 BeginningCharacter、SeparatorCharacter、EndingCharacter 的伸展方式<br/>            為 true 時，分隔符會垂直伸長以匹配其運算元高度。<br/>            預設值為 true |
| [`delimiter_shape`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/delimiter_shape/) | 指定分隔符於分隔符物件中的形狀。<br/>            當為 MathDelimiterShape.Centered 時，分隔符會以數學文字的數學軸為中心，且仍會調整以適合其內容的整體高度。<br/>            當為 MathDelimiterShape.Match 時，會將其高度與形狀更改為完全匹配其內容。 |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/join/#imathelement) | 將數學元素合併並形成數學區塊 |
| [`join(self, math_text)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/join/#str) | 将數學文字合併並形成數學區塊 |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/divide/#imathelement) | 以此分子與指定的分母建立分數 |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/divide/#str) | 以此分子與指定的分母建立分數 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/divide/#imathelement-mathfractiontypes) | 以此分子與指定的分母，依指定類型建立分數 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/divide/#str-mathfractiontypes) | 以此分子與指定的分母，依指定類型建立分數 |
| [`enclose(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/enclose/#) | 以括號將數學元素括起 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/enclose/#char-char) | 以指定字元（例如括號或其他字元）將數學元素框住 |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/function/#imathelement) | 以此實例作為函式名稱，取得帶參數的函式 |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/function/#str) | 以此實例作為函式名稱，取得帶參數的函式 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#imathelement) | 以此實例作為參數，取得指定函式 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#str) | 以此實例作為參數，取得指定函式 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) | 以此實例作為參數，取得指定函式 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 以此實例作為參數，並加入指定的額外參數，取得指定函式 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 以此實例作為參數，並加入指定的額外參數，取得指定函式 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/set_subscript/#imathelement) | 建立下標 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/set_subscript/#str) | 建立下標 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/set_superscript/#imathelement) | 建立上標 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/set_superscript/#str) | 建立上標 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) | 在右側建立下標與上標 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#str-str) | 在右側建立下標與上標 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) | 在左側建立下標與上標 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#str-str) | 在左側建立下標與上標 |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/radical/#imathelement) | 指定從給定參數取得指定次方的數學根號。 |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/radical/#str) | 指定從給定參數取得指定次方的數學根號。 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#imathelement) | 取得上限 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#str) | 取得上限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#imathelement) | 取得下限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#str) | 取得下限 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) | 建立 N 進制運算子 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-str-str) | 建立 N 進制運算子 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 取得積分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) | 取得積分 |
| [`integral(self, integral_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes) | 取得無上下限的積分 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) | 取得積分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str) | 取得積分 |
| [`group(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/group/#) | 使用底部大括號將此元素放入群組 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) | 使用群組字符（例如底部大括號或其他）將此元素放入群組 |
| [`to_border_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/to_border_box/#) | 將此元素放入邊框盒中 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 將此元素放入邊框盒中 |
| [`to_math_array(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/to_math_array/#) | 放入垂直陣列 |
| [`accent(self, accent_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/accent/#char) | 設定重音標記（此元素上方的字元） |
| [`overbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/overbar/#) | 在此元素上方設定橫線 |
| [`underbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/underbar/#) | 在此元素下方設定橫線 |
| [`to_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/to_box/#) | 將此元素放入非視覺方框（邏輯分組）<br/>            用於將方程式或其他數學文字的組件分組。<br/>            例如，方框物件可作為具有或不具有對齊點的運算子模擬器，<br/>            作為換行點，或以不允許內部換行的方式分組。 |
| [`delimit(self, separator_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/delimit/#char) | 使用指定的分隔字元界定參數 |
| [`get_children(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter/get_children/#) | 取得子元素 |

### 另請參閱
* 類別 [`MathDelimiter`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathdelimiter)
* 類別 [`MathElementBase`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase)
* 模組 [`aspose.slides.mathtext`](/slides/python-net/zh-hant/aspose.slides.mathtext)
* 函式庫 [`Aspose.Slides`](/slides/python-net)