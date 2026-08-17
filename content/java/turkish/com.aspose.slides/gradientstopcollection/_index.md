---
title: GradientStopCollection
second_title: Aspose.Slides for Java API Referansı
description: Gradient duraklarının bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/gradientstopcollection/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
```
public final class GradientStopCollection extends PVIObject implements IGradientStopCollection
```

Gradient duraklarının bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [size()](#size--) | Returns the number of gradient stops in a collection. |
| [get_Item(int index)](#get-Item-int-) | Returns the gradient stop by index. |
| [add(float position, Color color)](#add-float-java.awt.Color-) | Creates the new gradient stop and adds it to the end of collection. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Creates the new gradient stop and adds it to the end of collection. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Creates the new gradient stop and adds it to the end of collection. |
| [insert(int index, float position, Color color)](#insert-int-float-java.awt.Color-) | Creates the new gradient stop and inserts it at the specified index to the collection. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Creates the new gradient stop and inserts it at the specified index to the collection. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Creates the new gradient stop and inserts it at the specified index to the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes a gradient stop at the specified index. |
| [clear()](#clear--) | Removes all gradient stops from a collection. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies all elements from the collection to the specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Sürüm. Salt okunur long.

**Döndürür:**
long
### size() {#size--}
```
public final int size()
```


Koleksiyondaki gradient duraklarının sayısını döndürür. Salt okunur int .

**Döndürür:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IGradientStop get_Item(int index)
```


İndex ile gradient durakını döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Color color) {#add-float-java.awt.Color-}
```
public final IGradientStop add(float position, Color color)
```


Yeni gradient durakını oluşturur ve koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | float | Yeni gradient durakının konumu. |
| color | java.awt.Color | Yeni gradient durakının rengi. |

**Döndürür:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Koleksiyondaki yeni gradient durakının indeksi.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public final IGradientStop addPresetColor(float position, int presetColor)
```


Yeni gradient durakını oluşturur ve koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | float | Yeni gradient durakının konumu. |
| presetColor | int | Yeni gradient durakının rengi. |

**Döndürür:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Koleksiyondaki yeni gradient durakının indeksi.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public final IGradientStop addSchemeColor(float position, int schemeColor)
```


Yeni gradient durakını oluşturur ve koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | float | Yeni gradient durakının konumu. |
| schemeColor | int | Yeni gradient durakının rengi. |

**Döndürür:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Koleksiyondaki yeni gradient durakının indeksi.
### insert(int index, float position, Color color) {#insert-int-float-java.awt.Color-}
```
public final void insert(int index, float position, Color color)
```


Yeni gradient durakını oluşturur ve belirtilen indeksde koleksiyona ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni gradient durakının ekleneceği koleksiyondaki indeks. |
| position | float | Yeni gradient durakının konumu. |
| color | java.awt.Color | Yeni gradient durakının rengi. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public final void insertPresetColor(int index, float position, int presetColor)
```


Yeni gradient durakını oluşturur ve belirtilen indeksde koleksiyona ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni gradient durakının ekleneceği koleksiyondaki indeks. |
| position | float | Yeni gradient durakının konumu. |
| presetColor | int | Yeni gradient durakının rengi. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public final void insertSchemeColor(int index, float position, int schemeColor)
```


Yeni gradient durakını oluşturur ve belirtilen indeksde koleksiyona ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni gradient durakının ekleneceği koleksiyondaki indeks. |
| position | float | Yeni gradient durakının konumu. |
| schemeColor | int | Yeni gradient durakının rengi. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Belirtilen indeksdeki gradient durakını kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Silinmesi gereken gradient durakının indeksi. |

### clear() {#clear--}
```
public final void clear()
```


Koleksiyondaki tüm gradient duraklarını kaldırır.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iterator()
```


Koleksiyon içinde dolaşan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - Koleksiyon içinde dolaşmak için kullanılabilecek bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iteratorJava()
```


Koleksiyonun tamamı için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - Tam koleksiyon için bir java.util.Iterator.
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


Koleksiyona erişimin senkronize (thread-safe) olup olmadığını gösteren bir değer döndürür. Salt okunur boolean .

**Döndürür:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Bir senkronizasyon kökü döndürür. Salt okunur Object.

**Döndürür:**
java.lang.Object