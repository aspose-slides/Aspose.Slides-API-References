---
title: IMotionPath
second_title: Aspose.Slides için Java API Referansı
description: Hareket yolunu temsil eder.
type: docs
url: /tr/com.aspose.slides/imotionpath/
---
**Uygulanan Tüm Arayüzler:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMotionPath extends System.Collections.Generic.IGenericEnumerable<IMotionCmdPath>
```

Hareket yolunu temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#add-int-java.awt.geom.Point2D.Float---int-boolean-) | Yola yeni komut ekle |
| [getCount()](#getCount--) | Koleksiyondaki yol sayısını döndürür. |
| [insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-) | Yola yeni komut ekle |
| [clear()](#clear--) | Koleksiyondaki tüm komutları kaldırır. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Koleksiyondan belirtilen komutları kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen indeksteki komutu kaldırır. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki komutu döndürür. |
### add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#add-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public abstract IMotionCmdPath add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


Yola yeni komut ekle

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | int | Animasyon hareket efekti davranışı için komut tipi [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Nokta dizisi java.awt.geom.Point2D.Float[] |
| ptsType | int | Animasyon hareket yolundaki nokta türü [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | İlgili koordinatların kullanılacağını gösterir boolean |

**Döndürür:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Command of a path [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Koleksiyondaki yol sayısını döndürür. Yalnızca okunur int.

**Döndürür:**
int
### insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public abstract void insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


Yola yeni komut ekle

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Komut ekleme indeksi int |
| type | int | Animasyon hareket efekti davranışı için komut tipi [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Nokta dizisi java.awt.geom.Point2D.Float[] |
| ptsType | int | Animasyon hareket yolundaki nokta türü [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | İlgili koordinatların kullanılacağını gösterir boolean |
### clear() {#clear--}
```
public abstract void clear()
```


Koleksiyondaki tüm komutları kaldırır.
### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public abstract void remove(IMotionCmdPath item)
```


Koleksiyondan belirtilen komutları kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Kaldırılacak hareket yolu [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Belirtilen indeksteki komutu kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Komut kaldırma indeksi int |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMotionCmdPath get_Item(int index)
```


Belirtilen indeksteki komutu döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Elemanın indeksi. |

**Döndürür:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Command at specified index [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)