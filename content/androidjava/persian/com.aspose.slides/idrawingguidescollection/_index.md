---
title: IDrawingGuidesCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش یک مجموعه از راهنمای‌های تنظیم‌پذیر رسم.
type: docs
url: /fa/com.aspose.slides/idrawingguidescollection/
---
**تمام رابط‌های پیاده‌سازی شده:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IDrawingGuidesCollection extends System.Collections.Generic.IGenericEnumerable<IDrawingGuide>
```

نمایش یک مجموعه از راهنمای‌های تنظیم‌پذیر رسم.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | راهنمای رسم را بر اساس اندیس برمی‌گرداند. |
| [add(byte orientation, float position)](#add-byte-float-) | راهنمای رسم را در انتهای مجموعه اضافه می‌کند. |
| [removeAt(int index)](#removeAt-int-) | راهنمای رسم را در اندیس مشخص حذف می‌کند. |
| [clear()](#clear--) | تمام عناصر را از مجموعه حذف می‌کند. |
| [getCount()](#getCount--) | تعداد تمام عناصر موجود در مجموعه را دریافت می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDrawingGuide get_Item(int index)
```

راهنمای رسم را بر اساس اندیس برمی‌گرداند. فقط‌خواندنی [IDrawingGuide](../../com.aspose.slides/idrawingguide).

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
| orientation | byte | جهت‌گیری راهنمای رسم. |
| position | float | موقعیت راهنمای رسم بر حسب پوینت. |

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

تمام عناصر را از مجموعه حذف می‌کند.

### getCount() {#getCount--}
```
public abstract int getCount()
```

تعداد تمام عناصر موجود در مجموعه را دریافت می‌کند. فقط‌خواندنی int.

**بازگشت:**
int