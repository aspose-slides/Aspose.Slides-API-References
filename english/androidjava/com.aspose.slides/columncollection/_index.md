---
title: ColumnCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents collection of columns in a table.
type: docs
weight: 121
url: /androidjava/com.aspose.slides/columncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IColumnCollection](../../com.aspose.slides/icolumncollection)
```
public final class ColumnCollection extends DomObject<RowCollection> implements IColumnCollection
```

Represents collection of columns in a table.
## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | Returns the number of columns in a collection. |
| [get_Item(int index)](#get-Item-int-) | Returns the column at the specified index. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Creates a copy of the specified template row and inserts it at the bottom of a table. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Creates a copy of the specified template column and insert it at the specified position in a table. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Removes a column at the specified position from a table. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies all elements from the collection to the specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
### size() {#size--}
```
public final int size()
```


Returns the number of columns in a collection. Read-only int.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColumn get_Item(int index)
```


Returns the column at the specified index. Read-only [Column](../../com.aspose.slides/column).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
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
public final IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
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
public final void removeAt(int firstColumnIndex, boolean withAttachedRows)
```


Removes a column at the specified position from a table.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstColumnIndex | int | Index of a column to delete. |
| withAttachedRows | boolean | True to delete also all attached columns. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iteratorJava()
```


Returns a java iterator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - An java.util.Iterator for the entire collection.
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
