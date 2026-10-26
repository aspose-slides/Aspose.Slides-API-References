---
title: PointCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل مجموعة من نقاط الرسوم المتحركة.
type: docs
url: /ar/com.aspose.slides/pointcollection/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IPointCollection](../../com.aspose.slides/ipointcollection)
```
public class PointCollection implements IPointCollection
```

تمثّل مجموعة نقاط الرسوم المتحركة.
## المنشئات

| المنشيء | الوصف |
| --- | --- |
| [PointCollection()](#PointCollection--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getCount()](#getCount--) | يُرجِع عدد النقاط في المجموعة. |
| [get_Item(int index)](#get-Item-int-) | يُرجِع نقطة عند الفهرس المحدد. |
| [iterator()](#iterator--) | يُرجِع عدادًا يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يُرجِع مكرِّر java للمجموعة بالكامل. |
### PointCollection() {#PointCollection--}
```
public PointCollection()
```


### getCount() {#getCount--}
```
public final int getCount()
```

يُرجِع عدد النقاط في المجموعة. للقراءة فقط int.

**الإرجاع:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPoint get_Item(int index)
```

يُرجِع نقطة عند الفهرس المحدد.

**المعاملات:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العنصر. |

**الإرجاع:**
[IPoint](../../com.aspose.slides/ipoint) - الكائن [IPoint](../../com.aspose.slides/ipoint).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iterator()
```

يُرجِع عدادًا يتنقل عبر المجموعة.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - IGenericEnumerator الذي يمكن استخدامه للتنقل عبر المجموعة.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iteratorJava()
```

يُرجِع مكرِّر java للمجموعة بالكامل.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - java.util.Iterator للمجموعة بالكامل.