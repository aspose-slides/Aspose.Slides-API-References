---
title: IColumn
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a column in a table.
type: docs
weight: 722
url: /androidjava/com.aspose.slides/icolumn/
---
**All Implemented Interfaces:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IColumn extends ICellCollection, IBulkTextFormattable
```

Represents a column in a table.
## Methods

| Method | Description |
| --- | --- |
| [getWidth()](#getWidth--) | Returns or sets the width of a column. |
| [setWidth(double value)](#setWidth-double-) | Returns or sets the width of a column. |
| [getColumnFormat()](#getColumnFormat--) | Returns the ColumnFormat object that contains formatting properties for this column. |
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Returns or sets the width of a column. Read/write double.

**Returns:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```


Returns or sets the width of a column. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getColumnFormat() {#getColumnFormat--}
```
public abstract IColumnFormat getColumnFormat()
```


Returns the ColumnFormat object that contains formatting properties for this column. Read-only [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Returns:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)
