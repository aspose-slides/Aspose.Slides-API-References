---
title: MathematicalText class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/mathematicaltext/
---
## MathematicalText クラス

数式テキスト

**継承:**[`MathematicalText`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext) → [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)

MathematicalText 型は次のメンバーを公開します:

## コンストラクタ

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/__init__/#) | デフォルトコンストラクタ (String.Empty の値を作成) |
| [`__init__(self, math_symbol)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/__init__/#char) | 単一シンボルで MathText を作成 |
| [`__init__(self, math_text)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/__init__/#str) | テキストから MathematicalText を作成 |
| [`__init__(self, math_text, portion_format)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/__init__/#str-iportionformat) | テキストと書式設定から MathematicalText を作成 |

## プロパティ

| Property | Description |
| :- | :- |
| [`value`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/value/) | テキスト値 |
| [`format`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/format/) | テキスト書式プロパティ |

## メソッド

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/join/#imathelement) | 数式要素を結合して数式ブロックを形成 |
| [`join(self, math_text)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/join/#str) | 数式テキストを結合して数式ブロックを形成 |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/divide/#imathelement) | この分子と指定された分母で分数を作成 |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/divide/#str) | この分子と指定された分母で分数を作成 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/divide/#imathelement-mathfractiontypes) | この分子と指定された分母で、指定されたタイプの分数を作成 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/divide/#str-mathfractiontypes) | この分子と指定された分母で、指定されたタイプの分数を作成 |
| [`enclose(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/enclose/#) | 数式要素を括弧で囲む |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/enclose/#char-char) | 数式要素を括弧や他の文字など、指定された文字でフレーミングして囲む |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/function/#imathelement) | このインスタンスを関数名として、引数の関数を取得 |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/function/#str) | このインスタンスを関数名として、引数の関数を取得 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#imathelement) | このインスタンスを引数として、指定された関数を取得 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#str) | このインスタンスを引数として、指定された関数を取得 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsofoneargument) | このインスタンスを引数として、指定された関数を取得 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | このインスタンスを引数として、指定された関数と追加の引数を取得 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsoftwoarguments-str) | このインスタンスを引数として、指定された関数と追加の引数を取得 |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/set_subscript/#imathelement) | 下付き文字を作成 |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/set_subscript/#str) | 下付き文字を作成 |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/set_superscript/#imathelement) | 上付き文字を作成 |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/set_superscript/#str) | 上付き文字を作成 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_right/#imathelement-imathelement) | 右側に下付き文字と上付き文字を作成 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_right/#str-str) | 右側に下付き文字と上付き文字を作成 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_left/#imathelement-imathelement) | 左側に下付き文字と上付き文字を作成 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_left/#str-str) | 左側に下付き文字と上付き文字を作成 |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/radical/#imathelement) | 指定された引数から、指定された次数の数学的根を指定 |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/radical/#str) | 指定された引数から、指定された次数の数学的根を指定 |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/set_upper_limit/#imathelement) | 上限を取得 |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/set_upper_limit/#str) | 上限を取得 |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/set_lower_limit/#imathelement) | 下限を取得 |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/set_lower_limit/#str) | 下限を取得 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/nary/#mathnaryoperatortypes-imathelement-imathelement) | N項演算子を作成 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/nary/#mathnaryoperatortypes-str-str) | N項演算子を作成 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 積分を取得 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-imathelement-imathelement) | 積分を取得 |
| [`integral(self, integral_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes) | 上限と下限のない積分を取得 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-str-str-mathlimitlocations) | 積分を取得 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-str-str) | 積分を取得 |
| [`group(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/group/#) | 底部の波かっこでこの要素をグループに配置 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/group/#char-mathtopbotpositions-mathtopbotpositions) | 底部の波かっこや他の文字を使用してこの要素をグループに配置 |
| [`to_border_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/to_border_box/#) | この要素をボーダーボックスに配置 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | この要素をボーダーボックスに配置 |
| [`to_math_array(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/to_math_array/#) | 垂直配列に配置 |
| [`accent(self, accent_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/accent/#char) | アクセント記号を設定 (この要素の上部に文字) |
| [`overbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/overbar/#) | この要素の上部にバーを設定 |
| [`underbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/underbar/#) | この要素の下部にバーを設定 |
| [`to_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/to_box/#) | この要素を非視覚的ボックス (論理的グループ) に配置<br/>            これは方程式やその他の数式テキストの構成要素をグループ化するために使用されます。<br/>            ボックス化されたオブジェクトは、例えば、整列点の有無にかかわらず演算子エミュレータとして機能したり、<br/>            改行点として機能したり、内部で改行を許可しないようにグループ化されたりします。 |
| [`get_children(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext/get_children/#) |  |

### 参照
* クラス [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)
* クラス [`MathematicalText`](/slides/python-net/ja/aspose.slides.mathtext/mathematicaltext)
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)