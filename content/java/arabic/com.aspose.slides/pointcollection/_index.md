---
title: PointCollection
second_title: مرجع API لـ Aspose.Slides للغة Java
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

يمثل مجموعة من نقاط الرسوم المتحركة.
## البناؤات

| المنشئ | الوصف |
| --- | --- |
| [PointCollection()](#PointCollection--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getCount()](#getCount--) | يرجع عدد النقاط في المجموعة. |
| [get_Item(int index)](#get-Item-int-) | يرجع نقطة عند الفهرس المحدد. |
| [iterator()](#iterator--) | يرجع معدِّدًا يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يرجع مكرِّر Java للمجموعة بأكملها. |
### PointCollection() {#PointCollection--}
```
public PointCollection()
```


### getCount() {#getCount--}
```
public final int getCount()
```


يمثل عدد النقاط في المجموعة. int للقراءة فقط.

**القيمة المرجعة:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPoint get_Item(int index)
```


يرجع نقطة عند الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العنصر. |

**القيمة المرجعة:**
[IPoint](../../com.aspose.slides/ipoint) - The [IPoint](../../com.aspose.slides/ipoint) object.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iterator()
```


يرجع معدِّدًا يتنقل عبر المجموعة.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iteratorJava()
```


يرجع مكرِّر Java للمجموعة بأكملها.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - An java.util.Iterator for the entire collection.