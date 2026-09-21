---
title: ICell class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/icell/
---
## ICell 類別

表示表格中的儲存格。

ICell 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`offset_x`](/slides/python-net/zh-hant/aspose.slides/icell/offset_x/) | 傳回表格左側到儲存格左側的距離。<br/>            唯讀 **float**。 |
| [`offset_y`](/slides/python-net/zh-hant/aspose.slides/icell/offset_y/) | 傳回表格上側到儲存格上側的距離。<br/>            唯讀 **float**。 |
| [`first_row_index`](/slides/python-net/zh-hant/aspose.slides/icell/first_row_index/) | 傳回儲存格覆蓋的第一列索引。<br/>            唯讀 **int**。 |
| [`first_column_index`](/slides/python-net/zh-hant/aspose.slides/icell/first_column_index/) | 傳回儲存格覆蓋的第一欄索引。<br/>            唯讀 **int**。 |
| [`width`](/slides/python-net/zh-hant/aspose.slides/icell/width/) | 傳回儲存格的寬度。<br/>            唯讀 **float**。 |
| [`height`](/slides/python-net/zh-hant/aspose.slides/icell/height/) | 傳回儲存格的高度。<br/>            唯讀 **float**。 |
| [`minimal_height`](/slides/python-net/zh-hant/aspose.slides/icell/minimal_height/) | 傳回儲存格的最小高度。<br/>            這是所有被儲存格覆蓋之列的最小高度之總和。<br/>            唯讀 **float**。 |
| [`margin_left`](/slides/python-net/zh-hant/aspose.slides/icell/margin_left/) | 傳回或設定 TextFrame 中的左邊距。<br/>            可讀寫 **float**。 |
| [`margin_right`](/slides/python-net/zh-hant/aspose.slides/icell/margin_right/) | 傳回或設定 TextFrame 中的右邊距。<br/>            可讀寫 **float**。 |
| [`margin_top`](/slides/python-net/zh-hant/aspose.slides/icell/margin_top/) | 傳回或設定 TextFrame 中的上邊距。<br/>            可讀寫 **float**。 |
| [`margin_bottom`](/slides/python-net/zh-hant/aspose.slides/icell/margin_bottom/) | 傳回或設定 TextFrame 中的下邊距。<br/>            可讀寫 **float**。 |
| [`text_vertical_type`](/slides/python-net/zh-hant/aspose.slides/icell/text_vertical_type/) | 傳回或設定垂直文字的類型。<br/>            可讀寫 [`TextVerticalType`](/slides/python-net/zh-hant/aspose.slides/textverticaltype)。 |
| [`text_anchor_type`](/slides/python-net/zh-hant/aspose.slides/icell/text_anchor_type/) | 傳回或設定文字錨點類型。<br/>            可讀寫 [`TextAnchorType`](/slides/python-net/zh-hant/aspose.slides/textanchortype)。 |
| [`anchor_center`](/slides/python-net/zh-hant/aspose.slides/icell/anchor_center/) | 決定文字方塊是否在儲存格內置中。<br/>            可讀寫 **bool**。 |
| [`first_column`](/slides/python-net/zh-hant/aspose.slides/icell/first_column/) | 取得儲存格的第一欄。<br/>            唯讀 [`IColumn`](/slides/python-net/zh-hant/aspose.slides/icolumn)。 |
| [`first_row`](/slides/python-net/zh-hant/aspose.slides/icell/first_row/) | 取得儲存格的第一列。<br/>            唯讀 [`IRow`](/slides/python-net/zh-hant/aspose.slides/irow)。 |
| [`col_span`](/slides/python-net/zh-hant/aspose.slides/icell/col_span/) | 傳回父表格的表格格線中當前儲存格所跨越的欄數。<br/>            這些欄位將由目前的儲存格跨越。此屬性允許儲存格<br/>            呈現已合併的外觀，因為它跨越其他儲存格<br/>            在表格中的垂直邊界。<br/>            唯讀 **int**。 |
| [`row_span`](/slides/python-net/zh-hant/aspose.slides/icell/row_span/) | 傳回合併儲存格跨越的列數。<br/>            此資訊與其他儲存格的 vMerge 屬性結合使用，以指定水平合併的起始儲存格。<br/>            唯讀 **int**。 |
| [`text_frame`](/slides/python-net/zh-hant/aspose.slides/icell/text_frame/) | 傳回儲存格的文字框架。<br/>            唯讀 [`ITextFrame`](/slides/python-net/zh-hant/aspose.slides/itextframe)。 |
| [`table`](/slides/python-net/zh-hant/aspose.slides/icell/table/) | 傳回儲存格的父 Table 物件。<br/>            唯讀 [`ITable`](/slides/python-net/zh-hant/aspose.slides/itable)。 |
| [`is_merged_cell`](/slides/python-net/zh-hant/aspose.slides/icell/is_merged_cell/) | 如果儲存格已與任何已調整的儲存格合併則傳回 true，否則傳回 false。<br/>            唯讀 **bool**。 |
| [`cell_format`](/slides/python-net/zh-hant/aspose.slides/icell/cell_format/) | 傳回包含此儲存格格式屬性的 CellFormat 物件。<br/>            唯讀 [`ICellFormat`](/slides/python-net/zh-hant/aspose.slides/icellformat)。 |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/icell/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/icell/presentation/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/zh-hant/aspose.slides/icell/split_by_col_span/#int) | 依據欄索引將儲存格分割成兩個儲存格。 |
| [`split_by_row_span(self, index)`](/slides/python-net/zh-hant/aspose.slides/icell/split_by_row_span/#int) | 依據列索引將儲存格分割成兩個儲存格。 |
| [`split_by_height(self, height)`](/slides/python-net/zh-hant/aspose.slides/icell/split_by_height/#float) | 依高度分割儲存格。 |
| [`split_by_width(self, width)`](/slides/python-net/zh-hant/aspose.slides/icell/split_by_width/#float) | 依寬度分割儲存格。 |

### 參見
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)