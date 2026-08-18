---
title: SmartArtShapeCollection
second_title: Aspose.Slides for Java API Referansı
description: SmartArt şekillerinin bir koleksiyonunu temsil eder
type: docs
url: /tr/com.aspose.slides/smartartshapecollection/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
```
public class SmartArtShapeCollection implements ISmartArtShapeCollection
```

SmartArt şekillerinin bir koleksiyonunu temsil eder
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [size()](#size--) | Koleksiyonun gerçekte içerdiği eleman sayısını alır. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [isSynchronized()](#isSynchronized--) | Erişimin koleksiyona senkronize (iş parçacığı güvenli) olup olmadığını belirten bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Senkronizasyon kökü döndürür. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
### size() {#size--}
```
public final int size()
```

Koleksiyonun gerçekte içerdiği öğe sayısını alır. Salt okunur int.

**Döndürür:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtShape get_Item(int index)
```

Belirtilen indeksteki öğeyi alır. Salt okunur [SmartArtShape](../../com.aspose.slides/smartartshape).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Şeklin indeksi |

**Döndürür:**
[ISmartArtShape](../../com.aspose.slides/ismartartshape) - SmartArt şekli
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Erişimin koleksiyona senkronize (iş parçacığı güvenli) olup olmadığını belirten bir değer döndürür. Salt okunur boolean.

**Döndürür:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Senkronizasyon kökü döndürür. Salt okunur Object.

**Döndürür:**
java.lang.Object
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

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iterator()
```

Koleksiyon içinde yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - Bir IGenericEnumerator, koleksiyon içinde yineleme yapmak için kullanılabilir.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - Tüm koleksiyon için bir java.util.Iterator.