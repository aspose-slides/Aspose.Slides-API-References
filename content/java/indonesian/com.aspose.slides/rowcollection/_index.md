---
title: RowCollection
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili koleksi baris tabel.
type: docs
url: /id/com.aspose.slides/rowcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IRowCollection](../../com.aspose.slides/irowcollection)
```
public final class RowCollection extends DomObject<Table> implements IRowCollection
```

Represents table row collection.
## Metode

| Metode | Deskripsi |
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


Gets the number of rows actually contained in the collection. Baca-saja int.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IRow get_Item(int index)
```


Returns the row at the specified index. Baca-saja [Row](../../com.aspose.slides/row).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public final IRow[] addClone(IRow templ, boolean withAttachedRows)
```


Creates a copy of the specified template row and inserts it at the bottom of a table.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Baris yang digunakan sebagai templat. |
| withAttachedRows | boolean | True untuk menyalin juga semua baris yang terlampir pada baris templat. |

**Returns:**
com.aspose.slides.IRow[] - Baris yang ditambahkan.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public final IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```


Creates a copy of the specified template row and insert it at the specified position in a table.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks baris baru. |
| templ | [IRow](../../com.aspose.slides/irow) | Baris yang digunakan sebagai templat. |
| withAttachedRows | boolean | True untuk menyalin juga semua baris yang terlampir pada baris templat. |

**Returns:**
com.aspose.slides.IRow[] - Baris yang disisipkan.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstRowIndex, boolean withAttachedRows)
```


Removes a row at the specified position from a table.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| firstRowIndex | int | Indeks baris yang akan dihapus. |
| withAttachedRows | boolean | True untuk menghapus juga semua baris terlampir. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - IGenericEnumerator yang dapat digunakan untuk mengiterasi koleksi.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iteratorJava()
```


Returns a java iterator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - Iterator java.util.Iterator untuk seluruh koleksi.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copies all elements from the collection to the specified array.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array target. |
| index | int | Indeks mulai di array target. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Returns a value indicating whether access to the collection is synchronized (thread-safe). Baca-saja boolean.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Returns a synchronization root. Baca-saja Object.

**Returns:**
java.lang.Object