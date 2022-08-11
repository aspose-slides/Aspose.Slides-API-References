---
title: IRow
second_title: Aspose.Slides for Java API Reference
description:  Represents a row in a table.
type: docs
weight: 997
url: /java/com.aspose.slides/irow/
---
**All Implemented Interfaces:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IRow extends ICellCollection, IBulkTextFormattable
```

Represents a row in a table.
## Methods

| Method | Description |
| --- | --- |
| [getHeight()](#getHeight--) | Returns the height of a row. |
| [getMinimalHeight()](#getMinimalHeight--) | Returns or sets the minimal possible height of a row. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Returns or sets the minimal possible height of a row. |
| [getRowFormat()](#getRowFormat--) | Returns the RowFormat object that contains formatting properties for this row. |
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Returns the height of a row. Read-only double.

**Returns:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```


Returns or sets the minimal possible height of a row. Read/write double.

**Returns:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public abstract void setMinimalHeight(double value)
```


Returns or sets the minimal possible height of a row. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getRowFormat() {#getRowFormat--}
```
public abstract IRowFormat getRowFormat()
```


Returns the RowFormat object that contains formatting properties for this row. Read-only [IRowFormat](../../com.aspose.slides/irowformat).

**Returns:**
[IRowFormat](../../com.aspose.slides/irowformat)
