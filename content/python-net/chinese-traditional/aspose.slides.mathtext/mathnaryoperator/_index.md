---
title: MathNaryOperator class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.mathtext/mathnaryoperator/
---
## MathNaryOperator 類別

指定一個 N 元數學物件，例如求和與積分。  
它由運算子、基底（或運算元）以及可選的上、下限組成。  
N 元運算子的例子包括：求和、聯集、交集、積分

**繼承**：[`MathNaryOperator`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator) → [`MathElementBase`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase)

MathNaryOperator 型別公開以下成員：

## 建構函式

| 建構函式 | 說明 |
| :- | :- |
| [`__init__(self, operator_symbol, base_argument, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement-imathelement) | 初始化 MathNaryOperator 類別的新實例。 |
| [`__init__(self, operator_symbol, base_argument, lower_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement) | 初始化 MathNaryOperator 類別的新實例。 |
| [`__init__(self, operator_symbol, base_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement) | 初始化 MathNaryOperator 類別的新實例。 |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`base`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/base/) | 基底參數 |
| [`subscript`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/subscript/) | 指定次標參數，例如在積分的情況下，設定下限 |
| [`superscript`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/superscript/) | 指定上標參數，例如在積分的情況下，設定上限 |
| [`operator`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/operator/) | Nary 運算子字元<br/>例如：'∑'、'∫' |
| [`limit_location`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/limit_location/) | 限制的位置（次標與上標） |
| [`grow_to_match_operand_height`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/grow_to_match_operand_height/) | 運算子字元會垂直伸長以符合其運算元的高度 |
| [`hide_subscript`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/hide_subscript/) | 隱藏次標 |
| [`hide_superscript`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/hide_superscript/) | 隱藏上標 |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/join/#imathelement) | 將數學元素結合並形成數學區塊 |
| [`join(self, math_text)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/join/#str) | 將數學文字結合並形成數學區塊 |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement) | 以此分子與指定分母建立分數 |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/divide/#str) | 以此分子與指定分母建立分數 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement-mathfractiontypes) | 以此分子與指定分母建立指定類型的分數 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/divide/#str-mathfractiontypes) | 以此分子與指定分母建立指定類型的分數 |
| [`enclose(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/enclose/#) | 在數學元素外圍加上括號 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/enclose/#char-char) | 使用指定字元（如括號或其他字元）將數學元素框住 |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/function/#imathelement) | 使用此實例作為函式名稱，取得帶參數的函式 |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/function/#str) | 使用此實例作為函式名稱，取得帶參數的函式 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#imathelement) | 使用此實例作為參數，取得指定函式 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#str) | 使用此實例作為參數，取得指定函式 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsofoneargument) | 使用此實例作為參數，取得指定函式 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 使用此實例作為參數，取得指定函式並加入額外參數 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 使用此實例作為參數，取得指定函式並加入額外參數 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/set_subscript/#imathelement) | 建立次標 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/set_subscript/#str) | 建立次標 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/set_superscript/#imathelement) | 建立上標 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/set_superscript/#str) | 建立上標 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#imathelement-imathelement) | 在右側建立次標與上標 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#str-str) | 在右側建立次標與上標 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#imathelement-imathelement) | 在左側建立次標與上標 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#str-str) | 在左側建立次標與上標 |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/radical/#imathelement) | 從指定參數取得指定次方的數學根號 |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/radical/#str) | 從指定參數取得指定次方的數學根號 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#imathelement) | 取得上限 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#str) | 取得上限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#imathelement) | 取得下限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#str) | 取得下限 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-imathelement-imathelement) | 建立 N 元運算子 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-str-str) | 建立 N 元運算子 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 取得積分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement) | 取得積分 |
| [`integral(self, integral_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes) | 取得無限制的積分 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str-mathlimitlocations) | 取得積分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str) | 取得積分 |
| [`group(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/group/#) | 使用底部大括號將此元素放入群組 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/group/#char-mathtopbotpositions-mathtopbotpositions) | 使用分組字元（如底部大括號或其他）將此元素放入群組 |
| [`to_border_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/to_border_box/#) | 將此元素放入邊框盒 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 將此元素放入邊框盒 |
| [`to_math_array(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/to_math_array/#) | 放入垂直陣列 |
| [`accent(self, accent_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/accent/#char) | 設定重音符號（位於此元素上方的字元） |
| [`overbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/overbar/#) | 在此元素上方設定橫條 |
| [`underbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/underbar/#) | 在此元素下方設定橫條 |
| [`to_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/to_box/#) | 將此元素放入非視覺盒（邏輯分組）<br/>用於將方程式或其他數學文字的組件分組。<br/>盒狀物件可（例如）作為帶或不帶對齊點的運算子模擬器，<br/>作為換行點，或作為不允許換行的分組。 |
| [`get_children(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator/get_children/#) | 取得子元素 |

### 另見
* 類別 [`MathElementBase`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase)
* 類別 [`MathNaryOperator`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathnaryoperator)
* 模組 [`aspose.slides.mathtext`](/slides/python-net/zh-hant/aspose.slides.mathtext)
* 函式庫 [`Aspose.Slides`](/slides/python-net)