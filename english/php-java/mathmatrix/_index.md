---
title: MathMatrix
type: docs
weight: 0
url: /php-java/mathmatrix/
---

# MathMatrix class

 Specifies the Matrix object, consisting of child elements laid out in one or more rows and columns. 
 It is important to note that matrices do not have built in delimiters. 
 To place the matrix in the brackets you should use the delimiter object (IMathDelimiter).
 Null arguments can be used to create gaps in matrices.
 
Example:
 
```php
  $matrix = new MathMatrix(2, 3);
  $matrix->set_Item(0, 0, new MathematicalText("item.1.1"));
```

## Constructors

| name | description |
| --- | --- |
| [MathMatrix](/slides/php-java/mathmatrix/mathmatrix/)(int, int) | Initializes a new instance of the MathMatrix class. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [deleteColumn](/slides/php-java/mathmatrix/deletecolumn/)(int) | void | Deletes the specified column |
| [deleteRow](/slides/php-java/mathmatrix/deleterow/)(int) | void | Deletes the specified row |
| [getBaseJustification](/slides/php-java/mathmatrix/getbasejustification/)() | int | Specifies the vertical justification respect to surrounding text. Possible values are top, bottom, and center. Default: Center |
| [getChildren](/slides/php-java/mathmatrix/getchildren/)() | IMathElement | Get children elements |
| [getColumnAlignment](/slides/php-java/mathmatrix/getcolumnalignment/)(int) | int | Get the horizontal alignment of the specified column |
| [getColumnCount](/slides/php-java/mathmatrix/getcolumncount/)() | int | Number of columns in the matrix |
| [getColumnGap](/slides/php-java/mathmatrix/getcolumngap/)() | long | The value of horizontal spacing between columns of a matrix; If the ColumnGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the ColumnGapRule is set to 4 ("Multiple"), then the unit is interpreted as number of 0.5 em increments. In other cases ignored. Default: 0 |
| [getColumnGapRule](/slides/php-java/mathmatrix/getcolumngaprule/)() | int | The type of horizontal spacing between columns of a matrix; Horizontal spacing units can be ems or points (stored as twips). Default: SingleSpacingGap (0) |
| [getHidePlaceholders](/slides/php-java/mathmatrix/gethideplaceholders/)() | boolean | Hide the placeholders for empty matrix elements Default: false |
| [getMinColumnWidth](/slides/php-java/mathmatrix/getmincolumnwidth/)() | long | Minimum column width in twips (1/20th of a point) The gap spacing (also referred to as “Column Gap” or “Gap Width”) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). Default: 0. |
| [getRowCount](/slides/php-java/mathmatrix/getrowcount/)() | int | Number of rows in the matrix |
| [getRowGap](/slides/php-java/mathmatrix/getrowgap/)() | long | The value of vertical spacing between rows of a matrix; If the RowGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the RowGapRule is set to 4 ("Multiple"), then the unit is interpreted as half-lines. Default: 0 |
| [getRowGapRule](/slides/php-java/mathmatrix/getrowgaprule/)() | int | The type of vertical spacing between rows of a matrix; Vertical spacing units can be lines or points (stored as twips). Default: SingleSpacingGap (0) |
| [get_Item](/slides/php-java/mathmatrix/get_item/)(int, int) | IMathElement | Element of matrix |
| [insertColumnAfter](/slides/php-java/mathmatrix/insertcolumnafter/)(int) | void | Insert a new column after the specified one Initially all elements in the new column are null. |
| [insertColumnBefore](/slides/php-java/mathmatrix/insertcolumnbefore/)(int) | void | Insert a new column before the specified one Initially all elements in the new column are null. |
| [insertRowAfter](/slides/php-java/mathmatrix/insertrowafter/)(int) | void | Insert a new row after the specified one Initially all elements in the new row are null. |
| [insertRowBefore](/slides/php-java/mathmatrix/insertrowbefore/)(int) | void | Insert a new row before the specified one Initially all elements in the new row are null. |
| [setBaseJustification](/slides/php-java/mathmatrix/setbasejustification/)(int) | void | Specifies the vertical justification respect to surrounding text. Possible values are top, bottom, and center. Default: Center |
| [setColumnAlignment](/slides/php-java/mathmatrix/setcolumnalignment/)(int, int) | void | Set the horizontal alignment of the specified column |
| [setColumnGap](/slides/php-java/mathmatrix/setcolumngap/)(long) | void | The value of horizontal spacing between columns of a matrix; If the ColumnGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the ColumnGapRule is set to 4 ("Multiple"), then the unit is interpreted as number of 0.5 em increments. In other cases ignored. Default: 0 |
| [setColumnGapRule](/slides/php-java/mathmatrix/setcolumngaprule/)(int) | void | The type of horizontal spacing between columns of a matrix; Horizontal spacing units can be ems or points (stored as twips). Default: SingleSpacingGap (0) |
| [setColumnsAlignment](/slides/php-java/mathmatrix/setcolumnsalignment/)(int, long, int) | void | Set the horizontal alignment of the specified columns |
| [setHidePlaceholders](/slides/php-java/mathmatrix/sethideplaceholders/)(boolean) | void | Hide the placeholders for empty matrix elements Default: false |
| [setMinColumnWidth](/slides/php-java/mathmatrix/setmincolumnwidth/)(long) | void | Minimum column width in twips (1/20th of a point) The gap spacing (also referred to as “Column Gap” or “Gap Width”) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). Default: 0. |
| [setRowGap](/slides/php-java/mathmatrix/setrowgap/)(long) | void | The value of vertical spacing between rows of a matrix; If the RowGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the RowGapRule is set to 4 ("Multiple"), then the unit is interpreted as half-lines. Default: 0 |
| [setRowGapRule](/slides/php-java/mathmatrix/setrowgaprule/)(int) | void | The type of vertical spacing between rows of a matrix; Vertical spacing units can be lines or points (stored as twips). Default: SingleSpacingGap (0) |
| [set_Item](/slides/php-java/mathmatrix/set_item/)(int, int, IMathElement) | void | Element of matrix |
