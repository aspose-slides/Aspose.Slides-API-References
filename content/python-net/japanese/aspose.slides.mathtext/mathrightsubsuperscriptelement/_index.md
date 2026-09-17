---
title: MathRightSubSuperscriptElement class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/
---
## MathRightSubSuperscriptElement クラス

ベースと、その右側に配置された下付きと上付きから構成される Sub-Superscript オブジェクトを指定します。

**継承:**[`MathRightSubSuperscriptElement`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement) → [`BaseScript`](/slides/python-net/ja/aspose.slides.mathtext/basescript) → [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)

MathRightSubSuperscriptElement 型は以下のメンバーを公開します。

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self, base_arg, sub_script, super_script)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/__init__/#imathelement-imathelement-imathelement) | MathRightSubSuperscriptElement クラスの新しいインスタンスを初期化します。 |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`base`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/base/) | ベース引数 |
| [`subscript`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/subscript/) | 下付き引数 |
| [`superscript`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/superscript/) | 上付き引数 |
| [`align_scripts`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/align_scripts/) | 下付き/上付きの配置を指定します。 <br/>            true の場合、下付きと上付きは水平方向に揃えられます。<br/>            false の場合、ベースの形状に合わせてカーニングされます。<br/>            デフォルト値は false です。 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/join/#imathelement) | 数式要素を結合し、数式ブロックを作成します |
| [`join(self, math_text)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/join/#str) | 数式テキストを結合し、数式ブロックを作成します |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/divide/#imathelement) | この分子と指定された分母で分数を作成します |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/divide/#str) | この分子と指定された分母で分数を作成します |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/divide/#imathelement-mathfractiontypes) | 指定されたタイプの分数を、この分子と指定された分母で作成します |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/divide/#str-mathfractiontypes) | 指定されたタイプの分数を、この分子と指定された分母で作成します |
| [`enclose(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/enclose/#) | 数式要素をかっこで囲みます |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/enclose/#char-char) | 数式要素をかっこや他の文字など、指定された文字で枠囲みします |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/function/#imathelement) | このインスタンスを関数名として、引数の関数を取得します |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/function/#str) | このインスタンスを関数名として、引数の関数を取得します |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#imathelement) | このインスタンスを引数として、指定された関数を取得します |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#str) | このインスタンスを引数として、指定された関数を取得します |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#mathfunctionsofoneargument) | このインスタンスを引数として、指定された関数を取得します |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | このインスタンスを引数として、指定された関数と追加の引数を取得します |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-str) | このインスタンスを引数として、指定された関数と追加の引数を取得します |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_subscript/#imathelement) | 下付き文字を作成します |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_subscript/#str) | 下付き文字を作成します |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_superscript/#imathelement) | 上付き文字を作成します |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_superscript/#str) | 上付き文字を作成します |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_sub_superscript_on_the_right/#imathelement-imathelement) | 右側に下付きと上付きを作成します |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_sub_superscript_on_the_right/#str-str) | 右側に下付きと上付きを作成します |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_sub_superscript_on_the_left/#imathelement-imathelement) | 左側に下付きと上付きを作成します |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_sub_superscript_on_the_left/#str-str) | 左側に下付きと上付きを作成します |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/radical/#imathelement) | 指定された引数から与えられた次数の数学的根を指定します。 |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/radical/#str) | 指定された引数から与えられた次数の数学的根を指定します。 |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_upper_limit/#imathelement) | 上限を取得します |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_upper_limit/#str) | 上限を取得します |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_lower_limit/#imathelement) | 下限を取得します |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_lower_limit/#str) | 下限を取得します |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/nary/#mathnaryoperatortypes-imathelement-imathelement) | N項演算子を作成します |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/nary/#mathnaryoperatortypes-str-str) | N項演算子を作成します |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 積分を取得します |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes-imathelement-imathelement) | 積分を取得します |
| [`integral(self, integral_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes) | 上限・下限なしで積分を取得します |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes-str-str-mathlimitlocations) | 積分を取得します |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes-str-str) | 積分を取得します |
| [`group(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/group/#) | 下側の波括弧を使用してこの要素をグループに配置します |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/group/#char-mathtopbotpositions-mathtopbotpositions) | 下側の波括弧やその他のグルーピング文字を使用してこの要素をグループに配置します |
| [`to_border_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/to_border_box/#) | この要素をボーダーボックスに配置します |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | この要素をボーダーボックスに配置します |
| [`to_math_array(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/to_math_array/#) | 縦方向の配列に配置します |
| [`accent(self, accent_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/accent/#char) | この要素の上部にアクセント記号（文字）を設定します |
| [`overbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/overbar/#) | この要素の上部にバーを設定します |
| [`underbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/underbar/#) | この要素の下部にバーを設定します |
| [`to_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/to_box/#) | この要素を非表示ボックス（論理的グルーピング）に配置します <br/>            これは方程式の構成要素やその他の数式テキストのインスタンスをグループ化するために使用されます。<br/>            ボックス化されたオブジェクトは（例として）整列ポイントの有無にかかわらず演算子エミュレータとして機能したり、<br/>            改行ポイントとして機能したり、内部で改行を許可しないようにグループ化されたりします。 |
| [`get_children(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_children/#) | 子要素を取得します |

### 参照
* クラス [`BaseScript`](/slides/python-net/ja/aspose.slides.mathtext/basescript)
* クラス [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)
* クラス [`MathRightSubSuperscriptElement`](/slides/python-net/ja/aspose.slides.mathtext/mathrightsubsuperscriptelement)
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)