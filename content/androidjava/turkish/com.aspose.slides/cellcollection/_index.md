---
title: CellCollection
second_title: Aspose.Slides for Android via Java API Referansı
description: Hücrelerin bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/cellcollection/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), com.aspose.slides.IDOMObject
```
public abstract class CellCollection implements ICellCollection, IDOMObject
```

Hücrelerin bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [size()](#size--) | Bir koleksiyondaki hücre sayısını döndürür. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen konumdaki bir hücreyi döndürür. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iteratörü döndürür. |
| [getSlide()](#getSlide--) | CellCollection nesnesinin üst slaytını döndürür. |
| [getPresentation()](#getPresentation--) | CellCollection nesnesinin üst sunumunu döndürür. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Yalnızca okunabilir IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject
### size() {#size--}
```
public final int size()
```

Bir koleksiyondaki hücre sayısını döndürür. Yalnızca okunabilir int.

**Döndürür:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICell get_Item(int index)
```

Belirtilen konumdaki bir hücreyi döndürür. Yalnızca okunabilir [Cell](../../com.aspose.slides/cell).

--------------------

Bir hücre birleştirilmişse, aynı hücre nesnesi birden fazla indeks için döndürülebilir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[ICell](../../com.aspose.slides/icell)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iterator()
```

Koleksiyon içinde yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iteratorJava()
```

Tüm koleksiyon için bir java iteratörü döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - An java.util.Iterator for the entire collection.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

CellCollection nesnesinin üst slaytını döndürür. Yalnızca okunabilir [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Döndürür:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

CellCollection nesnesinin üst sunumunu döndürür. Yalnızca okunabilir [IPresentation](../../com.aspose.slides/ipresentation).

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation)
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

Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. Yalnızca okunabilir boolean.

**Döndürür:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Bir senkronizasyon kökü döndürür. Yalnızca okunabilir Object.

**Döndürür:**
java.lang.Object