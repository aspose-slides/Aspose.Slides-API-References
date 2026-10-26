---
title: ITrendlineCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش‌دهنده یک مجموعه از TrendlineEx
type: docs
url: /fa/com.aspose.slides/itrendlinecollection/
---
**تمام رابط‌های پیاده‌سازی‌شده:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ITrendlineCollection extends System.Collections.Generic.IGenericEnumerable<ITrendline>
```

نمایش‌دهنده یک مجموعه از TrendlineEx
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصر را در ایندکس مشخص‌شده دریافت می‌کند. |
| [getCount()](#getCount--) | تعداد عناصری که در واقع در مجموعه موجود است را دریافت می‌کند. |
| [add(int trendlineType)](#add-int-) | Trendline جدید را در انتهای مجموعه اضافه می‌کند و آن را برمی‌گرداند. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | مقدار مشخص‌شده را حذف می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITrendline get_Item(int index)
```

عنصر را در ایندکس مشخص‌شده دریافت می‌کند. فقط‌خواندنی [ITrendline](../../com.aspose.slides/itrendline).

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

تعداد عناصری که در واقع در مجموعه موجود است را دریافت می‌کند. فقط‌خواندنی int.

**بازگشت:**
int
### add(int trendlineType) {#add-int-}
```
public abstract ITrendline add(int trendlineType)
```

Trendline جدید را در انتهای مجموعه اضافه می‌کند و آن را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| trendlineType | int | نوع Trendline [TrendlineType](../../com.aspose.slides/trendlinetype) |

**بازگشت:**
[ITrendline](../../com.aspose.slides/itrendline) - Trendline جدید [ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public abstract void remove(ITrendline value)
```

مقدار مشخص‌شده را حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) | Trendline برای حذف [ITrendline](../../com.aspose.slides/itrendline) |