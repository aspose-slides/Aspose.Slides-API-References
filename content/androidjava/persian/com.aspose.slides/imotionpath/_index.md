---
title: IMotionPath
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایش مسیر حرکت.
type: docs
url: /fa/com.aspose.slides/imotionpath/
---
**تمام رابط‌های پیاده‌سازی شده:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMotionPath extends System.Collections.Generic.IGenericEnumerable<IMotionCmdPath>
```

نمایش مسیر حرکت.
## متدها

| متد | توضیح |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | دستوری جدید به مسیر اضافه کنید |
| [getCount()](#getCount--) | تعداد مسیرها در مجموعه را برمی‌گرداند. |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | دستوری جدید به مسیر وارد کنید |
| [clear()](#clear--) | تمام دستورات را از مجموعه حذف می‌کند. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | دستورات مشخص شده را از مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | دستوری را در ایندکس مشخص حذف می‌کند. |
| [get_Item(int index)](#get-Item-int-) | دستوری را در ایندکس مشخص برمی‌گرداند. |
### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public abstract IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

دستوری جدید به مسیر اضافه کنید

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | int | نوع دستور برای رفتار اثر حرکتی انیمیشن [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | آرایه نقاط android.graphics.PointF[] |
| ptsType | int | نوع نقاط در مسیر حرکتی انیمیشن [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | نشان می‌دهد آیا از مختصات نسبی استفاده شود یا نه boolean |

**بازگشت:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - دستورات مسیر [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```

تعداد مسیرها را در مجموعه برمی‌گرداند. فقط-خواندنی int.

**بازگشت:**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public abstract void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

دستوری جدید به مسیر وارد کنید

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس برای قرار دادن دستور insertion int |
| type | int | نوع دستور برای رفتار اثر حرکتی انیمیشن [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | آرایه نقاط android.graphics.PointF[] |
| ptsType | int | نوع نقاط در مسیر حرکتی انیمیشن [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | نشان می‌دهد آیا از مختصات نسبی استفاده شود یا نه boolean |
### clear() {#clear--}
```
public abstract void clear()
```

تمام دستورات را از مجموعه حذف می‌کند.
### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public abstract void remove(IMotionCmdPath item)
```

دستورات مشخص شده را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | مسیر حرکتی برای حذف [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

دستوری را در ایندکس مشخص حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس برای حذف دستور int |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMotionCmdPath get_Item(int index)
```

دستوری را در ایندکس مشخص برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس عنصر. |

**بازگشت:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - دستورات در ایندکس مشخص [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)