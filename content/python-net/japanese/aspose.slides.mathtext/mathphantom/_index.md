---
title: MathPhantom class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/mathphantom/
---
## MathPhantom クラス

ファントムの数学オブジェクト (<m:phant>) を表し、子要素のレイアウトに影響を与えますが、必ずしも表示されるわけではありません。ファントムはベース式を非表示にしながら、幅、高さ、または深さを保持して数式の配置や空間確保を行うことができます。表示と幾何構造の動作は Show、ZeroWid、ZeroAsc、ZeroDesc、Transp といったプロパティで制御されます。

**継承:**[`MathPhantom`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom) → [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)

MathPhantom 型は以下のメンバーを公開します。

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/__init__/#imathelement) | [`MathPhantom`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom) クラスの新しいインスタンスを初期化します <br/>            指定されたベース数学要素を使用して。 |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`base`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/base/) | ベース引数 |
| [`show`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/show/) | ベース要素が表示されるかどうかを示す値を取得または設定します。 |
| [`zero_width`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/zero_width/) | ベース要素の幅が <br/>            ゼロとして扱われるかどうかを示す値を取得または設定します。 |
| [`zero_asc`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/zero_asc/) | ベース要素の上昇 (ベースライン上の高さ) が <br/>            ゼロとして扱われるかどうかを示す値を取得または設定します。 |
| [`zero_desc`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/zero_desc/) | ベース要素の下降 (ベースライン下の深さ) が <br/>            ゼロとして扱われるかどうかを示す値を取得または設定します。 |
| [`transp`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/transp/) | クラスベースの間隔ルールに対して、ファントムが透明であるかどうかを示す値を取得または設定します <br/>            |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/join/#imathelement) | 数学要素を結合して数学ブロックを形成します。 |
| [`join(self, math_text)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/join/#str) | 数学テキストを結合して数学ブロックを形成します。 |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/divide/#imathelement) | この分子と指定された分母で分数を作成します。 |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/divide/#str) | この分子と指定された分母で分数を作成します。 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/divide/#imathelement-mathfractiontypes) | この分子と指定された分母を使用して、指定されたタイプの分数を作成します。 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/divide/#str-mathfractiontypes) | この分子と指定された分母を使用して、指定されたタイプの分数を作成します。 |
| [`enclose(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/enclose/#) | 数学要素を丸括弧で囲みます。 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/enclose/#char-char) | 数学要素を括弧や他の文字など、指定された文字で枠囲みします。 |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/function/#imathelement) | このインスタンスを関数名として、引数の関数を取得します。 |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/function/#str) | このインスタンスを関数名として、引数の関数を取得します。 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/as_argument_of_function/#imathelement) | このインスタンスを引数として、指定された関数を取得します。 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/as_argument_of_function/#str) | このインスタンスを引数として、指定された関数を取得します。 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsofoneargument) | このインスタンスを引数として、指定された関数を取得します。 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | このインスタンスを引数として、指定された関数と追加の引数を取得します。 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-str) | このインスタンスを引数として、指定された関数と追加の引数を取得します。 |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/set_subscript/#imathelement) | 下付き文字を作成します。 |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/set_subscript/#str) | 下付き文字を作成します。 |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/set_superscript/#imathelement) | 上付き文字を作成します。 |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/set_superscript/#str) | 上付き文字を作成します。 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#imathelement-imathelement) | 右側に下付き文字と上付き文字を作成します。 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#str-str) | 右側に下付き文字と上付き文字を作成します。 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#imathelement-imathelement) | 左側に下付き文字と上付き文字を作成します。 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#str-str) | 左側に下付き文字と上付き文字を作成します。 |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/radical/#imathelement) | 指定された引数から、与えられた次数の数学的ルートを指定します。 |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/radical/#str) | 指定された引数から、与えられた次数の数学的ルートを指定します。 |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/set_upper_limit/#imathelement) | 上限を取得します。 |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/set_upper_limit/#str) | 上限を取得します。 |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/set_lower_limit/#imathelement) | 下限を取得します。 |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/set_lower_limit/#str) | 下限を取得します。 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-imathelement-imathelement) | N項演算子を作成します。 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-str-str) | N項演算子を作成します。 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 積分を取得します。 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement) | 積分を取得します。 |
| [`integral(self, integral_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes) | 上限・下限なしの積分を取得します。 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str-mathlimitlocations) | 積分を取得します。 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str) | 積分を取得します。 |
| [`group(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/group/#) | この要素を下側の波かっこでグループ化します。 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/group/#char-mathtopbotpositions-mathtopbotpositions) | この要素を下側の波かっこやその他のグルーピング文字でグループに配置します。 |
| [`to_border_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/to_border_box/#) | この要素を枠箱に配置します。 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | この要素を枠箱に配置します。 |
| [`to_math_array(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/to_math_array/#) | 縦方向の配列に配置します。 |
| [`accent(self, accent_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/accent/#char) | アクセントマーク（この要素の上部の文字）を設定します。 |
| [`overbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/overbar/#) | この要素の上部にバーを設定します。 |
| [`underbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/underbar/#) | この要素の下部にバーを設定します。 |
| [`to_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/to_box/#) | この要素を非表示ボックス（論理的なグルーピング）に配置します <br/>            これは数式や他の数学テキストの構成要素をグループ化するために使用されます。<br/>            例えば、ボックス化されたオブジェクトは整列点の有無にかかわらず演算子エミュレータとして機能したり、 <br/>            改行ポイントとして機能したり、内部で改行が許可されないようにグループ化したりできます。 |
| [`get_children(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom/get_children/#) | 子要素を取得します。 |

### 参照
* クラス [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)
* クラス [`MathPhantom`](/slides/python-net/ja/aspose.slides.mathtext/mathphantom)
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)