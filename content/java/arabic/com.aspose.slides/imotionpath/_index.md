---
title: IMotionPath
second_title: مرجع API Aspose.Slides للغة Java
description: يمثل مسار الحركة.
type: docs
url: /ar/com.aspose.slides/imotionpath/
---
**جميع الواجهات المُطبقة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMotionPath extends System.Collections.Generic.IGenericEnumerable<IMotionCmdPath>
```

تمثيل مسار الحركة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#add-int-java.awt.geom.Point2D.Float---int-boolean-) | إضافة أمر جديد إلى المسار |
| [getCount()](#getCount--) | إرجاع عدد المسارات في المجموعة. |
| [insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-) | إدراج أمر جديد إلى المسار |
| [clear()](#clear--) | إزالة جميع الأوامر من المجموعة. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | إزالة الأوامر المحددة من المجموعة. |
| [removeAt(int index)](#removeAt-int-) | إزالة أمر عند الفهرس المحدد. |
| [get_Item(int index)](#get-Item-int-) | إرجاع أمر عند الفهرس المحدد. |
### add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#add-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public abstract IMotionCmdPath add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


إضافة أمر جديد إلى المسار

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| type | int | نوع الأمر لتأثير حركة الرسوم المتحركة [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | مصفوفة النقاط java.awt.geom.Point2D.Float[] |
| ptsType | int | نوع النقاط في مسار حركة الرسوم المتحركة [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | يدل على ما إذا كان سيتم استخدام إحداثيات نسبية أم لا boolean |

**الإرجاع:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - أمر من مسار [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```


إرجاع عدد المسارات في المجموعة. قراءة فقط int.

**الإرجاع:**
int
### insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public abstract void insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


إدراج أمر جديد إلى المسار

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس لإدراج الأمر int |
| type | int | نوع الأمر لتأثير حركة الرسوم المتحركة [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | مصفوفة النقاط java.awt.geom.Point2D.Float[] |
| ptsType | int | نوع النقاط في مسار حركة الرسوم المتحركة [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | يدل على ما إذا كان سيتم استخدام إحداثيات نسبية أم لا boolean |

### clear() {#clear--}
```
public abstract void clear()
```


إزالة جميع الأوامر من المجموعة.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public abstract void remove(IMotionCmdPath item)
```


إزالة الأوامر المحددة من المجموعة.

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | مسار الحركة للإزالة [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


إزالة أمر عند الفهرس المحدد.

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس لإزالة الأمر int |

### get_Item(int index) {#get-Item-int-}
```
public abstract IMotionCmdPath get_Item(int index)
```


إرجاع أمر عند الفهرس المحدد.

**الوسيط | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العنصر. |

**الإرجاع:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - أمر عند الفهرس المحدد [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)