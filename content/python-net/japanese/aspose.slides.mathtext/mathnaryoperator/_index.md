---
title: MathNaryOperator class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/mathnaryoperator/
---
## MathNaryOperator クラス

N 項の数学オブジェクト（例：Summation や Integral）を指定します。  
演算子、基底（またはオペランド）およびオプションの上限と下限で構成されます。  
N 項演算子の例: Summation、Union、Intersection、Integral

**継承:**[`MathNaryOperator`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator) → [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)

MathNaryOperator 型は次のメンバーを公開します:

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self, operator_symbol, base_argument, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement-imathelement) | MathNaryOperator クラスの新しいインスタンスを初期化します。 |
| [`__init__(self, operator_symbol, base_argument, lower_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement) | MathNaryOperator クラスの新しいインスタンスを初期化します。 |
| [`__init__(self, operator_symbol, base_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement) | MathNaryOperator クラスの新しいインスタンスを初期化します。 |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`base`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/base/) | 基底引数 |
| [`subscript`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/subscript/) | 例えば integral の場合に下限を設定する下付文字引数を指定します |
| [`superscript`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/superscript/) | 例えば integral の場合に上限を設定する上付文字引数を指定します |
| [`operator`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/operator/) | Nary Operator 文字<br/>            例: '∑', '∫' |
| [`limit_location`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/limit_location/) | 上限と下限（下付文字と上付文字）の位置 |
| [`grow_to_match_operand_height`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/grow_to_match_operand_height/) | オペランドの高さに合わせて縦方向に伸びる演算子文字 |
| [`hide_subscript`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/hide_subscript/) | 下付文字を非表示にする |
| [`hide_superscript`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/hide_superscript/) | 上付文字を非表示にする |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/join/#imathelement) | 数学要素を結合して数学ブロックを形成します |
| [`join(self, math_text)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/join/#str) | 数学テキストを結合して数学ブロックを形成します |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement) | この分子と指定した分母で分数を作成します |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/divide/#str) | この分子と指定した分母で分数を作成します |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement-mathfractiontypes) | 指定したタイプの分数を、この分子と指定した分母で作成します |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/divide/#str-mathfractiontypes) | 指定したタイプの分数を、この分子と指定した分母で作成します |
| [`enclose(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/enclose/#) | 数学要素を丸括弧で囲みます |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/enclose/#char-char) | 指定した文字（丸括弧など）で数学要素をフレーム化します |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/function/#imathelement) | このインスタンスを関数名として引数の関数を取ります |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/function/#str) | このインスタンスを関数名として引数の関数を取ります |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#imathelement) | このインスタンスを引数として指定関数を取ります |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#str) | このインスタンスを引数として指定関数を取ります |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsofoneargument) | このインスタンスを引数として指定関数を取ります |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | このインスタンスを引数として指定関数を取り、追加の引数も指定します |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-str) | このインスタンスを引数として指定関数を取り、追加の引数も指定します |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/set_subscript/#imathelement) | 下付文字を作成します |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/set_subscript/#str) | 下付文字を作成します |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/set_superscript/#imathelement) | 上付文字を作成します |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/set_superscript/#str) | 上付文字を作成します |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#imathelement-imathelement) | 右側に下付文字と上付文字を作成します |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#str-str) | 右側に下付文字と上付文字を作成します |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#imathelement-imathelement) | 左側に下付文字と上付文字を作成します |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#str-str) | 左側に下付文字と上付文字を作成します |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/radical/#imathelement) | 指定された引数から指定次数の数学的根を求めます |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/radical/#str) | 指定された引数から指定次数の数学的根を求めます |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#imathelement) | 上限を取ります |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#str) | 上限を取ります |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#imathelement) | 下限を取ります |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#str) | 下限を取ります |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-imathelement-imathelement) | N 項演算子を作成します |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-str-str) | N 項演算子を作成します |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 積分を取ります |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement) | 積分を取ります |
| [`integral(self, integral_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes) | 制限なしで積分を取ります |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str-mathlimitlocations) | 積分を取ります |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str) | 積分を取ります |
| [`group(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/group/#) | 下部の波かっこでこの要素をグループ化します |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/group/#char-mathtopbotpositions-mathtopbotpositions) | 下部の波かっこやその他の文字でこの要素をグループ化します |
| [`to_border_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/to_border_box/#) | この要素を枠ボックスに入れます |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | この要素を枠ボックスに入れます |
| [`to_math_array(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/to_math_array/#) | 縦方向の配列に配置します |
| [`accent(self, accent_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/accent/#char) | アクセント記号（要素の上部に文字）を設定します |
| [`overbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/overbar/#) | 要素の上部にバーを設定します |
| [`underbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/underbar/#) | 要素の下部にバーを設定します |
| [`to_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/to_box/#) | 論理的なグループ化を目的とした非表示ボックスに要素を配置します<br/>            これは方程式や他の数学テキストの構成要素をグループ化するために使用されます。<br/>            ボックス化されたオブジェクトは、整列点の有無にかかわらず演算子エミュレータとして機能したり、<br/>            改行点として機能したり、改行を許可しないようにグループ化されたりします。 |
| [`get_children(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator/get_children/#) | 子要素を取得します |

### 関連項目
* class [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)
* class [`MathNaryOperator`](/slides/python-net/ja/aspose.slides.mathtext/mathnaryoperator)
* module [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)