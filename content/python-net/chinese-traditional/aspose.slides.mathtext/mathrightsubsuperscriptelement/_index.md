---
title: MathRightSubSuperscriptElement class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/
---
## MathRightSubSuperscriptElement 類別

指定位於基底右側的上下標對象，它由基底以及放置在基底右側的下標和上標組成。

**繼承關係：**[`MathRightSubSuperscriptElement`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement) → [`BaseScript`](/slides/python-net/zh-hant/aspose.slides.mathtext/basescript) → [`MathElementBase`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase)

MathRightSubSuperscriptElement 類型公開以下成員：

## 建構函式

| 建構函式 | 說明 |
| :- | :- |
| [`__init__(self, base_arg, sub_script, super_script)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/__init__/#imathelement-imathelement-imathelement) | 初始化 MathRightSubSuperscriptElement 類別的新執行個體。 |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`base`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/base/) | 基底參數 |
| [`subscript`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/subscript/) | 下標參數 |
| [`superscript`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/superscript/) | 上標參數 |
| [`align_scripts`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/align_scripts/) | 指定下標/上標的對齊方式。<br/>當為 true 時，下標與上標水平對齊。<br/>當為 false 時，它們會根據基底的形狀進行字距調整。<br/>預設值為 false。 |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/join/#imathelement) | 將數學元素合併並形成數學區塊 |
| [`join(self, math_text)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/join/#str) | 將數學文字合併並形成數學區塊 |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/divide/#imathelement) | 使用此分子和指定的分母建立分數 |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/divide/#str) | 使用此分子和指定的分母建立分數 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/divide/#imathelement-mathfractiontypes) | 使用此分子和指定的分母，建立指定類型的分數 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/divide/#str-mathfractiontypes) | 使用此分子和指定的分母，建立指定類型的分數 |
| [`enclose(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/enclose/#) | 將數學元素置於括號中 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/enclose/#char-char) | 將數學元素置於指定的字元中，例如括號或其他作為框架的字元 |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/function/#imathelement) | 以此實例作為函式名稱，接受一個參數的函式 |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/function/#str) | 以此實例作為函式名稱，接受一個參數的函式 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#imathelement) | 以此實例作為參數，接受指定的函式 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#str) | 以此實例作為參數，接受指定的函式 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#mathfunctionsofoneargument) | 以此實例作為參數，接受指定的函式 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 以此實例作為參數，接受指定的函式及指定的額外參數 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 以此實例作為參數，接受指定的函式及指定的額外參數 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_subscript/#imathelement) | 建立下標 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_subscript/#str) | 建立下標 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_superscript/#imathelement) | 建立上標 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_superscript/#str) | 建立上標 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_sub_superscript_on_the_right/#imathelement-imathelement) | 在右側建立下標與上標 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_sub_superscript_on_the_right/#str-str) | 在右側建立下標與上標 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_sub_superscript_on_the_left/#imathelement-imathelement) | 在左側建立下標與上標 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_sub_superscript_on_the_left/#str-str) | 在左側建立下標與上標 |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/radical/#imathelement) | 指定從給定參數計算指定次方的數學根號。 |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/radical/#str) | 指定從給定參數計算指定次方的數學根號。 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_upper_limit/#imathelement) | 接受上限 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_upper_limit/#str) | 接受上限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_lower_limit/#imathelement) | 接受下限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_lower_limit/#str) | 接受下限 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/nary/#mathnaryoperatortypes-imathelement-imathelement) | 建立 N 元運算子 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/nary/#mathnaryoperatortypes-str-str) | 建立 N 元運算子 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 接受積分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes-imathelement-imathelement) | 接受積分 |
| [`integral(self, integral_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes) | 接受無上下限的積分 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes-str-str-mathlimitlocations) | 接受積分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes-str-str) | 接受積分 |
| [`group(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/group/#) | 使用底部大括號將此元素置於群組中 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/group/#char-mathtopbotpositions-mathtopbotpositions) | 使用分組字元（例如底部大括號或其他）將此元素置於群組中 |
| [`to_border_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/to_border_box/#) | 將此元素置於邊框盒中 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 將此元素置於邊框盒中 |
| [`to_math_array(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/to_math_array/#) | 放入垂直陣列 |
| [`accent(self, accent_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/accent/#char) | 設定重音符號（此元素頂部的字元） |
| [`overbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/overbar/#) | 在此元素頂部設定橫線 |
| [`underbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/underbar/#) | 在此元素底部設定橫線 |
| [`to_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/to_box/#) | 將此元素放入非可視盒（邏輯分組）<br/>用於對方程式或其他數學文字的組件進行分組。<br/>盒狀對象可以（例如）作為帶或不帶對齊點的運算子模擬器，<br/>作為換行點，或被分組以防止內部換行。 |
| [`get_children(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_children/#) | 取得子元素 |

### 另請參閱
* 類別 [`BaseScript`](/slides/python-net/zh-hant/aspose.slides.mathtext/basescript)
* 類別 [`MathElementBase`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase)
* 類別 [`MathRightSubSuperscriptElement`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelement)
* 模組 [`aspose.slides.mathtext`](/slides/python-net/zh-hant/aspose.slides.mathtext)
* 函式庫 [`Aspose.Slides`](/slides/python-net)