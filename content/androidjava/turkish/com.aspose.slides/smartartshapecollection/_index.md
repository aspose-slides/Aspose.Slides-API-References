---
title: SmartArtShapeCollection
second_title: Aspose.Slides for Android Java API Referansı
description: SmartArt şekillerinin bir koleksiyonunu temsil eder
type: docs
url: /tr/com.aspose.slides/smartartshapecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
```
public class SmartArtShapeCollection implements ISmartArtShapeCollection
```

SmartArt şekillerinin bir koleksiyonunu temsil eder
## Yöntemler

| Method | Description |
| --- | --- |
| [size()](#size--) | Koleksiyonda gerçekten bulunan öğelerin sayısını alır. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen dizindeki öğeyi alır. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (iş parçacığı-güvenli) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator'ı döndürür. |
### size() {#size--}
```
public final int size()
```


Koleksiyonda gerçekten bulunan öğelerin sayısını alır. Yalnızca okunabilir int.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtShape get_Item(int index)
```


Belirtilen dizindeki öğeyi alır. Yalnızca okunabilir [SmartArtShape](../../com.aspose.slides/smartartshape).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Şeklin dizini |

**Döndürür:**
[ISmartArtShape](../../com.aspose.slides/ismartartshape) - SmartArt şekli
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Koleksiyona erişimin senkronize (iş parçacığı-güvenli) olup olmadığını gösteren bir değer döndürür. Yalnızca okunabilir boolean.

**Döndürür:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Bir senkronizasyon kökü döndürür. Yalnızca okunabilir Object.

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
| index | int | Hedef dizideki başlangıç dizini. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iterator()
```


Koleksiyon içinde yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - Koleksiyon içinde yineleme yapılabilen bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iteratorJava()
```


Tüm koleksiyon için bir java iterator'ı döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - Tüm koleksiyon için bir java.util.Iterator.