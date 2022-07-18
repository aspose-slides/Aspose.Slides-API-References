---
title: Cell
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/cell/
---

## Cell class

 Represents a cell of a table.
 

## Methods

| Name | Description |
| --- | --- |
| [getAnchorCenter](getanchorcenter)() | Determines whether or not text box centered inside a cell. Read/write boolean. |
| [getCellFormat](getcellformat)() | Returns the CellFormat object that contains formatting properties for this cell. Read-only ICellFormat. |
| [getColSpan](getcolspan)() | Returns the number of grid columns in the parent table's table grid which shall be spanned by the current cell. This property allows cells to have the appearance of being merged, as they span vertical boundaries of other cells in the table. Read-only int. |
| [getFirstColumn](getfirstcolumn)() | Gets first column of cell. Read-only IColumn. |
| [getFirstColumnIndex](getfirstcolumnindex)() | Returns an index of first column, covered by the cell. Read-only int. |
| [getFirstRow](getfirstrow)() | Gets first row of cell. Read-only IRow. |
| [getFirstRowIndex](getfirstrowindex)() | Returns an index of first row, covered by the cell. Read-only int. |
| [getHeight](getheight)() | Returns the height of the cell. Read-only double. |
| [getMarginBottom](getmarginbottom)() | Returns or sets the bottom margin in a TextFrame. Read/write double. |
| [getMarginLeft](getmarginleft)() | Returns or sets the left margin in a TextFrame. Read/write double. |
| [getMarginRight](getmarginright)() | Returns or sets the right margin in a TextFrame. Read/write double. |
| [getMarginTop](getmargintop)() | Returns or sets the top margin in a TextFrame. Read/write double. |
| [getMinimalHeight](getminimalheight)() | Returns the minimum height of a cell. This is a sum of minimal heights of all rows cowered by the cell. Read-only double. |
| [getOffsetX](getoffsetx)() | Returns a distance from left side of a table to left side of a cell. Read-only double. |
| [getOffsetY](getoffsety)() | Returns a distance from top side of a table to top side of a cell. Read-only double. |
| [getPresentation](getpresentation)() | Returns the parent presentation of a cell. Read-only IPresentation. |
| [getRowSpan](getrowspan)() | Returns the number of rows that a merged cell spans. This is used in combination with the vMerge attribute on other cells in order to specify the beginning cell of a horizontal merge. Read-only int. |
| [getSlide](getslide)() | Returns the parent slide of a cell. Read-only IBaseSlide. |
| [getTable](gettable)() | Returns the parent Table object for a cell. Read-only ITable. |
| [getTextAnchorType](gettextanchortype)() | Returns or sets the text anchor type. Read/write TextAnchorType. |
| [getTextFrame](gettextframe)() | Returns the text frame of a cell. Read-only ITextFrame. |
| [getTextVerticalType](gettextverticaltype)() | Returns or sets the type of vertical text. Read/write TextVerticalType. |
| [getWidth](getwidth)() | Returns the width of the cell. Read-only double. |
| [isMergedCell](ismergedcell)() | Returns true if the cell is merged with any adjusted cell, false otherwise. Read-only boolean. |
| [setAnchorCenter](setanchorcenter)(boolean) | Determines whether or not text box centered inside a cell. Read/write boolean. |
| [setMarginBottom](setmarginbottom)(double) | Returns or sets the bottom margin in a TextFrame. Read/write double. |
| [setMarginLeft](setmarginleft)(double) | Returns or sets the left margin in a TextFrame. Read/write double. |
| [setMarginRight](setmarginright)(double) | Returns or sets the right margin in a TextFrame. Read/write double. |
| [setMarginTop](setmargintop)(double) | Returns or sets the top margin in a TextFrame. Read/write double. |
| [setTextAnchorType](settextanchortype)(OrderedDictionary) | Returns or sets the text anchor type. Read/write TextAnchorType. |
| [setTextAnchorType](settextanchortype)(Hashtable) | Returns or sets the text anchor type. Read/write TextAnchorType. |
| [setTextAnchorType](settextanchortype)(LinkedList) | Returns or sets the text anchor type. Read/write TextAnchorType. |
| [setTextVerticalType](settextverticaltype)(OrderedDictionary) | Returns or sets the type of vertical text. Read/write TextVerticalType. |
| [setTextVerticalType](settextverticaltype)(Hashtable) | Returns or sets the type of vertical text. Read/write TextVerticalType. |
| [setTextVerticalType](settextverticaltype)(LinkedList) | Returns or sets the type of vertical text. Read/write TextVerticalType. |
| [splitByColSpan](splitbycolspan)(int) | Splits the cell to two cells by index of column. |
| [splitByHeight](splitbyheight)(double) | Splits the cell by height. |
| [splitByRowSpan](splitbyrowspan)(int) | Splits the cell to two cells by index of row. |
| [splitByWidth](splitbywidth)(double) | Splits the cell by width. |
