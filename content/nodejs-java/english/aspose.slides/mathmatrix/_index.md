---
title: MathMatrix
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/mathmatrix/
---

## MathMatrix class

 Specifies the Matrix object, consisting of child elements laid out in one or more rows and columns. 
 It is important to note that matrices do not have built in delimiters. 
 To place the matrix in the brackets you should use the delimiter object (IMathDelimiter).
 Null arguments can be used to create gaps in matrices.
 
| Name | Description |
| --- | --- |
| MathMatrix(int, int) | Initializes a new instance of the MathMatrix class. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| rowCount | int | row count |
| columnCount | int | column count |

### Result
MathMatrix


---


| Name | Description |
| --- | --- |
| deleteColumn (int) | Deletes the specified column |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| columnIndex | int | The zero-based index of the column to delete. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | If columnIndex less than zero or greater or equal to the ColumnCount |


---


| Name | Description |
| --- | --- |
| deleteRow (int) | Deletes the specified row |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| rowIndex | int | The zero-based index of the row to delete. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | If rowIndex less than zero or greater or equal to the RowCount |


---


| Name | Description |
| --- | --- |
| getBaseJustification () | Specifies the vertical justification respect to surrounding text. Possible values are top, bottom, and center. Default: Center |

### Result
int


---


| Name | Description |
| --- | --- |
| getChildren () | Get children elements |

### Result
MathLimit(../../mathlimit), MathBorderBox(../../mathborderbox), MathFraction(../../mathfraction), MathDelimiter(../../mathdelimiter), MathSuperscriptElement(../../mathsuperscriptelement), MathLeftSubSuperscriptElement(../../mathleftsubsuperscriptelement), MathRightSubSuperscriptElement(../../mathrightsubsuperscriptelement), MathBox(../../mathbox), MathMatrix(../../mathmatrix), MathGroupingCharacter(../../mathgroupingcharacter), MathArray(../../matharray), MathBlock(../../mathblock), MathSubscriptElement(../../mathsubscriptelement), MathFunction(../../mathfunction), MathNaryOperator(../../mathnaryoperator), MathematicalText(../../mathematicaltext), BaseScript(../../basescript), MathAccent(../../mathaccent), MathRadical(../../mathradical), MathBar(../../mathbar), MathElementBase(../../mathelementbase)


---


| Name | Description |
| --- | --- |
| getColumnAlignment (int) | Get the horizontal alignment of the specified column |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| columnIndex | int | Zero-based column index |

### Result
int


---


| Name | Description |
| --- | --- |
| getColumnCount () | Number of columns in the matrix |

### Result
int


---


| Name | Description |
| --- | --- |
| getColumnGap () | The value of horizontal spacing between columns of a matrix; If the ColumnGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the ColumnGapRule is set to 4 ("Multiple"), then the unit is interpreted as number of 0.5 em increments. In other cases ignored. Default: 0 |

### Result
long


---


| Name | Description |
| --- | --- |
| getColumnGapRule () | The type of horizontal spacing between columns of a matrix; Horizontal spacing units can be ems or points (stored as twips). Default: SingleSpacingGap (0) |

### Result
int


---


| Name | Description |
| --- | --- |
| getHidePlaceholders () | Hide the placeholders for empty matrix elements Default: false |

### Result
boolean


---


| Name | Description |
| --- | --- |
| getMinColumnWidth () | Minimum column width in twips (1/20th of a point) The gap spacing (also referred to as “Column Gap” or “Gap Width”) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). Default: 0. |

### Result
long


---


| Name | Description |
| --- | --- |
| getRowCount () | Number of rows in the matrix |

### Result
int


---


| Name | Description |
| --- | --- |
| getRowGap () | The value of vertical spacing between rows of a matrix; If the RowGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the RowGapRule is set to 4 ("Multiple"), then the unit is interpreted as half-lines. Default: 0 |

### Result
long


---


| Name | Description |
| --- | --- |
| getRowGapRule () | The type of vertical spacing between rows of a matrix; Vertical spacing units can be lines or points (stored as twips). Default: SingleSpacingGap (0) |

