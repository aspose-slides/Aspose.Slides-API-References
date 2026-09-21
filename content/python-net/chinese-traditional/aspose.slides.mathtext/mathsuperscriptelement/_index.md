---
title: MathSuperscriptElement class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.mathtext/mathsuperscriptelement/
---
## MathSuperscriptElement 類別

指定上標物件，其由基底和置於右上方的縮小尺寸上標組成

**繼承：**[`MathSuperscriptElement`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement) → [`BaseScript`](/slides/python-net/zh-hant/aspose.slides.mathtext/basescript) → [`MathElementBase`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase)

MathSuperscriptElement 型別公開以下成員：

## 建構式

| Constructor | Description |
| :- | :- |
| [`__init__(self, base_arg, super_script)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/__init__/#imathelement-imathelement) | 初始化 MathSuperscriptElement 類別的新執行個體。 |

## 屬性

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/base/) | 基底參數 |
| [`superscript`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/superscript/) | 上標 |

## 方法

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/join/#imathelement) | 將數學元素結合並形成數學區塊 |
| [`join(self, math_text)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/join/#str) | 將數學文字結合並形成數學區塊 |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/divide/#imathelement) | 以此分子和指定的分母建立分數 |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/divide/#str) | 以此分子和指定的分母建立分數 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/divide/#imathelement-mathfractiontypes) | 以此分子和指定的分母建立指定類型的分數 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/divide/#str-mathfractiontypes) | 以此分子和指定的分母建立指定類型的分數 |
| [`enclose(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/enclose/#) | 將數學元素置於括號中 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/enclose/#char-char) | 使用指定的字元（如括號或其他字元）將數學元素框住 |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/function/#imathelement) | 以此實例作為函式名稱，接受一個參數的函式 |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/function/#str) | 以此實例作為函式名稱，接受一個參數的函式 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#imathelement) | 以此實例作為參數，接受指定的函式 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#str) | 以此實例作為參數，接受指定的函式 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#mathfunctionsofoneargument) | 以此實例作為參數，接受指定的函式 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 以此實例作為參數，接受指定的函式及指定的額外參數 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 以此實例作為參數，接受指定的函式及指定的額外參數 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/set_subscript/#imathelement) | 建立下標 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/set_subscript/#str) | 建立下標 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/set_superscript/#imathelement) | 建立上標 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/set_superscript/#str) | 建立上標 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/set_sub_superscript_on_the_right/#imathelement-imathelement) | 在右側建立下標和上標 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/set_sub_superscript_on_the_right/#str-str) | 在右側建立下標和上標 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/set_sub_superscript_on_the_left/#imathelement-imathelement) | 在左側建立下標和上標 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/set_sub_superscript_on_the_left/#str-str) | 在左側建立下標和上標 |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/radical/#imathelement) | 指定從給定參數取得指定次方的數學根號。 |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/radical/#str) | 指定從給定參數取得指定次方的數學根號。 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/set_upper_limit/#imathelement) | 接受上限 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/set_upper_limit/#str) | 接受上限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/set_lower_limit/#imathelement) | 接受下限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/set_lower_limit/#str) | 接受下限 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/nary/#mathnaryoperatortypes-imathelement-imathelement) | 建立 N 元運算子 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/nary/#mathnaryoperatortypes-str-str) | 建立 N 元運算子 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 接受積分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes-imathelement-imathelement) | 接受積分 |
| [`integral(self, integral_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes) | 接受無上下限的積分 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes-str-str-mathlimitlocations) | 接受積分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes-str-str) | 接受積分 |
| [`group(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/group/#) | 使用底部大括號將此元素放入群組 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/group/#char-mathtopbotpositions-mathtopbotpositions) | 使用群組字元（如底部大括號或其他）將此元素放入群組 |
| [`to_border_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/to_border_box/#) | 將此元素放入邊框盒中 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 將此元素放入邊框盒中 |
| [`to_math_array(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/to_math_array/#) | 放入垂直陣列 |
| [`accent(self, accent_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/accent/#char) | 設定重音標記（此元素上方的字元） |
| [`overbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/overbar/#) | 在此元素上方設定條線 |
| [`underbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/underbar/#) | 在此元素下方設定條線 |
| [`to_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/to_box/#) | 將此元素放入非可視的盒子（邏輯分組） <br/>            用於將方程式或其他數學文字的組件分組。<br/>            盒狀物件可以（例如）作為帶或不帶對齊點的運算子模擬器，<br/>            作為換行點，或以不允許換行的方式分組。 |
| [`get_children(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement/get_children/#) | 取得子元素 |

### 另見
* 類別 [`BaseScript`](/slides/python-net/zh-hant/aspose.slides.mathtext/basescript)
* 類別 [`MathElementBase`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase)
* 類別 [`MathSuperscriptElement`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathsuperscriptelement)
* 模組 [`aspose.slides.mathtext`](/slides/python-net/zh-hant/aspose.slides.mathtext)
* 函式庫 [`Aspose.Slides`](/slides/python-net)