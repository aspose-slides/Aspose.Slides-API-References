---
title: MathBorderBox class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/mathborderbox/
---
## MathBorderBox クラス

Draws a rectangular or some other border around the IMathElement.

**継承:**[`MathBorderBox`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox) → [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)

The MathBorderBox type exposes the following members:

## コンストラクタ

| Constructor | Description |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/__init__/#imathelement) | 矩形の枠線で MathBorderBox 要素を作成します |
| [`__init__(self, element, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/__init__/#imathelement-bool-bool-bool-bool-bool-bool-bool-bool) | MathBorderBox 要素を作成します |

## プロパティ

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/base/) | 基底引数 |
| [`hide_top`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/hide_top/) | 上端を非表示にする (default is false) - specifies the hidden or shown state of the top edge of border box. |
| [`hide_bottom`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/hide_bottom/) | 下端を非表示にする (default is false) - specifies the hidden or shown state of the bottom edge of border box. |
| [`hide_left`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/hide_left/) | 左端を非表示にする (default is false) - specifies the hidden or shown state of the left edge of border box. |
| [`hide_right`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/hide_right/) | 右端を非表示にする (default is false) - specifies the hidden or shown state of the right edge of border box. |
| [`strikethrough_horizontal`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/strikethrough_horizontal/) | 水平取り消し線 (default is false) - specifies the hidden or shown state of a strikethrough horizontal line. |
| [`strikethrough_vertical`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/strikethrough_vertical/) | 垂直取り消し線 (default is false) - specifies the hidden or shown state of a strikethrough vertical line. |
| [`strikethrough_bottom_left_to_top_right`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/strikethrough_bottom_left_to_top_right/) | 左下から右上への取り消し線 (default is false).<br/>Specifies the hidden or shown state of a strikethrough diagonal line from the bottom-left corner to the top-right corner of border box. |
| [`strikethrough_top_left_to_bottom_right`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/strikethrough_top_left_to_bottom_right/) | 左上から右下への取り消し線 (default is false).<br/>Specifies the hidden or shown state of a strikethrough diagonal line from the top-left corner to the bottom-right corner of border box. |

## メソッド

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/join/#imathelement) | 数式要素を結合して数式ブロックを形成します |
| [`join(self, math_text)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/join/#str) | 数式テキストを結合して数式ブロックを形成します |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/divide/#imathelement) | この分子と指定された分母で分数を作成します |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/divide/#str) | この分子と指定された分母で分数を作成します |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/divide/#imathelement-mathfractiontypes) | 指定されたタイプの分数を、この分子と指定された分母で作成します |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/divide/#str-mathfractiontypes) | 指定されたタイプの分数を、この分子と指定された分母で作成します |
| [`enclose(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/enclose/#) | 数式要素を括弧で囲みます |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/enclose/#char-char) | 数式要素を括弧やその他の文字など、指定された文字でフレーミングして囲みます |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/function/#imathelement) | このインスタンスを関数名として、引数の関数を取ります |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/function/#str) | このインスタンスを関数名として、引数の関数を取ります |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#imathelement) | このインスタンスを引数として、指定された関数を取ります |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#str) | このインスタンスを引数として、指定された関数を取ります |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsofoneargument) | このインスタンスを引数として、指定された関数を取ります |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | このインスタンスを引数として、指定された関数と追加の引数を取ります |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | このインスタンスを引数として、指定された関数と追加の引数を取ります |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/set_subscript/#imathelement) | 下付き文字を作成します |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/set_subscript/#str) | 下付き文字を作成します |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/set_superscript/#imathelement) | 上付き文字を作成します |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/set_superscript/#str) | 上付き文字を作成します |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | 右側に下付き文字と上付き文字を作成します |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_right/#str-str) | 右側に下付き文字と上付き文字を作成します |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | 左側に下付き文字と上付き文字を作成します |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_left/#str-str) | 左側に下付き文字と上付き文字を作成します |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/radical/#imathelement) | 指定された引数から、指定された次数の数学的根を指定します |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/radical/#str) | 指定された引数から、指定された次数の数学的根を指定します |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/set_upper_limit/#imathelement) | 上限を取ります |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/set_upper_limit/#str) | 上限を取ります |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/set_lower_limit/#imathelement) | 下限を取ります |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/set_lower_limit/#str) | 下限を取ります |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | N元演算子を作成します |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/nary/#mathnaryoperatortypes-str-str) | N元演算子を作成します |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 積分を取ります |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-imathelement-imathelement) | 積分を取ります |
| [`integral(self, integral_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes) | 限界なしで積分を取ります |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | 積分を取ります |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-str-str) | 積分を取ります |
| [`group(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/group/#) | 下部の波括弧を使用してこの要素をグループに配置します |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/group/#char-mathtopbotpositions-mathtopbotpositions) | 下部の波括弧やその他のグルーピング文字を使用してこの要素をグループに配置します |
| [`to_border_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/to_border_box/#) | この要素をボーダーボックスに配置します |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | この要素をボーダーボックスに配置します |
| [`to_math_array(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/to_math_array/#) | 縦配列に配置します |
| [`accent(self, accent_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/accent/#char) | アクセント記号を設定します（この要素の上部の文字） |
| [`overbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/overbar/#) | この要素の上部にバーを設定します |
| [`underbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/underbar/#) | この要素の下部にバーを設定します |
| [`to_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/to_box/#) | この要素を非表示ボックス（論理的グルーピング）に配置します <br/>            これは方程式や他の数式テキストの構成要素をグループ化するために使用されます。<br/>            ボックス化されたオブジェクトは、（例えば）整列ポイントの有無にかかわらず演算子エミュレータとして機能したり、<br/>            改行ポイントとして機能したり、内部で改行を許可しないようにグループ化したりできます。 |
| [`get_children(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox/get_children/#) | 子要素を取得します |

### 参照
* クラス [`MathBorderBox`](/slides/python-net/ja/aspose.slides.mathtext/mathborderbox)
* クラス [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)