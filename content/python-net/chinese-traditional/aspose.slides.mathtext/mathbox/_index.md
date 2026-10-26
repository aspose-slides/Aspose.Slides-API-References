---
title: MathBox class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.mathtext/mathbox/
---
## MathBox 類別

指定數學元素的邏輯盒裝（封裝）。
            例如，盒裝物件可以作為帶或不帶對齊點的運算子模擬器，作為換行點，或被分組以防止在其中換行。例如，應將 "==" 運算子盒裝以防止換行。

**繼承:**[`MathBox`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox) → [`MathElementBase`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase)

The MathBox type exposes the following members:

## 建構子

| 建構子 | 描述 |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/__init__/#imathelement) | 使用指定的元素作為參數來初始化 MathBox |

## 屬性

| 屬性 | 描述 |
| :- | :- |
| [`base`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/base/) | 基礎參數 |
| [`operator_emulator`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/operator_emulator/) | 運算子模擬器。<br/>            當為 true 時，盒子及其內容會表現為單一運算子並繼承運算子的屬性。<br/>            這表示，例如，該字符可作為換行點，且可對齊至其他運算子。<br/>            當一個或多個字形結合形成運算子（例如 '=='）時，常會使用運算子模擬器。<br/>            Default value: false |
| [`no_break`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/no_break/) | 不換行<br/>            此屬性指定物件盒的「不可換行」屬性。當為 true 時，盒內不會發生換行。<br/>            這對於由多個二元運算子組成的運算子模擬器可能很重要。<br/>            若未指定此元素，則盒內可能產生換行。<br/>            Default: true |
| [`differential`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/differential/) | 微分<br/>            當為 true 時，盒子充當微分（例如積分式中的 𝑑𝑥），並獲得適當的水平間距以符合數學微分。<br/>            Default: false |
| [`alignment_point`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/alignment_point/) | 當為 true 時，此運算子模擬器充當對齊點；也就是說，其他等式中指定的對齊點可以與之對齊。<br/>            Default: false |
| [`explicit_break`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/explicit_break/) | 明確換行指定 Box 物件起始處是否有換行，<br/>            使得行在盒子物件起始處斷行。<br/>            指定前一行數學文字中運算子的編號，該運算子將作為當前行數學文字的對齊點。<br/>            可能的值：1..255<br/>            Default: 0（無明確換行） |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/join/#imathelement) | 將數學元素加入並形成數學區塊 |
| [`join(self, math_text)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/join/#str) | 將數學元素加入並形成數學區塊 |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/divide/#imathelement) | 使用此分子和指定的分母建立分數 |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/divide/#str) | 使用此分子和指定的分母建立分數 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/divide/#imathelement-mathfractiontypes) | 使用此分子和指定的分母建立指定類型的分數 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/divide/#str-mathfractiontypes) | 使用此分子和指定的分母建立指定類型的分數 |
| [`enclose(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/enclose/#) | 將數學元素以括號括起 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/enclose/#char-char) | 使用指定字符（如括號或其他字符）將數學元素框住 |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/function/#imathelement) | 以此實例作為函式名稱，取得帶參數的函式 |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/function/#str) | 以此實例作為函式名稱，取得帶參數的函式 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/as_argument_of_function/#imathelement) | 使用此實例作為參數，取得指定函式 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/as_argument_of_function/#str) | 使用此實例作為參數，取得指定函式 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsofoneargument) | 使用此實例作為參數，取得指定函式 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 使用此實例作為參數，取得指定函式並加入指定的附加參數 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 使用此實例作為參數，取得指定函式並加入指定的附加參數 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/set_subscript/#imathelement) | 建立下標 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/set_subscript/#str) | 建立下標 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/set_superscript/#imathelement) | 建立上標 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/set_superscript/#str) | 建立上標 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | 在右側建立下標與上標 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#str-str) | 在右側建立下標與上標 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | 在左側建立下標與上標 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#str-str) | 在左側建立下標與上標 |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/radical/#imathelement) | 指定給定次方的數學根號，來源於指定的參數。 |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/radical/#str) | 指定給定次方的數學根號，來源於指定的參數。 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/set_upper_limit/#imathelement) | 取得上限 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/set_upper_limit/#str) | 取得上限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/set_lower_limit/#imathelement) | 取得下限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/set_lower_limit/#str) | 取得下限 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | 建立 N 元運算子 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-str-str) | 建立 N 元運算子 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 取得積分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement) | 取得積分 |
| [`integral(self, integral_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes) | 取得無上下限的積分 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | 取得積分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str) | 取得積分 |
| [`group(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/group/#) | 使用底部大括號將此元素放入群組 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/group/#char-mathtopbotpositions-mathtopbotpositions) | 使用分組字符（例如底部大括號或其他）將此元素放入群組 |
| [`to_border_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/to_border_box/#) | 將此元素放入邊框盒中 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 將此元素放入邊框盒中 |
| [`to_math_array(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/to_math_array/#) | 置於垂直陣列中 |
| [`accent(self, accent_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/accent/#char) | 設定重音符號（位於此元素上方的字符） |
| [`overbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/overbar/#) | 在此元素上方設定橫線 |
| [`underbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/underbar/#) | 在此元素下方設定橫線 |
| [`to_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/to_box/#) | 將此元素放入非可視盒（邏輯分組） <br/>            用於將等式或其他數學文字的元件分組。<br/>            盒裝物件可以（例如）作為帶或不帶對齊點的運算子模擬器，<br/>            作為換行點，或被分組以防止在其中換行。 |
| [`get_children(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox/get_children/#) | 取得子元素 |

### 另見
* 類別 [`MathBox`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathbox)
* 類別 [`MathElementBase`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase)
* 模組 [`aspose.slides.mathtext`](/slides/python-net/zh-hant/aspose.slides.mathtext)
* 函式庫 [`Aspose.Slides`](/slides/python-net)