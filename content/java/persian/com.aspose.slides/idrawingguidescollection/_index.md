---
title: IDrawingGuidesCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایش‌دهندهٔ مجموعه‌ای از راهنمایی‌های قابل تنظیم برای رسم.
type: docs
url: /fa/com.aspose.slides/idrawingguidescollection/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IDrawingGuidesCollection extends System.Collections.Generic.IGenericEnumerable<IDrawingGuide>
```

نمایش‌دهندهٔ مجموعه‌ای از راهنمایی‌های قابل تنظیم برای رسم.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | راهنمای رسم را بر اساس اندیس برمی‌گرداند. |
| [add(byte orientation, float position)](#add-byte-float-) | راهنمای رسم را در انتهای مجموعه اضافه می‌کند. |
| [removeAt(int index)](#removeAt-int-) | راهنمای رسم را در اندیس مشخص حذف می‌کند. |
| [clear()](#clear--) | تمام عناصر مجموعه را حذف می‌کند. |
| [getCount()](#getCount--) | تعداد کل عناصر مجموعه را دریافت می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDrawingGuide get_Item(int index)
```


راهنمای رسم را بر اساس اندیس برمی‌گرداند. فقط خواندنی [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public abstract IDrawingGuide add(byte orientation, float position)
```


راهنمای رسم را در انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| orientation | byte | جهت راهنمای رسم. |
| position | float | موقعیت راهنمای رسم بر حسب نقطه. |

**بازگشت:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


راهنمای رسم را در اندیس مشخص حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس راهنمای رسم که باید حذف شود. |

### clear() {#clear--}
```
public abstract void clear()
```


تمام عناصر مجموعه را حذف می‌کند.

### getCount() {#getCount--}
```
public abstract int getCount()
```


تعداد کل عناصر مجموعه را دریافت می‌کند. فقط خواندنی int.

**بازگشت:**
int