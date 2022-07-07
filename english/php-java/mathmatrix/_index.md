---
title: MathMatrix
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/mathmatrix/
---

## MathMatrix class

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

| Name | Description |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | Initializes a new instance of the MathMatrix class. |

## Methods

| Name | Description |
| --- | --- |
| [deleteColumn](deletecolumn)(int) | Deletes the specified column |
| [deleteRow](deleterow)(int) | Deletes the specified row |
| [getBaseJustification](getbasejustification)() | Specifies the vertical justification respect to surrounding text. Possible values are top, bottom, and center. Default: Center |
| [getChildren](getchildren)() | Get children elements |
| [getColumnAlignment](getcolumnalignment)(int) | Get the horizontal alignment of the specified column |
| [getColumnCount](getcolumncount)() | Number of columns in the matrix |
| [getColumnGap](getcolumngap)() | The value of horizontal spacing between columns of a matrix; If the ColumnGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the ColumnGapRule is set to 4 ("Multiple"), then the unit is interpreted as number of 0.5 em increments. In other cases ignored. Default: 0 |
| [getColumnGapRule](getcolumngaprule)() | The type of horizontal spacing between columns of a matrix; Horizontal spacing units can be ems or points (stored as twips). Default: SingleSpacingGap (0) |
| [getHidePlaceholders](gethideplaceholders)() | Hide the placeholders for empty matrix elements Default: false |
| [getMinColumnWidth](getmincolumnwidth)() | Minimum column width in twips (1/20th of a point) The gap spacing (also referred to as “Column Gap” or “Gap Width”) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). Default: 0. |
| [getRowCount](getrowcount)() | Number of rows in the matrix |
| [getRowGap](getrowgap)() | The value of vertical spacing between rows of a matrix; If the RowGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the RowGapRule is set to 4 ("Multiple"), then the unit is interpreted as half-lines. Default: 0 |
| [getRowGapRule](getrowgaprule)() | The type of vertical spacing between rows of a matrix; Vertical spacing units can be lines or points (stored as twips). Default: SingleSpacingGap (0) |
| [get_Item](get_item)(int, int) | Element of matrix |
| [insertColumnAfter](insertcolumnafter)(int) | Insert a new column after the specified one Initially all elements in the new column are null. |
| [insertColumnBefore](insertcolumnbefore)(int) | Insert a new column before the specified one Initially all elements in the new column are null. |
| [insertRowAfter](insertrowafter)(int) | Insert a new row after the specified one Initially all elements in the new row are null. |
| [insertRowBefore](insertrowbefore)(int) | Insert a new row before the specified one Initially all elements in the new row are null. |
| [setBaseJustification](setbasejustification)(int) | Specifies the vertical justification respect to surrounding text. Possible values are top, bottom, and center. Default: Center |
| [setColumnAlignment](setcolumnalignment)(int, int) | Set the horizontal alignment of the specified column |
| [setColumnGap](setcolumngap)(long) | The value of horizontal spacing between columns of a matrix; If the ColumnGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the ColumnGapRule is set to 4 ("Multiple"), then the unit is interpreted as number of 0.5 em increments. In other cases ignored. Default: 0 |
| [setColumnGapRule](setcolumngaprule)(int) | The type of horizontal spacing between columns of a matrix; Horizontal spacing units can be ems or points (stored as twips). Default: SingleSpacingGap (0) |
| [setColumnsAlignment](setcolumnsalignment)(int, long, int) | Set the horizontal alignment of the specified columns |
| [setHidePlaceholders](sethideplaceholders)(boolean) | Hide the placeholders for empty matrix elements Default: false |
| [setMinColumnWidth](setmincolumnwidth)(long) | Minimum column width in twips (1/20th of a point) The gap spacing (also referred to as “Column Gap” or “Gap Width”) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). Default: 0. |
| [setRowGap](setrowgap)(long) | The value of vertical spacing between rows of a matrix; If the RowGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the RowGapRule is set to 4 ("Multiple"), then the unit is interpreted as half-lines. Default: 0 |
| [setRowGapRule](setrowgaprule)(int) | The type of vertical spacing between rows of a matrix; Vertical spacing units can be lines or points (stored as twips). Default: SingleSpacingGap (0) |
| [set_Item](set_item)(int, int, [BaseScript](../basescript)) | Element of matrix |
| [set_Item](set_item)(int, int, [MathAccent](../mathaccent)) | Element of matrix |
| [set_Item](set_item)(int, int, [MathArray](../matharray)) | Element of matrix |
| [set_Item](set_item)(int, int, [MathBar](../mathbar)) | Element of matrix |
| [set_Item](set_item)(int, int, [MathBlock](../mathblock)) | Element of matrix |
| [set_Item](set_item)(int, int, [MathBorderBox](../mathborderbox)) | Element of matrix |
| [set_Item](set_item)(int, int, [MathBox](../mathbox)) | Element of matrix |
| [set_Item](set_item)(int, int, [MathDelimiter](../mathdelimiter)) | Element of matrix |
| [set_Item](set_item)(int, int, [MathElementBase](../mathelementbase)) | Element of matrix |
| [set_Item](set_item)(int, int, [MathematicalText](../mathematicaltext)) | Element of matrix |
| [set_Item](set_item)(int, int, [MathFraction](../mathfraction)) | Element of matrix |
| [set_Item](set_item)(int, int, [MathFunction](../mathfunction)) | Element of matrix |
| [set_Item](set_item)(int, int, [MathGroupingCharacter](../mathgroupingcharacter)) | Element of matrix |
| [set_Item](set_item)(int, int, [MathLeftSubSuperscriptElement](../mathleftsubsuperscriptelement)) | Element of matrix |
| [set_Item](set_item)(int, int, [MathLimit](../mathlimit)) | Element of matrix |
| [set_Item](set_item)(int, int, [MathMatrix](../mathmatrix)) | Element of matrix |
| [set_Item](set_item)(int, int, [MathNaryOperator](../mathnaryoperator)) | Element of matrix |
| [set_Item](set_item)(int, int, [MathRadical](../mathradical)) | Element of matrix |
| [set_Item](set_item)(int, int, [MathRightSubSuperscriptElement](../mathrightsubsuperscriptelement)) | Element of matrix |
| [set_Item](set_item)(int, int, [MathSubscriptElement](../mathsubscriptelement)) | Element of matrix |
| [set_Item](set_item)(int, int, [MathSuperscriptElement](../mathsuperscriptelement)) | Element of matrix |
