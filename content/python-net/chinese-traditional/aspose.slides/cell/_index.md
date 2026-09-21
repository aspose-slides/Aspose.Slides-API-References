---
title: Cell class
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/cell/
---
## Cell 類別

表示表格中的儲存格。

Cell 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`offset_x`](/slides/python-net/zh-hant/aspose.slides/cell/offset_x/) | 返回表格左側到儲存格左側的距離。<br/>            唯讀 **float**. |
| [`offset_y`](/slides/python-net/zh-hant/aspose.slides/cell/offset_y/) | 返回表格上側到儲存格上側的距離。<br/>            唯讀 **float**. |
| [`first_row_index`](/slides/python-net/zh-hant/aspose.slides/cell/first_row_index/) | 返回被儲存格覆蓋的第一列索引。<br/>            唯讀 **int**. |
| [`first_column_index`](/slides/python-net/zh-hant/aspose.slides/cell/first_column_index/) | 返回被儲存格覆蓋的第一欄索引。<br/>            唯讀 **int**. |
| [`width`](/slides/python-net/zh-hant/aspose.slides/cell/width/) | 返回儲存格的寬度。<br/>            唯讀 **float**. |
| [`height`](/slides/python-net/zh-hant/aspose.slides/cell/height/) | 返回儲存格的高度。<br/>            唯讀 **float**. |
| [`minimal_height`](/slides/python-net/zh-hant/aspose.slides/cell/minimal_height/) | 返回儲存格的最小高度。<br/>            這是所有被儲存格覆蓋之列的最小高度之總和。<br/>            唯讀 **float**. |
| [`margin_left`](/slides/python-net/zh-hant/aspose.slides/cell/margin_left/) | 返回或設定 TextFrame 中的左邊距。<br/>            讀寫 **float**. |
| [`margin_right`](/slides/python-net/zh-hant/aspose.slides/cell/margin_right/) | 返回或設定 TextFrame 中的右邊距。<br/>            讀寫 **float**. |
| [`margin_top`](/slides/python-net/zh-hant/aspose.slides/cell/margin_top/) | 返回或設定 TextFrame 中的上邊距。<br/>            讀寫 **float**. |
| [`margin_bottom`](/slides/python-net/zh-hant/aspose.slides/cell/margin_bottom/) | 返回或設定 TextFrame 中的下邊距。<br/>            讀寫 **float**. |
| [`text_vertical_type`](/slides/python-net/zh-hant/aspose.slides/cell/text_vertical_type/) | 返回或設定垂直文字的類型。<br/>            讀寫 [`TextVerticalType`](/slides/python-net/zh-hant/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/zh-hant/aspose.slides/cell/text_anchor_type/) | 返回或設定文字錨點類型。<br/>            讀寫 [`TextAnchorType`](/slides/python-net/zh-hant/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/zh-hant/aspose.slides/cell/anchor_center/) | 判斷文字方塊是否置中於儲存格內。<br/>            讀寫 **bool**. |
| [`first_row`](/slides/python-net/zh-hant/aspose.slides/cell/first_row/) | 取得儲存格的第一列。<br/>            唯讀 [`IRow`](/slides/python-net/zh-hant/aspose.slides/irow). |
| [`first_column`](/slides/python-net/zh-hant/aspose.slides/cell/first_column/) | 取得儲存格的第一欄。<br/>            唯讀 [`IColumn`](/slides/python-net/zh-hant/aspose.slides/icolumn). |
| [`col_span`](/slides/python-net/zh-hant/aspose.slides/cell/col_span/) | 返回父表格之表格格線中將被目前儲存格跨越的欄數。<br/>            此屬性允許儲存格呈現合併的外觀，<br/>            因為它跨越表格中其他儲存格的垂直邊界，<br/>            所以看起來像是合併的儲存格。<br/>            唯讀 **int**. |
| [`row_span`](/slides/python-net/zh-hant/aspose.slides/cell/row_span/) | 返回合併儲存格跨越的列數。<br/>            此資訊與其他儲存格的 vMerge 屬性結合使用，<br/>            以指定水平合併的起始儲存格。<br/>            唯讀 **int**. |
| [`text_frame`](/slides/python-net/zh-hant/aspose.slides/cell/text_frame/) | 返回儲存格的文字框。<br/>            唯讀 [`ITextFrame`](/slides/python-net/zh-hant/aspose.slides/itextframe). |
| [`table`](/slides/python-net/zh-hant/aspose.slides/cell/table/) | 返回儲存格所在的父 Table 物件。<br/>            唯讀 [`ITable`](/slides/python-net/zh-hant/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/zh-hant/aspose.slides/cell/is_merged_cell/) | 若儲存格與任何已調整的儲存格合併則返回 true，否則返回 false。<br/>            唯讀 **bool**. |
| [`cell_format`](/slides/python-net/zh-hant/aspose.slides/cell/cell_format/) | 返回包含此儲存格格式屬性的 CellFormat 物件。<br/>            唯讀 [`ICellFormat`](/slides/python-net/zh-hant/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/cell/slide/) | 返回儲存格所在的父投影片。<br/>            唯讀 [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/cell/presentation/) | 返回儲存格所在的父簡報。<br/>            唯讀 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation). |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/zh-hant/aspose.slides/cell/split_by_col_span/#int) | 依欄索引將儲存格分割為兩個儲存格。 |
| [`split_by_row_span(self, index)`](/slides/python-net/zh-hant/aspose.slides/cell/split_by_row_span/#int) | 依列索引將儲存格分割為兩個儲存格。 |
| [`split_by_height(self, height)`](/slides/python-net/zh-hant/aspose.slides/cell/split_by_height/#float) | 依高度分割儲存格。 |
| [`split_by_width(self, width)`](/slides/python-net/zh-hant/aspose.slides/cell/split_by_width/#float) | 依寬度分割儲存格。 |


### 另請參閱
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)