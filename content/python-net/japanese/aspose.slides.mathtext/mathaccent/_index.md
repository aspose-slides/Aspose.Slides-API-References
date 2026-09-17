---
title: MathAccent class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/mathaccent/
---
## MathAccent クラス

ベースと結合アクセント記号からなるアクセント関数を指定します。例: 𝑎́

**継承:**[`MathAccent`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent) → [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)

MathAccent 型は以下のメンバーを公開します。

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/__init__/#imathelement) | 指定された数学要素にデフォルトのアクセント文字値を適用した数式アクセントを作成します |
| [`__init__(self, element, accent_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/__init__/#imathelement-char) | 指定された数学要素に適用する数式アクセントを作成します |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`base`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/base/) | アクセントが適用された引数 |
| [`character`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/character/) | アクセント文字<br/>            値は (U+0300–U+036F) または (U+20D0–U+20EF) の範囲内である必要があります<br/>            デフォルト値: 結合サーカムフレックスアクセント (U+0302) |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/join/#imathelement) | 数式要素を結合し、数式ブロックを形成します |
| [`join(self, math_text)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/join/#str) | 数式テキストを結合し、数式ブロックを形成します |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/divide/#imathelement) | この分子と指定された分母で分数を作成します |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/divide/#str) | この分子と指定された分母で分数を作成します |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/divide/#imathelement-mathfractiontypes) | 指定されたタイプの分数を、この分子と指定された分母で作成します |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/divide/#str-mathfractiontypes) | 指定されたタイプの分数を、この分子と指定された分母で作成します |
| [`enclose(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/enclose/#) | 数式要素を丸括弧で囲みます |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/enclose/#char-char) | 数式要素を丸括弧や他の文字など、指定された文字で枠として囲みます |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/function/#imathelement) | このインスタンスを関数名として、引数の関数を取得します |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/function/#str) | このインスタンスを関数名として、引数の関数を取得します |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/as_argument_of_function/#imathelement) | 指定された関数を取得し、このインスタンスを引数として使用します |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/as_argument_of_function/#str) | 指定された関数を取得し、このインスタンスを引数として使用します |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsofoneargument) | 指定された関数を取得し、このインスタンスを引数として使用します |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 指定された関数を取得し、このインスタンスを引数として、さらに指定された追加引数を使用します |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 指定された関数を取得し、このインスタンスを引数として、さらに指定された追加引数を使用します |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/set_subscript/#imathelement) | 下付文字を作成します |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/set_subscript/#str) | 下付文字を作成します |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/set_superscript/#imathelement) | 上付文字を作成します |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/set_superscript/#str) | 上付文字を作成します |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_right/#imathelement-imathelement) | 右側に下付文字と上付文字を作成します |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_right/#str-str) | 右側に下付文字と上付文字を作成します |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_left/#imathelement-imathelement) | 左側に下付文字と上付文字を作成します |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_left/#str-str) | 左側に下付文字と上付文字を作成します |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/radical/#imathelement) | 指定された引数から、指定された次数の数学的根号を指定します。 |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/radical/#str) | 指定された引数から、指定された次数の数学的根号を指定します。 |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/set_upper_limit/#imathelement) | 上限を取得します |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/set_upper_limit/#str) | 上限を取得します |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/set_lower_limit/#imathelement) | 下限を取得します |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/set_lower_limit/#str) | 下限を取得します |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/nary/#mathnaryoperatortypes-imathelement-imathelement) | N元演算子を作成します |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/nary/#mathnaryoperatortypes-str-str) | N元演算子を作成します |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 積分を取得します |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-imathelement-imathelement) | 積分を取得します |
| [`integral(self, integral_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes) | 上限・下限なしで積分を取得します |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-str-str-mathlimitlocations) | 積分を取得します |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-str-str) | 積分を取得します |
| [`group(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/group/#) | この要素を下側の波括弧でグループ化します |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/group/#char-mathtopbotpositions-mathtopbotpositions) | この要素を下側の波括弧やその他のグルーピング文字でグループ化します |
| [`to_border_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/to_border_box/#) | この要素をボーダーボックスに配置します |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | この要素をボーダーボックスに配置します |
| [`to_math_array(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/to_math_array/#) | 縦方向の配列に配置します |
| [`accent(self, accent_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/accent/#char) | アクセント記号（この要素の上部に付く文字）を設定します |
| [`overbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/overbar/#) | この要素の上部にバーを設定します |
| [`underbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/underbar/#) | この要素の下部にバーを設定します |
| [`to_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/to_box/#) | この要素を非表示ボックス（論理的グループ）に配置します <br/>            これは、数式の構成要素やその他の数式テキストのインスタンスをグループ化するために使用されます。<br/>            ボックス化されたオブジェクトは（例として）整列ポイントの有無にかかわらず演算子エミュレータとして機能したり、<br/>            改行ポイントとして機能したり、内部で改行を許可しないようにグループ化されたりします。 |
| [`get_children(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent/get_children/#) | 子要素を取得します |

### 参照
* クラス [`MathAccent`](/slides/python-net/ja/aspose.slides.mathtext/mathaccent)
* クラス [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)