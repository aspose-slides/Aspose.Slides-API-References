---
title: MathGroupingCharacter class
second_title: Aspose.Slides for Python via .NET APIリファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/mathgroupingcharacter/
---
## MathGroupingCharacter クラス

式の上部または下部に配置されるグルーピング記号を指定し、通常は要素間の関係を強調します

**Inheritance:**[`MathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter) → [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)

MathGroupingCharacter 型は以下のメンバーを公開します:

## コンストラクタ

| Constructor | Description |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement) | MathGroupingCharacter クラスの新しいインスタンスを、デフォルトのグルーピング文字 U+23DF (BOTTOM CURLY BRACKET) で初期化します<br/>            with the default grouping character U+23DF (BOTTOM CURLY BRACKET) |
| [`__init__(self, element, character, position, vertical_justification)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement-char-mathtopbotpositions-mathtopbotpositions) | MathGroupingCharacter クラスの新しいインスタンスを初期化します。 |

## プロパティ

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/base/) | 基本引数 |
| [`character`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/character/) | グルーピング文字<br/>            デフォルト値: U+23DF (BOTTOM CURLY BRACKET) |
| [`position`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/position/) | グルーピング文字の位置。<br/>            デフォルト: Bottom |
| [`vertical_justification`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/vertical_justification/) | グループ文字の垂直位置揃え。<br/>            オブジェクトのベースラインに対する配置を指定します。<br/>            例えば、グループ文字がオブジェクトの上にある場合、 <br/>            VerticalJustification が Top の場合、オブジェクトの上部がベースライン上にあることを示します；<br/>            VerticalJustification が Bottom に設定されている場合、オブジェクトの下部がベースライン上にあります<br/>            デフォルト: Position=Top の場合は Bottom、Position=Bottom の場合は Top |

## メソッド

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/join/#imathelement) | 数学要素を結合し、数学ブロックを作成します |
| [`join(self, math_text)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/join/#str) | 数学テキストを結合し、数学ブロックを作成します |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement) | この分子と指定された分母で分数を作成します |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/divide/#str) | この分子と指定された分母で分数を作成します |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement-mathfractiontypes) | この分子と指定された分母で、指定されたタイプの分数を作成します |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/divide/#str-mathfractiontypes) | この分子と指定された分母で、指定されたタイプの分数を作成します |
| [`enclose(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/enclose/#) | 数学要素を括弧で囲みます |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/enclose/#char-char) | 数学要素を括弧やその他の文字など、指定された文字で枠囲みします |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/function/#imathelement) | このインスタンスを関数名として、引数の関数を取得します |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/function/#str) | このインスタンスを関数名として、引数の関数を取得します |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#imathelement) | このインスタンスを引数として、指定された関数を取得します |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#str) | このインスタンスを引数として、指定された関数を取得します |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsofoneargument) | このインスタンスを引数として、指定された関数を取得します |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | このインスタンスを引数および指定された追加引数として、指定された関数を取得します |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | このインスタンスを引数および指定された追加引数として、指定された関数を取得します |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#imathelement) | 下付き文字を作成します |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#str) | 下付き文字を作成します |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#imathelement) | 上付き文字を作成します |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#str) | 上付き文字を作成します |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#imathelement-imathelement) | 右側に下付き文字と上付き文字を作成します |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#str-str) | 右側に下付き文字と上付き文字を作成します |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#imathelement-imathelement) | 左側に下付き文字と上付き文字を作成します |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#str-str) | 左側に下付き文字と上付き文字を作成します |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/radical/#imathelement) | 指定された引数から、与えられた次数の数学的根を指定します。 |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/radical/#str) | 指定された引数から、与えられた次数の数学的根を指定します。 |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#imathelement) | 上限を取ります |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#str) | 上限を取ります |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#imathelement) | 下限を取ります |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#str) | 下限を取ります |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-imathelement-imathelement) | N元演算子を作成します |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-str-str) | N元演算子を作成します |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 積分を取ります |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement) | 積分を取ります |
| [`integral(self, integral_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes) | 上限・下限なしで積分を取ります |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str-mathlimitlocations) | 積分を取ります |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str) | 積分を取ります |
| [`group(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/group/#) | この要素を下の波括弧でグループ化します |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/group/#char-mathtopbotpositions-mathtopbotpositions) | この要素を、下の波括弧やその他のグルーピング文字を使用してグループ化します |
| [`to_border_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#) | この要素をボーダーボックスに配置します |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | この要素をボーダーボックスに配置します |
| [`to_math_array(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/to_math_array/#) | 垂直配列に配置します |
| [`accent(self, accent_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/accent/#char) | アクセント記号を設定します（この要素の上部に文字を置く） |
| [`overbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/overbar/#) | この要素の上部にバーを設定します |
| [`underbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/underbar/#) | この要素の下部にバーを設定します |
| [`to_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/to_box/#) | この要素を非表示ボックス（論理的グルーピング）に配置します <br/>            これは、方程式やその他の数学テキストの構成要素をグループ化するために使用されます。<br/>            ボックス化されたオブジェクトは、例えば、整列ポイントの有無にかかわらず演算子エミュレータとして機能したり、<br/>            改行ポイントとして機能したり、内部で改行を許可しないようにグループ化したりできます。 |
| [`get_children(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter/get_children/#) | 子要素を取得します |

### 参照
* クラス [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)
* クラス [`MathGroupingCharacter`](/slides/python-net/ja/aspose.slides.mathtext/mathgroupingcharacter)
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)