---
title: MotionPath
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل مسار الحركة.
type: docs
url: /ar/com.aspose.slides/motionpath/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IMotionPath](../../com.aspose.slides/imotionpath)
```
public class MotionPath implements IMotionPath
```

يمثل مسار الحركة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [MotionPath()](#MotionPath--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | إضافة أمر جديد إلى المسار |
| [getCount()](#getCount--) | إرجاع عدد المسارات في المجموعة. |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | إدراج أمر جديد إلى المسار |
| [clear()](#clear--) | إزالة جميع الأوامر من المجموعة. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | إزالة الأوامر المحددة من المجموعة. |
| [removeAt(int index)](#removeAt-int-) | إزالة أمر في الفهرس المحدد. |
| [get_Item(int index)](#get-Item-int-) | إرجاع أمر في الفهرس المحدد. |
| [iterator()](#iterator--) | إرجاع عداد يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | إرجاع مكرّر java للمجموعة بأكملها. |
### MotionPath() {#MotionPath--}
```
public MotionPath()
```


### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public final IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


إضافة أمر جديد إلى المسار

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | مصفوفة من النقاط |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | قيمة منطقية للإحداثيات النسبية |

**الإرجاع:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public final int getCount()
```


إرجاع عدد المسارات في المجموعة. int للقراءة فقط.

**الإرجاع:**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public final void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


إدراج أمر جديد إلى المسار

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي يجب إدراج العنصر فيه. |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | مصفوفة من النقاط |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | قيمة منطقية للإحداثيات النسبية |

### clear() {#clear--}
```
public final void clear()
```


إزالة جميع الأوامر من المجموعة.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public final void remove(IMotionCmdPath item)
```


إزالة الأوامر المحددة من المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | مسار الحركة المراد إزالته. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


إزالة أمر في الفهرس المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الأمر الذي يجب حذفه. |

### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```


إرجاع أمر في الفهرس المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العنصر. |

**الإرجاع:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - الكائن [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```


إرجاع عداد يتنقل عبر المجموعة.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```


إرجاع مكرّر java للمجموعة بأكملها.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - An java.util.Iterator for the entire collection.