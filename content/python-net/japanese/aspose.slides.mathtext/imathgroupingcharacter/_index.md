---
title: IMathGroupingCharacter class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/imathgroupingcharacter/
---
## IMathGroupingCharacter クラス

式の上または下に配置されるグルーピング記号を指定し、通常は要素間の関係を強調します。

IMathGroupingCharacter 型は以下のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`base`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/base/) | ベース引数 |
| [`character`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/character/) | グルーピング文字<br/>            デフォルト値: U+23DF (BOTTOM CURLY BRACKET) |
| [`position`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/position/) | グルーピング文字の位置。<br/>            デフォルト: Bottom |
| [`vertical_justification`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/vertical_justification/) | グループ文字の垂直方向の配置。<br/>            オブジェクトのベースラインに対する配置を指定します。<br/>            例えば、グループ文字がオブジェクトの上にある場合、<br/>            VerticalJustification が Top の場合、オブジェクトの上部がベースライン上に位置することを示します。<br/>            VerticalJustification が Bottom に設定されている場合、オブジェクトの下部がベースライン上に位置します。<br/>            デフォルト: Position=Top の場合は Bottom、Position=Bottom の場合は Top |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_children(self)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/imathgroupingcharacter/to_box/#) |  |

### 参照
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)