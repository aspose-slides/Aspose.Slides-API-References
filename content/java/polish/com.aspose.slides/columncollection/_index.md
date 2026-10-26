---
title: ColumnCollection
second_title: Aspose.Slides dla Java - Dokumentacja API
description: Reprezentuje kolekcję kolumn w tabeli.
type: docs
url: /pl/com.aspose.slides/columncollection/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.slides.DomObject

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IColumnCollection](../../com.aspose.slides/icolumncollection)
```
public final class ColumnCollection extends DomObject<RowCollection> implements IColumnCollection
```

Reprezentuje kolekcję kolumn w tabeli.
## Metody

| Metoda | Opis |
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


Zwraca liczbę kolumn w kolekcji. Tylko do odczytu int.

**Zwraca:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColumn get_Item(int index)
```


Zwraca kolumnę o określonym indeksie. Tylko do odczytu [Column](../../com.aspose.slides/column).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```


Creates a copy of the specified template row and inserts it at the bottom of a table.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Column which is used as a template. |
| withAttachedColumns | boolean | True to copy also all columns attached to the template row. |

**Zwraca:**
com.aspose.slides.IColumn[] - Added columns.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```


Creates a copy of the specified template column and insert it at the specified position in a table.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Index of a new column. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Column which is used as a template. |
| withAttachedColumns | boolean | True to copy also all columns attached to the template column. |

**Zwraca:**
com.aspose.slides.IColumn[] - Inserted columns.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstColumnIndex, boolean withAttachedRows)
```


Removes a column at the specified position from a table.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| firstColumnIndex | int | Index of a column to delete. |
| withAttachedRows | boolean | True to delete also all attached columns. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iterator()
```


Returns an enumerator that iterates through the collection.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iteratorJava()
```


Returns a java iterator for the entire collection.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copies all elements from the collection to the specified array.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Target array. |
| index | int | Starting index in the target array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Returns a value indicating whether access to the collection is synchronized (thread-safe). Tylko do odczytu boolean.

**Zwraca:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Returns a synchronization root. Tylko do odczytu Object.

**Zwraca:**
java.lang.Object