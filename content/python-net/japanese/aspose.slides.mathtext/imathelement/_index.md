---
title: IMathElement class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/imathelement/
---
## IMathElement クラス

Base interface of any mathematical element: 
            分数、数学テキスト、関数、複数要素の式など

IMathElement 型は次のメンバーを公開します:

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/join/#imathelement) | 数学要素を結合して数学ブロックを形成します |
| [`join(self, math_text)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/join/#str) | 数学テキストを結合して数学ブロックを形成します |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/divide/#imathelement) | この分子と指定された分母で分数を作成します |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/divide/#str) | この分子と指定された分母で分数を作成します |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/divide/#imathelement-mathfractiontypes) | この分子と指定された分母で、指定されたタイプの分数を作成します |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/divide/#str-mathfractiontypes) | この分子と指定された分母で、指定されたタイプの分数を作成します |
| [`enclose(self)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/enclose/#) | 数学要素を括弧で囲みます |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/enclose/#char-char) | この要素を括弧などの指定文字で枠付けします |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/function/#imathelement) | このインスタンスを関数名として、引数の関数を取ります |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/function/#str) | このインスタンスを関数名として、引数の関数を取ります |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/as_argument_of_function/#imathelement) | このインスタンスを引数として、指定された関数を取ります |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/as_argument_of_function/#str) | このインスタンスを引数として、指定された関数を取ります |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/as_argument_of_function/#mathfunctionsofoneargument) | このインスタンスを引数として、指定された関数を取ります |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | このインスタンスを引数として、指定された関数と追加の引数を取ります |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/as_argument_of_function/#mathfunctionsoftwoarguments-str) | このインスタンスを引数として、指定された関数と追加の引数を取ります |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/set_subscript/#imathelement) | 下付き文字を作成します |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/set_subscript/#str) | 下付き文字を作成します |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/set_superscript/#imathelement) | 上付き文字を作成します |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/set_superscript/#str) | 上付き文字を作成します |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/set_sub_superscript_on_the_right/#imathelement-imathelement) | 右側に下付き文字と上付き文字を作成します |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/set_sub_superscript_on_the_right/#str-str) | 右側に下付き文字と上付き文字を作成します |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/set_sub_superscript_on_the_left/#imathelement-imathelement) | 左側に下付き文字と上付き文字を作成します |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/set_sub_superscript_on_the_left/#str-str) | 左側に下付き文字と上付き文字を作成します |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/radical/#imathelement) | 指定された引数から、与えられた次数の数学的ルートを指定します。 |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/radical/#str) | 指定された引数から、与えられた次数の数学的ルートを指定します。 |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/set_upper_limit/#imathelement) | 上限を取ります |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/set_upper_limit/#str) | 上限を取ります |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/set_lower_limit/#imathelement) | 下限を取ります |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/set_lower_limit/#str) | 下限を取ります |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/nary/#mathnaryoperatortypes-imathelement-imathelement) | N元演算子を作成します |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/nary/#mathnaryoperatortypes-str-str) | N元演算子を作成します |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 積分を取ります |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes-imathelement-imathelement) | 積分を取ります |
| [`integral(self, integral_type)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes) | 限界なしで積分を取ります |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes-str-str-mathlimitlocations) | 積分を取ります |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes-str-str) | 積分を取ります |
| [`group(self)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/group/#) | 下部の波括弧を使用して、この要素をグループに配置します |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/group/#char-mathtopbotpositions-mathtopbotpositions) | 下部の波括弧などのグループ文字を使用して、この要素をグループに配置します |
| [`to_border_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/to_border_box/#) | この要素をボーダーボックスに配置します |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | この要素をボーダーボックスに配置します |
| [`get_children(self)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/get_children/#) | 子要素を取得します |
| [`to_math_array(self)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/to_math_array/#) | 縦配列に配置します |
| [`accent(self, accent_character)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/accent/#char) | アクセント記号（要素の上にある文字）を設定します |
| [`overbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/overbar/#) | 要素の上部にバーを設定します |
| [`underbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/underbar/#) | 要素の下部にバーを設定します |
| [`to_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/imathelement/to_box/#) | この要素を非可視ボックス（論理的グループ）に配置します <br/>            これは方程式の構成要素や他の数学テキストのインスタンスをグループ化するために使用されます。<br/>            ボックス化されたオブジェクトは（例として）整列ポイントの有無にかかわらず演算子エミュレータとして機能したり、<br/>            改行ポイントとして使用されたり、内部で改行を許さないようにグループ化されたりします。 |

### 参照
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)