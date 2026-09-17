---
title: Cell class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/cell/
---
## Cell Klasse

Stellt eine Zelle einer Tabelle dar.

Der Cell-Typ stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`offset_x`](/slides/python-net/de/aspose.slides/cell/offset_x/) | Returns a distance from left side of a table to left side of a cell.<br/>            Schreibgeschützt **float**. |
| [`offset_y`](/slides/python-net/de/aspose.slides/cell/offset_y/) | Returns a distance from top side of a table to top side of a cell.<br/>            Schreibgeschützt **float**. |
| [`first_row_index`](/slides/python-net/de/aspose.slides/cell/first_row_index/) | Returns an index of first row, covered by the cell.<br/>            Schreibgeschützt **int**. |
| [`first_column_index`](/slides/python-net/de/aspose.slides/cell/first_column_index/) | Returns an index of first column, covered by the cell.<br/>            Schreibgeschützt **int**. |
| [`width`](/slides/python-net/de/aspose.slides/cell/width/) | Returns the width of the cell.<br/>            Schreibgeschützt **float**. |
| [`height`](/slides/python-net/de/aspose.slides/cell/height/) | Returns the height of the cell.<br/>            Schreibgeschützt **float**. |
| [`minimal_height`](/slides/python-net/de/aspose.slides/cell/minimal_height/) | Returns the minimum height of a cell.<br/>            This is a sum of minimal heights of all rows cowered by the cell.<br/>            Schreibgeschützt **float**. |
| [`margin_left`](/slides/python-net/de/aspose.slides/cell/margin_left/) | Returns or sets the left margin in a TextFrame.<br/>            Lese/Schreib **float**. |
| [`margin_right`](/slides/python-net/de/aspose.slides/cell/margin_right/) | Returns or sets the right margin in a TextFrame.<br/>            Lese/Schreib **float**. |
| [`margin_top`](/slides/python-net/de/aspose.slides/cell/margin_top/) | Returns or sets the top margin in a TextFrame.<br/>            Lese/Schreib **float**. |
| [`margin_bottom`](/slides/python-net/de/aspose.slides/cell/margin_bottom/) | Returns or sets the bottom margin in a TextFrame.<br/>            Lese/Schreib **float**. |
| [`text_vertical_type`](/slides/python-net/de/aspose.slides/cell/text_vertical_type/) | Returns or sets the type of vertical text.<br/>            Lese/Schreib [`TextVerticalType`](/slides/python-net/de/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/de/aspose.slides/cell/text_anchor_type/) | Returns or sets the text anchor type.<br/>            Lese/Schreib [`TextAnchorType`](/slides/python-net/de/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/de/aspose.slides/cell/anchor_center/) | Determines whether or not text box centered inside a cell.<br/>            Lese/Schreib **bool**. |
| [`first_row`](/slides/python-net/de/aspose.slides/cell/first_row/) | Gets first row of cell.<br/>            Schreibgeschützt [`IRow`](/slides/python-net/de/aspose.slides/irow). |
| [`first_column`](/slides/python-net/de/aspose.slides/cell/first_column/) | Gets first column of cell.<br/>            Schreibgeschützt [`IColumn`](/slides/python-net/de/aspose.slides/icolumn). |
| [`col_span`](/slides/python-net/de/aspose.slides/cell/col_span/) | Returns the number of grid columns in the parent table's table grid<br/>            which shall be spanned by the current cell. This property allows cells<br/>            to have the appearance of being merged, as they span vertical boundaries<br/>            of other cells in the table.<br/>            Schreibgeschützt **int**. |
| [`row_span`](/slides/python-net/de/aspose.slides/cell/row_span/) | Returns the number of rows that a merged cell spans. This is used in combination<br/>            with the vMerge attribute on other cells in order to specify the beginning cell<br/>            of a horizontal merge.<br/>            Schreibgeschützt **int**. |
| [`text_frame`](/slides/python-net/de/aspose.slides/cell/text_frame/) | Returns the text frame of a cell.<br/>            Schreibgeschützt [`ITextFrame`](/slides/python-net/de/aspose.slides/itextframe). |
| [`table`](/slides/python-net/de/aspose.slides/cell/table/) | Returns the parent Table object for a cell.<br/>            Schreibgeschützt [`ITable`](/slides/python-net/de/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/de/aspose.slides/cell/is_merged_cell/) | Returns true if the cell is merged with any adjusted cell, false otherwise.<br/>            Schreibgeschützt **bool**. |
| [`cell_format`](/slides/python-net/de/aspose.slides/cell/cell_format/) | Returns the CellFormat object that contains formatting properties for this cell.<br/>            Schreibgeschützt [`ICellFormat`](/slides/python-net/de/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/de/aspose.slides/cell/slide/) | Returns the parent slide of a cell.<br/>            Schreibgeschützt [`IBaseSlide`](/slides/python-net/de/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/de/aspose.slides/cell/presentation/) | Returns the parent presentation of a cell.<br/>            Schreibgeschützt [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation). |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/de/aspose.slides/cell/split_by_col_span/#int) | Splits the cell to two cells by index of column. |
| [`split_by_row_span(self, index)`](/slides/python-net/de/aspose.slides/cell/split_by_row_span/#int) | Splits the cell to two cells by index of row. |
| [`split_by_height(self, height)`](/slides/python-net/de/aspose.slides/cell/split_by_height/#float) | Splits the cell by height. |
| [`split_by_width(self, width)`](/slides/python-net/de/aspose.slides/cell/split_by_width/#float) | Splits the cell by width. |

### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)