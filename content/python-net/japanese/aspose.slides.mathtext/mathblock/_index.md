---
title: MathBlock class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/mathblock/
---
## MathBlock クラス

MathParagraph 内に含まれ、独自の行で開始する数式テキストのインスタンスを指定します。 方程式、式、方程式や式の配列、および数式を含むすべての数式領域は、math block によって表されます。

**継承:**[`MathBlock`](/slides/python-net/ja/aspose.slides.mathtext/mathblock) → [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)

MathBlock 型は以下のメンバーを公開します:

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/__init__/#) | MathBlock クラスの新しいインスタンスを初期化します。 |
| [`__init__(self, math_element)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/__init__/#imathelement) | 新しい数式ブロックを作成し、指定された要素をその中に配置します。 |
| [`__init__(self, math_elements)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/__init__/#iterableimathelement) |  |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`count`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/count/) | コレクションに実際に含まれている子数式要素の数を取得します。<br/>            読み取り専用 **int**。 |
| [`is_read_only`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/is_read_only/) | 子要素コレクションは変更可能であるため、false を返します。 |

指定されたインデックスにある IMathElement を取得または設定します。

## インデクサ

| 名前 | 説明 |
| :- | :- |
| [`[index]`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/__getitem__/) | 項目のゼロベースインデックス |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/join/#imathelement) | この数式ブロックに数式要素を結合します。 |
| [`join(self, math_text)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/join/#str) | この数式ブロックに数式テキストを結合します。 |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/divide/#imathelement) | この分子と指定された分母で分数を作成します。 |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/divide/#str) | この分子と指定された分母で分数を作成します。 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/divide/#imathelement-mathfractiontypes) | この分子と指定された分母で、指定されたタイプの分数を作成します。 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/divide/#str-mathfractiontypes) | この分子と指定された分母で、指定されたタイプの分数を作成します。 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/enclose/#char-char) | このブロックの子要素を、括弧などの指定文字で囲みます。 |
| [`enclose(self, beginning_character, ending_character, separator_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/enclose/#char-char-char) | このブロックの子要素を、括弧などの指定文字で囲み、<br/>            区切り文字で区切ります。 |
| [`enclose(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/enclose/#) | 数式要素を括弧で囲みます。 |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/function/#imathelement) | このインスタンスを関数名として、引数の関数を取ります。 |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/function/#str) | このインスタンスを関数名として、引数の関数を取ります。 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/as_argument_of_function/#imathelement) | このインスタンスを引数として、指定された関数を取ります。 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/as_argument_of_function/#str) | このインスタンスを引数として、指定された関数を取ります。 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsofoneargument) | このインスタンスを引数として、指定された関数を取ります。 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | このインスタンスを引数として、指定された関数と追加の引数を取ります。 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-str) | このインスタンスを引数として、指定された関数と追加の引数を取ります。 |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/set_subscript/#imathelement) | 下付文字を作成します。 |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/set_subscript/#str) | 下付文字を作成します。 |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/set_superscript/#imathelement) | 上付文字を作成します。 |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/set_superscript/#str) | 上付文字を作成します。 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#imathelement-imathelement) | 右側に下付文字と上付文字を作成します。 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#str-str) | 右側に下付文字と上付文字を作成します。 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#imathelement-imathelement) | 左側に下付文字と上付文字を作成します。 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#str-str) | 左側に下付文字と上付文字を作成します。 |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/radical/#imathelement) | 指定された引数から、指定された次数の数学的根を指定します。 |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/radical/#str) | 指定された引数から、指定された次数の数学的根を指定します。 |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/set_upper_limit/#imathelement) | 上限を取ります。 |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/set_upper_limit/#str) | 上限を取ります。 |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/set_lower_limit/#imathelement) | 下限を取ります。 |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/set_lower_limit/#str) | 下限を取ります。 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-imathelement-imathelement) | N元演算子を作成します。 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-str-str) | N元演算子を作成します。 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 積分を取ります。 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement) | 積分を取ります。 |
| [`integral(self, integral_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes) | 上限・下限なしで積分を取ります。 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str-mathlimitlocations) | 積分を取ります。 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str) | 積分を取ります。 |
| [`group(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/group/#) | 下部の波括弧を使用してこの要素をグループに配置します。 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/group/#char-mathtopbotpositions-mathtopbotpositions) | 下部の波括弧などのグループ化文字を使用してこの要素をグループに配置します。 |
| [`to_border_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/to_border_box/#) | この要素をボーダーボックスに配置します。 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | この要素をボーダーボックスに配置します。 |
| [`to_math_array(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/to_math_array/#) | 子要素を垂直配列に配置します。 |
| [`accent(self, accent_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/accent/#char) | アクセント記号（この要素の上に付く文字）を設定します。 |
| [`overbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/overbar/#) | この要素の上にバーを設定します。 |
| [`underbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/underbar/#) | この要素の下にバーを設定します。 |
| [`to_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/to_box/#) | この要素を非表示ボックス（論理的グループ）に配置します。<br/>            これは方程式やその他の数式テキストの構成要素をグループ化するために使用されます。<br/>            たとえば、ボックス化されたオブジェクトは、整列ポイントの有無にかかわらず演算子エミュレータとして機能したり、<br/>            改行ポイントとして使用されたり、内部で改行を許可しないようにグループ化されたりします。 |
| [`get_children(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/get_children/#) | 子要素を取得します。 |
| [`add(self, item)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/add/#imathelement) | コレクションの末尾に数式要素を追加します。 |
| [`clear(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/clear/#) | コレクションからすべての要素を削除します。 |
| [`contains(self, item)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/contains/#imathelement) | コレクションに特定の値が含まれているかどうかを判断します。 |
| [`copy_to(self, array, array_index)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/copy_to/#listimathelement-int) | 指定された配列にコピーします。 |
| [`remove(self, item)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/remove/#imathelement) | コレクションから特定のオブジェクトの最初の出現を削除します。 |
| [`index_of(self, item)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/index_of/#imathelement) | コレクション内の特定の数式要素のインデックスを決定します。 |
| [`insert(self, index, item)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/insert/#int-imathelement) | 指定されたインデックスに MathElement を挿入します。 |
| [`remove_at(self, index)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/remove_at/#int) | コレクションの指定インデックスにある要素を削除します。 |
| [`join_block(self, other)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/join_block/#imathblock) | 別の数式ブロックをこのブロックに結合します。 |
| [`delimit(self, separator_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/delimit/#char) | 子要素を区切り文字で区切ります（括弧なし）。 |
| [`write_as_math_ml(self, stream)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/write_as_math_ml/#iorawiobase) | この [`MathBlock`](/slides/python-net/ja/aspose.slides.mathtext/mathblock) の内容を MathML として保存します。 |

### 参照
* クラス [`MathBlock`](/slides/python-net/ja/aspose.slides.mathtext/mathblock)
* クラス [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)