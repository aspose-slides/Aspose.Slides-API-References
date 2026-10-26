---
title: MathBorderBox class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.mathtext/mathborderbox/
---
## MathBorderBox 類別

在 IMathElement 周圍繪製矩形或其他類型的邊框。

**繼承:**[`MathBorderBox`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox) → [`MathElementBase`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase)

MathBorderBox 類型公開以下成員：

## 建構函式

| 建構式 | 說明 |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/__init__/#imathelement) | Creates MathBorderBox element with rectangular border |
| [`__init__(self, element, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/__init__/#imathelement-bool-bool-bool-bool-bool-bool-bool-bool) | Creates MathBorderBox element |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`base`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/base/) | 基礎參數 |
| [`hide_top`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/hide_top/) | 隱藏上邊緣（預設為 false）- 指定邊框盒上邊緣的隱藏或顯示狀態。 |
| [`hide_bottom`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/hide_bottom/) | 隱藏下邊緣（預設為 false）- 指定邊框盒下邊緣的隱藏或顯示狀態。 |
| [`hide_left`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/hide_left/) | 隱藏左邊緣（預設為 false）- 指定邊框盒左邊緣的隱藏或顯示狀態。 |
| [`hide_right`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/hide_right/) | 隱藏右邊緣（預設為 false）- 指定邊框盒右邊緣的隱藏或顯示狀態。 |
| [`strikethrough_horizontal`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/strikethrough_horizontal/) | 水平刪除線（預設為 false）- 指定水平刪除線的隱藏或顯示狀態。 |
| [`strikethrough_vertical`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/strikethrough_vertical/) | 垂直刪除線（預設為 false）- 指定垂直刪除線的隱藏或顯示狀態。 |
| [`strikethrough_bottom_left_to_top_right`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/strikethrough_bottom_left_to_top_right/) | 從左下角到右上角的刪除線（預設為 false）。<br/>            指定邊框盒左下角至右上角對角刪除線的隱藏或顯示狀態。 |
| [`strikethrough_top_left_to_bottom_right`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/strikethrough_top_left_to_bottom_right/) | 從左上角到右下角的刪除線（預設為 false）。<br/>            指定邊框盒左上角至右下角對角刪除線的隱藏或顯示狀態。 |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/join/#imathelement) | 將數學元素合併並形成數學區塊 |
| [`join(self, math_text)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/join/#str) | 將數學文字合併並形成數學區塊 |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/divide/#imathelement) | 使用此分子和指定的分母建立分數 |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/divide/#str) | 使用此分子和指定的分母建立分數 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/divide/#imathelement-mathfractiontypes) | 使用此分子和指定的分母，建立指定類型的分數 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/divide/#str-mathfractiontypes) | 使用此分子和指定的分母，建立指定類型的分數 |
| [`enclose(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/enclose/#) | 將數學元素包於括號中 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/enclose/#char-char) | 將數學元素以指定字符（如括號或其他字符）框住 |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/function/#imathelement) | 使用此實例作為函式名稱，取得參數的函式 |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/function/#str) | 使用此實例作為函式名稱，取得參數的函式 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#imathelement) | 使用此實例作為參數，取得指定函式 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#str) | 使用此實例作為參數，取得指定函式 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsofoneargument) | 使用此實例作為參數，取得指定函式 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 使用此實例作為參數，並加入指定的額外參數，取得指定函式 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 使用此實例作為參數，並加入指定的額外參數，取得指定函式 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/set_subscript/#imathelement) | 建立下標 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/set_subscript/#str) | 建立下標 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/set_superscript/#imathelement) | 建立上標 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/set_superscript/#str) | 建立上標 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | 在右側建立下標與上標 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_right/#str-str) | 在右側建立下標與上標 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | 在左側建立下標與上標 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_left/#str-str) | 在左側建立下標與上標 |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/radical/#imathelement) | 指定給定次方的數學根，來源於指定的參數。 |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/radical/#str) | 指定給定次方的數學根，來源於指定的參數。 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/set_upper_limit/#imathelement) | 取得上限 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/set_upper_limit/#str) | 取得上限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/set_lower_limit/#imathelement) | 取得下限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/set_lower_limit/#str) | 取得下限 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | 建立 N 元運算子 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/nary/#mathnaryoperatortypes-str-str) | 建立 N 元運算子 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 取得積分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-imathelement-imathelement) | 取得積分 |
| [`integral(self, integral_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes) | 取得無上下限的積分 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | 取得積分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-str-str) | 取得積分 |
| [`group(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/group/#) | 使用底部大括號將此元素放入群組中 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/group/#char-mathtopbotpositions-mathtopbotpositions) | 使用群組字符（如底部大括號或其他）將此元素放入群組中 |
| [`to_border_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/to_border_box/#) | 將此元素放入邊框盒中 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 將此元素放入邊框盒中 |
| [`to_math_array(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/to_math_array/#) | 放入垂直陣列 |
| [`accent(self, accent_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/accent/#char) | 設定重音符號（此元素上方的字符） |
| [`overbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/overbar/#) | 在此元素上方設定條線 |
| [`underbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/underbar/#) | 在此元素下方設定條線 |
| [`to_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/to_box/#) | 将此元素放入非可視盒（邏輯分組）<br/>            用於將方程式或其他數學文字的組件分組。<br/>            盒狀物件例如可作為帶或不帶對齊點的運算子模擬器，<br/>            作為換行點，或被分組以防止內部換行。 |
| [`get_children(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox/get_children/#) | 取得子元素 |

### 另見
* 類別 [`MathBorderBox`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathborderbox)
* 類別 [`MathElementBase`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase)
* 模組 [`aspose.slides.mathtext`](/slides/python-net/zh-hant/aspose.slides.mathtext)
* 程式庫 [`Aspose.Slides`](/slides/python-net)