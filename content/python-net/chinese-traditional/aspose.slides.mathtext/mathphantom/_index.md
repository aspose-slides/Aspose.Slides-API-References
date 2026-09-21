---
title: MathPhantom class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.mathtext/mathphantom/
---
## MathPhantom 類別

表示一個幻影數學物件 (<m:phant>)，會影響其子元素的版面配置，即使不一定顯示它。幻影可以隱藏其基礎表示式，同時保留寬度、高度或深度，以對齊公式或保留空間。可見性與幾何行為由屬性如 Show、ZeroWid、ZeroAsc、ZeroDesc 與 Transp 控制。

**繼承:**[`MathPhantom`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom) → [`MathElementBase`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase)

MathPhantom 類型公開以下成員：

## 建構函式

| 建構子 | 說明 |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/__init__/#imathelement) | 使用指定的基礎數學元素 <br/>            初始化 [`MathPhantom`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom) 類別的新實例。 |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`base`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/base/) | 基礎參數 |
| [`show`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/show/) | 取得或設定一個值，以指示是否顯示基礎元素。 |
| [`zero_width`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/zero_width/) | 取得或設定一個值，以指示基礎元素的寬度 <br/>            是否應視為零。 |
| [`zero_asc`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/zero_asc/) | 取得或設定一個值，以指示基礎元素的上升（基線上方的高度） <br/>            是否應視為零。 |
| [`zero_desc`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/zero_desc/) | 取得或設定一個值，以指示基礎元素的下降（基線下方的深度）<br/>            是否應視為零。 |
| [`transp`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/transp/) | 取得或設定一個值，以指示幻影在基於類別的間距規則下是否為透明 <br/>            。 |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/join/#imathelement) | 將數學元素合併，並形成數學區塊 |
| [`join(self, math_text)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/join/#str) | 將數學文字合併，並形成數學區塊 |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/divide/#imathelement) | 以此分子與指定的分母建立分數 |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/divide/#str) | 以此分子與指定的分母建立分數 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/divide/#imathelement-mathfractiontypes) | 以此分子與指定的分母，依指定類型建立分數 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/divide/#str-mathfractiontypes) | 以此分子與指定的分母，依指定類型建立分數 |
| [`enclose(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/enclose/#) | 將數學元素括於括號中 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/enclose/#char-char) | 將數學元素以指定字元（例如括號或其他字元）作為框架包住 |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/function/#imathelement) | 以此實例作為函式名稱，取得帶參數的函式 |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/function/#str) | 以此實例作為函式名稱，取得帶參數的函式 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/as_argument_of_function/#imathelement) | 以此實例作為參數，取得指定函式 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/as_argument_of_function/#str) | 以此實例作為參數，取得指定函式 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsofoneargument) | 以此實例作為參數，取得指定函式 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 以此實例和指定的額外參數，取得指定函式 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 以此實例和指定的額外參數，取得指定函式 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/set_subscript/#imathelement) | 建立下標 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/set_subscript/#str) | 建立下標 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/set_superscript/#imathelement) | 建立上標 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/set_superscript/#str) | 建立上標 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#imathelement-imathelement) | 在右側建立下標與上標 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#str-str) | 在右側建立下標與上標 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#imathelement-imathelement) | 在左側建立下標與上標 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#str-str) | 在左側建立下標與上標 |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/radical/#imathelement) | 指定從給定參數求取指定次方的根 |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/radical/#str) | 指定從給定參數求取指定次方的根 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/set_upper_limit/#imathelement) | 取得上限 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/set_upper_limit/#str) | 取得上限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/set_lower_limit/#imathelement) | 取得下限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/set_lower_limit/#str) | 取得下限 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-imathelement-imathelement) | 建立 N 元運算子 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-str-str) | 建立 N 元運算子 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 取得積分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement) | 取得積分 |
| [`integral(self, integral_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes) | 取得無上下限的積分 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str-mathlimitlocations) | 取得積分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str) | 取得積分 |
| [`group(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/group/#) | 使用底部大括號將此元素置於群組中 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/group/#char-mathtopbotpositions-mathtopbotpositions) | 使用群組字元（例如底部大括號或其他）將此元素置於群組中 |
| [`to_border_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/to_border_box/#) | 將此元素置於邊框盒中 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 將此元素置於邊框盒中 |
| [`to_math_array(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/to_math_array/#) | 放入垂直陣列 |
| [`accent(self, accent_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/accent/#char) | 設定重音符號（此元素上方的字元） |
| [`overbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/overbar/#) | 在此元素上方設定橫線 |
| [`underbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/underbar/#) | 在此元素下方設定橫線 |
| [`to_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/to_box/#) | 將此元素置於非可視盒（邏輯群組） <br/>            用於將方程式的組件或其他數學文字實例分組。<br/>            盒狀物件可（例如）作為帶或不帶對齊點的運算子模擬器，<br/>            作為換行點，或被分組以防止其內部換行。 |
| [`get_children(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom/get_children/#) | 取得子元素 |

### 參見
* 類別 [`MathElementBase`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase)
* 類別 [`MathPhantom`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathphantom)
* 模組 [`aspose.slides.mathtext`](/slides/python-net/zh-hant/aspose.slides.mathtext)
* 函式庫 [`Aspose.Slides`](/slides/python-net)