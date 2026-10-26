---
title: IPointCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: مجموعه‌ای از بخش‌ها را نمایش می‌دهد.
type: docs
url: /fa/com.aspose.slides/ipointcollection/
---
**تمام رابط‌های پیاده‌سازی شده:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPointCollection extends System.Collections.Generic.IGenericEnumerable<IPoint>
```

نمایشگر مجموعه‌ای از بخش‌ها.
## روش‌ها

| متد | توضیح |
| --- | --- |
| [getCount()](#getCount--) | تعداد نقاط موجود در مجموعه را برمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | نقطه‌ای را در اندیس مشخص شده برمی‌گرداند. |
### getCount() {#getCount--}
```
public abstract int getCount()
```


تعداد نقاط موجود در مجموعه را برمی‌گرداند. فقط-خواندنی int.

**بازگشت:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract IPoint get_Item(int index)
```


نقطه‌ای را در اندیس مشخص شده برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس عنصر. |

**بازگشت:**
[IPoint](../../com.aspose.slides/ipoint) - شیء [IPoint](../../com.aspose.slides/ipoint)