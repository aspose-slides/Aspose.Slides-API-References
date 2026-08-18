---
title: AdjustValueCollection
second_title: Aspose.Slides for Java API Referansı
description: Şekil ayarlamalarının bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/adjustvaluecollection/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
```
public final class AdjustValueCollection extends DomObject<GeometryShape> implements IAdjustValueCollection
```

Bir şeklin ayarlamalarının koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [size()](#size--) | Ayarlamaların sayısını döndürür. |
| [get_Item(int index)](#get-Item-int-) | Dizine göre ayarlamayı döndürür. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını belirten bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
| [iterator()](#iterator--) | Tüm koleksiyon için bir yineleyici döndürür. |
### size() {#size--}
```
public final int size()
```

Ayarlamaların sayısını döndürür. Salt okunur int.

**Döndürür:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAdjustValue get_Item(int index)
```

Dizine göre ayarlamayı döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | ayarlamanın indeksi. |

**Döndürür:**
[IAdjustValue](../../com.aspose.slides/iadjustvalue) - [AdjustValue](../../com.aspose.slides/adjustvalue).
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
### iterator() {#iterator--}
```
public final System.Collections.IEnumerator iterator()
```

Tüm koleksiyon için bir yineleyici döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.IEnumerator