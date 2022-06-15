---
title: Cell
type: docs
weight: 0
url: /php-java/cell/
---

# Cell class

 Represents a cell of a table.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [getAnchorCenter](/slides/php-java/cell/getanchorcenter/)() | boolean | Determines whether or not text box centered inside a cell. Read/write boolean. |
| [getCellFormat](/slides/php-java/cell/getcellformat/)() | ICellFormat | Returns the CellFormat object that contains formatting properties for this cell. Read-only ICellFormat. |
| [getColSpan](/slides/php-java/cell/getcolspan/)() | int | Returns the number of grid columns in the parent table's table grid which shall be spanned by the current cell. This property allows cells to have the appearance of being merged, as they span vertical boundaries of other cells in the table. Read-only int. |
| [getFirstColumn](/slides/php-java/cell/getfirstcolumn/)() | IColumn | Gets first column of cell. Read-only IColumn. |
| [getFirstColumnIndex](/slides/php-java/cell/getfirstcolumnindex/)() | int | Returns an index of first column, covered by the cell. Read-only int. |
| [getFirstRow](/slides/php-java/cell/getfirstrow/)() | IRow | Gets first row of cell. Read-only IRow. |
| [getFirstRowIndex](/slides/php-java/cell/getfirstrowindex/)() | int | Returns an index of first row, covered by the cell. Read-only int. |
| [getHeight](/slides/php-java/cell/getheight/)() | double | Returns the height of the cell. Read-only double. |
| [getMarginBottom](/slides/php-java/cell/getmarginbottom/)() | double | Returns or sets the bottom margin in a TextFrame. Read/write double. |
| [getMarginLeft](/slides/php-java/cell/getmarginleft/)() | double | Returns or sets the left margin in a TextFrame. Read/write double. |
| [getMarginRight](/slides/php-java/cell/getmarginright/)() | double | Returns or sets the right margin in a TextFrame. Read/write double. |
| [getMarginTop](/slides/php-java/cell/getmargintop/)() | double | Returns or sets the top margin in a TextFrame. Read/write double. |
| [getMinimalHeight](/slides/php-java/cell/getminimalheight/)() | double | Returns the minimum height of a cell. This is a sum of minimal heights of all rows cowered by the cell. Read-only double. |
| [getOffsetX](/slides/php-java/cell/getoffsetx/)() | double | Returns a distance from left side of a table to left side of a cell. Read-only double. |
| [getOffsetY](/slides/php-java/cell/getoffsety/)() | double | Returns a distance from top side of a table to top side of a cell. Read-only double. |
| [getPresentation](/slides/php-java/cell/getpresentation/)() | IPresentation | Returns the parent presentation of a cell. Read-only IPresentation. |
| [getRowSpan](/slides/php-java/cell/getrowspan/)() | int | Returns the number of rows that a merged cell spans. This is used in combination with the vMerge attribute on other cells in order to specify the beginning cell of a horizontal merge. Read-only int. |
| [getSlide](/slides/php-java/cell/getslide/)() | IBaseSlide | Returns the parent slide of a cell. Read-only IBaseSlide. |
| [getTable](/slides/php-java/cell/gettable/)() | ITable | Returns the parent Table object for a cell. Read-only ITable. |
| [getTextAnchorType](/slides/php-java/cell/gettextanchortype/)() | byte | Returns or sets the text anchor type. Read/write TextAnchorType. |
| [getTextFrame](/slides/php-java/cell/gettextframe/)() | ITextFrame | Returns the text frame of a cell. Read-only ITextFrame. |
| [getTextVerticalType](/slides/php-java/cell/gettextverticaltype/)() | byte | Returns or sets the type of vertical text. Read/write TextVerticalType. |
| [getWidth](/slides/php-java/cell/getwidth/)() | double | Returns the width of the cell. Read-only double. |
| [isMergedCell](/slides/php-java/cell/ismergedcell/)() | boolean | Returns true if the cell is merged with any adjusted cell, false otherwise. Read-only boolean. |
| [setAnchorCenter](/slides/php-java/cell/setanchorcenter/)(boolean) | void | Determines whether or not text box centered inside a cell. Read/write boolean. |
| [setMarginBottom](/slides/php-java/cell/setmarginbottom/)(double) | void | Returns or sets the bottom margin in a TextFrame. Read/write double. |
| [setMarginLeft](/slides/php-java/cell/setmarginleft/)(double) | void | Returns or sets the left margin in a TextFrame. Read/write double. |
| [setMarginRight](/slides/php-java/cell/setmarginright/)(double) | void | Returns or sets the right margin in a TextFrame. Read/write double. |
| [setMarginTop](/slides/php-java/cell/setmargintop/)(double) | void | Returns or sets the top margin in a TextFrame. Read/write double. |
| [setTextAnchorType](/slides/php-java/cell/settextanchortype/)(byte) | void | Returns or sets the text anchor type. Read/write TextAnchorType. |
| [setTextVerticalType](/slides/php-java/cell/settextverticaltype/)(byte) | void | Returns or sets the type of vertical text. Read/write TextVerticalType. |
| [splitByColSpan](/slides/php-java/cell/splitbycolspan/)(int) | void | Splits the cell to two cells by index of column. |
| [splitByHeight](/slides/php-java/cell/splitbyheight/)(double) | void | Splits the cell by height. |
| [splitByRowSpan](/slides/php-java/cell/splitbyrowspan/)(int) | void | Splits the cell to two cells by index of row. |
| [splitByWidth](/slides/php-java/cell/splitbywidth/)(double) | void | Splits the cell by width. |
