---
title: IMotionPath
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایش مسیر حرکت.
type: docs
url: /fa/com.aspose.slides/imotionpath/
---
**تمامی اینترفیس‌های پیاده‌سازی‌شده:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMotionPath extends System.Collections.Generic.IGenericEnumerable<IMotionCmdPath>
```

نمایش مسیر حرکت.
## متدها

| متد | توضیح |
| --- | --- |
| [add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#add-int-java.awt.geom.Point2D.Float---int-boolean-) | یک فرمان جدید به مسیر اضافه می‌کند |
| [getCount()](#getCount--) | تعداد مسیرها در مجموعه را برمی‌گرداند. |
| [insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-) | یک فرمان جدید به مسیر وارد می‌کند |
| [clear()](#clear--) | تمامی فرمان‌ها را از مجموعه حذف می‌کند. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | فرمان‌های مشخص‌شده را از مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | یک فرمان را در ایندکس مشخص حذف می‌کند. |
| [get_Item(int index)](#get-Item-int-) | یک فرمان را در ایندکس مشخص برمی‌گرداند. |
### add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#add-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public abstract IMotionCmdPath add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```

یک فرمان جدید به مسیر اضافه می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | int | نوع فرمان برای رفتار اثر انیمیشن حرکت [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | آرایه نقاط java.awt.geom.Point2D.Float[] |
| ptsType | int | نوع نقاط در مسیر حرکت انیمیشن [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | نشان می‌دهد که آیا مختصات نسبی استفاده شود یا نه boolean |

**بازگشت:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - فرمانی از مسیر [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```

تعداد مسیرها در مجموعه را برمی‌گرداند. فقط-خواندنی int.

**بازگشت:**
int
### insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public abstract void insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```

یک فرمان جدید به مسیر وارد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | نمایه برای درج فرمان int |
| type | int | نوع فرمان برای رفتار اثر انیمیشن حرکت [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | آرایه نقاط java.awt.geom.Point2D.Float[] |
| ptsType | int | نوع نقاط در مسیر حرکت انیمیشن [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | نشان می‌دهد که آیا مختصات نسبی استفاده شود یا نه boolean |
### clear() {#clear--}
```
public abstract void clear()
```

تمامی فرمان‌ها را از مجموعه حذف می‌کند.
### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public abstract void remove(IMotionCmdPath item)
```

فرمان‌های مشخص‌شده را از مجموعه حذف می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | مسیر حرکتی برای حذف [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

یک فرمان را در ایندکس مشخص حذف می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | نمایه برای حذف فرمان int |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMotionCmdPath get_Item(int index)
```

یک فرمان را در ایندکس مشخص برمی‌گرداند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | نمایه عنصر. |

**بازگشت:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - فرمانی در ایندکس مشخص [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)