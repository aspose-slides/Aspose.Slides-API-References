---
title: BaseScript class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/basescript/
---
## BaseScript クラス

数学スクリプト

**継承:**[`BaseScript`](/slides/python-net/ja/aspose.slides.mathtext/basescript) → [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)

BaseScript 型は次のメンバーを公開します:

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`base`](/slides/python-net/ja/aspose.slides.mathtext/basescript/base/) | 基本引数 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/join/#imathelement) | 数学要素を結合し、数学ブロックを作成します |
| [`join(self, math_text)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/join/#str) | 数学テキストを結合し、数学ブロックを作成します |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/divide/#imathelement) | この分子と指定された分母で分数を作ります |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/divide/#str) | この分子と指定された分母で分数を作ります |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/divide/#imathelement-mathfractiontypes) | この分子と指定された分母で、指定されたタイプの分数を作ります |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/divide/#str-mathfractiontypes) | この分子と指定された分母で、指定されたタイプの分数を作ります |
| [`enclose(self)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/enclose/#) | 数学要素を丸括弧で囲みます |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/enclose/#char-char) | 数学要素を括弧やその他の文字など、指定された文字で囲みます |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/function/#imathelement) | このインスタンスを関数名として、引数の関数を取得します |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/function/#str) | このインスタンスを関数名として、引数の関数を取得します |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/as_argument_of_function/#imathelement) | このインスタンスを引数として、指定された関数を取得します |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/as_argument_of_function/#str) | このインスタンスを引数として、指定された関数を取得します |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/as_argument_of_function/#mathfunctionsofoneargument) | このインスタンスを引数として、指定された関数を取得します |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | このインスタンスを引数として、指定された関数と追加の引数を取得します |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/as_argument_of_function/#mathfunctionsoftwoarguments-str) | このインスタンスを引数として、指定された関数と追加の引数を取得します |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/set_subscript/#imathelement) | 下付き文字を作ります |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/set_subscript/#str) | 下付き文字を作ります |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/set_superscript/#imathelement) | 上付き文字を作ります |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/set_superscript/#str) | 上付き文字を作ります |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/set_sub_superscript_on_the_right/#imathelement-imathelement) | 右側に下付き文字と上付き文字を作ります |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/set_sub_superscript_on_the_right/#str-str) | 右側に下付き文字と上付き文字を作ります |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/set_sub_superscript_on_the_left/#imathelement-imathelement) | 左側に下付き文字と上付き文字を作ります |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/set_sub_superscript_on_the_left/#str-str) | 左側に下付き文字と上付き文字を作ります |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/radical/#imathelement) | 指定された引数から、指定された次数の根号を指定します |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/radical/#str) | 指定された引数から、指定された次数の根号を指定します |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/set_upper_limit/#imathelement) | 上限を取得します |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/set_upper_limit/#str) | 上限を取得します |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/set_lower_limit/#imathelement) | 下限を取得します |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/set_lower_limit/#str) | 下限を取得します |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/nary/#mathnaryoperatortypes-imathelement-imathelement) | N元演算子を作ります |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/nary/#mathnaryoperatortypes-str-str) | N元演算子を作ります |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 積分を取得します |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/integral/#mathintegraltypes-imathelement-imathelement) | 積分を取得します |
| [`integral(self, integral_type)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/integral/#mathintegraltypes) | 限界なしの積分を取得します |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/integral/#mathintegraltypes-str-str-mathlimitlocations) | 積分を取得します |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/integral/#mathintegraltypes-str-str) | 積分を取得します |
| [`group(self)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/group/#) | この要素を下側の波かっこでグループに配置します |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/group/#char-mathtopbotpositions-mathtopbotpositions) | この要素を下側の波かっこやその他の文字でグループに配置します |
| [`to_border_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/to_border_box/#) | この要素を枠ボックスに配置します |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | この要素を枠ボックスに配置します |
| [`to_math_array(self)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/to_math_array/#) | 縦配列に配置します |
| [`accent(self, accent_character)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/accent/#char) | アクセント記号（要素の上にある文字）を設定します |
| [`overbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/overbar/#) | この要素の上部にバーを設定します |
| [`underbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/underbar/#) | この要素の下部にバーを設定します |
| [`to_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/to_box/#) | この要素を非可視ボックス（論理的グループ化）に配置します<br/>            これは方程式やその他の数学テキストの構成要素をグループ化するために使用されます。<br/>            ボックス化されたオブジェクトは、例えば、整列ポイントの有無にかかわらず演算子エミュレータとして機能したり、<br/>            改行ポイントとして機能したり、または内部で改行を許可しないようにグループ化されたりします。 |
| [`get_children(self)`](/slides/python-net/ja/aspose.slides.mathtext/basescript/get_children/#) |  |

### 参照
* クラス [`BaseScript`](/slides/python-net/ja/aspose.slides.mathtext/basescript)
* クラス [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)