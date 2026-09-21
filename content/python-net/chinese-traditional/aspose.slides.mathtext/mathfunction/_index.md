---
title: MathFunction class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.mathtext/mathfunction/
---
## MathFunction 類別

Specifies a function of an argument.

**Inheritance:**[`MathFunction`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction) → [`MathElementBase`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase)

The MathFunction type exposes the following members:

## 建構函式

| 建構函式 | 說明 |
| :- | :- |
| [`__init__(self, func_name, base_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/__init__/#imathelement-imathelement) | 初始化 MathFunction 類別的新執行個體。 |
| [`__init__(self, func_name, base_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/__init__/#str-imathelement) | 初始化 MathFunction 類別的新執行個體。 |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`name`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/name/) | 函式名稱<br/>            例如，函式名稱為 sin 和 cos |
| [`base`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/base/) | 函式參數 |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/join/#imathelement) | 將數學元素連接起來並形成數學區塊 |
| [`join(self, math_text)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/join/#str) | 將數學文字連接起來並形成數學區塊 |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/divide/#imathelement) | 使用此分子和指定的分母建立分數 |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/divide/#str) | 使用此分子和指定的分母建立分數 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/divide/#imathelement-mathfractiontypes) | 使用此分子和指定的分母，以指定類型建立分數 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/divide/#str-mathfractiontypes) | 使用此分子和指定的分母，以指定類型建立分數 |
| [`enclose(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/enclose/#) | 將數學元素置於括號內 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/enclose/#char-char) | 使用指定字元（例如括號或其他字元）將數學元素框起來 |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/function/#imathelement) | 以此實例作為函式名稱，取得一個帶參數的函式 |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/function/#str) | 以此實例作為函式名稱，取得一個帶參數的函式 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/as_argument_of_function/#imathelement) | 以此實例作為參數，傳遞指定函式 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/as_argument_of_function/#str) | 以此實例作為參數，傳遞指定函式 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/as_argument_of_function/#mathfunctionsofoneargument) | 以此實例作為參數，傳遞指定函式 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 以此實例作為參數，傳遞指定函式及指定的額外參數 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 以此實例作為參數，傳遞指定函式及指定的額外參數 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/set_subscript/#imathelement) | 建立下標 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/set_subscript/#str) | 建立下標 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/set_superscript/#imathelement) | 建立上標 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/set_superscript/#str) | 建立上標 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_right/#imathelement-imathelement) | 在右側建立下標與上標 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_right/#str-str) | 在右側建立下標與上標 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_left/#imathelement-imathelement) | 在左側建立下標與上標 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_left/#str-str) | 在左側建立下標與上標 |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/radical/#imathelement) | 指定給定次方的數學根號，來源於指定參數。 |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/radical/#str) | 指定給定次方的數學根號，來源於指定參數。 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/set_upper_limit/#imathelement) | 取得上限 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/set_upper_limit/#str) | 取得上限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/set_lower_limit/#imathelement) | 取得下限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/set_lower_limit/#str) | 取得下限 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/nary/#mathnaryoperatortypes-imathelement-imathelement) | 建立 N 元運算子 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/nary/#mathnaryoperatortypes-str-str) | 建立 N 元運算子 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 取得積分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-imathelement-imathelement) | 取得積分 |
| [`integral(self, integral_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes) | 取得無上下限的積分 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-str-str-mathlimitlocations) | 取得積分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-str-str) | 取得積分 |
| [`group(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/group/#) | 使用底部大括號將此元素置於群組中 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/group/#char-mathtopbotpositions-mathtopbotpositions) | 使用群組字元（如底部大括號或其他）將此元素置於群組中 |
| [`to_border_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/to_border_box/#) | 將此元素放入邊框盒中 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 將此元素放入邊框盒中 |
| [`to_math_array(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/to_math_array/#) | 放入垂直陣列中 |
| [`accent(self, accent_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/accent/#char) | 設定變音符號（此元素上方的字元） |
| [`overbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/overbar/#) | 在此元素上方設定橫線 |
| [`underbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/underbar/#) | 在此元素下方設定橫線 |
| [`to_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/to_box/#) | 將此元素放入非可視方框（邏輯分組） <br/>            用於將方程式或其他數學文字的組件分組。<br/>            方框物件可以（例如）作為帶或不帶對齊點的運算子模擬器，<br/>            作為換行點，或以不允許內部換行的方式分組。 |
| [`get_children(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction/get_children/#) | 取得子元素 |


### 另請參閱
* 類別 [`MathElementBase`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase)
* 類別 [`MathFunction`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathfunction)
* 模組 [`aspose.slides.mathtext`](/slides/python-net/zh-hant/aspose.slides.mathtext)
* 函式庫 [`Aspose.Slides`](/slides/python-net)