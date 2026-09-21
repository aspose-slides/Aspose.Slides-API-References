---
title: MathBlock class
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.mathtext/mathblock/
---
## MathBlock 類別

指定位於 MathParagraph 內且自行佔一行的數學文字實例。  
所有數學區域，包括方程式、運算式、方程式或運算式陣列，以及公式，都以數學區塊表示。

**繼承:**[`MathBlock`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock) → [`MathElementBase`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase)

MathBlock 型別公開以下成員：

## 建構函式

| 建構函式 | 說明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/__init__/#) | 初始化 MathBlock 類別的新實例。 |
| [`__init__(self, math_element)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/__init__/#imathelement) | 建立新的數學區塊並將指定元素放入其中 |
| [`__init__(self, math_elements)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/__init__/#iterableimathelement) |  |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`count`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/count/) | 取得集合中實際包含的子數學元素數量。<br/>            唯讀 **int**。 |
| [`is_read_only`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/is_read_only/) | 回傳 false，因為子元素集合可被修改。 |

取得或設定指定索引處的 IMathElement。

## 索引子

| 名稱 | 說明 |
| :- | :- |
| [`[index]`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/__getitem__/) | 項目的零基索引 |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/join/#imathelement) | 將數學元素與此數學區塊結合 |
| [`join(self, math_text)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/join/#str) | 將數學文字與此數學區塊結合 |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/divide/#imathelement) | 以此分子與指定分母建立分數 |
| [`divide(self, denominator)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/divide/#str) | 以此分子與指定分母建立分數 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/divide/#imathelement-mathfractiontypes) | 以此分子與指定分母建立指定類型的分數 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/divide/#str-mathfractiontypes) | 以此分子與指定分母建立指定類型的分數 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/enclose/#char-char) | 使用指定字符（如括號或其他字符）將此區塊的子元素括起來 |
| [`enclose(self, beginning_character, ending_character, separator_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/enclose/#char-char-char) | 使用指定字符（如括號或其他）將此區塊的子元素括起來<br/>            並以分隔字符分隔 |
| [`enclose(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/enclose/#) | 將數學元素括於括號中 |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/function/#imathelement) | 使用此實例作為函式名稱，接受一個參數的函式 |
| [`function(self, function_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/function/#str) | 使用此實例作為函式名稱，接受一個參數的函式 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/as_argument_of_function/#imathelement) | 使用此實例作為參數，接受指定函式 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/as_argument_of_function/#str) | 使用此實例作為參數，接受指定函式 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsofoneargument) | 使用此實例作為參數，接受指定函式 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 使用此實例作為參數，接受指定函式與額外參數 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 使用此實例作為參數，接受指定函式與額外參數 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/set_subscript/#imathelement) | 建立下標 |
| [`set_subscript(self, subscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/set_subscript/#str) | 建立下標 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/set_superscript/#imathelement) | 建立上標 |
| [`set_superscript(self, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/set_superscript/#str) | 建立上標 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#imathelement-imathelement) | 在右側建立下標與上標 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#str-str) | 在右側建立下標與上標 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#imathelement-imathelement) | 在左側建立下標與上標 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#str-str) | 在左側建立下標與上標 |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/radical/#imathelement) | 指定給定次方根的度數，來源於指定參數。 |
| [`radical(self, degree)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/radical/#str) | 指定給定次方根的度數，來源於指定參數。 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/set_upper_limit/#imathelement) | 取得上限 |
| [`set_upper_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/set_upper_limit/#str) | 取得上限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/set_lower_limit/#imathelement) | 取得下限 |
| [`set_lower_limit(self, limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/set_lower_limit/#str) | 取得下限 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-imathelement-imathelement) | 建立 N 進制運算子 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-str-str) | 建立 N 進制運算子 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 取得積分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement) | 取得積分 |
| [`integral(self, integral_type)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes) | 取得無上下限的積分 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str-mathlimitlocations) | 取得積分 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str) | 取得積分 |
| [`group(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/group/#) | 使用底部大括號將此元素置於群組中 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/group/#char-mathtopbotpositions-mathtopbotpositions) | 使用群組字符（如底部大括號或其他）將此元素置於群組中 |
| [`to_border_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/to_border_box/#) | 將此元素置於邊框盒中 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 將此元素置於邊框盒中 |
| [`to_math_array(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/to_math_array/#) | 將子元素以垂直陣列排列 |
| [`accent(self, accent_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/accent/#char) | 設定重音記號（此元素上方的字符） |
| [`overbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/overbar/#) | 在此元素上方設定橫線 |
| [`underbar(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/underbar/#) | 在此元素下方設定橫線 |
| [`to_box(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/to_box/#) | 將此元素置於非可視盒（邏輯分組） <br/>            用於將等式或其他數學文字的組件分組。<br/>            盒狀物件可（例如）作為帶或不帶對齊點的運算子模擬，<br/>            作為換行點，或分組以防止內部換行。 |
| [`get_children(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/get_children/#) | 取得子元素 |
| [`add(self, item)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/add/#imathelement) | 在集合末端加入數學元素。 |
| [`clear(self)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/clear/#) | 移除集合中的所有元素。 |
| [`contains(self, item)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/contains/#imathelement) | 判斷集合是否包含特定值。 |
| [`copy_to(self, array, array_index)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/copy_to/#listimathelement-int) | 複製至指定陣列。 |
| [`remove(self, item)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/remove/#imathelement) | 移除集合中第一次出現的特定物件。 |
| [`index_of(self, item)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/index_of/#imathelement) | 判斷特定數學元素在集合中的索引。 |
| [`insert(self, index, item)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/insert/#int-imathelement) | 在指定索引處插入 MathElement 至集合。 |
| [`remove_at(self, index)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/remove_at/#int) | 移除集合中指定索引處的元素。 |
| [`join_block(self, other)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/join_block/#imathblock) | 將另一個數學區塊與此區塊結合 |
| [`delimit(self, separator_character)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/delimit/#char) | 使用分隔字符（不含括號）分隔子元素 |
| [`write_as_math_ml(self, stream)`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock/write_as_math_ml/#iorawiobase) | 將此 [`MathBlock`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock) 的內容另存為 MathML |


### 另見
* 類別 [`MathBlock`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathblock)
* 類別 [`MathElementBase`](/slides/python-net/zh-hant/aspose.slides.mathtext/mathelementbase)
* 模組 [`aspose.slides.mathtext`](/slides/python-net/zh-hant/aspose.slides.mathtext)
* 函式庫 [`Aspose.Slides`](/slides/python-net)