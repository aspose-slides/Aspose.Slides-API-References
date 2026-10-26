---
title: IMathMatrix class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix クラス

Specifies the Matrix object, consisting of child elements laid out in one or more rows and columns.  
It is important to note that matrices do not have built in delimiters.  
To place the matrix in the brackets you should use the delimiter object (IMathDelimiter).  
Null arguments can be used to create gaps in matrices.

IMathMatrix 型は以下のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`row_count`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/row_count/) | マトリックスの行数 |
| [`column_count`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/column_count/) | マトリックスの列数 |
| [`hide_placeholders`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/hide_placeholders/) | 空のマトリックス要素のプレースホルダーを非表示にします<br/>            デフォルト: false |
| [`base_justification`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/base_justification/) | 周囲のテキストに対する垂直方向の揃えを指定します。<br/>            許容できる値は top、bottom、center です。<br/>            デフォルト: Center |
| [`min_column_width`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/min_column_width/) | 列の最小幅（twips (1/20th of a point)）<br/>            ギャップ間隔（「Column Gap」または「Gap Width」）は MinColumnWidth に加算され、合計のマトリックス列間隔を決定します<br/>            （異なる列の同じエッジ間の距離）。<br/>            デフォルト: 0. |
| [`column_gap_rule`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/column_gap_rule/) | マトリックスの列間の水平間隔のタイプ；<br/>            水平間隔単位は em またはポイント（twips で保存）です。<br/>            デフォルト: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/column_gap/) | マトリックスの列間の水平間隔の値；<br/>            ColumnGapRule が 3 ("Exactly") に設定されている場合、単位は twips (1/20th of a point) と解釈されます。<br/>            ColumnGapRule が 4 ("Multiple") に設定されている場合、単位は 0.5 em の増分数として解釈されます。<br/>            その他の場合は無視されます。<br/>            デフォルト: 0 |
| [`row_gap_rule`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/row_gap_rule/) | マトリックスの行間の垂直間隔のタイプ；<br/>            垂直間隔単位は行またはポイント（twips で保存）です。<br/>            デフォルト: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/row_gap/) | マトリックスの行間の垂直間隔の値；<br/>            RowGapRule が 3 ("Exactly") に設定されている場合、単位は twips (1/20th of a point) と解釈されます。<br/>            RowGapRule が 4 ("Multiple") に設定されている場合、単位は half-lines と解釈されます。<br/>            デフォルト: 0 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_column_alignment(self, column_index)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/get_column_alignment/#int) | 指定した列の水平揃えを取得します |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/set_column_alignment/#int-mathhorizontalalignment) | 指定した列の水平揃えを設定します |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | 指定した列群の水平揃えを設定します |
| [`insert_row_before(self, row_index)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/insert_row_before/#int) | 指定した行の前に新しい行を挿入します<br/>            新しい行のすべての要素は最初は None です。 |
| [`insert_row_after(self, row_index)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/insert_row_after/#int) | 指定した行の後に新しい行を挿入します<br/>            新しい行のすべての要素は最初は None です。 |
| [`delete_row(self, row_index)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/delete_row/#int) | 指定した行を削除します |
| [`insert_column_before(self, column_index)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/insert_column_before/#int) | 指定した列の前に新しい列を挿入します<br/>            新しい列のすべての要素は最初は None です。 |
| [`insert_column_after(self, column_index)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/insert_column_after/#int) | 指定した列の後に新しい列を挿入します<br/>            新しい列のすべての要素は最初は None です。 |
| [`delete_column(self, column_index)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/delete_column/#int) | 指定した列を削除します |
| [`get_children(self)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/ja/aspose.slides.mathtext/imathmatrix/to_box/#) |  |

### 参照
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)