### Result
int


---


| Name | Description |
| --- | --- |
| get_Item (int, int) | Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | int | The zero-based index of the row to get item |
| column | int | The zero-based index of the column to get item |

### Result
MathLimit(../../mathlimit), MathBorderBox(../../mathborderbox), MathFraction(../../mathfraction), MathDelimiter(../../mathdelimiter), MathSuperscriptElement(../../mathsuperscriptelement), MathLeftSubSuperscriptElement(../../mathleftsubsuperscriptelement), MathRightSubSuperscriptElement(../../mathrightsubsuperscriptelement), MathBox(../../mathbox), MathMatrix(../../mathmatrix), MathGroupingCharacter(../../mathgroupingcharacter), MathArray(../../matharray), MathBlock(../../mathblock), MathSubscriptElement(../../mathsubscriptelement), MathFunction(../../mathfunction), MathNaryOperator(../../mathnaryoperator), MathematicalText(../../mathematicaltext), BaseScript(../../basescript), MathAccent(../../mathaccent), MathRadical(../../mathradical), MathBar(../../mathbar), MathElementBase(../../mathelementbase)


---


| Name | Description |
| --- | --- |
| insertColumnAfter (int) | Insert a new column after the specified one Initially all elements in the new column are null. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| columnIndex | int | Index of the column after which to insert a new one |


---


| Name | Description |
| --- | --- |
| insertColumnBefore (int) | Insert a new column before the specified one Initially all elements in the new column are null. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| columnIndex | int | Index of the column before which to insert a new one |


---


| Name | Description |
| --- | --- |
| insertRowAfter (int) | Insert a new row after the specified one Initially all elements in the new row are null. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| rowIndex | int | Index of the row after which to insert a new one |


---


| Name | Description |
| --- | --- |
| insertRowBefore (int) | Insert a new row before the specified one Initially all elements in the new row are null. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| rowIndex | int | Index of the row before which to insert a new one |


---


| Name | Description |
| --- | --- |
| setBaseJustification (int) | Specifies the vertical justification respect to surrounding text. Possible values are top, bottom, and center. Default: Center |


---


| Name | Description |
| --- | --- |
| setColumnAlignment (int, int) | Set the horizontal alignment of the specified column |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| columnIndex | int | Zero-based column index |
| val | int | New value of horizontal alignment of specified column |


---


| Name | Description |
| --- | --- |
| setColumnGap (long) | The value of horizontal spacing between columns of a matrix; If the ColumnGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the ColumnGapRule is set to 4 ("Multiple"), then the unit is interpreted as number of 0.5 em increments. In other cases ignored. Default: 0 |


---


| Name | Description |
| --- | --- |
| setColumnGapRule (int) | The type of horizontal spacing between columns of a matrix; Horizontal spacing units can be ems or points (stored as twips). Default: SingleSpacingGap (0) |


---


| Name | Description |
| --- | --- |
| setColumnsAlignment (int, long, int) | Set the horizontal alignment of the specified columns |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| columnIndex | int | Zero-based index of the first column to set alignment |
| columnsCount | long | The number of columns to specify the alignment |
| val | int | New value of horizontal alignment of specified column |


---


| Name | Description |
| --- | --- |
| setHidePlaceholders (boolean) | Hide the placeholders for empty matrix elements Default: false |


---


| Name | Description |
| --- | --- |
| setMinColumnWidth (long) | Minimum column width in twips (1/20th of a point) The gap spacing (also referred to as “Column Gap” or “Gap Width”) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). Default: 0. |


---


| Name | Description |
| --- | --- |
| setRowGap (long) | The value of vertical spacing between rows of a matrix; If the RowGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the RowGapRule is set to 4 ("Multiple"), then the unit is interpreted as half-lines. Default: 0 |


---


| Name | Description |
| --- | --- |
| setRowGapRule (int) | The type of vertical spacing between rows of a matrix; Vertical spacing units can be lines or points (stored as twips). Default: SingleSpacingGap (0) |


