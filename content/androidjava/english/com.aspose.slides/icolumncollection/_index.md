---
title: IColumnCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents collection of columns in a table.
type: docs
url: /com.aspose.slides/icolumncollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IColumnCollection extends IGenericCollection<IColumn>
```

Represents collection of columns in a table.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns the column at the specified index. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Creates a copy of the specified template row and inserts it at the bottom of a table. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Creates a copy of the specified template column and insert it at the specified position in a table. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Removes a column at the specified position from a table. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColumn get_Item(int index)
```


Returns the column at the specified index. Read-only [IColumn](../../com.aspose.slides/icolumn).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```


Creates a copy of the specified template row and inserts it at the bottom of a table.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Column which is used as a template. |
| withAttachedColumns | boolean | True to copy also all columns attached to the template row. |

**Returns:**
com.aspose.slides.IColumn[] - Added columns.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```


Creates a copy of the specified template column and insert it at the specified position in a table.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of a new column. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Column which is used as a template. |
| withAttachedColumns | boolean | True to copy also all columns attached to the template column. |

**Returns:**
com.aspose.slides.IColumn[] - Inserted columns.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstColumnIndex, boolean withAttachedRows)
```


Removes a column at the specified position from a table.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstColumnIndex | int | Index of a column to delete. |
| withAttachedRows | boolean | True to delete also all attached columns. |

