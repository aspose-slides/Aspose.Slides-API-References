---
title: GradientStopCollection
second_title: Aspose.Slides for Android via Java API Referansı
description: Gradient durak noktalarının bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/gradientstopcollection/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
```
public final class GradientStopCollection extends PVIObject implements IGradientStopCollection
```

Gradient durak noktalarının bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [size()](#size--) | Bir koleksiyondaki gradient durak noktalarının sayısını döndürür. |
| [get_Item(int index)](#get-Item-int-) | İndekse göre gradient durak noktasını döndürür. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | Yeni gradient durak noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Yeni gradient durak noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Yeni gradient durak noktasını oluşturur ve koleksiyonun sonuna ekler. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | Yeni gradient durak noktasını oluşturur ve koleksiyonda belirtilen indeksde ekler. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Yeni gradient durak noktasını oluşturur ve koleksiyonda belirtilen indeksde ekler. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Yeni gradient durak noktasını oluşturur ve koleksiyonda belirtilen indeksde ekler. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen indeksdeki bir gradient durak noktasını kaldırır. |
| [clear()](#clear--) | Bir koleksiyondan tüm gradient durak noktalarını kaldırır. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Koleksiyondaki tüm elemanları belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını belirten bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |

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

Bir koleksiyondaki gradient durak noktalarının sayısını döndürür. Salt okunur int.

**Döndürür:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IGradientStop get_Item(int index)
```

İndekse göre gradient durak noktasını döndürür.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public final IGradientStop add(float position, Integer color)
```

Yeni gradient durak noktasını oluşturur ve koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| position | float | Yeni gradient durak noktasının konumu. |
| color | java.lang.Integer | Yeni gradient durak noktasının rengi. |

**Döndürür:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Koleksiyondaki yeni gradient durak noktasının indeksi.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public final IGradientStop addPresetColor(float position, int presetColor)
```

Yeni gradient durak noktasını oluşturur ve koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| position | float | Yeni gradient durak noktasının konumu. |
| presetColor | int | Yeni gradient durak noktasının rengi. |

**Döndürür:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Koleksiyondaki yeni gradient durak noktasının indeksi.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public final IGradientStop addSchemeColor(float position, int schemeColor)
```

Yeni gradient durak noktasını oluşturur ve koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| position | float | Yeni gradient durak noktasının konumu. |
| schemeColor | int | Yeni gradient durak noktasının rengi. |

**Döndürür:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Koleksiyondaki yeni gradient durak noktasının indeksi.
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public final void insert(int index, float position, Integer color)
```

Yeni gradient durak noktasını oluşturur ve koleksiyonda belirtilen indeksde ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Yeni gradient durak noktasının ekleneceği koleksiyondaki indeks. |
| position | float | Yeni gradient durak noktasının konumu. |
| color | java.lang.Integer | Yeni gradient durak noktasının rengi. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public final void insertPresetColor(int index, float position, int presetColor)
```

Yeni gradient durak noktasını oluşturur ve koleksiyonda belirtilen indeksde ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Yeni gradient durak noktasının ekleneceği koleksiyondaki indeks. |
| position | float | Yeni gradient durak noktasının konumu. |
| presetColor | int | Yeni gradient durak noktasının rengi. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public final void insertSchemeColor(int index, float position, int schemeColor)
```

Yeni gradient durak noktasını oluşturur ve koleksiyonda belirtilen indeksde ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Yeni gradient durak noktasının ekleneceği koleksiyondaki indeks. |
| position | float | Yeni gradient durak noktasının konumu. |
| schemeColor | int | Yeni gradient durak noktasının rengi. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Belirtilen indeksdeki bir gradient durak noktasını kaldırır.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Silinmesi gereken gradient durak noktasının indeksi. |

### clear() {#clear--}
```
public final void clear()
```

Bir koleksiyondan tüm gradient durak noktalarını kaldırır.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iterator()
```

Koleksiyon içinde yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Koleksiyondaki tüm elemanları belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Hedef dizi. |
| index | int | Hedef dizideki başlangıç indeksi. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını belirten bir değer döndürür. Salt okunur boolean.

**Döndürür:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Bir senkronizasyon kökü döndürür. Salt okunur Object.

**Döndürür:**
java.lang.Object