---


| Name | Description |
| --- | --- |
| set_Item (int, int, MathLimit(../mathlimit)) | Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | int | The zero-based index of the row to get item |
| column | int | The zero-based index of the column to get item |


---


| Name | Description |
| --- | --- |
| set_Item (int, int, MathBorderBox(../mathborderbox)) | Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | int | The zero-based index of the row to get item |
| column | int | The zero-based index of the column to get item |


---


| Name | Description |
| --- | --- |
| set_Item (int, int, MathFraction(../mathfraction)) | Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | int | The zero-based index of the row to get item |
| column | int | The zero-based index of the column to get item |


---


| Name | Description |
| --- | --- |
| set_Item (int, int, MathDelimiter(../mathdelimiter)) | Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | int | The zero-based index of the row to get item |
| column | int | The zero-based index of the column to get item |


---


| Name | Description |
| --- | --- |
| set_Item (int, int, MathSuperscriptElement(../mathsuperscriptelement)) | Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | int | The zero-based index of the row to get item |
| column | int | The zero-based index of the column to get item |


---


| Name | Description |
| --- | --- |
| set_Item (int, int, MathLeftSubSuperscriptElement(../mathleftsubsuperscriptelement)) | Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | int | The zero-based index of the row to get item |
| column | int | The zero-based index of the column to get item |


---


| Name | Description |
| --- | --- |
| set_Item (int, int, MathRightSubSuperscriptElement(../mathrightsubsuperscriptelement)) | Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | int | The zero-based index of the row to get item |
| column | int | The zero-based index of the column to get item |


---


| Name | Description |
| --- | --- |
| set_Item (int, int, MathBox(../mathbox)) | Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | int | The zero-based index of the row to get item |
| column | int | The zero-based index of the column to get item |


---


| Name | Description |
| --- | --- |
| set_Item (int, int, MathMatrix(../mathmatrix)) | Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | int | The zero-based index of the row to get item |
| column | int | The zero-based index of the column to get item |


---


| Name | Description |
| --- | --- |
| set_Item (int, int, MathGroupingCharacter(../mathgroupingcharacter)) | Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | int | The zero-based index of the row to get item |
| column | int | The zero-based index of the column to get item |


---


| Name | Description |
| --- | --- |
| set_Item (int, int, MathArray(../matharray)) | Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | int | The zero-based index of the row to get item |
| column | int | The zero-based index of the column to get item |


---


| Name | Description |
| --- | --- |
| set_Item (int, int, MathBlock(../mathblock)) | Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | int | The zero-based index of the row to get item |
| column | int | The zero-based index of the column to get item |


---


| Name | Description |
| --- | --- |
| set_Item (int, int, MathSubscriptElement(../mathsubscriptelement)) | Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | int | The zero-based index of the row to get item |
| column | int | The zero-based index of the column to get item |


---


| Name | Description |
| --- | --- |
| set_Item (int, int, MathFunction(../mathfunction)) | Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | int | The zero-based index of the row to get item |
| column | int | The zero-based index of the column to get item |


---


| Name | Description |
| --- | --- |
| set_Item (int, int, MathNaryOperator(../mathnaryoperator)) | Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | int | The zero-based index of the row to get item |
| column | int | The zero-based index of the column to get item |


---


| Name | Description |
| --- | --- |
| set_Item (int, int, MathematicalText(../mathematicaltext)) | Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | int | The zero-based index of the row to get item |
| column | int | The zero-based index of the column to get item |


---


| Name | Description |
| --- | --- |
| set_Item (int, int, MathAccent(../mathaccent)) | Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | int | The zero-based index of the row to get item |
| column | int | The zero-based index of the column to get item |


---


| Name | Description |
| --- | --- |
| set_Item (int, int, MathRadical(../mathradical)) | Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | int | The zero-based index of the row to get item |
| column | int | The zero-based index of the column to get item |


---


| Name | Description |
| --- | --- |
| set_Item (int, int, MathBar(../mathbar)) | Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | int | The zero-based index of the row to get item |
| column | int | The zero-based index of the column to get item |


---


