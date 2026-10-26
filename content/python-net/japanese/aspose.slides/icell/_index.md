---
title: ICell class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/icell/
---
## ICell クラス

テーブル内のセルを表します。

ICell 型は次のメンバーを公開します。

## プロパティ

| Property | Description |
| :- | :- |
| [`offset_x`](/slides/python-net/ja/aspose.slides/icell/offset_x/) | テーブルの左側からセルの左側までの距離を返します。<br/>            読み取り専用 **float**. |
| [`offset_y`](/slides/python-net/ja/aspose.slides/icell/offset_y/) | テーブルの上側からセルの上側までの距離を返します。<br/>            読み取り専用 **float**. |
| [`first_row_index`](/slides/python-net/ja/aspose.slides/icell/first_row_index/) | セルがカバーする最初の行のインデックスを返します。<br/>            読み取り専用 **int**. |
| [`first_column_index`](/slides/python-net/ja/aspose.slides/icell/first_column_index/) | セルがカバーする最初の列のインデックスを返します。<br/>            読み取り専用 **int**. |
| [`width`](/slides/python-net/ja/aspose.slides/icell/width/) | セルの幅を返します。<br/>            読み取り専用 **float**. |
| [`height`](/slides/python-net/ja/aspose.slides/icell/height/) | セルの高さを返します。<br/>            読み取り専用 **float**. |
| [`minimal_height`](/slides/python-net/ja/aspose.slides/icell/minimal_height/) | セルの最小高さを返します。<br/>            これはセルがカバーするすべての行の最小高さの合計です。<br/>            読み取り専用 **float**. |
| [`margin_left`](/slides/python-net/ja/aspose.slides/icell/margin_left/) | TextFrame の左余白を取得または設定します。<br/>            読み書き可能 **float**. |
| [`margin_right`](/slides/python-net/ja/aspose.slides/icell/margin_right/) | TextFrame の右余白を取得または設定します。<br/>            読み書き可能 **float**. |
| [`margin_top`](/slides/python-net/ja/aspose.slides/icell/margin_top/) | TextFrame の上余白を取得または設定します。<br/>            読み書き可能 **float**. |
| [`margin_bottom`](/slides/python-net/ja/aspose.slides/icell/margin_bottom/) | TextFrame の下余白を取得または設定します。<br/>            読み書き可能 **float**. |
| [`text_vertical_type`](/slides/python-net/ja/aspose.slides/icell/text_vertical_type/) | 縦書きテキストのタイプを取得または設定します。<br/>            読み書き可能 [`TextVerticalType`](/slides/python-net/ja/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/ja/aspose.slides/icell/text_anchor_type/) | テキストアンカーのタイプを取得または設定します。<br/>            読み書き可能 [`TextAnchorType`](/slides/python-net/ja/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/ja/aspose.slides/icell/anchor_center/) | テキストボックスがセル内で中央に配置されているかどうかを決定します。<br/>            読み書き可能 **bool**. |
| [`first_column`](/slides/python-net/ja/aspose.slides/icell/first_column/) | セルの最初の列を取得します。<br/>            読み取り専用 [`IColumn`](/slides/python-net/ja/aspose.slides/icolumn). |
| [`first_row`](/slides/python-net/ja/aspose.slides/icell/first_row/) | セルの最初の行を取得します。<br/>            読み取り専用 [`IRow`](/slides/python-net/ja/aspose.slides/irow). |
| [`col_span`](/slides/python-net/ja/aspose.slides/icell/col_span/) | 現在のセルが跨ぐ、親テーブルのテーブルグリッド内の列数を返します。このプロパティにより、セルはテーブル内の他のセルの垂直境界を跨いで結合されたように見えるようになります。<br/>            読み取り専用 **int**. |
| [`row_span`](/slides/python-net/ja/aspose.slides/icell/row_span/) | 結合されたセルが跨ぐ行数を返します。これは、他のセルの vMerge 属性と組み合わせて、水平結合の開始セルを指定するために使用されます。<br/>            読み取り専用 **int**. |
| [`text_frame`](/slides/python-net/ja/aspose.slides/icell/text_frame/) | セルのテキストフレームを返します。<br/>            読み取り専用 [`ITextFrame`](/slides/python-net/ja/aspose.slides/itextframe). |
| [`table`](/slides/python-net/ja/aspose.slides/icell/table/) | セルの親 Table オブジェクトを返します。<br/>            読み取り専用 [`ITable`](/slides/python-net/ja/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/ja/aspose.slides/icell/is_merged_cell/) | セルが調整されたセルと結合されている場合は true、そうでない場合は false を返します。<br/>            読み取り専用 **bool**. |
| [`cell_format`](/slides/python-net/ja/aspose.slides/icell/cell_format/) | このセルの書式設定プロパティを含む CellFormat オブジェクトを返します。<br/>            読み取り専用 [`ICellFormat`](/slides/python-net/ja/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/ja/aspose.slides/icell/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides/icell/presentation/) |  |

## メソッド

| Method | Description |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/ja/aspose.slides/icell/split_by_col_span/#int) | 列インデックスでセルを2つに分割します。 |
| [`split_by_row_span(self, index)`](/slides/python-net/ja/aspose.slides/icell/split_by_row_span/#int) | 行インデックスでセルを2つに分割します。 |
| [`split_by_height(self, height)`](/slides/python-net/ja/aspose.slides/icell/split_by_height/#float) | 高さでセルを分割します。 |
| [`split_by_width(self, width)`](/slides/python-net/ja/aspose.slides/icell/split_by_width/#float) | 幅でセルを分割します。 |


### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)