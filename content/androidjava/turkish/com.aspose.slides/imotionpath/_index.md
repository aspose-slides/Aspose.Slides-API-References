---
title: IMotionPath
second_title: Android için Aspose.Slides Java API Referansı
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
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | Yola yeni komut ekle |
| [getCount()](#getCount--) | Koleksiyondaki yolların sayısını döndürür. |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | Yola yeni komut ekle |
| [clear()](#clear--) | Koleksiyondaki tüm komutları kaldırır. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Koleksiyondan belirtilen komutları kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen indisteki bir komutu kaldırır. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indisteki bir komutu döndürür. |
### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public abstract IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

Yola yeni komut ekle

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | int | Animasyon hareket efekti davranışı için komut tipi [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Nokta dizisi android.graphics.PointF[] |
| ptsType | int | Animasyon hareket yolundaki noktaların türü [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Göreli koordinatların kullanılıp kullanılmayacağını belirtir boolean |

**Döndürür:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Bir yolun komutu [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Koleksiyondaki yolların sayısını döndürür. Salt okunur int.

**Döndürür:**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public abstract void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

Yola yeni komut ekle

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Komut ekleme için indeks int |
| type | int | Animasyon hareket efekti davranışı için komut tipi [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Nokta dizisi android.graphics.PointF[] |
| ptsType | int | Animasyon hareket yolundaki noktaların türü [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Göreli koordinatların kullanılıp kullanılmayacağını belirtir boolean |
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

Belirtilen indisteki bir komutu kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Komut kaldırmak için indeks int |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMotionCmdPath get_Item(int index)
```

Belirtilen indisteki bir komutu döndürür.

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Elemanın indeksi. |

**Döndürür:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Belirtilen indeksdeki komut [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)