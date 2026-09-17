---
title: MathFraction class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/mathfraction/
---
## MathFraction クラス

分子と分母が分数線で区切られた分数オブジェクトを指定します。
            分数線は、分数のプロパティに応じて水平または斜めにすることができます。
            分数オブジェクトは、分数線なしで要素を上に重ねるスタック関数を表すためにも使用されます。

**継承:**[`MathFraction`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction) → [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)

MathFraction タイプは以下のメンバーを公開します：

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self, numerator, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/__init__/#imathelement-imathelement-mathfractiontypes) | 指定された分子、分母、およびタイプで MathFraction を初期化します |
| [`__init__(self, numerator, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/__init__/#imathelement-imathelement) | 'Bar' タイプの MathFraction を指定された分子と分母で初期化します |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`fraction_type`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/fraction_type/) | 分数タイプ<br/>            デフォルト: Bar |
| [`numerator`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/numerator/) | 分子 |
| [`denominator`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/denominator/) | 分母 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/join/#imathelement) | 数学要素を結合し、数学ブロックを形成します |
| [`join(self, math_text)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/join/#str) | 数学テキストを結合し、数学ブロックを形成します |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/divide/#imathelement) | この分子と指定された分母で分数を作成します |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/divide/#str) | この分子と指定された分母で分数を作成します |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/divide/#imathelement-mathfractiontypes) | この分子と指定された分母で、指定されたタイプの分数を作成します |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/divide/#str-mathfractiontypes) | この分子と指定された分母で、指定されたタイプの分数を作成します |
| [`enclose(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/enclose/#) | 数学要素を括弧で囲みます |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/enclose/#char-char) | 数学要素を括弧やその他の文字など、指定された文字で囲みます |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/function/#imathelement) | このインスタンスを関数名として、引数の関数を取得します |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/function/#str) | このインスタンスを関数名として、引数の関数を取得します |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/as_argument_of_function/#imathelement) | このインスタンスを引数として、指定された関数を取得します |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/as_argument_of_function/#str) | このインスタンスを引数として、指定された関数を取得します |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsofoneargument) | このインスタンスを引数として、指定された関数を取得します |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | このインスタンスを引数として、指定された関数と追加の引数を取得します |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsoftwoarguments-str) | このインスタンスを引数として、指定された関数と追加の引数を取得します |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/set_subscript/#imathelement) | 下付き文字を作成します |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/set_subscript/#str) | 下付き文字を作成します |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/set_superscript/#imathelement) | 上付き文字を作成します |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/set_superscript/#str) | 上付き文字を作成します |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_right/#imathelement-imathelement) | 右側に下付き文字と上付き文字を作成します |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_right/#str-str) | 右側に下付き文字と上付き文字を作成します |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_left/#imathelement-imathelement) | 左側に下付き文字と上付き文字を作成します |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_left/#str-str) | 左側に下付き文字と上付き文字を作成します |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/radical/#imathelement) | 指定された引数から、指定された次数の数学的ルートを指定します |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/radical/#str) | 指定された引数から、指定された次数の数学的ルートを指定します |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/set_upper_limit/#imathelement) | 上限を取得します |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/set_upper_limit/#str) | 上限を取得します |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/set_lower_limit/#imathelement) | 下限を取得します |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/set_lower_limit/#str) | 下限を取得します |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/nary/#mathnaryoperatortypes-imathelement-imathelement) | N元演算子を作成します |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/nary/#mathnaryoperatortypes-str-str) | N元演算子を作成します |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 積分を取得します |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-imathelement-imathelement) | 積分を取得します |
| [`integral(self, integral_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes) | 限界なしの積分を取得します |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-str-str-mathlimitlocations) | 積分を取得します |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-str-str) | 積分を取得します |
| [`group(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/group/#) | 下部の中括弧を使用してこの要素をグループに配置します |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/group/#char-mathtopbotpositions-mathtopbotpositions) | 下部の中括弧やその他の文字など、グループ化文字を使用してこの要素をグループに配置します |
| [`to_border_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/to_border_box/#) | この要素をボーダーボックスに配置します |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | この要素をボーダーボックスに配置します |
| [`to_math_array(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/to_math_array/#) | 垂直配列に配置します |
| [`accent(self, accent_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/accent/#char) | アクセント記号を設定します（この要素の上部に文字） |
| [`overbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/overbar/#) | この要素の上部にバーを設定します |
| [`underbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/underbar/#) | この要素の下部にバーを設定します |
| [`to_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/to_box/#) | この要素を非表示ボックス（論理的グループ） <br/>            これは、方程式やその他の数学テキストの構成要素をグループ化するために使用されます。<br/>            ボックス化されたオブジェクトは、例えば、整列ポイントの有無にかかわらず演算子エミュレータとして機能したり、<br/>            改行ポイントとして機能したり、内部で改行を許可しないようにグループ化したりできます。 |
| [`get_children(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction/get_children/#) | 子要素を取得します |

### 参照
* クラス [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)
* クラス [`MathFraction`](/slides/python-net/ja/aspose.slides.mathtext/mathfraction)
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)