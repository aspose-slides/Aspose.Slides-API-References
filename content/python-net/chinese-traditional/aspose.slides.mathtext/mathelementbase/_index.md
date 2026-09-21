---
title: MathElementBase class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.mathtext/mathelementbase/
---
## MathElementBase 類別

Base class for IMathElement with the implementation of some methods that are common to all inherited classes
            For internal use only. Inherited class must be IMathElement.

The MathElementBase type exposes the following members:

## 方法

| 方法 | 說明 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/join/#imathelement) | 將數學元素連接並形成一個數學區塊 |
| [`join(self, math_text)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/join/#str) | 將數學文字連接並形成一個數學區塊 |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/divide/#imathelement) | 使用此分子和指定的分母建立分數 |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/divide/#str) | 使用此分子和指定的分母建立分數 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/divide/#imathelement-mathfractiontypes) | 使用此分子和指定的分母建立指定類型的分數 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/divide/#str-mathfractiontypes) | 使用此分子和指定的分母建立指定類型的分數 |
| [`enclose(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/enclose/#) | 以括號將數學元素括起來 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/enclose/#char-char) | 以指定的字元（例如括號或其他字元）將數學元素框住 |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/function/#imathelement) | 以此實例作為函數名稱，接受帶參數的函式 |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/function/#str) | 以此實例作為函數名稱，接受帶參數的函式 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#imathelement) | 以此實例作為參數，接受指定函式 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#str) | 以此實例作為參數，接受指定函式 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#mathfunctionsofoneargument) | 以此實例作為參數，接受指定函式 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 以此實例作為參數，接受指定函式以及指定的額外參數 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 以此實例作為參數，接受指定函式以及指定的額外參數 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/set_subscript/#imathelement) | 建立下標 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/set_subscript/#str) | 建立下標 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/set_superscript/#imathelement) | 建立上標 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/set_superscript/#str) | 建立上標 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_right/#imathelement-imathelement) | 在右側建立下標和上標 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_right/#str-str) | 在右側建立下標和上標 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_left/#imathelement-imathelement) | 在左側建立下標和上標 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_left/#str-str) | 在左側建立下標和上標 |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/radical/#imathelement) | 指定給定次方的數學根號，來源於指定的參數。 |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/radical/#str) | 指定給定次方的數學根號，來源於指定的參數。 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/set_upper_limit/#imathelement) | 接受上限 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/set_upper_limit/#str) | 接受上限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/set_lower_limit/#imathelement) | 接受下限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/set_lower_limit/#str) | 接受下限 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/nary/#mathnaryoperatortypes-imathelement-imathelement) | 建立 N 元運算子 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/nary/#mathnaryoperatortypes-str-str) | 建立 N 元運算子 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 接受積分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-imathelement-imathelement) | 接受積分 |
| [`integral(self, integral_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes) | 接受無上下限的積分 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-str-str-mathlimitlocations) | 接受積分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-str-str) | 接受積分 |
| [`group(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/group/#) | 使用底部大括號將此元素放入群組 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/group/#char-mathtopbotpositions-mathtopbotpositions) | 使用分組字元（例如底部大括號或其他）將此元素放入群組 |
| [`to_border_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/to_border_box/#) | 將此元素放入框線盒子中 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 將此元素放入框線盒子中 |
| [`to_math_array(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/to_math_array/#) | 放入垂直陣列 |
| [`accent(self, accent_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/accent/#char) | 設定重音符號（此元素上方的字元） |
| [`overbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/overbar/#) | 在此元素上方設定橫線 |
| [`underbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/underbar/#) | 在此元素底部設定橫線 |
| [`to_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/to_box/#) | 將此元素放入非可視盒子（邏輯分組） <br/>            用於將方程式的組件或其他數學文字實例分組。<br/>            盒狀物件可以（例如）作為帶或不帶對齊點的運算子模擬器， <br/>            作為換行點，或被分組以防止內部換行。 |
| [`get_children(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase/get_children/#) |  |

### 參見
* 模組 [`aspose.slides.mathtext`](/slides/python-net/zh-hant/aspose.slides.mathtext)
* 函式庫 [`Aspose.Slides`](/slides/python-net)