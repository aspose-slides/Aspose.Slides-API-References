---
title: MathBar class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/mathbar/
---
## MathBar クラス

ベース引数と上バーまたは下バーで構成されるバー関数を指定します。

**継承:**[`MathBar`](/slides/python-net/ja/aspose.slides.mathtext/mathbar) → [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)

MathBar 型は以下のメンバーを公開します。

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/__init__/#imathelement) | 上バー（上位置）で MathBar を初期化します。 |
| [`__init__(self, element, position)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/__init__/#imathelement-mathtopbotpositions) | 指定された位置で MathBar を初期化します。 |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`base`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/base/) | ベース引数 |
| [`position`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/position/) | バーラインの位置。<br/>            デフォルト: 上 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/join/#imathelement) | 数学要素を結合し、数学ブロックを形成します。 |
| [`join(self, math_text)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/join/#str) | 数学テキストを結合し、数学ブロックを形成します。 |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/divide/#imathelement) | この分子と指定された分母で分数を作成します。 |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/divide/#str) | この分子と指定された分母で分数を作成します。 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/divide/#imathelement-mathfractiontypes) | この分子と指定された分母で、指定されたタイプの分数を作成します。 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/divide/#str-mathfractiontypes) | この分子と指定された分母で、指定されたタイプの分数を作成します。 |
| [`enclose(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/enclose/#) | 数学要素を括弧で囲みます。 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/enclose/#char-char) | 数学要素を括弧やその他の文字など、指定された文字で囲みます。 |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/function/#imathelement) | このインスタンスを関数名として、引数の関数を取得します。 |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/function/#str) | このインスタンスを関数名として、引数の関数を取得します。 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/as_argument_of_function/#imathelement) | このインスタンスを引数として、指定された関数を取得します。 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/as_argument_of_function/#str) | このインスタンスを引数として、指定された関数を取得します。 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsofoneargument) | このインスタンスを引数として、指定された関数を取得します。 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | このインスタンスを引数として、指定された関数と追加の引数を取得します。 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsoftwoarguments-str) | このインスタンスを引数として、指定された関数と追加の引数を取得します。 |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/set_subscript/#imathelement) | 下付き文字を作成します。 |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/set_subscript/#str) | 下付き文字を作成します。 |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/set_superscript/#imathelement) | 上付き文字を作成します。 |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/set_superscript/#str) | 上付き文字を作成します。 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_right/#imathelement-imathelement) | 右側に下付き文字と上付き文字を作成します。 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_right/#str-str) | 右側に下付き文字と上付き文字を作成します。 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_left/#imathelement-imathelement) | 左側に下付き文字と上付き文字を作成します。 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_left/#str-str) | 左側に下付き文字と上付き文字を作成します。 |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/radical/#imathelement) | 指定された引数から、指定された次数の数学的根を指定します。 |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/radical/#str) | 指定された引数から、指定された次数の数学的根を指定します。 |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/set_upper_limit/#imathelement) | 上限を取得します。 |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/set_upper_limit/#str) | 上限を取得します。 |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/set_lower_limit/#imathelement) | 下限を取得します。 |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/set_lower_limit/#str) | 下限を取得します。 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/nary/#mathnaryoperatortypes-imathelement-imathelement) | N元演算子を作成します。 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/nary/#mathnaryoperatortypes-str-str) | N元演算子を作成します。 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 積分を取得します。 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-imathelement-imathelement) | 積分を取得します。 |
| [`integral(self, integral_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes) | 制限なしで積分を取得します。 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-str-str-mathlimitlocations) | 積分を取得します。 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-str-str) | 積分を取得します。 |
| [`group(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/group/#) | 下部の波括弧を使用してこの要素をグループ化します。 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/group/#char-mathtopbotpositions-mathtopbotpositions) | 下部の波括弧やその他のグループ文字を使用してこの要素をグループ化します。 |
| [`to_border_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/to_border_box/#) | この要素をボーダーボックスに配置します。 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | この要素をボーダーボックスに配置します。 |
| [`to_math_array(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/to_math_array/#) | 縦配列に配置します。 |
| [`accent(self, accent_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/accent/#char) | アクセント記号（この要素の上部にある文字）を設定します。 |
| [`overbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/overbar/#) | この要素の上部にバーを設定します。 |
| [`underbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/underbar/#) | この要素の下部にバーを設定します。 |
| [`to_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/to_box/#) | この要素を非可視ボックス（論理的グループ）に配置します。<br/>            これは方程式の構成要素やその他の数学テキストをグループ化するために使用されます。<br/>            ボックス化されたオブジェクトは、（例として）配置点の有無にかかわらず演算子エミュレータとして機能したり、<br/>            改行ポイントとして機能したり、内部で改行を許可しないようにグループ化されたりします。 |
| [`get_children(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathbar/get_children/#) | 子要素を取得します。 |

### 参照
* クラス [`MathBar`](/slides/python-net/ja/aspose.slides.mathtext/mathbar)
* クラス [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)