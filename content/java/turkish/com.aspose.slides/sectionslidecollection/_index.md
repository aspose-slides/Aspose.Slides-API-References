---
title: SectionSlideCollection
second_title: Aspose.Slides için Java API Referansı
description: Bölümdeki slaytların bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/sectionslidecollection/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)
```
public final class SectionSlideCollection extends DomObject<Section> implements ISectionSlideCollection
```

Bölümdeki slaytların bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen dizindeki öğeyi alır. |
| [size()](#size--) | Koleksiyon içinde gerçekte bulunan öğe sayısını alır. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Tüm koleksiyonu belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (istek güvenli) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir sayıcı döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java yineleyicisi döndürür. |
### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

Belirtilen dizindeki öğeyi alır. Salt-okunur [ISlide](../../com.aspose.slides/islide).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[ISlide](../../com.aspose.slides/islide)
### size() {#size--}
```
public final int size()
```

Koleksiyon içinde gerçekte bulunan öğe sayısını alır. Salt-okunur int.

**Döndürür:**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Tüm koleksiyonu belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Hedef dizi |
| index | int | Hedef dizideki dizin. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Koleksiyona erişimin senkronize (istek güvenli) olup olmadığını gösteren bir değer döndürür. Salt-okunur boolean.

**Döndürür:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Bir senkronizasyon kökü döndürür. Salt-okunur Object.

**Döndürür:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

Koleksiyon içinde yineleme yapan bir sayıcı döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Koleksiyon içinde yineleme yapmak için kullanılabilen bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

Tüm koleksiyon için bir java yineleyicisi döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Tüm koleksiyon için bir java.util.Iterator.