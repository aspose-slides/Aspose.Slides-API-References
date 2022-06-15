---
title: Table
type: docs
weight: 0
url: /php-java/table/
---

# Table class

 Represents a table on a slide.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [getColumns](/slides/php-java/table/getcolumns/)() | IColumnCollection | Returns the collectoin of columns. Read-only IColumnCollection. |
| [getFillFormat](/slides/php-java/table/getfillformat/)() | IFillFormat | Returns the FillFormat object that contains fill formatting properties for a shape. Note: can return null for certain types of shapes which don't have fill properties. Read-only IFillFormat. |
| [getFirstCol](/slides/php-java/table/getfirstcol/)() | boolean | Determines whether the first column of a table has to be drawn with a special formatting. Read/write boolean. |
| [getFirstRow](/slides/php-java/table/getfirstrow/)() | boolean | Determines whether the first row of a table has to be drawn with a special formatting. Read/write boolean. |
| [getHorizontalBanding](/slides/php-java/table/gethorizontalbanding/)() | boolean | Determines whether the even rows has to be drawn with a different formatting. Read/write boolean. |
| [getLastCol](/slides/php-java/table/getlastcol/)() | boolean | Determines whether the last column of a table has to be drawn with a special formatting. Read/write boolean. |
| [getLastRow](/slides/php-java/table/getlastrow/)() | boolean | Determines whether the last row of a table has to be drawn with a special formatting. Read/write boolean. |
| [getRightToLeft](/slides/php-java/table/getrighttoleft/)() | boolean | Determines whether the table has right to left reading order. Read-write boolean. |
| [getRows](/slides/php-java/table/getrows/)() | IRowCollection | Returns the collectoin of rows. Read-only IRowCollection. |
| [getStylePreset](/slides/php-java/table/getstylepreset/)() | int | Gets or sets builtin table style. Read/write TableStylePreset. |
| [getTableFormat](/slides/php-java/table/gettableformat/)() | ITableFormat | Returns the TableFormat object that contains formatting properties for this table. Read-only ITableFormat. |
| [getVerticalBanding](/slides/php-java/table/getverticalbanding/)() | boolean | Determines whether the even columns has to be drawn with a different formatting. Read/write boolean. |
| [get_Item](/slides/php-java/table/get_item/)(int, int) | ICell | Returns the cell at the specified column and row indexes. Read-only Cell. |
| [mergeCells](/slides/php-java/table/mergecells/)(ICell, ICell, boolean) | ICell | Merges neighbour cells. |
| [setFirstCol](/slides/php-java/table/setfirstcol/)(boolean) | void | Determines whether the first column of a table has to be drawn with a special formatting. Read/write boolean. |
| [setFirstRow](/slides/php-java/table/setfirstrow/)(boolean) | void | Determines whether the first row of a table has to be drawn with a special formatting. Read/write boolean. |
| [setHorizontalBanding](/slides/php-java/table/sethorizontalbanding/)(boolean) | void | Determines whether the even rows has to be drawn with a different formatting. Read/write boolean. |
| [setLastCol](/slides/php-java/table/setlastcol/)(boolean) | void | Determines whether the last column of a table has to be drawn with a special formatting. Read/write boolean. |
| [setLastRow](/slides/php-java/table/setlastrow/)(boolean) | void | Determines whether the last row of a table has to be drawn with a special formatting. Read/write boolean. |
| [setRightToLeft](/slides/php-java/table/setrighttoleft/)(boolean) | void | Determines whether the table has right to left reading order. Read-write boolean. |
| [setStylePreset](/slides/php-java/table/setstylepreset/)(int) | void | Gets or sets builtin table style. Read/write TableStylePreset. |
| [setTextFormat](/slides/php-java/table/settextformat/)(IPortionFormat) | void | Sets defined portion format properties to all table cells' portions. |
| [setTextFormat](/slides/php-java/table/settextformat/)(IParagraphFormat) | void | Sets defined paragraph format properties to all table cells' paragraphs. |
| [setTextFormat](/slides/php-java/table/settextformat/)(ITextFrameFormat) | void | Sets defined text frame format properties to all table cells' text frames. |
| [setVerticalBanding](/slides/php-java/table/setverticalbanding/)(boolean) | void | Determines whether the even columns has to be drawn with a different formatting. Read/write boolean. |
