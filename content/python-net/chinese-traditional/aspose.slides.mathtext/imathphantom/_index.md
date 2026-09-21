---
title: IMathPhantom class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.mathtext/imathphantom/
---
## IMathPhantom 類別

表示一個幻影數學物件 (<m:phant>)，會影響其子元素的版面配置，但不一定會顯示它。幻影可以隱藏其基礎表達式，同時保留寬度、高度或深度，以對齊公式或保留空間。可見性與幾何行為由諸如 Show、ZeroWid、ZeroAsc、ZeroDesc 與 Transp 等屬性控制。

IMathPhantom 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/base/) | 基礎參數 |
| [`show`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/show/) | 取得或設定一個值，以指示基礎元素是否顯示。 |
| [`zero_width`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/zero_width/) | 取得或設定一個值，以指示基礎元素的寬度是否應視為零。 |
| [`zero_asc`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/zero_asc/) | 取得或設定一個值，以指示基礎元素的上升（基線上方的高度）是否應視為零。 |
| [`zero_desc`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/zero_desc/) | 取得或設定一個值，以指示基礎元素的下降（基線下方的深度）是否應視為零。 |
| [`transp`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/transp/) | 取得或設定一個值，以指示幻影是否對基於類別的間距規則透明。 |

## 方法

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_children(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/imathphantom/to_box/#) |  |


### 另請參閱
* 模組 [`aspose.slides.mathtext`](/slides/python-net/zh-hant/aspose.slides.mathtext)
* 函式庫 [`Aspose.Slides`](/slides/python-net)