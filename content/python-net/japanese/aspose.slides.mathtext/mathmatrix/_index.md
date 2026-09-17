---
title: MathMatrix class
second_title: Aspose.Slides for Python via .NET の API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix クラス

Specifies the Matrix object, consisting of child elements laid out in one or more rows and columns. 
            It is important to note that matrices do not have built in delimiters. 
            To place the matrix in the brackets you should use the delimiter object (IMathDelimiter).
            Null arguments can be used to create gaps in matrices.

**継承:**[`MathMatrix`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix) → [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)

The MathMatrix type exposes the following members:

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self, row_count, column_count)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/__init__/#int-int) | MathMatrix クラスの新しいインスタンスを初期化します。 |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`row_count`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/row_count/) | 行列の行数 |
| [`column_count`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/column_count/) | 行列の列数 |
| [`hide_placeholders`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/hide_placeholders/) | 空の行列要素のプレースホルダーを非表示にします<br/>            デフォルト: false |
| [`base_justification`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/base_justification/) | 周囲のテキストに対する縦方向の揃えを指定します。<br/>            許容される値は top、bottom、center です。<br/>            デフォルト: Center |
| [`min_column_width`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/min_column_width/) | twips（ポイントの 1/20）単位の最小列幅<br/>            ギャップ間隔（「Column Gap」または「Gap Width」とも呼ばれる）は<br/>            MinColumnWidth に加算され、全体の Matrix Column Spacing（異なる列の同じエッジ間の距離）を決定します。<br/>            デフォルト: 0. |
| [`column_gap_rule`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/column_gap_rule/) | 行列の列間の水平間隔の種類です。<br/>            水平間隔の単位は ems または points（twips として保存）です。<br/>            デフォルト: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/column_gap/) | 行列の列間の水平間隔の値です。<br/>            ColumnGapRule が 3（"Exactly"）に設定されている場合、単位は twips（ポイントの 1/20）として解釈されます。<br/>            ColumnGapRule が 4（"Multiple"）に設定されている場合、単位は 0.5 em 増分の数として解釈されます。<br/>            その他の場合は無視されます。<br/>            デフォルト: 0 |
| [`row_gap_rule`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/row_gap_rule/) | 行列の行間の垂直間隔の種類です。<br/>            垂直間隔の単位は行（lines）または points（twips として保存）です。<br/>            デフォルト: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/row_gap/) | 行列の行間の垂直間隔の値です。<br/>            RowGapRule が 3（"Exactly"）に設定されている場合、単位は twips（ポイントの 1/20）として解釈されます。<br/>            RowGapRule が 4（"Multiple"）に設定されている場合、単位は半行として解釈されます。<br/>            デフォルト: 0 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/join/#imathelement) | 数学要素を結合し、数学ブロックを作成します |
| [`join(self, math_text)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/join/#str) | 数学テキストを結合し、数学ブロックを作成します |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/divide/#imathelement) | この分子と指定された分母で分数を作成します |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/divide/#str) | この分子と指定された分母で分数を作成します |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/divide/#imathelement-mathfractiontypes) | 指定されたタイプの分数を、この分子と指定された分母で作成します |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/divide/#str-mathfractiontypes) | 指定されたタイプの分数を、この分子と指定された分母で作成します |
| [`enclose(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/enclose/#) | 数学要素を丸括弧で囲みます |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/enclose/#char-char) | 数学要素を丸括弧など、指定された文字で枠付けします |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/function/#imathelement) | このインスタンスを関数名として、引数の関数を取得します |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/function/#str) | このインスタンスを関数名として、引数の関数を取得します |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#imathelement) | このインスタンスを引数として、指定された関数を取得します |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#str) | このインスタンスを引数として、指定された関数を取得します |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsofoneargument) | このインスタンスを引数として、指定された関数を取得します |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | このインスタンスを引数として、指定された関数と追加の引数を取得します |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) | このインスタンスを引数として、指定された関数と追加の引数を取得します |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/set_subscript/#imathelement) | 下付き文字を作成します |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/set_subscript/#str) | 下付き文字を作成します |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/set_superscript/#imathelement) | 上付き文字を作成します |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/set_superscript/#str) | 上付き文字を作成します |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) | 右側に下付きと上付き文字を作成します |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#str-str) | 右側に下付きと上付き文字を作成します |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) | 左側に下付きと上付き文字を作成します |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#str-str) | 左側に下付きと上付き文字を作成します |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/radical/#imathelement) | 指定された引数から、与えられた次数の数学的根を指定します |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/radical/#str) | 指定された引数から、与えられた次数の数学的根を指定します |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/set_upper_limit/#imathelement) | 上限を取得します |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/set_upper_limit/#str) | 上限を取得します |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/set_lower_limit/#imathelement) | 下限を取得します |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/set_lower_limit/#str) | 下限を取得します |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) | N元演算子を作成します |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-str-str) | N元演算子を作成します |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 積分を取得します |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement) | 積分を取得します |
| [`integral(self, integral_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes) | 上限・下限なしで積分を取得します |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) | 積分を取得します |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str) | 積分を取得します |
| [`group(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/group/#) | 下カッコを使用してこの要素をグループ化します |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) | 下カッコなどのグルーピング文字を使用してこの要素をグループ化します |
| [`to_border_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/to_border_box/#) | この要素をボーダーボックスに配置します |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | この要素をボーダーボックスに配置します |
| [`to_math_array(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/to_math_array/#) | 縦方向配列に配置します |
| [`accent(self, accent_character)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/accent/#char) | アクセント記号（この要素の上に表示される文字）を設定します |
| [`overbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/overbar/#) | この要素の上にバーを設定します |
| [`underbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/underbar/#) | この要素の下にバーを設定します |
| [`to_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/to_box/#) | この要素を非表示ボックス（論理的なグルーピング）に配置します<br/>            これは方程式やその他の数学テキストの構成要素をグループ化するために使用されます。<br/>            ボックス化されたオブジェクトは、例えば、位置合わせ点の有無に関わらず演算子エミュレータとして機能したり、改行ポイントとして使用したり、内部で改行を許可しないようにグループ化したりできます。 |
| [`get_column_alignment(self, column_index)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/get_column_alignment/#int) | 指定された列の水平揃えを取得します |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/set_column_alignment/#int-mathhorizontalalignment) | 指定された列の水平揃えを設定します |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | 指定された列の水平揃えを設定します |
| [`insert_row_before(self, row_index)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/insert_row_before/#int) | 指定された行の前に新しい行を挿入します<br/>            新しい行のすべての要素は最初 None です。 |
| [`insert_row_after(self, row_index)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/insert_row_after/#int) | 指定された行の後に新しい行を挿入します<br/>            新しい行のすべての要素は最初 None です。 |
| [`delete_row(self, row_index)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/delete_row/#int) | 指定された行を削除します |
| [`insert_column_before(self, column_index)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/insert_column_before/#int) | 指定された列の前に新しい列を挿入します<br/>            新しい列のすべての要素は最初 None です。 |
| [`insert_column_after(self, column_index)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/insert_column_after/#int) | 指定された列の後に新しい列を挿入します<br/>            新しい列のすべての要素は最初 None です。 |
| [`delete_column(self, column_index)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/delete_column/#int) | 指定された列を削除します |
| [`get_children(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix/get_children/#) | 子要素を取得します |

### 参照
* クラス [`MathElementBase`](/slides/python-net/ja/aspose.slides.mathtext/mathelementbase)
* クラス [`MathMatrix`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix)
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)