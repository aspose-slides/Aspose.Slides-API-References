---
title: MathFunction class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/mathfunction/
---
## MathFunction クラス

引数の関数を指定します。

**継承:**[`MathFunction`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction) → [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)

MathFunction型は以下のメンバーを公開します。

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self, func_name, base_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/__init__/#imathelement-imathelement) | MathFunction クラスの新しいインスタンスを初期化します。 |
| [`__init__(self, func_name, base_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/__init__/#str-imathelement) | MathFunction クラスの新しいインスタンスを初期化します。 |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`name`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/name/) | 関数名<br/>            例: 関数名は sin や cos です |
| [`base`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/base/) | 関数の引数 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/join/#imathelement) | 数学要素を結合し、数学ブロックを作成します。 |
| [`join(self, math_text)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/join/#str) | 数学テキストを結合し、数学ブロックを作成します。 |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/divide/#imathelement) | この分子と指定された分母で分数を作成します。 |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/divide/#str) | この分子と指定された分母で分数を作成します。 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/divide/#imathelement-mathfractiontypes) | この分子と指定された分母を使用して、指定されたタイプの分数を作成します。 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/divide/#str-mathfractiontypes) | この分子と指定された分母を使用して、指定されたタイプの分数を作成します。 |
| [`enclose(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/enclose/#) | 数学要素を括弧で囲みます。 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/enclose/#char-char) | 数学要素を括弧や他の文字など、指定された文字で囲みます。 |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/function/#imathelement) | このインスタンスを関数名として、引数の関数を取ります。 |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/function/#str) | このインスタンスを関数名として、引数の関数を取ります。 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/as_argument_of_function/#imathelement) | このインスタンスを引数として、指定された関数を取ります。 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/as_argument_of_function/#str) | このインスタンスを引数として、指定された関数を取ります。 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/as_argument_of_function/#mathfunctionsofoneargument) | このインスタンスを引数として、指定された関数を取ります。 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | このインスタンスを引数として、指定された関数と追加の引数を取ります。 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/as_argument_of_function/#mathfunctionsoftwoarguments-str) | このインスタンスを引数として、指定された関数と追加の引数を取ります。 |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/set_subscript/#imathelement) | 下付き文字を作成します。 |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/set_subscript/#str) | 下付き文字を作成します。 |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/set_superscript/#imathelement) | 上付き文字を作成します。 |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/set_superscript/#str) | 上付き文字を作成します。 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_right/#imathelement-imathelement) | 右側に下付き文字と上付き文字を作成します。 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_right/#str-str) | 右側に下付き文字と上付き文字を作成します。 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_left/#imathelement-imathelement) | 左側に下付き文字と上付き文字を作成します。 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_left/#str-str) | 左側に下付き文字と上付き文字を作成します。 |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/radical/#imathelement) | 指定された引数から、与えられた次数の数学的根を指定します。 |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/radical/#str) | 指定された引数から、与えられた次数の数学的根を指定します。 |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/set_upper_limit/#imathelement) | 上限を取ります。 |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/set_upper_limit/#str) | 上限を取ります。 |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/set_lower_limit/#imathelement) | 下限を取ります。 |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/set_lower_limit/#str) | 下限を取ります。 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/nary/#mathnaryoperatortypes-imathelement-imathelement) | N元演算子を作成します。 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/nary/#mathnaryoperatortypes-str-str) | N元演算子を作成します。 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 積分を取ります。 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-imathelement-imathelement) | 積分を取ります。 |
| [`integral(self, integral_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes) | 制限なしで積分を取ります。 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-str-str-mathlimitlocations) | 積分を取ります。 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-str-str) | 積分を取ります。 |
| [`group(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/group/#) | 下の波括弧を使用してこの要素をグループに配置します。 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/group/#char-mathtopbotpositions-mathtopbotpositions) | 下の波括弧や他のグルーピング文字を使用してこの要素をグループに配置します。 |
| [`to_border_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/to_border_box/#) | この要素をボーダーボックスに配置します。 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | この要素をボーダーボックスに配置します。 |
| [`to_math_array(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/to_math_array/#) | 縦配列に配置します。 |
| [`accent(self, accent_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/accent/#char) | アクセント記号（この要素の上にある文字）を設定します。 |
| [`overbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/overbar/#) | この要素の上にバーを設定します。 |
| [`underbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/underbar/#) | この要素の下にバーを設定します。 |
| [`to_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/to_box/#) | この要素を非表示のボックス（論理的なグルーピング）に配置します <br/>            これは方程式や他の数学テキストの構成要素をグループ化するために使用されます。<br/>            ボックス化されたオブジェクトは（例として）整列ポイントの有無にかかわらず演算子エミュレータとして機能したり、 <br/>            改行ポイントとして機能したり、内部で改行を許可しないようにグループ化されたりします。 |
| [`get_children(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction/get_children/#) | 子要素を取得します。 |

### 参照
* クラス [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)
* クラス [`MathFunction`](/slides/python-net/ja/aspose.slides.mathtext/mathfunction)
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)