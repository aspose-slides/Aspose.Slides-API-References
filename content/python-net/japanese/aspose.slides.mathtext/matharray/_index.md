---
title: MathArray class
second_title: .NET 経由の Python 用 Aspose.Slides API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/matharray/
---
## MathArray class

方程式または任意の数学オブジェクトの縦方向配列を指定します

**継承:**[`MathArray`](/slides/python-net/ja/aspose.slides.mathtext/matharray) → [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)

MathArray 型は次のメンバーを公開します:

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/__init__/#imathelement) | 数学配列を作成し、指定された要素を配置します |
| [`__init__(self, elements)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/__init__/#iterableimathelement) |  |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`arguments`](/slides/python-net/ja/aspose.slides.mathtext/matharray/arguments/) | 配列の項目の集合 |
| [`base_justification`](/slides/python-net/ja/aspose.slides.mathtext/matharray/base_justification/) | 配列の周囲のテキストに対する配置を指定します<br/>配列外のテキストは配列オブジェクトの下部、上部、または中央に揃えることができます<br/>デフォルト値: Center |
| [`maximum_distribution`](/slides/python-net/ja/aspose.slides.mathtext/matharray/maximum_distribution/) | 最大分布<br/>true の場合、配列は containing element（ページ、列、セルなど）の最大幅に合わせて間隔が設定されます |
| [`object_distribution`](/slides/python-net/ja/aspose.slides.mathtext/matharray/object_distribution/) | オブジェクト分布<br/>true の場合、配列の内容は配列オブジェクトの最大幅に合わせて間隔が設定されます |
| [`row_spacing_rule`](/slides/python-net/ja/aspose.slides.mathtext/matharray/row_spacing_rule/) | 配列要素間の垂直間隔の種類<br/>デフォルト: SingleLineGap |
| [`row_spacing`](/slides/python-net/ja/aspose.slides.mathtext/matharray/row_spacing/) | 配列の行間の間隔<br/>RowSpacingRule が 3 の Exactly に設定されている場合にのみ使用され、この場合の測定単位はポイントです<br/>or Multiple の場合、測定単位は半行です<br/>デフォルト: 0 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/join/#imathelement) | 数学要素を結合し、数学ブロックを形成します |
| [`join(self, math_text)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/join/#str) | 数学テキストを結合し、数学ブロックを形成します |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/divide/#imathelement) | この分子と指定された分母で分数を作成します |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/divide/#str) | この分子と指定された分母で分数を作成します |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/divide/#imathelement-mathfractiontypes) | 指定されたタイプの分数を、この分子と指定された分母で作成します |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/divide/#str-mathfractiontypes) | 指定されたタイプの分数を、この分子と指定された分母で作成します |
| [`enclose(self)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/enclose/#) | 数学要素を括弧で囲みます |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/enclose/#char-char) | 数学要素を括弧やその他の文字など、指定された文字で枠取ります |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/function/#imathelement) | このインスタンスを関数名として、引数の関数を取得します |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/function/#str) | このインスタンスを関数名として、引数の関数を取得します |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/as_argument_of_function/#imathelement) | このインスタンスを引数として、指定された関数を取得します |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/as_argument_of_function/#str) | このインスタンスを引数として、指定された関数を取得します |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsofoneargument) | このインスタンスを引数として、指定された関数を取得します |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | このインスタンスを引数として、指定された関数と追加の引数を取得します |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-str) | このインスタンスを引数として、指定された関数と追加の引数を取得します |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/set_subscript/#imathelement) | 下付き文字を作成します |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/set_subscript/#str) | 下付き文字を作成します |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/set_superscript/#imathelement) | 上付き文字を作成します |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/set_superscript/#str) | 上付き文字を作成します |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#imathelement-imathelement) | 右側に下付き文字と上付き文字を作成します |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#str-str) | 右側に下付き文字と上付き文字を作成します |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#imathelement-imathelement) | 左側に下付き文字と上付き文字を作成します |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#str-str) | 左側に下付き文字と上付き文字を作成します |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/radical/#imathelement) | 指定された引数から、指定された次数の数学的ルートを指定します |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/radical/#str) | 指定された引数から、指定された次数の数学的ルートを指定します |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/set_upper_limit/#imathelement) | 上限を取得します |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/set_upper_limit/#str) | 上限を取得します |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/set_lower_limit/#imathelement) | 下限を取得します |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/set_lower_limit/#str) | 下限を取得します |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-imathelement-imathelement) | N元演算子を作成します |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-str-str) | N元演算子を作成します |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 積分を取得します |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement) | 積分を取得します |
| [`integral(self, integral_type)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/integral/#mathintegraltypes) | 制限なしの積分を取得します |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str-mathlimitlocations) | 積分を取得します |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str) | 積分を取得します |
| [`group(self)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/group/#) | この要素を下部の波括弧を使用してグループに配置します |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/group/#char-mathtopbotpositions-mathtopbotpositions) | この要素を下部の波括弧やその他のグループ化文字を使用してグループに配置します |
| [`to_border_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/to_border_box/#) | この要素をボーダーボックスに配置します |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | この要素をボーダーボックスに配置します |
| [`to_math_array(self)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/to_math_array/#) | 縦方向配列に配置します |
| [`accent(self, accent_character)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/accent/#char) | アクセント記号（この要素の上部にある文字）を設定します |
| [`overbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/overbar/#) | この要素の上部にバーを設定します |
| [`underbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/underbar/#) | この要素の下部にバーを設定します |
| [`to_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/to_box/#) | この要素を非可視ボックス（論理的グループ化）に配置します<br/>方程式のコンポーネントやその他の数学テキストのインスタンスをグループ化するために使用されます<br/>ボックス化されたオブジェクトは、たとえば、整列点の有無にかかわらず演算子エミュレータとして機能したり、<br/>改行ポイントとして機能したり、内部で改行を許可しないようにグループ化されたりします |
| [`get_children(self)`](/slides/python-net/ja/aspose.slides.mathtext/matharray/get_children/#) | 子要素を取得します |

### 参照
* クラス [`MathArray`](/slides/python-net/ja/aspose.slides.mathtext/matharray)
* クラス [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)