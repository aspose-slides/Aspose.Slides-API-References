---
title: MotionPath
second_title: Aspose.Slides برای Java مرجع API
description: نمایش مسیر حرکت.
type: docs
url: /fa/com.aspose.slides/motionpath/
---
**ارث‌بری:**  
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IMotionPath](../../com.aspose.slides/imotionpath)
```
public class MotionPath implements IMotionPath
```

نمایش مسیر حرکت.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [MotionPath()](#MotionPath--) |  |
## متدها

| متد | توضیح |
| --- | --- |
| [add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#add-int-java.awt.geom.Point2D.Float---int-boolean-) |  |
| [getCount()](#getCount--) | تعداد مسیرها را در مجموعه بازمی‌گرداند. |
| [insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-) |  |
| [clear()](#clear--) | تمام دستورات را از مجموعه حذف می‌کند. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | دستورات مشخص شده را از مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | دستوری را در شاخص مشخص حذف می‌کند. |
| [get_Item(int index)](#get-Item-int-) | دستوری را در شاخص مشخص بازمی‌گرداند. |
| [iterator()](#iterator--) | یک enumerator که از مجموعه عبور می‌کند را بازمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه بازمی‌گرداند. |
### MotionPath() {#MotionPath--}
```
public MotionPath()
```

### add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#add-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final IMotionCmdPath add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```

یک فرمان جدید به مسیر اضافه می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | آرایه‌ای از نقاط |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | بولی مختصات نسبی |

**بازگرداندن:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public final int getCount()
```

تعداد مسیرها را در مجموعه بازمی‌گرداند. فقط-خواندنی int.

**بازگرداندن:**
int
### insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final void insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```

یک فرمان جدید به مسیر اضافه می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص صفر-مبنا که آیتم باید در آن وارد شود. |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | آرایه‌ای از نقاط |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | بولی مختصات نسبی |

### clear() {#clear--}
```
public final void clear()
```

تمام دستورات را از مجموعه حذف می‌کند.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public final void remove(IMotionCmdPath item)
```

دستورات مشخص شده را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | مسیر حرکتی برای حذف. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

دستوری را در شاخص مشخص حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص دستوری که باید حذف شود. |

### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```

دستوری را در شاخص مشخص بازمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص عنصر. |

**بازگرداندن:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - شی [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```

یک enumerator که از مجموعه عبور می‌کند را بازمی‌گرداند.

**بازگرداندن:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - یک IGenericEnumerator که می‌تواند برای پیمایش مجموعه استفاده شود

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```

یک iterator جاوا برای کل مجموعه بازمی‌گرداند.

**بازگرداندن:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - یک java.util.Iterator برای کل مجموعه.