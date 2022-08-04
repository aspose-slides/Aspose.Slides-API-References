---
title: Cell
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents a cell of a table.
type: docs
weight: 70
url: /java/com.aspose.slides/cell/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.slides.IDOMObject, [com.aspose.slides.ICell](../../com.aspose.slides/icell)
```
public class Cell implements IDOMObject, ICell
```

Represents a cell of a table.
## Constructors

| Constructor | Description |
| --- | --- |
| [Cell(Row parentRow, Column parentColumn)](#Cell-com.aspose.slides.Row-com.aspose.slides.Column-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | Returns a distance from left side of a table to left side of a cell. |
| [getOffsetY()](#getOffsetY--) | Returns a distance from top side of a table to top side of a cell. |
| [getFirstRowIndex()](#getFirstRowIndex--) | Returns an index of first row, covered by the cell. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | Returns an index of first column, covered by the cell. |
| [getWidth()](#getWidth--) | Returns the width of the cell. |
| [getHeight()](#getHeight--) | Returns the height of the cell. |
| [getMinimalHeight()](#getMinimalHeight--) | Returns the minimum height of a cell. |
| [getMarginLeft()](#getMarginLeft--) | Returns or sets the left margin in a TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Returns or sets the left margin in a TextFrame. |
| [getMarginRight()](#getMarginRight--) | Returns or sets the right margin in a TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Returns or sets the right margin in a TextFrame. |
| [getMarginTop()](#getMarginTop--) | Returns or sets the top margin in a TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Returns or sets the top margin in a TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Returns or sets the bottom margin in a TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Returns or sets the bottom margin in a TextFrame. |
| [getTextVerticalType()](#getTextVerticalType--) | Returns or sets the type of vertical text. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Returns or sets the type of vertical text. |
| [getTextAnchorType()](#getTextAnchorType--) | Returns or sets the text anchor type. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | Returns or sets the text anchor type. |
| [getAnchorCenter()](#getAnchorCenter--) | Determines whether or not text box centered inside a cell. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | Determines whether or not text box centered inside a cell. |
| [getFirstRow()](#getFirstRow--) | Gets first row of cell. |
| [getFirstColumn()](#getFirstColumn--) | Gets first column of cell. |
| [getColSpan()](#getColSpan--) | Returns the number of grid columns in the parent table's table grid which shall be spanned by the current cell. |
| [getRowSpan()](#getRowSpan--) | Returns the number of rows that a merged cell spans. |
| [getTextFrame()](#getTextFrame--) | Returns the text frame of a cell. |
| [getTable()](#getTable--) | Returns the parent Table object for a cell. |
| [isMergedCell()](#isMergedCell--) | Returns true if the cell is merged with any adjusted cell, false otherwise. |
| [getCellFormat()](#getCellFormat--) | Returns the CellFormat object that contains formatting properties for this cell. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | Splits the cell to two cells by index of column. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | Splits the cell to two cells by index of row. |
| [splitByHeight(double height)](#splitByHeight-double-) | Splits the cell by height. |
| [splitByWidth(double width)](#splitByWidth-double-) | Splits the cell by width. |
| [getSlide()](#getSlide--) | Returns the parent slide of a cell. |
| [getPresentation()](#getPresentation--) | Returns the parent presentation of a cell. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Cell(Row parentRow, Column parentColumn) {#Cell-com.aspose.slides.Row-com.aspose.slides.Column-}
```
 Cell(Row parentRow, Column parentColumn)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentRow | [Row](../../com.aspose.slides/row) |  |
| parentColumn | [Column](../../com.aspose.slides/column) |  |

### getOffsetX() {#getOffsetX--}
```
public final double getOffsetX()
```


Returns a distance from left side of a table to left side of a cell. Read-only double.

**Returns:**
double
### getOffsetY() {#getOffsetY--}
```
public final double getOffsetY()
```


Returns a distance from top side of a table to top side of a cell. Read-only double.

**Returns:**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public final int getFirstRowIndex()
```


Returns an index of first row, covered by the cell. Read-only int.

**Returns:**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public final int getFirstColumnIndex()
```


Returns an index of first column, covered by the cell. Read-only int.

**Returns:**
int
### getWidth() {#getWidth--}
```
public final double getWidth()
```


Returns the width of the cell. Read-only double.

**Returns:**
double
### getHeight() {#getHeight--}
```
public final double getHeight()
```


Returns the height of the cell. Read-only double.

**Returns:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```


Returns the minimum height of a cell. This is a sum of minimal heights of all rows cowered by the cell. Read-only double.

**Returns:**
double
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```


Returns or sets the left margin in a TextFrame. Read/write double.

**Returns:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```


Returns or sets the left margin in a TextFrame. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```


Returns or sets the right margin in a TextFrame. Read/write double.

**Returns:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```


Returns or sets the right margin in a TextFrame. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```


Returns or sets the top margin in a TextFrame. Read/write double.

**Returns:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```


Returns or sets the top margin in a TextFrame. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```


Returns or sets the bottom margin in a TextFrame. Read/write double.

**Returns:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```


Returns or sets the bottom margin in a TextFrame. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```


Returns or sets the type of vertical text. Read/write [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Returns:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```


Returns or sets the type of vertical text. Read/write [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTextAnchorType() {#getTextAnchorType--}
```
public final byte getTextAnchorType()
```


Returns or sets the text anchor type. Read/write [TextAnchorType](../../com.aspose.slides/textanchortype).

**Returns:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public final void setTextAnchorType(byte value)
```


Returns or sets the text anchor type. Read/write [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getAnchorCenter() {#getAnchorCenter--}
```
public final boolean getAnchorCenter()
```


Determines whether or not text box centered inside a cell. Read/write boolean.

**Returns:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public final void setAnchorCenter(boolean value)
```


Determines whether or not text box centered inside a cell. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final IRow getFirstRow()
```


Gets first row of cell. Read-only [IRow](../../com.aspose.slides/irow).

**Returns:**
[IRow](../../com.aspose.slides/irow)
### getFirstColumn() {#getFirstColumn--}
```
public final IColumn getFirstColumn()
```


Gets first column of cell. Read-only [IColumn](../../com.aspose.slides/icolumn).

**Returns:**
[IColumn](../../com.aspose.slides/icolumn)
### getColSpan() {#getColSpan--}
```
public final int getColSpan()
```


Returns the number of grid columns in the parent table's table grid which shall be spanned by the current cell. This property allows cells to have the appearance of being merged, as they span vertical boundaries of other cells in the table. Read-only int.

**Returns:**
int
### getRowSpan() {#getRowSpan--}
```
public final int getRowSpan()
```


Returns the number of rows that a merged cell spans. This is used in combination with the vMerge attribute on other cells in order to specify the beginning cell of a horizontal merge. Read-only int.

**Returns:**
int
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```


Returns the text frame of a cell. Read-only [ITextFrame](../../com.aspose.slides/itextframe).

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public final ITable getTable()
```


Returns the parent Table object for a cell. Read-only [ITable](../../com.aspose.slides/itable).

**Returns:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public final boolean isMergedCell()
```


Returns true if the cell is merged with any adjusted cell, false otherwise. Read-only boolean.

**Returns:**
boolean
### getCellFormat() {#getCellFormat--}
```
public final ICellFormat getCellFormat()
```


Returns the CellFormat object that contains formatting properties for this cell. Read-only [ICellFormat](../../com.aspose.slides/icellformat).

**Returns:**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public final void splitByColSpan(int index)
```


Splits the cell to two cells by index of column.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of column. |

### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public final void splitByRowSpan(int index)
```


Splits the cell to two cells by index of row.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of row. |

### splitByHeight(double height) {#splitByHeight-double-}
```
public final void splitByHeight(double height)
```


Splits the cell by height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| height | double | Height of a row. |

### splitByWidth(double width) {#splitByWidth-double-}
```
public final void splitByWidth(double width)
```


Splits the cell by width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | double | Width of a column. |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Returns the parent slide of a cell. Read-only [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Returns the parent presentation of a cell. Read-only [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
