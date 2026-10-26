---
title: ITrendlineCollection
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایش‌دهنده یک مجموعه از TrendlineEx
type: docs
url: /fa/com.aspose.slides/itrendlinecollection/
---
**تمام رابط‌های پیاده‌سازی شده:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ITrendlineCollection extends System.Collections.Generic.IGenericEnumerable<ITrendline>
```

نمایش‌دهنده یک مجموعه از TrendlineEx
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [getCount()](#getCount--) | Gets the number of elements actually contained in the collection. |
| [add(int trendlineType)](#add-int-) | Adds the new Trendline at the end of a collection and return it. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Removes the specified value. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITrendline get_Item(int index)
```


عنصری را که در شاخص مشخص شده قرار دارد بدست می‌آورد. فقط‌خواندنی [ITrendline](../../com.aspose.slides/itrendline).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[ITrendline](../../com.aspose.slides/itrendline)
### getCount() {#getCount--}
```
public abstract int getCount()
```


تعداد عناصری که در واقع در مجموعه موجود هستند را بدست می‌آورد. فقط‌خواندنی int.

**بازگشت:**
int
### add(int trendlineType) {#add-int-}
```
public abstract ITrendline add(int trendlineType)
```


Trendline جدید را در انتهای یک مجموعه اضافه می‌کند و آن را بازمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| trendlineType | int | Trendline نوع [TrendlineType](../../com.aspose.slides/trendlinetype) |

**بازگشت:**
[ITrendline](../../com.aspose.slides/itrendline) - Trendline جدید [ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public abstract void remove(ITrendline value)
```


مقدار مشخص شده را حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) | Trendline برای حذف [ITrendline](../../com.aspose.slides/itrendline) |