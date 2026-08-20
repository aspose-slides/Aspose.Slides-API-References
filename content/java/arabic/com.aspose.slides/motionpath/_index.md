---
title: MotionPath
second_title: مرجع API Aspose.Slides للغة جافا
description: تمثيل مسار الحركة.
type: docs
url: /ar/com.aspose.slides/motionpath/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المُنفذة:**  
[com.aspose.slides.IMotionPath](../../com.aspose.slides/imotionpath)  
```
public class MotionPath implements IMotionPath
```

تمثيل مسار الحركة.
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [MotionPath()](#MotionPath--) |  |

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#add-int-java.awt.geom.Point2D.Float---int-boolean-) | إضافة أمر جديد إلى المسار |
| [getCount()](#getCount--) | إرجاع عدد المسارات في المجموعة. |
| [insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-) | إدراج أمر جديد إلى المسار |
| [clear()](#clear--) | إزالة جميع الأوامر من المجموعة. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | إزالة الأوامر المحددة من المجموعة. |
| [removeAt(int index)](#removeAt-int-) | إزالة أمر في الفهرس المحدد. |
| [get_Item(int index)](#get-Item-int-) | إرجاع أمر في الفهرس المحدد. |
| [iterator()](#iterator--) | إرجاع مُعدِّد يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | إرجاع مكرِّر جافا للمجموعة بأكملها. |

### MotionPath() {#MotionPath--}
```
public MotionPath()
```

### add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#add-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final IMotionCmdPath add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```

إضافة أمر جديد إلى المسار

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | مصفوفة من النقاط |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | قيمة منطقية للإحداثيات النسبية |

**القيمة المرجعة:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)

### getCount() {#getCount--}
```
public final int getCount()
```

إرجاع عدد المسارات في المجموعة. عدد صحيح للقراءة فقط.

**الإرجاع:**
int

### insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final void insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```

إدراج أمر جديد إلى المسار

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الذي يبدأ من الصفر حيث يجب إدراج العنصر. |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | مصفوفة من النقاط |
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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | مسار الحركة المراد إزالته. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

إزالة أمر في الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الأمر الذي يجب حذفه. |

### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```

إرجاع أمر في الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العنصر. |

**الإرجاع:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - الكائن [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```

إرجاع مُعدِّد يتنقل عبر المجموعة.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - مُعدِّد عام يمكن استخدامه للتنقل عبر المجموعة.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```

إرجاع مكرِّر جافا للمجموعة بأكملها.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - java.util.Iterator للمجموعة بأكملها.