---
title: MathDelimiter class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter クラス

開始文字と終了文字（括弧、波括弧、角括弧、縦棒など）で構成され、内部に1つ以上の数式要素を指定文字で区切って配置するデリミタオブジェクトを指定します。例: (𝑥2); [𝑥2|𝑦2]

**継承:**[`MathDelimiter`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter) → [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)

MathDelimiter 型は次のメンバーを公開します:

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/__init__/#imathelement) | Initializes MathDelimiter with the specified element as single base argument |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`arguments`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/arguments/) | デリミタ文字で区切られた1つ以上の数式要素 |
| [`beginning_character`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/beginning_character/) | Delimiter Beginning Character は開始（開き）デリミタ文字を指定します。<br/>            数学的デリミタは括弧、角括弧、波括弧などの囲み文字です。<br/>            デフォルト: '('. |
| [`separator_character`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/separator_character/) | Delimiter Separator Character はデリミタオブジェクト内の引数を区切る文字を指定します。<br/>            デフォルト: '\|'. |
| [`ending_character`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/ending_character/) | Delimiter Ending Character は終了（閉じ）デリミタ文字を指定します。<br/>            数学的デリミタは括弧、角括弧、波括弧などの囲み文字です。<br/>            デフォルト: ')'. |
| [`grow_to_match_operand_height`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/grow_to_match_operand_height/) | BeginningCharacter、SeparatorCharacter、EndingCharacter の伸長を指定します。<br/>            true の場合、デリミタはオペランドの高さに合わせて垂直方向に伸長します。<br/>            デフォルト値は true です |
| [`delimiter_shape`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/delimiter_shape/) | delimiters の形状をデリミタオブジェクトで指定します。<br/>            MathDelimiterShape.Centered の場合、デリミタは数式テキストの数学軸を中心に配置され、内容全体の高さに合わせて調整されます。<br/>            MathDelimiterShape.Match の場合、高さと形状が内容に正確に一致するように変更されます。 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/join/#imathelement) | 数式要素を結合して数式ブロックを作成します |
| [`join(self, math_text)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/join/#str) | 数式テキストを結合して数式ブロックを作成します |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/divide/#imathelement) | この分子と指定された分母で分数を作成します |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/divide/#str) | この分子と指定された分母で分数を作成します |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/divide/#imathelement-mathfractiontypes) | この分子と指定された分母を使用し、指定されたタイプの分数を作成します |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/divide/#str-mathfractiontypes) | この分子と指定された分母を使用し、指定されたタイプの分数を作成します |
| [`enclose(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/enclose/#) | 数式要素を括弧で囲みます |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/enclose/#char-char) | 数式要素を括弧やその他の指定文字で枠付けして囲みます |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/function/#imathelement) | このインスタンスを関数名として、引数の関数を取得します |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/function/#str) | このインスタンスを関数名として、引数の関数を取得します |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#imathelement) | このインスタンスを引数として、指定された関数を取得します |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#str) | このインスタンスを引数として、指定された関数を取得します |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) | このインスタンスを引数として、指定された関数を取得します |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | このインスタンスを引数として、指定された関数と追加の引数を取得します |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | このインスタンスを引数として、指定された関数と追加の引数を取得します |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/set_subscript/#imathelement) | 下付き文字を作成します |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/set_subscript/#str) | 下付き文字を作成します |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/set_superscript/#imathelement) | 上付き文字を作成します |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/set_superscript/#str) | 上付き文字を作成します |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) | 右側に下付き文字と上付き文字を作成します |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#str-str) | 右側に下付き文字と上付き文字を作成します |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) | 左側に下付き文字と上付き文字を作成します |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#str-str) | 左側に下付き文字と上付き文字を作成します |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/radical/#imathelement) | 指定された引数から指定された次数の数学的根を指定します |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/radical/#str) | 指定された引数から指定された次数の数学的根を指定します |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#imathelement) | 上限を取得します |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#str) | 上限を取得します |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#imathelement) | 下限を取得します |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#str) | 下限を取得します |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) | N元演算子を作成します |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-str-str) | N元演算子を作成します |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 積分を取得します |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) | 積分を取得します |
| [`integral(self, integral_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes) | 限界なしの積分を取得します |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) | 積分を取得します |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str) | 積分を取得します |
| [`group(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/group/#) | この要素を下部の中括弧でグループ化します |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) | 下部の中括弧やその他のグルーピング文字を使用してこの要素をグループ化します |
| [`to_border_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/to_border_box/#) | この要素をボーダーボックスに配置します |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | この要素をボーダーボックスに配置します |
| [`to_math_array(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/to_math_array/#) | 縦配列に入れます |
| [`accent(self, accent_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/accent/#char) | アクセント記号（この要素の上部にある文字）を設定します |
| [`overbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/overbar/#) | この要素の上部にバーを設定します |
| [`underbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/underbar/#) | この要素の下部にバーを設定します |
| [`to_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/to_box/#) | この要素を非可視ボックス（論理的グルーピング）に配置します。<br/>            これは数式や他の数式テキストのコンポーネントをグループ化するために使用されます。<br/>            ボックス化されたオブジェクトは、例えば、整列ポイントの有無にかかわらず演算子エミュレータとして機能したり、<br/>            改行ポイントとして機能したり、内部で改行を許可しないようにグループ化されたりします。 |
| [`delimit(self, separator_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/delimit/#char) | 指定されたデリミタ文字で引数を区切ります |
| [`get_children(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/get_children/#) | 子要素を取得します |

### 参照
* クラス [`MathDelimiter`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter)
* クラス [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)