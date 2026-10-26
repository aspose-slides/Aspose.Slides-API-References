---
title: MathDelimiter class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter クラス

開き文字と閉じ文字（丸括弧、波括弧、角括弧、縦棒など）で構成され、内部に1つ以上の数学要素が指定された文字で区切られたデリミタオブジェクトを指定します。例: (𝑥2); [𝑥2|𝑦2]

**継承:**[`MathDelimiter`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter) → [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)

MathDelimiter 型は次のメンバーを公開します。

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/__init__/#imathelement) | 指定された要素を単一の基本引数として MathDelimiter を初期化します |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`arguments`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/arguments/) | 区切り文字で区切られた1つ以上の数学要素 |
| [`beginning_character`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/beginning_character/) | Delimiter Beginning Character は開始（開き）デリミタ文字を指定します。<br/>数学的デリミタは丸括弧、角括弧、波括弧などの囲む文字です。<br/>デフォルト: '('。 |
| [`separator_character`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/separator_character/) | Delimiter Separator Character はデリミタオブジェクト内で引数を区切る文字を指定します。<br/>デフォルト: '\|'. |
| [`ending_character`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/ending_character/) | Delimiter Ending Character は終了（閉じ）デリミタ文字を指定します。<br/>数学的デリミタは丸括弧、角括弧、波括弧などの囲む文字です。<br/>デフォルト: ')'. |
| [`grow_to_match_operand_height`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/grow_to_match_operand_height/) | BeginningCharacter、SeparatorCharacter、EndingCharacter の拡張を指定します。<br/>true の場合、デリミタはオペランドの高さに合わせて垂直方向に拡大します。<br/>デフォルト値は true です。 |
| [`delimiter_shape`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/delimiter_shape/) | デリミタオブジェクト内のデリミタの形状を指定します。<br/>MathDelimiterShape.Centered の場合、デリミタは数式テキストの数式軸を中心に配置され、内容全体の高さに合わせて調整されます。<br/>MathDelimiterShape.Match の場合、高さと形状が内容に完全に一致するように変更されます。 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/join/#imathelement) | 数学要素を結合して数学ブロックを形成します |
| [`join(self, math_text)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/join/#str) | 数学テキストを結合して数学ブロックを形成します |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/divide/#imathelement) | この分子と指定された分母で分数を作成します |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/divide/#str) | この分子と指定された分母で分数を作成します |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/divide/#imathelement-mathfractiontypes) | 指定されたタイプの分数を、この分子と指定された分母で作成します |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/divide/#str-mathfractiontypes) | 指定されたタイプの分数を、この分子と指定された分母で作成します |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/enclose/#char-char) | 数学要素を丸括弧などの指定文字で囲んでフレーム化します |
| [`enclose(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/enclose/#) | 数学要素を丸括弧で囲みます |
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
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/radical/#imathelement) | 指定された引数から、指定された次数の数学的根を指定します |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/radical/#str) | 指定された引数から、指定された次数の数学的根を指定します |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#imathelement) | 上限を取得します |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#str) | 上限を取得します |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#imathelement) | 下限を取得します |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#str) | 下限を取得します |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) | N元演算子を作成します |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-str-str) | N元演算子を作成します |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 積分を取得します |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) | 積分を取得します |
| [`integral(self, integral_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes) | 上限・下限なしの積分を取得します |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) | 積分を取得します |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str) | 積分を取得します |
| [`group(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/group/#) | 下部の波括弧を使用してこの要素をグループに配置します |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) | 下部の波括弧などのグループ化文字を使用してこの要素をグループに配置します |
| [`to_border_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/to_border_box/#) | この要素をボーダーボックスに配置します |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | この要素をボーダーボックスに配置します |
| [`to_math_array(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/to_math_array/#) | 縦方向配列に配置します |
| [`accent(self, accent_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/accent/#char) | アクセント記号（この要素の上にある文字）を設定します |
| [`overbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/overbar/#) | この要素の上部にバーを設定します |
| [`underbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/underbar/#) | この要素の下部にバーを設定します |
| [`to_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/to_box/#) | この要素を非表示ボックス（論理的グループ）に配置します <br/>方程式やその他の数式テキストの構成要素をグループ化するために使用されます。<br/>ボックス化されたオブジェクトは、例えば、整列点の有無にかかわらず演算子エミュレータとして機能したり、<br/>改行ポイントとして機能したり、内部で改行を許可しないようにグループ化したりできます。 |
| [`delimit(self, separator_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/delimit/#char) | 指定されたデリミタ文字を使用して引数を区切ります |
| [`get_children(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter/get_children/#) | 子要素を取得します |

### 参照
* クラス [`MathDelimiter`](/slides/python-net/ja/aspose.slides.mathtext/mathdelimiter)
* クラス [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)