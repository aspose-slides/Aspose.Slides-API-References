---
title: RowCollection
second_title: Aspose.Slides for Android via Java API Referansı
description: Tablo satır koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/rowcollection/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IRowCollection](../../com.aspose.slides/irowcollection)
```
public final class RowCollection extends DomObject<Table> implements IRowCollection
```

Tablo satır koleksiyonunu temsil eder.
## Metotlar

| Yöntem | Açıklama |
| --- | --- |
| [size()](#size--) | Koleksiyonda gerçekte bulunan satır sayısını alır. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen dizindeki satırı döndürür. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Belirtilen şablon satırının bir kopyasını oluşturur ve bir tablonun altına ekler. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Belirtilen şablon satırının bir kopyasını oluşturur ve tablo içinde belirtilen konuma ekler. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Bir tablodan belirtilen konumdaki satırı kaldırır. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iteratoru döndürür. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Koleksiyondaki tüm elemanları belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Erişimin senkronize (thread-safe) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
### size() {#size--}
```
public final int size()
```

Koleksiyonda gerçekte bulunan satır sayısını alır. Yalnızca okunabilir int.

**Döndürür:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IRow get_Item(int index)
```

Belirtilen dizindeki satırı döndürür. Yalnızca okunabilir [Row](../../com.aspose.slides/row).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public final IRow[] addClone(IRow templ, boolean withAttachedRows)
```

Belirtilen şablon satırının bir kopyasını oluşturur ve bir tablonun altına ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Şablon olarak kullanılan satır. |
| withAttachedRows | boolean | Şablon satıra bağlı tüm satırların da kopyalanması için doğru. |

**Döndürür:**
com.aspose.slides.IRRow[] - Eklenen satırlar.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public final IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

Belirtilen şablon satırının bir kopyasını oluşturur ve tablo içinde belirtilen konuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni bir satırın indeksi. |
| templ | [IRow](../../com.aspose.slides/irow) | Şablon olarak kullanılan satır. |
| withAttachedRows | boolean | Şablon satıra bağlı tüm satırların da kopyalanması için doğru. |

**Döndürür:**
com.aspose.slides.IRRow[] - Eklenen satırlar.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstRowIndex, boolean withAttachedRows)
```

Bir tablodan belirtilen konumdaki satırı kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| firstRowIndex | int | Silinecek satırın indeksi. |
| withAttachedRows | boolean | Bağlı tüm satırların da silinmesi için doğru. |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iterator()
```

Koleksiyon içinde yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - Koleksiyon içinde yineleme için kullanılabilecek bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iteratorJava()
```

Tüm koleksiyon için bir java iteratoru döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - Tüm koleksiyon için bir java.util.Iterator.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Koleksiyondaki tüm elemanları belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Hedef dizi. |
| index | int | Hedef dizideki başlangıç indeksi. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Erişimin senkronize (thread-safe) olup olmadığını gösteren bir değer döndürür. Yalnızca okunabilir boolean.

**Döndürür:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Bir senkronizasyon kökü döndürür. Yalnızca okunabilir Object.

**Döndürür:**
java.lang.Object