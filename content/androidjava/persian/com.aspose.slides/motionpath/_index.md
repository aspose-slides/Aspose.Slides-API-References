---
title: MotionPath
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش مسیر حرکت.
type: docs
url: /fa/com.aspose.slides/motionpath/
---
**ارث‌بری:**  
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**  
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
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | یک فرمان جدید به مسیر اضافه می‌کند |
| [getCount()](#getCount--) | تعداد مسیرها در مجموعه را برمی‌گرداند. |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | یک فرمان جدید به مسیر اضافه می‌کند |
| [clear()](#clear--) | تمام فرمان‌ها را از مجموعه حذف می‌کند. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | فرمان‌های مشخص شده را از مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | فرمانی را در اندیس مشخص حذف می‌کند. |
| [get_Item(int index)](#get-Item-int-) | فرمانی را در اندیس مشخص برمی‌گرداند. |
| [iterator()](#iterator--) | Enumeratorی را که بر مجموعه تکرار می‌کند برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه برمی‌گرداند. |

### MotionPath() {#MotionPath--}
```
public MotionPath()
```

### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public final IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

یک فرمان جدید به مسیر اضافه می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | آرایه‌ای از نقاط |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | بولی مختصات نسبی |

**بازده:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)

### getCount() {#getCount--}
```
public final int getCount()
```

تعداد مسیرها در مجموعه را برمی‌گرداند. int فقط-خواندنی.

**بازده:**
int

### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public final void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

یک فرمان جدید به مسیر اضافه می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس مبتنی بر صفر که مورد باید در آن افزوده شود. |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | آرایه‌ای از نقاط |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | بولی مختصات نسبی |

### clear() {#clear--}
```
public final void clear()
```

تمام فرمان‌ها را از مجموعه حذف می‌کند.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public final void remove(IMotionCmdPath item)
```

فرمان‌های مشخص شده را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | مسیر حرکتی که باید حذف شود. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

فرمانی را در اندیس مشخص حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس فرمانی که باید حذف شود. |

### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```

فرمانی را در اندیس مشخص برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس عنصر. |

**بازده:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - شی [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```

Enumeratorی را که بر مجموعه تکرار می‌کند برمی‌گرداند.

**بازده:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - IGenericEnumerator‌ای که می‌توان برای تکرار بر مجموعه استفاده کرد.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```

یک iterator جاوا برای کل مجموعه برمی‌گرداند.

**بازده:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - java.util.Iterator برای کل مجموعه.