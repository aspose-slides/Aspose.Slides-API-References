---
title: PointCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش مجموعه‌ای از نقاط انیمیشن.
type: docs
url: /fa/com.aspose.slides/pointcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IPointCollection](../../com.aspose.slides/ipointcollection)
```
public class PointCollection implements IPointCollection
```

نمایش مجموعه‌ای از نقاط انیمیشن.

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [PointCollection()](#PointCollection--) |  |

## متدها

| متد | توضیح |
| --- | --- |
| [getCount()](#getCount--) | تعداد نقاط در مجموعه را برمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | نقطه‌ای را در ایندکس مشخص شده برمی‌گرداند. |
| [iterator()](#iterator--) | یک شمارشگر بر می‌گرداند که از طریق مجموعه تکرار می‌کند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه برمی‌گرداند. |

### PointCollection() {#PointCollection--}
```
public PointCollection()
```

### getCount() {#getCount--}
```
public final int getCount()
```

تعداد نقاط در مجموعه را برمی‌گرداند. int فقط خواندنی.

**باز می‌گردد:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IPoint get_Item(int index)
```

نقطه‌ای را در ایندکس مشخص شده برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس عنصر. |

**باز می‌گردد:**
[IPoint](../../com.aspose.slides/ipoint) - شیء [IPoint](../../com.aspose.slides/ipoint)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iterator()
```

یک شمارشگر بر می‌گرداند که از طریق مجموعه تکرار می‌کند.

**باز می‌گردد:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - یک IGenericEnumerator که می‌توان از آن برای تکرار در مجموعه استفاده کرد.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iteratorJava()
```

یک iterator جاوا برای کل مجموعه برمی‌گرداند.

**باز می‌گردد:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - یک java.util.Iterator برای کل مجموعه.