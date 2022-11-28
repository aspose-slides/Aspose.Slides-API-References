---
title: IRowCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents table row collection.
type: docs
weight: 1003
url: /androidjava/com.aspose.slides/irowcollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IRowCollection extends IGenericCollection<IRow>
```

Represents table row collection.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Creates a copy of the specified template row and inserts it at the bottom of a table. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Creates a copy of the specified template row and insert it at the specified position in a table. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Removes a row at the specified position from a table. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```


Gets the element at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] addClone(IRow templ, boolean withAttachedRows)
```


Creates a copy of the specified template row and inserts it at the bottom of a table.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Row which is used as a template. |
| withAttachedRows | boolean | True to copy also all rows attached to the template row. |

**Returns:**
com.aspose.slides.IRow[] - Added rows.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```


Creates a copy of the specified template row and insert it at the specified position in a table.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of a new row. |
| templ | [IRow](../../com.aspose.slides/irow) | Row which is used as a template. |
| withAttachedRows | boolean | True to copy also all rows attached to the template row. |

**Returns:**
com.aspose.slides.IRow[] - Inserted rows.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```


Removes a row at the specified position from a table.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstRowIndex | int | Index of a row to delete. |
| withAttachedRows | boolean | True to delete also all attached rows. |

