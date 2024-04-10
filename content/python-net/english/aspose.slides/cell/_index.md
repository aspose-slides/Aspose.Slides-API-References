---
title: Cell
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/cell/
---


Cell class

Represents a cell of a table.

The Cell type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [offset_x](/slides/python-net/aspose.slides/cell/offset_x/) | Returns a distance from left side of a table to left side of a cell.<br/>            Read-only :py:class:`float`. |
| [offset_y](/slides/python-net/aspose.slides/cell/offset_y/) | Returns a distance from top side of a table to top side of a cell.<br/>            Read-only :py:class:`float`. |
| [first_row_index](/slides/python-net/aspose.slides/cell/first_row_index/) | Returns an index of first row, covered by the cell.<br/>            Read-only :py:class:`int`. |
| [first_column_index](/slides/python-net/aspose.slides/cell/first_column_index/) | Returns an index of first column, covered by the cell.<br/>            Read-only :py:class:`int`. |
| [width](/slides/python-net/aspose.slides/cell/width/) | Returns the width of the cell.<br/>            Read-only :py:class:`float`. |
| [height](/slides/python-net/aspose.slides/cell/height/) | Returns the height of the cell.<br/>            Read-only :py:class:`float`. |
| [minimal_height](/slides/python-net/aspose.slides/cell/minimal_height/) | Returns the minimum height of a cell.<br/>            This is a sum of minimal heights of all rows cowered by the cell.<br/>            Read-only :py:class:`float`. |
| [margin_left](/slides/python-net/aspose.slides/cell/margin_left/) | Returns or sets the left margin in a TextFrame.<br/>            Read/write :py:class:`float`. |
| [margin_right](/slides/python-net/aspose.slides/cell/margin_right/) | Returns or sets the right margin in a TextFrame.<br/>            Read/write :py:class:`float`. |
| [margin_top](/slides/python-net/aspose.slides/cell/margin_top/) | Returns or sets the top margin in a TextFrame.<br/>            Read/write :py:class:`float`. |
| [margin_bottom](/slides/python-net/aspose.slides/cell/margin_bottom/) | Returns or sets the bottom margin in a TextFrame.<br/>            Read/write :py:class:`float`. |
| [text_vertical_type](/slides/python-net/aspose.slides/cell/text_vertical_type/) | Returns or sets the type of vertical text.<br/>            Read/write :py:enum:`aspose.slides.TextVerticalType`. |
| [text_anchor_type](/slides/python-net/aspose.slides/cell/text_anchor_type/) | Returns or sets the text anchor type.<br/>            Read/write :py:enum:`aspose.slides.TextAnchorType`. |
| [anchor_center](/slides/python-net/aspose.slides/cell/anchor_center/) | Determines whether or not text box centered inside a cell.<br/>            Read/write :py:class:`bool`. |
| [first_row](/slides/python-net/aspose.slides/cell/first_row/) | Gets first row of cell.<br/>            Read-only :py:class:`aspose.slides.IRow`. |
| [first_column](/slides/python-net/aspose.slides/cell/first_column/) | Gets first column of cell.<br/>            Read-only :py:class:`aspose.slides.IColumn`. |
| [col_span](/slides/python-net/aspose.slides/cell/col_span/) | Returns the number of grid columns in the parent table's table grid<br/>            which shall be spanned by the current cell. This property allows cells<br/>            to have the appearance of being merged, as they span vertical boundaries<br/>            of other cells in the table.<br/>            Read-only :py:class:`int`. |
| [row_span](/slides/python-net/aspose.slides/cell/row_span/) | Returns the number of rows that a merged cell spans. This is used in combination<br/>            with the vMerge attribute on other cells in order to specify the beginning cell<br/>            of a horizontal merge.<br/>            Read-only :py:class:`int`. |
| [text_frame](/slides/python-net/aspose.slides/cell/text_frame/) | Returns the text frame of a cell.<br/>            Read-only :py:class:`aspose.slides.ITextFrame`. |
| [table](/slides/python-net/aspose.slides/cell/table/) | Returns the parent Table object for a cell.<br/>            Read-only :py:class:`aspose.slides.ITable`. |
| [is_merged_cell](/slides/python-net/aspose.slides/cell/is_merged_cell/) | Returns true if the cell is merged with any adjusted cell, false otherwise.<br/>            Read-only :py:class:`bool`. |
| [cell_format](/slides/python-net/aspose.slides/cell/cell_format/) | Returns the CellFormat object that contains formatting properties for this cell.<br/>            Read-only :py:class:`aspose.slides.ICellFormat`. |
| [slide](/slides/python-net/aspose.slides/cell/slide/) | Returns the parent slide of a cell.<br/>            Read-only :py:class:`aspose.slides.IBaseSlide`. |
| [presentation](/slides/python-net/aspose.slides/cell/presentation/) | Returns the parent presentation of a cell.<br/>            Read-only :py:class:`aspose.slides.IPresentation`. |
| [as_i_slide_component](/slides/python-net/aspose.slides/cell/as_i_slide_component/) |  |
| [as_i_presentation_component](/slides/python-net/aspose.slides/cell/as_i_presentation_component/) |  |

## Methods

| Method | Description |
| :- | :- |
| [split_by_col_span](/slides/python-net/aspose.slides/cell/cell/#int/) | Splits the cell to two cells by index of column. |
| [split_by_row_span](/slides/python-net/aspose.slides/cell/cell/#int/) | Splits the cell to two cells by index of row. |
| [split_by_height](/slides/python-net/aspose.slides/cell/cell/#float/) | Splits the cell by height. |
| [split_by_width](/slides/python-net/aspose.slides/cell/cell/#float/) | Splits the cell by width. |

