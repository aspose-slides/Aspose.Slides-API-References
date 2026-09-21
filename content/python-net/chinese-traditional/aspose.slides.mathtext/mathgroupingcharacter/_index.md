---
title: MathGroupingCharacter class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.mathtext/mathgroupingcharacter/
---
## MathGroupingCharacter 類別

指定一個位於表達式上方或下方的分組符號，通常用於突出元素之間的關係

**繼承：**[`MathGroupingCharacter`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter) → [`MathElementBase`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase)

MathGroupingCharacter 類型公開以下成員：

## 建構函式

| 建構函式 | 說明 |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement) | 初始化 MathGroupingCharacter 類別的新執行個體<br/>            使用預設的分組字元 U+23DF (BOTTOM CURLY BRACKET) |
| [`__init__(self, element, character, position, vertical_justification)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement-char-mathtopbotpositions-mathtopbotpositions) | 初始化 MathGroupingCharacter 類別的新執行個體。 |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`base`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/base/) | 基底參數 |
| [`character`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/character/) | 分組字元<br/>            預設值: U+23DF (BOTTOM CURLY BRACKET) |
| [`position`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/position/) | 分組字元的位置。<br/>            預設: Bottom |
| [`vertical_justification`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/vertical_justification/) | 群組字元的垂直對齊方式。<br/>            指定物件相對於基線的對齊方式。<br/>            例如，當群組字元位於物件之上時，<br/>            垂直對齊為 Top 表示物件的頂部落在基線上；<br/>            當垂直對齊設定為 Bottom 時，物件的底部在基線上<br/>            預設: Position=Top 時為 Bottom，Position=Bottom 時為 Top |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/join/#imathelement) | 將數學元素結合，形成一個數學區塊 |
| [`join(self, math_text)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/join/#str) | 將數學文字結合，形成一個數學區塊 |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement) | 使用此分子與指定的分母建立分數 |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/divide/#str) | 使用此分子與指定的分母建立分數 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement-mathfractiontypes) | 使用此分子與指定的分母，依指定類型建立分數 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/divide/#str-mathfractiontypes) | 使用此分子與指定的分母，依指定類型建立分數 |
| [`enclose(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/enclose/#) | 以圓括號將數學元素包圍 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/enclose/#char-char) | 以指定的字元（如圓括號或其他字元）將數學元素框住 |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/function/#imathelement) | 使用此實例作為函式名稱，取得帶參數的函式 |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/function/#str) | 使用此實例作為函式名稱，取得帶參數的函式 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#imathelement) | 使用此實例作為參數，取得指定的函式 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#str) | 使用此實例作為參數，取得指定的函式 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsofoneargument) | 使用此實例作為參數，取得指定的函式 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 使用此實例作為參數，並帶入指定的額外參數，取得指定的函式 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 使用此實例作為參數，並帶入指定的額外參數，取得指定的函式 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#imathelement) | 建立下標 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#str) | 建立下標 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#imathelement) | 建立上標 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#str) | 建立上標 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#imathelement-imathelement) | 在右側建立下標與上標 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#str-str) | 在右側建立下標與上標 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#imathelement-imathelement) | 在左側建立下標與上標 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#str-str) | 在左側建立下標與上標 |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/radical/#imathelement) | 指定給定次方的數學根號，來源於指定的參數。 |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/radical/#str) | 指定給定次方的數學根號，來源於指定的參數。 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#imathelement) | 取得上界 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#str) | 取得上界 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#imathelement) | 取得下界 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#str) | 取得下界 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-imathelement-imathelement) | 建立 N 元運算子 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-str-str) | 建立 N 元運算子 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 取得積分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement) | 取得積分 |
| [`integral(self, integral_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes) | 取得無界限的積分 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str-mathlimitlocations) | 取得積分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str) | 取得積分 |
| [`group(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/group/#) | 使用底部大括號將此元素置於一個群組中 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/group/#char-mathtopbotpositions-mathtopbotpositions) | 使用分組字元（如底部大括號或其他）將此元素置於群組中 |
| [`to_border_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#) | 將此元素置於邊框盒中 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 將此元素置於邊框盒中 |
| [`to_math_array(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/to_math_array/#) | 放入垂直陣列 |
| [`accent(self, accent_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/accent/#char) | 設定重音記號（此元素上方的字元） |
| [`overbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/overbar/#) | 在此元素頂部設定橫線 |
| [`underbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/underbar/#) | 在此元素底部設定橫線 |
| [`to_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/to_box/#) | 將此元素置於非視覺盒（邏輯分組）<br/>            用於將方程式或其他數學文字的組件分組。<br/>            盒狀物件可以（例如）作為具有或不具有對齊點的運算子模擬器，<br/>            作為換行點，或以分組方式防止內部換行。 |
| [`get_children(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter/get_children/#) | 取得子元素 |

### 參見
* 類別 [`MathElementBase`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase)
* 類別 [`MathGroupingCharacter`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathgroupingcharacter)
* 模組 [`aspose.slides.mathtext`](/slides/python-net/zh-hant/aspose.slides.mathtext)
* 函式庫 [`Aspose.Slides`](/slides/python-net)