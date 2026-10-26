---
title: MotionPath
second_title: Aspose.Slides for Java API Referansı
description: Hareket yolunu temsil eder.
type: docs
url: /tr/com.aspose.slides/motionpath/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IMotionPath](../../com.aspose.slides/imotionpath)
```
public class MotionPath implements IMotionPath
```

Hareket yolunu temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MotionPath()](#MotionPath--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#add-int-java.awt.geom.Point2D.Float---int-boolean-) | Yola yeni komut ekle |
| [getCount()](#getCount--) | Koleksiyondaki yol sayısını döndürür. |
| [insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-) | Yola yeni komut ekle |
| [clear()](#clear--) | Koleksiyondaki tüm komutları kaldırır. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Koleksiyondan belirtilen komutları kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen indeksteki bir komutu kaldırır. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki bir komutu döndürür. |
| [iterator()](#iterator--) | Koleksiyon üzerinden yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
### MotionPath() {#MotionPath--}
```
public MotionPath()
```


### add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#add-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final IMotionCmdPath add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


Yola yeni komut ekle

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Nokta dizisi |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Göreceli koordinatlar boolean |

**Döndürür:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public final int getCount()
```


Koleksiyondaki yol sayısını döndürür. Salt okunur int.

**Döndürür:**
int
### insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final void insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


Yola yeni komut ekle

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | The zero-based index at which item should be inserted. |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Nokta dizisi |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Göreceli koordinatlar boolean |
### clear() {#clear--}
```
public final void clear()
```


Koleksiyondaki tüm komutları kaldırır.
### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public final void remove(IMotionCmdPath item)
```


Koleksiyondan belirtilen komutları kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Kaldırılacak hareket yolu. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Belirtilen indeksteki bir komutu kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Silinmesi gereken komutun indeksi. |
### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```


Belirtilen indeksteki bir komutu döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Elemanın indeksi. |

**Döndürür:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - The [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) object.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```


Koleksiyon üzerinden yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```


Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - An java.util.Iterator for the entire collection.