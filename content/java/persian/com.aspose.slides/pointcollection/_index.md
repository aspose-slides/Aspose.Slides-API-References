---
title: PointCollection
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایش‌دهنده‌ی مجموعه‌ای از نقاط انیمیشن.
type: docs
url: /fa/com.aspose.slides/pointcollection/
---
**ارث‌بری:**
java.lang.Object

**همه رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IPointCollection](../../com.aspose.slides/ipointcollection)
```
public class PointCollection implements IPointCollection
```

نمایش‌دهنده‌ی مجموعه‌ای از نقاط انیمیشن.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [PointCollection()](#PointCollection--) |  |
## متدها

| متد | توضیح |
| --- | --- |
| [getCount()](#getCount--) | تعداد نقاط موجود در مجموعه را برمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | نقطه‌ای را در اندیس مشخص‌شده برمی‌گرداند. |
| [iterator()](#iterator--) | یک شمارنده که از طریق مجموعه تکرار می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای تمام مجموعه را برمی‌گرداند. |
### PointCollection() {#PointCollection--}
```
public PointCollection()
```


### getCount() {#getCount--}
```
public final int getCount()
```


تعداد نقاط موجود در مجموعه را برمی‌گرداند. int فقط‌خواندنی.

**برمی‌گرداند:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPoint get_Item(int index)
```


نقطه‌ای را در اندیس مشخص‌شده برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس عنصر. |

**برمی‌گرداند:**
[IPoint](../../com.aspose.slides/ipoint) - شیء [IPoint](../../com.aspose.slides/ipoint).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iterator()
```


یک شمارنده که از طریق مجموعه تکرار می‌کند را برمی‌گرداند.

**برمی‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - یک IGenericEnumerator که می‌توان از آن برای تکرار در مجموعه استفاده کرد.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iteratorJava()
```


یک iterator جاوا برای تمام مجموعه را برمی‌گرداند.

**برمی‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - یک java.util.Iterator برای تمام مجموعه.