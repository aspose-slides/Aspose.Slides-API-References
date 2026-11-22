---
title: MathBlock class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/mathblock/
---
## MathBlock クラス

MathParagraph に含まれ、独自の行で開始する数式テキストのインスタンスを指定します。  
すべての数式領域、方程式、式、方程式や式の配列、そして数式は数式ブロックで表されます。

**継承:**[`MathBlock`](/slides/python-net/ja/aspose.slides.mathtext/mathblock) → [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)

MathBlock 型は次のメンバーを公開します:

## コンストラクター

| コンストラクター | 説明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/__init__/#) | MathBlock クラスの新しいインスタンスを初期化します。 |
| [`__init__(self, math_element)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/__init__/#imathelement) | 新しい数式ブロックを作成し、指定された要素をその中に配置します |
| [`__init__(self, math_elements)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/__init__/#iterableimathelement) |  |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`count`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/count/) | コレクションに実際に含まれる子数式要素の数を取得します。<br/>            読み取り専用 **int**. |
| [`is_read_only`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/is_read_only/) | 子要素コレクションは変更可能なため、false を返します。 |

指定されたインデックスの IMathElement を取得または設定します。

## インデクサー

| 名前 | 説明 |
| :- | :- |
| [`[index]`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/__getitem__/) | アイテムのゼロベースインデックス |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/join/#imathelement) | この数式ブロックに数式要素を結合します |
| [`join(self, math_text)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/join/#str) | この数式ブロックに数式テキストを結合します |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/divide/#imathelement) | この分子と指定された分母で分数を作成します |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/divide/#str) | この分子と指定された分母で分数を作成します |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/divide/#imathelement-mathfractiontypes) | この分子と指定された分母で、指定されたタイプの分数を作成します |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/divide/#str-mathfractiontypes) | この分子と指定された分母で、指定されたタイプの分数を作成します |
| [`enclose(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/enclose/#) | 数式要素を括弧で囲みます |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/enclose/#char-char) | このブロックの子要素を、括弧や他の文字など、指定された文字で枠付けします |
| [`enclose(self, beginning_character, ending_character, separator_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/enclose/#char-char-char) | このブロックの子要素を、括弧や他の文字など、指定された文字で枠付けし、<br/>            区切り文字で区切ります |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/function/#imathelement) | このインスタンスを関数名として、引数の関数を取得します |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/function/#str) | このインスタンスを関数名として、引数の関数を取得します |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/as_argument_of_function/#imathelement) | このインスタンスを引数として、指定された関数を取得します |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/as_argument_of_function/#str) | このインスタンスを引数として、指定された関数を取得します |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsofoneargument) | このインスタンスを引数として、指定された関数を取得します |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | このインスタンスと指定された追加引数を使用して、指定された関数を取得します |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-str) | このインスタンスと指定された追加引数を使用して、指定された関数を取得します |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/set_subscript/#imathelement) | 下付き文字を作成します |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/set_subscript/#str) | 下付き文字を作成します |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/set_superscript/#imathelement) | 上付き文字を作成します |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/set_superscript/#str) | 上付き文字を作成します |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#imathelement-imathelement) | 右側に下付き文字と上付き文字を作成します |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#str-str) | 右側に下付き文字と上付き文字を作成します |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#imathelement-imathelement) | 左側に下付き文字と上付き文字を作成します |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#str-str) | 左側に下付き文字と上付き文字を作成します |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/radical/#imathelement) | 指定された引数から、指定された次数の数学的根を指定します |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/radical/#str) | 指定された引数から、指定された次数の数学的根を指定します |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/set_upper_limit/#imathelement) | 上限を取得します |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/set_upper_limit/#str) | 上限を取得します |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/set_lower_limit/#imathelement) | 下限を取得します |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/set_lower_limit/#str) | 下限を取得します |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-imathelement-imathelement) | N元演算子を作成します |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-str-str) | N元演算子を作成します |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 積分を取得します |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement) | 積分を取得します |
| [`integral(self, integral_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes) | 限界なしの積分を取得します |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str-mathlimitlocations) | 積分を取得します |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str) | 積分を取得します |
| [`group(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/group/#) | 下部の波括弧を使用して、この要素をグループに配置します |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/group/#char-mathtopbotpositions-mathtopbotpositions) | 下部の波括弧やその他のグルーピング文字を使用して、この要素をグループに配置します |
| [`to_border_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/to_border_box/#) | この要素をボーダーボックスに配置します |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | この要素をボーダーボックスに配置します |
| [`to_math_array(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/to_math_array/#) | 子要素を縦方向の配列に配置します |
| [`accent(self, accent_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/accent/#char) | アクセント記号（この要素の上にある文字）を設定します |
| [`overbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/overbar/#) | この要素の上部にバーを設定します |
| [`underbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/underbar/#) | この要素の下部にバーを設定します |
| [`to_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/to_box/#) | この要素を非可視ボックス（論理的なグルーピング）に配置します <br/>            これは、方程式や他の数式テキストの構成要素をグループ化するために使用されます。<br/>            ボックス化されたオブジェクトは、例えば、整列ポイントの有無にかかわらず演算子エミュレータとして機能したり、<br/>            改行ポイントとして機能したり、内部で改行を許可しないようにグループ化したりできます |
| [`get_children(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/get_children/#) | 子要素を取得します |
| [`add(self, item)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/add/#imathelement) | コレクションの末尾に数式要素を追加します |
| [`clear(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/clear/#) | コレクションからすべての要素を削除します |
| [`contains(self, item)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/contains/#imathelement) | コレクションが特定の値を含むかどうかを判断します |
| [`copy_to(self, array, array_index)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/copy_to/#listimathelement-int) | 指定された配列にコピーします |
| [`remove(self, item)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/remove/#imathelement) | コレクションから特定オブジェクトの最初の出現を削除します |
| [`index_of(self, item)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/index_of/#imathelement) | コレクション内の特定の数式要素のインデックスを決定します |
| [`insert(self, index, item)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/insert/#int-imathelement) | 指定されたインデックスに MathElement をコレクションに挿入します |
| [`remove_at(self, index)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/remove_at/#int) | コレクションの指定インデックスの要素を削除します |
| [`join_block(self, other)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/join_block/#imathblock) | このブロックに別の数式ブロックを結合します |
| [`delimit(self, separator_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/delimit/#char) | 子要素を区切り文字で区切ります（括弧なし） |
| [`write_as_math_ml(self, stream)`](/slides/python-net/ja/aspose.slides.mathtext/mathblock/write_as_math_ml/#iorawiobase) | この [`MathBlock`](/slides/python-net/ja/aspose.slides.mathtext/mathblock) の内容を MathML として保存します |

### 参照
* クラス [`MathBlock`](/slides/python-net/ja/aspose.slides.mathtext/mathblock)
* クラス [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)