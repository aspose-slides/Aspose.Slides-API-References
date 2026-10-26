---
title: ColumnCollection
second_title: Aspose.Slides Android için Java API Referansı
description: Bir tabloda sütun koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/columncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IColumnCollection](../../com.aspose.slides/icolumncollection)
```
public final class ColumnCollection extends DomObject<RowCollection> implements IColumnCollection
```

Represents collection of columns in a table.
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [size()](#size--) | Bir koleksiyondaki sütun sayısını döndürür. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki sütunu döndürür. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Belirtilen şablon satırının bir kopyasını oluşturur ve bir tablonun altına ekler. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Belirtilen şablon sütununun bir kopyasını oluşturur ve bir tabloda belirtilen konuma ekler. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Bir tablodan belirtilen konumdaki sütunu kaldırır. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin eşzamanlı (thread-safe) olup olmadığını belirten bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
### size() {#size--}
```
public final int size()
```

Bir koleksiyondaki sütun sayısını döndürür. Salt-okunur int.

**Döndürür:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColumn get_Item(int index)
```

Belirtilen indeksteki sütunu döndürür. Salt-okunur [Column](../../com.aspose.slides/column).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

Belirtilen şablon satırının bir kopyasını oluşturur ve bir tablonun altına ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Şablon olarak kullanılan sütun. |
| withAttachedColumns | boolean | Şablon satıra eklenmiş tüm sütunları da kopyalamak için true. |

**Döndürür:**
com.aspose.slides.IColumn[] - Eklenen sütunlar.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

Belirtilen şablon sütununun bir kopyasını oluşturur ve bir tabloda belirtilen konuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni bir sütunun indeksi. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Şablon olarak kullanılan sütun. |
| withAttachedColumns | boolean | Şablon sütuna eklenmiş tüm sütunları da kopyalamak için true. |

**Döndürür:**
com.aspose.slides.IColumn[] - Eklenen sütunlar.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

Bir tablodan belirtilen konumdaki sütunu kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| firstColumnIndex | int | Silinecek bir sütunun indeksi. |
| withAttachedRows | boolean | Eklenmiş tüm sütunları da silmek için true. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iterator()
```

Koleksiyon içinde yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - Koleksiyon içinde yineleme yapmak için kullanılabilen bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - Tüm koleksiyon için bir java.util.Iterator.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Hedef dizi. |
| index | int | Hedef dizideki başlangıç indeksi. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Koleksiyona erişimin eşzamanlı (thread-safe) olup olmadığını belirten bir değer döndürür. Salt-okunur boolean.

**Döndürür:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Bir senkronizasyon kökü döndürür. Salt-okunur Object.

**Döndürür:**
java.lang.Object