---
title: IPieSplitCustomPointCollection
second_title: Aspose.Slides برای Java مرجع API
description: نمایشگر مجموعه‌ای از نقاط است که باید در پای دوم یا نوار دوم در نمودار bar-of-pie یا pie-of-pie با تقسیم سفارشی رسم شوند.
type: docs
url: /fa/com.aspose.slides/ipiesplitcustompointcollection/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IPieSplitCustomPointCollection extends System.Collections.Generic.IGenericCollection<IChartDataPoint>
```

نمایشگر مجموعه‌ای از نقاط است که باید در پای دوم یا نوار دوم در نمودار bar-of-pie یا pie-of-pie با تقسیم سفارشی رسم شوند.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | نقطه دادهٔ نمودار را بر اساس اندیس برمی‌گرداند. |
| [add(int dataPointIndex)](#add-int-) | نقطه داده را بر اساس اندیس آن در مجموعه نقاط سری والد اضافه می‌کند. |
| [remove(int dataPointIndex)](#remove-int-) | مورد را از مجموعه بر اساس اندیس آن در مجموعه نقاط سری والد حذف می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

نقطه دادهٔ نمودار را بر اساس اندیس برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توصیف |
| --- | --- | --- |
| index | int | اندیس نقطه داده. |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ نمودار.
### add(int dataPointIndex) {#add-int-}
```
public abstract void add(int dataPointIndex)
```

نقطه داده را بر اساس اندیس آن در مجموعه نقاط سری والد اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توصیف |
| --- | --- | --- |
| dataPointIndex | int | اندیس نقطه داده در مجموعه نقاط سری والد. |
### remove(int dataPointIndex) {#remove-int-}
```
public abstract void remove(int dataPointIndex)
```

مورد را از مجموعه بر اساس اندیس آن در مجموعه نقاط سری والد حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توصیف |
| --- | --- | --- |
| dataPointIndex | int | اندیس نقطه داده در مجموعه نقاط سری والد.. |