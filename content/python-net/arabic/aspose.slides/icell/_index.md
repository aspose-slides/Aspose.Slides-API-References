---
title: ICell class
second_title: Aspose.Slides للـ Python عبر .NET – مرجع API
description: 
type: docs
url: /ar/aspose.slides/icell/
---
## فئة ICell

يمثل خلية في جدول.

يعرض نوع ICell الأعضاء التالية:

## الخصائص

| Property | Description |
| :- | :- |
| [`offset_x`](/slides/python-net/ar/aspose.slides/icell/offset_x/) | Returns a distance from left side of a table to left side of a cell.<br/>            للقراءة فقط **float**. |
| [`offset_y`](/slides/python-net/ar/aspose.slides/icell/offset_y/) | Returns a distance from top side of a table to top side of a cell.<br/>            للقراءة فقط **float**. |
| [`first_row_index`](/slides/python-net/ar/aspose.slides/icell/first_row_index/) | Returns an index of first row, covered by the cell.<br/>            للقراءة فقط **int**. |
| [`first_column_index`](/slides/python-net/ar/aspose.slides/icell/first_column_index/) | Returns an index of first column, covered by the cell.<br/>            للقراءة فقط **int**. |
| [`width`](/slides/python-net/ar/aspose.slides/icell/width/) | Returns the width of the cell.<br/>            للقراءة فقط **float**. |
| [`height`](/slides/python-net/ar/aspose.slides/icell/height/) | Returns the height of the cell.<br/>            للقراءة فقط **float**. |
| [`minimal_height`](/slides/python-net/ar/aspose.slides/icell/minimal_height/) | Returns the minimum height of a cell.<br/>            هذا مجموع الارتفاعات الدنيا لجميع الصفوف التي تغطيها الخلية.<br/>            للقراءة فقط **float**. |
| [`margin_left`](/slides/python-net/ar/aspose.slides/icell/margin_left/) | Returns or sets the left margin in a TextFrame.<br/>            للقراءة والكتابة **float**. |
| [`margin_right`](/slides/python-net/ar/aspose.slides/icell/margin_right/) | Returns or sets the right margin in a TextFrame.<br/>            للقراءة والكتابة **float**. |
| [`margin_top`](/slides/python-net/ar/aspose.slides/icell/margin_top/) | Returns or sets the top margin in a TextFrame.<br/>            للقراءة والكتابة **float**. |
| [`margin_bottom`](/slides/python-net/ar/aspose.slides/icell/margin_bottom/) | Returns or sets the bottom margin in a TextFrame.<br/>            للقراءة والكتابة **float**. |
| [`text_vertical_type`](/slides/python-net/ar/aspose.slides/icell/text_vertical_type/) | Returns or sets the type of vertical text.<br/>            للقراءة والكتابة [`TextVerticalType`](/slides/python-net/ar/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/ar/aspose.slides/icell/text_anchor_type/) | Returns or sets the text anchor type.<br/>            للقراءة والكتابة [`TextAnchorType`](/slides/python-net/ar/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/ar/aspose.slides/icell/anchor_center/) | Determines whether or not text box centered inside a cell.<br/>            للقراءة والكتابة **bool**. |
| [`first_column`](/slides/python-net/ar/aspose.slides/icell/first_column/) | Gets first column of cell.<br/>            للقراءة فقط [`IColumn`](/slides/python-net/ar/aspose.slides/icolumn). |
| [`first_row`](/slides/python-net/ar/aspose.slides/icell/first_row/) | Gets first row of cell.<br/>            للقراءة فقط [`IRow`](/slides/python-net/ar/aspose.slides/irow). |
| [`col_span`](/slides/python-net/ar/aspose.slides/icell/col_span/) | Returns the number of grid columns in the parent table's table grid<br/>            التي ستمتد عبرها الخلية الحالية. تسمح هذه الخاصية للخلية<br/>            بأن تظهر كما لو كانت مدمجة، حيث تمتد عبر الحدود العمودية<br/>            للخلية الأخرى في الجدول.<br/>            للقراءة فقط **int**. |
| [`row_span`](/slides/python-net/ar/aspose.slides/icell/row_span/) | Returns the number of rows that a merged cell spans. This is used in combination<br/>            with the vMerge attribute on other cells in order to specify the beginning cell<br/>            of a horizontal merge.<br/>            للقراءة فقط **int**. |
| [`text_frame`](/slides/python-net/ar/aspose.slides/icell/text_frame/) | Returns the text frame of a cell.<br/>            للقراءة فقط [`ITextFrame`](/slides/python-net/ar/aspose.slides/itextframe). |
| [`table`](/slides/python-net/ar/aspose.slides/icell/table/) | Returns the parent Table object for a cell.<br/>            للقراءة فقط [`ITable`](/slides/python-net/ar/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/ar/aspose.slides/icell/is_merged_cell/) | Returns true if the cell is merged with any adjusted cell, false otherwise.<br/>            للقراءة فقط **bool**. |
| [`cell_format`](/slides/python-net/ar/aspose.slides/icell/cell_format/) | Returns the CellFormat object that contains formatting properties for this cell.<br/>            للقراءة فقط [`ICellFormat`](/slides/python-net/ar/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/ar/aspose.slides/icell/slide/) |  |
| [`presentation`](/slides/python-net/ar/aspose.slides/icell/presentation/) |  |

## الطرق

| Method | Description |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/ar/aspose.slides/icell/split_by_col_span/#int) | يقسم الخلية إلى خليتين وفقًا لفهرس العمود. |
| [`split_by_row_span(self, index)`](/slides/python-net/ar/aspose.slides/icell/split_by_row_span/#int) | يقسم الخلية إلى خليتين وفقًا لفهرس الصف. |
| [`split_by_height(self, height)`](/slides/python-net/ar/aspose.slides/icell/split_by_height/#float) | يقسم الخلية حسب الارتفاع. |
| [`split_by_width(self, width)`](/slides/python-net/ar/aspose.slides/icell/split_by_width/#float) | يقسم الخلية حسب العرض. |


### انظر أيضًا
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)