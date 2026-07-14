---
title: IMotionPath
second_title: Aspose.Slides لأندرويد عبر مرجع API جافا
description: تمثيل مسار الحركة.
type: docs
url: /ar/com.aspose.slides/imotionpath/
---
**جميع الواجهات المنفذة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMotionPath extends System.Collections.Generic.IGenericEnumerable<IMotionCmdPath)
```

تمثيل مسار الحركة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | إضافة أمر جديد إلى المسار |
| [getCount()](#getCount--) | إرجاع عدد المسارات في المجموعة. |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | إدراج أمر جديد إلى المسار |
| [clear()](#clear--) | يزيل جميع الأوامر من المجموعة. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | يزيل الأوامر المحددة من المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل أمرًا عند الفهرس المحدد. |
| [get_Item(int index)](#get-Item-int-) | يعيد أمرًا عند الفهرس المحدد. |
### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public abstract IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

إضافة أمر جديد إلى المسار

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | int | نوع الأمر لتأثير حركة الرسوم المتحركة [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | مصفوفة النقاط android.graphics.PointF[] |
| ptsType | int | نوع النقاط في مسار حركة الرسوم المتحركة [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | يشير إلى ما إذا كان يجب استخدام إحداثيات نسبية أم لا boolean |

**الإرجاع:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - أمر مسار [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```

إرجاع عدد المسارات في المجموعة. للقراءة فقط int.

**الإرجاع:**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public abstract void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

إدراج أمر جديد إلى المسار

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس لإدراج الأمر int |
| type | int | نوع الأمر لتأثير حركة الرسوم المتحركة [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | مصفوفة النقاط android.graphics.PointF[] |
| ptsType | int | نوع النقاط في مسار حركة الرسوم المتحركة [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | يشير إلى ما إذا كان يجب استخدام إحداثيات نسبية أم لا boolean |
### clear() {#clear--}
```
public abstract void clear()
```

يزيل جميع الأوامر من المجموعة.
### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public abstract void remove(IMotionCmdPath item)
```

يزيل الأوامر المحددة من المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | مسار الحركة لإزالته [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل أمرًا عند الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس لإزالة الأمر int |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMotionCmdPath get_Item(int index)
```

يعيد أمرًا عند الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العنصر. |

**الإرجاع:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - أمر عند الفهرس المحدد [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)