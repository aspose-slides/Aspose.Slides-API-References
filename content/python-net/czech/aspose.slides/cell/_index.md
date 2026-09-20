---
title: Cell class
second_title: Aspose.Slides pro Python přes .NET referenční příručka API
description: 
type: docs
url: /cs/aspose.slides/cell/
---
## Cell třída

Reprezentuje buňku tabulky.

Typ Cell obsahuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`offset_x`](/slides/python-net/cs/aspose.slides/cell/offset_x/) | Returns a distance from left side of a table to left side of a cell.<br/>            Pouze pro čtení **float**. |
| [`offset_y`](/slides/python-net/cs/aspose.slides/cell/offset_y/) | Returns a distance from top side of a table to top side of a cell.<br/>            Pouze pro čtení **float**. |
| [`first_row_index`](/slides/python-net/cs/aspose.slides/cell/first_row_index/) | Returns an index of first row, covered by the cell.<br/>            Pouze pro čtení **int**. |
| [`first_column_index`](/slides/python-net/cs/aspose.slides/cell/first_column_index/) | Returns an index of first column, covered by the cell.<br/>            Pouze pro čtení **int**. |
| [`width`](/slides/python-net/cs/aspose.slides/cell/width/) | Returns the width of the cell.<br/>            Pouze pro čtení **float**. |
| [`height`](/slides/python-net/cs/aspose.slides/cell/height/) | Returns the height of the cell.<br/>            Pouze pro čtení **float**. |
| [`minimal_height`](/slides/python-net/cs/aspose.slides/cell/minimal_height/) | Returns the minimum height of a cell.<br/>            This is a sum of minimal heights of all rows cowered by the cell.<br/>            Pouze pro čtení **float**. |
| [`margin_left`](/slides/python-net/cs/aspose.slides/cell/margin_left/) | Returns or sets the left margin in a TextFrame.<br/>            Čtení/zápis **float**. |
| [`margin_right`](/slides/python-net/cs/aspose.slides/cell/margin_right/) | Returns or sets the right margin in a TextFrame.<br/>            Čtení/zápis **float**. |
| [`margin_top`](/slides/python-net/cs/aspose.slides/cell/margin_top/) | Returns or sets the top margin in a TextFrame.<br/>            Čtení/zápis **float**. |
| [`margin_bottom`](/slides/python-net/cs/aspose.slides/cell/margin_bottom/) | Returns or sets the bottom margin in a TextFrame.<br/>            Čtení/zápis **float**. |
| [`text_vertical_type`](/slides/python-net/cs/aspose.slides/cell/text_vertical_type/) | Returns or sets the type of vertical text.<br/>            Čtení/zápis [`TextVerticalType`](/slides/python-net/cs/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/cs/aspose.slides/cell/text_anchor_type/) | Returns or sets the text anchor type.<br/>            Čtení/zápis [`TextAnchorType`](/slides/python-net/cs/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/cs/aspose.slides/cell/anchor_center/) | Determines whether or not text box centered inside a cell.<br/>            Čtení/zápis **bool**. |
| [`first_row`](/slides/python-net/cs/aspose.slides/cell/first_row/) | Gets first row of cell.<br/>            Pouze pro čtení [`IRow`](/slides/python-net/cs/aspose.slides/irow). |
| [`first_column`](/slides/python-net/cs/aspose.slides/cell/first_column/) | Gets first column of cell.<br/>            Pouze pro čtení [`IColumn`](/slides/python-net/cs/aspose.slides/icolumn). |
| [`col_span`](/slides/python-net/cs/aspose.slides/cell/col_span/) | Returns the number of grid columns in the parent table's table grid<br/>            which shall be spanned by the current cell. This property allows cells<br/>            to have the appearance of being merged, as they span vertical boundaries<br/>            of other cells in the table.<br/>            Pouze pro čtení **int**. |
| [`row_span`](/slides/python-net/cs/aspose.slides/cell/row_span/) | Returns the number of rows that a merged cell spans. This is used in combination<br/>            with the vMerge attribute on other cells in order to specify the beginning cell<br/>            of a horizontal merge.<br/>            Pouze pro čtení **int**. |
| [`text_frame`](/slides/python-net/cs/aspose.slides/cell/text_frame/) | Returns the text frame of a cell.<br/>            Pouze pro čtení [`ITextFrame`](/slides/python-net/cs/aspose.slides/itextframe). |
| [`table`](/slides/python-net/cs/aspose.slides/cell/table/) | Returns the parent Table object for a cell.<br/>            Pouze pro čtení [`ITable`](/slides/python-net/cs/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/cs/aspose.slides/cell/is_merged_cell/) | Returns true if the cell is merged with any adjusted cell, false otherwise.<br/>            Pouze pro čtení **bool**. |
| [`cell_format`](/slides/python-net/cs/aspose.slides/cell/cell_format/) | Returns the CellFormat object that contains formatting properties for this cell.<br/>            Pouze pro čtení [`ICellFormat`](/slides/python-net/cs/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/cs/aspose.slides/cell/slide/) | Returns the parent slide of a cell.<br/>            Pouze pro čtení [`IBaseSlide`](/slides/python-net/cs/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/cs/aspose.slides/cell/presentation/) | Returns the parent presentation of a cell.<br/>            Pouze pro čtení [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation). |

## Metody

| Metoda | Popis |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/cs/aspose.slides/cell/split_by_col_span/#int) | Splits the cell to two cells by index of column. |
| [`split_by_row_span(self, index)`](/slides/python-net/cs/aspose.slides/cell/split_by_row_span/#int) | Splits the cell to two cells by index of row. |
| [`split_by_height(self, height)`](/slides/python-net/cs/aspose.slides/cell/split_by_height/#float) | Splits the cell by height. |
| [`split_by_width(self, width)`](/slides/python-net/cs/aspose.slides/cell/split_by_width/#float) | Splits the cell by width. |


### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)