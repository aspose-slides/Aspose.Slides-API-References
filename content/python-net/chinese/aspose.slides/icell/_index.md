---
title: ICell class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/icell/
---
## ICell 类

表示表格中的一个单元格。

ICell 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`offset_x`](/slides/python-net/zh/aspose.slides/icell/offset_x/) | 返回表格左侧到单元格左侧的距离。<br/>            只读 **float**. |
| [`offset_y`](/slides/python-net/zh/aspose.slides/icell/offset_y/) | 返回表格顶部到单元格顶部的距离。<br/>            只读 **float**. |
| [`first_row_index`](/slides/python-net/zh/aspose.slides/icell/first_row_index/) | 返回单元格覆盖的第一行的索引。<br/>            只读 **int**. |
| [`first_column_index`](/slides/python-net/zh/aspose.slides/icell/first_column_index/) | 返回单元格覆盖的第一列的索引。<br/>            只读 **int**. |
| [`width`](/slides/python-net/zh/aspose.slides/icell/width/) | 返回单元格的宽度。<br/>            只读 **float**. |
| [`height`](/slides/python-net/zh/aspose.slides/icell/height/) | 返回单元格的高度。<br/>            只读 **float**. |
| [`minimal_height`](/slides/python-net/zh/aspose.slides/icell/minimal_height/) | 返回单元格的最小高度。<br/>            这是单元格覆盖的所有行的最小高度之和。<br/>            只读 **float**. |
| [`margin_left`](/slides/python-net/zh/aspose.slides/icell/margin_left/) | 返回或设置 TextFrame 中的左边距。<br/>            读写 **float**. |
| [`margin_right`](/slides/python-net/zh/aspose.slides/icell/margin_right/) | 返回或设置 TextFrame 中的右边距。<br/>            读写 **float**. |
| [`margin_top`](/slides/python-net/zh/aspose.slides/icell/margin_top/) | 返回或设置 TextFrame 中的上边距。<br/>            读写 **float**. |
| [`margin_bottom`](/slides/python-net/zh/aspose.slides/icell/margin_bottom/) | 返回或设置 TextFrame 中的下边距。<br/>            读写 **float**. |
| [`text_vertical_type`](/slides/python-net/zh/aspose.slides/icell/text_vertical_type/) | 返回或设置垂直文字的类型。<br/>            读写 [`TextVerticalType`](/slides/python-net/zh/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/zh/aspose.slides/icell/text_anchor_type/) | 返回或设置文本锚点类型。<br/>            读写 [`TextAnchorType`](/slides/python-net/zh/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/zh/aspose.slides/icell/anchor_center/) | 确定文本框是否在单元格内部居中。<br/>            读写 **bool**. |
| [`first_column`](/slides/python-net/zh/aspose.slides/icell/first_column/) | 获取单元格的第一列。<br/>            只读 [`IColumn`](/slides/python-net/zh/aspose.slides/icolumn). |
| [`first_row`](/slides/python-net/zh/aspose.slides/icell/first_row/) | 获取单元格的第一行。<br/>            只读 [`IRow`](/slides/python-net/zh/aspose.slides/irow). |
| [`col_span`](/slides/python-net/zh/aspose.slides/icell/col_span/) | 返回父表格的表格网格中当前单元格将跨越的列数。<br/>            此属性允许单元格看起来被合并，因为它们跨越表格中其他单元格的垂直边界。<br/>            只读 **int**. |
| [`row_span`](/slides/python-net/zh/aspose.slides/icell/row_span/) | 返回合并单元格跨越的行数。此属性与其他单元格的 vMerge 属性结合使用，以指定水平合并的起始单元格。<br/>            只读 **int**. |
| [`text_frame`](/slides/python-net/zh/aspose.slides/icell/text_frame/) | 返回单元格的文本框架。<br/>            只读 [`ITextFrame`](/slides/python-net/zh/aspose.slides/itextframe). |
| [`table`](/slides/python-net/zh/aspose.slides/icell/table/) | 返回单元格所在的父 Table 对象。<br/>            只读 [`ITable`](/slides/python-net/zh/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/zh/aspose.slides/icell/is_merged_cell/) | 如果单元格与任何已调整的单元格合并则返回 true，否则返回 false。<br/>            只读 **bool**. |
| [`cell_format`](/slides/python-net/zh/aspose.slides/icell/cell_format/) | 返回包含此单元格格式属性的 CellFormat 对象。<br/>            只读 [`ICellFormat`](/slides/python-net/zh/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/zh/aspose.slides/icell/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides/icell/presentation/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/zh/aspose.slides/icell/split_by_col_span/#int) | 按列索引将单元格拆分为两个单元格。 |
| [`split_by_row_span(self, index)`](/slides/python-net/zh/aspose.slides/icell/split_by_row_span/#int) | 按行索引将单元格拆分为两个单元格。 |
| [`split_by_height(self, height)`](/slides/python-net/zh/aspose.slides/icell/split_by_height/#float) | 按高度拆分单元格。 |
| [`split_by_width(self, width)`](/slides/python-net/zh/aspose.slides/icell/split_by_width/#float) | 按宽度拆分单元格。 |


### 另见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)