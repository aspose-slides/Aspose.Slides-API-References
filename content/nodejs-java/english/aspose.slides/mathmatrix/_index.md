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
 
| [MathMatrix]([int], [int]) | Initializes a new instance of the MathMatrix class. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| rowCount | [int] | row count |
| columnCount | [int] | column count |

### Result
MathMatrix


---


| [deleteColumn] ([int]) Deletes the specified column |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| columnIndex | [int] | The zero-based index of the column to delete. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | If columnIndex less than zero or greater or equal to the ColumnCount |


---


| [deleteRow] ([int]) Deletes the specified row |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| rowIndex | [int] | The zero-based index of the row to delete. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | If rowIndex less than zero or greater or equal to the RowCount |


---


| [getBaseJustification] () Specifies the vertical justification respect to surrounding text. Possible values are top, bottom, and center. Default: Center |

### Result
int


---


| [getChildren] () Get children elements |

### Result
[MathLimit], [MathBorderBox], [MathFraction], [MathDelimiter], [MathSuperscriptElement], [MathLeftSubSuperscriptElement], [MathRightSubSuperscriptElement], [MathBox], [MathMatrix], [MathGroupingCharacter], [MathArray], [MathBlock], [MathSubscriptElement], [MathFunction], [MathNaryOperator], [MathematicalText], [BaseScript], [MathAccent], [MathRadical], [MathBar], [MathElementBase]


---


| [getColumnAlignment] ([int]) Get the horizontal alignment of the specified column |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| columnIndex | [int] | Zero-based column index |

### Result
int


---


| [getColumnCount] () Number of columns in the matrix |

### Result
int


---


| [getColumnGap] () The value of horizontal spacing between columns of a matrix; If the ColumnGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the ColumnGapRule is set to 4 ("Multiple"), then the unit is interpreted as number of 0.5 em increments. In other cases ignored. Default: 0 |

### Result
long


---


| [getColumnGapRule] () The type of horizontal spacing between columns of a matrix; Horizontal spacing units can be ems or points (stored as twips). Default: SingleSpacingGap (0) |

### Result
int


---


| [getHidePlaceholders] () Hide the placeholders for empty matrix elements Default: false |

### Result
boolean


---


| [getMinColumnWidth] () Minimum column width in twips (1/20th of a point) The gap spacing (also referred to as “Column Gap” or “Gap Width”) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). Default: 0. |

### Result
long


---


| [getRowCount] () Number of rows in the matrix |

### Result
int


---


| [getRowGap] () The value of vertical spacing between rows of a matrix; If the RowGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the RowGapRule is set to 4 ("Multiple"), then the unit is interpreted as half-lines. Default: 0 |

### Result
long


---


| [getRowGapRule] () The type of vertical spacing between rows of a matrix; Vertical spacing units can be lines or points (stored as twips). Default: SingleSpacingGap (0) |

### Result
int


---


| [get_Item] ([int], [int]) Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | [int] | The zero-based index of the row to get item |
| column | [int] | The zero-based index of the column to get item |

### Result
[MathLimit], [MathBorderBox], [MathFraction], [MathDelimiter], [MathSuperscriptElement], [MathLeftSubSuperscriptElement], [MathRightSubSuperscriptElement], [MathBox], [MathMatrix], [MathGroupingCharacter], [MathArray], [MathBlock], [MathSubscriptElement], [MathFunction], [MathNaryOperator], [MathematicalText], [BaseScript], [MathAccent], [MathRadical], [MathBar], [MathElementBase]


---


| [insertColumnAfter] ([int]) Insert a new column after the specified one Initially all elements in the new column are null. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| columnIndex | [int] | Index of the column after which to insert a new one |


---


| [insertColumnBefore] ([int]) Insert a new column before the specified one Initially all elements in the new column are null. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| columnIndex | [int] | Index of the column before which to insert a new one |


---


| [insertRowAfter] ([int]) Insert a new row after the specified one Initially all elements in the new row are null. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| rowIndex | [int] | Index of the row after which to insert a new one |


---


| [insertRowBefore] ([int]) Insert a new row before the specified one Initially all elements in the new row are null. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| rowIndex | [int] | Index of the row before which to insert a new one |


---


| [setBaseJustification] ([int]) Specifies the vertical justification respect to surrounding text. Possible values are top, bottom, and center. Default: Center |


---


| [setColumnAlignment] ([int], [int]) Set the horizontal alignment of the specified column |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| columnIndex | [int] | Zero-based column index |
| val | [int] | New value of horizontal alignment of specified column |


---


