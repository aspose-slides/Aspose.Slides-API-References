---
title: ICell class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/icell/
---


## ICell class

Represents a cell in a table.

The ICell type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [offset_x](/slides/python-net/aspose.slides/icell/offset_x/) | Returns a distance from left side of a table to left side of a cell.<br/>            Read-only .NET type System.Double. |
| [offset_y](/slides/python-net/aspose.slides/icell/offset_y/) | Returns a distance from top side of a table to top side of a cell.<br/>            Read-only .NET type System.Double. |
| [first_row_index](/slides/python-net/aspose.slides/icell/first_row_index/) | Returns an index of first row, covered by the cell.<br/>            Read-only .NET type System.Int32. |
| [first_column_index](/slides/python-net/aspose.slides/icell/first_column_index/) | Returns an index of first column, covered by the cell.<br/>            Read-only .NET type System.Int32. |
| [width](/slides/python-net/aspose.slides/icell/width/) | Returns the width of the cell.<br/>            Read-only .NET type System.Double. |
| [height](/slides/python-net/aspose.slides/icell/height/) | Returns the height of the cell.<br/>            Read-only .NET type System.Double. |
| [minimal_height](/slides/python-net/aspose.slides/icell/minimal_height/) | Returns the minimum height of a cell.<br/>            This is a sum of minimal heights of all rows cowered by the cell.<br/>            Read-only .NET type System.Double. |
| [margin_left](/slides/python-net/aspose.slides/icell/margin_left/) | Returns or sets the left margin in a TextFrame.<br/>            Read/write .NET type System.Double. |
| [margin_right](/slides/python-net/aspose.slides/icell/margin_right/) | Returns or sets the right margin in a TextFrame.<br/>            Read/write .NET type System.Double. |
| [margin_top](/slides/python-net/aspose.slides/icell/margin_top/) | Returns or sets the top margin in a TextFrame.<br/>            Read/write .NET type System.Double. |
| [margin_bottom](/slides/python-net/aspose.slides/icell/margin_bottom/) | Returns or sets the bottom margin in a TextFrame.<br/>            Read/write .NET type System.Double. |
| [text_vertical_type](/slides/python-net/aspose.slides/icell/text_vertical_type/) | Returns or sets the type of vertical text.<br/>            Read/write [`TextVerticalType`](/slides/python-net/aspose.slides/textverticaltype). |
| [text_anchor_type](/slides/python-net/aspose.slides/icell/text_anchor_type/) | Returns or sets the text anchor type.<br/>            Read/write [`TextAnchorType`](/slides/python-net/aspose.slides/textanchortype). |
| [anchor_center](/slides/python-net/aspose.slides/icell/anchor_center/) | Determines whether or not text box centered inside a cell.<br/>            Read/write .NET type System.Boolean. |
| [first_column](/slides/python-net/aspose.slides/icell/first_column/) | Gets first column of cell.<br/>            Read-only [`IColumn`](/slides/python-net/aspose.slides/icolumn). |
| [first_row](/slides/python-net/aspose.slides/icell/first_row/) | Gets first row of cell.<br/>            Read-only [`IRow`](/slides/python-net/aspose.slides/irow). |
| [col_span](/slides/python-net/aspose.slides/icell/col_span/) | Returns the number of grid columns in the parent table's table grid<br/>            which shall be spanned by the current cell. This property allows cells<br/>            to have the appearance of being merged, as they span vertical boundaries<br/>            of other cells in the table.<br/>            Read-only .NET type System.Int32. |
| [row_span](/slides/python-net/aspose.slides/icell/row_span/) | Returns the number of rows that a merged cell spans. This is used in combination<br/>            with the vMerge attribute on other cells in order to specify the beginning cell<br/>            of a horizontal merge.<br/>            Read-only .NET type System.Int32. |
| [text_frame](/slides/python-net/aspose.slides/icell/text_frame/) | Returns the text frame of a cell.<br/>            Read-only [`ITextFrame`](/slides/python-net/aspose.slides/itextframe). |
| [table](/slides/python-net/aspose.slides/icell/table/) | Returns the parent Table object for a cell.<br/>            Read-only [`ITable`](/slides/python-net/aspose.slides/itable). |
| [is_merged_cell](/slides/python-net/aspose.slides/icell/is_merged_cell/) | Returns true if the cell is merged with any adjusted cell, false otherwise.<br/>            Read-only .NET type System.Boolean. |
| [cell_format](/slides/python-net/aspose.slides/icell/cell_format/) | Returns the CellFormat object that contains formatting properties for this cell.<br/>            Read-only [`ICellFormat`](/slides/python-net/aspose.slides/icellformat). |
| [as_i_slide_component](/slides/python-net/aspose.slides/icell/as_i_slide_component/) | Allows to get base ISlideComponent interface.<br/>            Read-only [`ISlideComponent`](/slides/python-net/aspose.slides/islidecomponent). |
| [slide](/slides/python-net/aspose.slides/icell/slide/) |  |
| [as_i_presentation_component](/slides/python-net/aspose.slides/icell/as_i_presentation_component/) |  |
| [presentation](/slides/python-net/aspose.slides/icell/presentation/) |  |

## Methods

| Method | Description |
| :- | :- |
| [split_by_col_span](/slides/python-net/aspose.slides/icell/split_by_col_span/#int) | Splits the cell to two cells by index of column. |
| [split_by_row_span](/slides/python-net/aspose.slides/icell/split_by_row_span/#int) | Splits the cell to two cells by index of row. |
| [split_by_height](/slides/python-net/aspose.slides/icell/split_by_height/#float) | Splits the cell by height. |
| [split_by_width](/slides/python-net/aspose.slides/icell/split_by_width/#float) | Splits the cell by width. |

