---
title: IPieSplitCustomPointCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر مجموعه‌ای از نقاط است که باید در دومین دایره یا میله در نمودار میله-در-دایره یا دایره-در-دایره با تقسیم سفارشی رسم شوند.
type: docs
url: /fa/com.aspose.slides/ipiesplitcustompointcollection/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IPieSplitCustomPointCollection extends System.Collections.Generic.IGenericCollection<IChartDataPoint>
```

نمایانگر مجموعه‌ای از نقاط است که باید در قطعه دوم دایره یا میله در نمودار میله-در-دایره یا دایره-در-دایره با تقسیم سفارشی رسم شوند.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | نقطه داده نمودار را بر اساس اندیس بر می‌گرداند. |
| [add(int dataPointIndex)](#add-int-) | نقطه داده را بر اساس اندیس آن در مجموعه نقاط سری والد اضافه می‌کند. |
| [remove(int dataPointIndex)](#remove-int-) | آیتم را از مجموعه بر اساس اندیس آن در مجموعه نقاط سری والد حذف می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```


نقطه داده نمودار را بر اساس اندیس بر می‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس نقطه داده. |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده نمودار.
### add(int dataPointIndex) {#add-int-}
```
public abstract void add(int dataPointIndex)
```


نقطه داده را بر اساس اندیس آن در مجموعه نقاط سری والد اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| dataPointIndex | int | اندیس نقطه داده در مجموعه نقاط سری والد. |

### remove(int dataPointIndex) {#remove-int-}
```
public abstract void remove(int dataPointIndex)
```


آیتم را از مجموعه بر اساس اندیس آن در مجموعه نقاط سری والد حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| dataPointIndex | int | اندیس نقطه داده در مجموعه نقاط سری والد.. |