| [setColumnGap] ([long]) The value of horizontal spacing between columns of a matrix; If the ColumnGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the ColumnGapRule is set to 4 ("Multiple"), then the unit is interpreted as number of 0.5 em increments. In other cases ignored. Default: 0 |


---


| [setColumnGapRule] ([int]) The type of horizontal spacing between columns of a matrix; Horizontal spacing units can be ems or points (stored as twips). Default: SingleSpacingGap (0) |


---


| [setColumnsAlignment] ([int], [long], [int]) Set the horizontal alignment of the specified columns |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| columnIndex | [int] | Zero-based index of the first column to set alignment |
| columnsCount | [long] | The number of columns to specify the alignment |
| val | [int] | New value of horizontal alignment of specified column |


---


| [setHidePlaceholders] ([boolean]) Hide the placeholders for empty matrix elements Default: false |


---


| [setMinColumnWidth] ([long]) Minimum column width in twips (1/20th of a point) The gap spacing (also referred to as “Column Gap” or “Gap Width”) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). Default: 0. |


---


| [setRowGap] ([long]) The value of vertical spacing between rows of a matrix; If the RowGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the RowGapRule is set to 4 ("Multiple"), then the unit is interpreted as half-lines. Default: 0 |


---


| [setRowGapRule] ([int]) The type of vertical spacing between rows of a matrix; Vertical spacing units can be lines or points (stored as twips). Default: SingleSpacingGap (0) |


---


| [set_Item] ([int], [int], [MathLimit]) Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | [int] | The zero-based index of the row to get item |
| column | [int] | The zero-based index of the column to get item |


---


| [set_Item] ([int], [int], [MathBorderBox]) Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | [int] | The zero-based index of the row to get item |
| column | [int] | The zero-based index of the column to get item |


---


| [set_Item] ([int], [int], [MathFraction]) Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | [int] | The zero-based index of the row to get item |
| column | [int] | The zero-based index of the column to get item |


---


| [set_Item] ([int], [int], [MathDelimiter]) Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | [int] | The zero-based index of the row to get item |
| column | [int] | The zero-based index of the column to get item |


---


| [set_Item] ([int], [int], [MathSuperscriptElement]) Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | [int] | The zero-based index of the row to get item |
| column | [int] | The zero-based index of the column to get item |


---


| [set_Item] ([int], [int], [MathLeftSubSuperscriptElement]) Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | [int] | The zero-based index of the row to get item |
| column | [int] | The zero-based index of the column to get item |


---


| [set_Item] ([int], [int], [MathRightSubSuperscriptElement]) Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | [int] | The zero-based index of the row to get item |
| column | [int] | The zero-based index of the column to get item |


---


| [set_Item] ([int], [int], [MathBox]) Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | [int] | The zero-based index of the row to get item |
| column | [int] | The zero-based index of the column to get item |


---


| [set_Item] ([int], [int], [MathMatrix]) Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | [int] | The zero-based index of the row to get item |
| column | [int] | The zero-based index of the column to get item |


---


| [set_Item] ([int], [int], [MathGroupingCharacter]) Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | [int] | The zero-based index of the row to get item |
| column | [int] | The zero-based index of the column to get item |


---


| [set_Item] ([int], [int], [MathArray]) Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | [int] | The zero-based index of the row to get item |
| column | [int] | The zero-based index of the column to get item |


---


| [set_Item] ([int], [int], [MathBlock]) Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | [int] | The zero-based index of the row to get item |
| column | [int] | The zero-based index of the column to get item |


---


| [set_Item] ([int], [int], [MathSubscriptElement]) Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | [int] | The zero-based index of the row to get item |
| column | [int] | The zero-based index of the column to get item |


---


| [set_Item] ([int], [int], [MathFunction]) Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | [int] | The zero-based index of the row to get item |
| column | [int] | The zero-based index of the column to get item |


---


| [set_Item] ([int], [int], [MathNaryOperator]) Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | [int] | The zero-based index of the row to get item |
| column | [int] | The zero-based index of the column to get item |


---


| [set_Item] ([int], [int], [MathematicalText]) Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | [int] | The zero-based index of the row to get item |
| column | [int] | The zero-based index of the column to get item |


---


| [set_Item] ([int], [int], [MathAccent]) Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | [int] | The zero-based index of the row to get item |
| column | [int] | The zero-based index of the column to get item |


---


| [set_Item] ([int], [int], [MathRadical]) Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | [int] | The zero-based index of the row to get item |
| column | [int] | The zero-based index of the column to get item |


---


| [set_Item] ([int], [int], [MathBar]) Element of matrix |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| row | [int] | The zero-based index of the row to get item |
| column | [int] | The zero-based index of the column to get item |


---


