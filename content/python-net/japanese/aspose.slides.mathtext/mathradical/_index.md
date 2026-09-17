---
title: MathRadical class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/mathradical/
---
## MathRadical クラス

基底とオプションの次数からなる根号関数を指定します。
            例: √𝑥 の根号オブジェクトです。

**継承:**[`MathRadical`](/slides/python-net/ja/aspose.slides.mathtext/mathradical) → [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)

MathRadical 型は以下のメンバーを公開します：

## コンストラクタ

| Constructor | Description |
| :- | :- |
| [`__init__(self, base_argument, degree_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/__init__/#imathelement-imathelement) | MathRadical クラスの新しいインスタンスを初期化します。 |

## プロパティ

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/base/) | 基底引数 |
| [`degree`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/degree/) | 次数引数 |
| [`hide_degree`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/hide_degree/) | 次数を非表示にする<br/>            true の場合、次数は表示されません（例: √𝑥） |

## メソッド

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/join/#imathelement) | 数学要素を結合して数学ブロックを形成します |
| [`join(self, math_text)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/join/#str) | 数学テキストを結合して数学ブロックを形成します |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/divide/#imathelement) | この分子と指定された分母で分数を作成します |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/divide/#str) | この分子と指定された分母で分数を作成します |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/divide/#imathelement-mathfractiontypes) | 指定された種類の分数を、この分子と指定された分母で作成します |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/divide/#str-mathfractiontypes) | 指定された種類の分数を、この分子と指定された分母で作成します |
| [`enclose(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/enclose/#) | 数学要素を括弧で囲みます |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/enclose/#char-char) | 数学要素を括弧や他の指定文字で囲みます |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/function/#imathelement) | このインスタンスを関数名として、引数の関数を取得します |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/function/#str) | このインスタンスを関数名として、引数の関数を取得します |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/as_argument_of_function/#imathelement) | このインスタンスを引数として、指定された関数を取得します |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/as_argument_of_function/#str) | このインスタンスを引数として、指定された関数を取得します |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/as_argument_of_function/#mathfunctionsofoneargument) | このインスタンスを引数として、指定された関数を取得します |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | このインスタンスを引数として、指定された関数と追加の引数を取得します |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/as_argument_of_function/#mathfunctionsoftwoarguments-str) | このインスタンスを引数として、指定された関数と追加の引数を取得します |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/set_subscript/#imathelement) | 下付文字を作成します |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/set_subscript/#str) | 下付文字を作成します |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/set_superscript/#imathelement) | 上付文字を作成します |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/set_superscript/#str) | 上付文字を作成します |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/set_sub_superscript_on_the_right/#imathelement-imathelement) | 右側に下付文字と上付文字を作成します |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/set_sub_superscript_on_the_right/#str-str) | 右側に下付文字と上付文字を作成します |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/set_sub_superscript_on_the_left/#imathelement-imathelement) | 左側に下付文字と上付文字を作成します |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/set_sub_superscript_on_the_left/#str-str) | 左側に下付文字と上付文字を作成します |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/radical/#imathelement) | 指定された引数から与えられた次数の数学的ルートを指定します。 |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/radical/#str) | 指定された引数から与えられた次数の数学的ルートを指定します。 |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/set_upper_limit/#imathelement) | 上限を取得します |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/set_upper_limit/#str) | 上限を取得します |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/set_lower_limit/#imathelement) | 下限を取得します |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/set_lower_limit/#str) | 下限を取得します |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/nary/#mathnaryoperatortypes-imathelement-imathelement) | N元演算子を作成します |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/nary/#mathnaryoperatortypes-str-str) | N元演算子を作成します |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 積分を取得します |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/integral/#mathintegraltypes-imathelement-imathelement) | 積分を取得します |
| [`integral(self, integral_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/integral/#mathintegraltypes) | 上限・下限なしの積分を取得します |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/integral/#mathintegraltypes-str-str-mathlimitlocations) | 積分を取得します |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/integral/#mathintegraltypes-str-str) | 積分を取得します |
| [`group(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/group/#) | 下部中括弧を使用してこの要素をグループに配置します |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/group/#char-mathtopbotpositions-mathtopbotpositions) | 下部中括弧やその他のグループ文字を使用してこの要素をグループに配置します |
| [`to_border_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/to_border_box/#) | ボーダーボックスにこの要素を配置します |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | ボーダーボックスにこの要素を配置します |
| [`to_math_array(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/to_math_array/#) | 垂直配列に配置します |
| [`accent(self, accent_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/accent/#char) | アクセント記号（要素の上にある文字）を設定します |
| [`overbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/overbar/#) | 要素の上にバーを設定します |
| [`underbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/underbar/#) | 要素の下にバーを設定します |
| [`to_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/to_box/#) | 要素を非表示ボックス（論理的グルーピング）に配置します<br/>            これは方程式の構成要素やその他の数学テキストをグループ化するために使用されます。<br/>            ボックス化されたオブジェクトは、たとえば整列ポイントの有無にかかわらず演算子エミュレータとして機能したり、<br/>            改行ポイントとして機能したり、内部で改行を許可しないようにグループ化したりできます。 |
| [`get_children(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathradical/get_children/#) | 子要素を取得します |

### 参照
* クラス [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)
* クラス [`MathRadical`](/slides/python-net/ja/aspose.slides.mathtext/mathradical)
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)