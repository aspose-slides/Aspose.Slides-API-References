---
title: LayoutSlideCollection
second_title: Aspose.Slides Android için Java API Referansı
description: Yerleşim slaytlarından oluşan bir koleksiyon için temel sınıfı temsil eder.
type: docs
url: /tr/com.aspose.slides/layoutslidecollection/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection), com.aspose.slides.IDOMObject
```
public class LayoutSlideCollection implements ILayoutSlideCollection, IDOMObject
```

Yerleşim slaytlarından oluşan bir koleksiyon için temel sınıfı temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [size()](#size--) | Bir koleksiyondaki yerleşim slaytlarının sayısını döndürür. |
| [get_Item(int index)](#get-Item-int-) | İndeksine göre yerleşim slaytını döndürür. |
| [getByType(byte type)](#getByType-byte-) | Belirtilen türdeki ilk yerleşim slaytını döndürür. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Koleksiyondan bir yerleşim kaldırır. |
| [removeUnused()](#removeUnused--) | Kullanılmayan yerleşim slaytlarını kaldırır (HasDependingSlides özelliği false olan yerleşim slaytları). |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Koleksiyondan tüm elemanları belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (thread-safe) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```

Bir koleksiyondaki yerleşim slaytlarının sayısını döndürür. Salt okunur int.

**Döndürür:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ILayoutSlide get_Item(int index)
```

İndeksine göre yerleşim slaytını döndürür. Salt okunur [LayoutSlide](../../com.aspose.slides/layoutslide).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public final ILayoutSlide getByType(byte type)
```

Belirtilen türdeki ilk yerleşim slaytını döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | byte | Bulunacak yerleşim slaytının türü. |

**Döndürür:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [LayoutSlide](../../com.aspose.slides/layoutslide) belirtilen türde veya hiçbir yerleşim bulunamazsa null.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public final void remove(ILayoutSlide value)
```

Koleksiyondan bir yerleşim kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Koleksiyondan kaldırılacak yerleşim slaytı.

--------------------

1) PptxEditException'ın atılmasını önlemek için önce yerleşimin HasDependingSlides özelliğini kontrol edin. 2) Kodu basitleştirmek için ayrıca [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) yöntemini kullanabilirsiniz. |
### removeUnused() {#removeUnused--}
```
public final void removeUnused()
```

Kullanılmayan yerleşim slaytlarını kaldırır (HasDependingSlides özelliği false olan yerleşim slaytları).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iterator()
```

Koleksiyon içinde yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - Koleksiyon içinde yineleme için kullanılabilen bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - Tüm koleksiyon için bir java.util.Iterator.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Koleksiyondan tüm elemanları belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Hedef dizi. |
| index | int | Hedef dizideki başlangıç indeksi. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Koleksiyona erişimin senkronize (thread-safe) olup olmadığını gösteren bir değer döndürür. Salt okunur boolean.

**Döndürür:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Bir senkronizasyon kökü döndürür. Salt okunur Object.

**Döndürür:**
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Salt okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject