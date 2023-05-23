---
title: RowCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents table row collection.
type: docs
weight: 473
url: /androidjava/com.aspose.slides/rowcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IRowCollection](../../com.aspose.slides/irowcollection)
```
public final class RowCollection extends DomObject<Table> implements IRowCollection
```

Represents table row collection.
## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | Gets the number of rows actually contained in the collection. |
| [get_Item(int index)](#get-Item-int-) | Returns the row at the specified index. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Creates a copy of the specified template row and inserts it at the bottom of a table. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Creates a copy of the specified template row and insert it at the specified position in a table. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Removes a row at the specified position from a table. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies all elements from the collection to the specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
### size() {#size--}
```
public final int size()
```


Gets the number of rows actually contained in the collection. Read-only int.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IRow get_Item(int index)
```


Returns the row at the specified index. Read-only [Row](../../com.aspose.slides/row).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public final IRow[] addClone(IRow templ, boolean withAttachedRows)
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
public final IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
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
public final void removeAt(int firstRowIndex, boolean withAttachedRows)
```


Removes a row at the specified position from a table.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstRowIndex | int | Index of a row to delete. |
| withAttachedRows | boolean | True to delete also all attached rows. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iteratorJava()
```


Returns a java iterator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copies all elements from the collection to the specified array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Target array. |
| index | int | Starting index in the target array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Returns a synchronization root. Read-only Object.

**Returns:**
java.lang.Object
