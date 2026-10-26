---
title: DrawingGuidesCollection
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایانگر مجموعه‌ای از راهنماهای قابل تنظیم برای رسم.
type: docs
url: /fa/com.aspose.slides/drawingguidescollection/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)
```
public final class DrawingGuidesCollection implements IDrawingGuidesCollection
```

نمایش‌گر مجموعه‌ای از راهنمایی‌های قابل تنظیم برای رسم است.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | راهنمای رسم را بر اساس اندیس برمی‌گرداند. |
| [add(byte orientation, float position)](#add-byte-float-) | راهنمای رسم را در انتهای مجموعه اضافه می‌کند. |
| [removeAt(int index)](#removeAt-int-) | راهنمای رسم را در اندیس مشخص حذف می‌کند. |
| [clear()](#clear--) | تمام عناصر را از مجموعه حذف می‌کند. |
| [iterator()](#iterator--) | یک enumerator برمی‌گرداند که از مجموعه عبور می‌کند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه برمی‌گرداند. |
| [getCount()](#getCount--) | تعداد عناصر در مجموعه را برمی‌گرداند. |
| [copyTo(IDrawingGuide[] array, int index)](#copyTo-com.aspose.slides.IDrawingGuide---int-) | تمام عناصر را از مجموعه به آرایهٔ مشخص شده کپی می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public final IDrawingGuide get_Item(int index)
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
public final IDrawingGuide add(byte orientation, float position)
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
public final void removeAt(int index)
```


راهنمای رسم را در اندیس مشخص حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس راهنمای رسم که باید حذف شود. |

### clear() {#clear--}
```
public final void clear()
```


تمام عناصر را از مجموعه حذف می‌کند.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iterator()
```


یک enumerator برمی‌گرداند که از مجموعه عبور می‌کند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - یک IGenericEnumerator که می‌تواند برای عبور از مجموعه استفاده شود.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iteratorJava()
```


یک iterator جاوا برای کل مجموعه برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - یک java.util.Iterator برای کل مجموعه.
### getCount() {#getCount--}
```
public final int getCount()
```


تعداد عناصر در مجموعه را برمی‌گرداند. فقط خواندنی int.

**بازگشت:**
int
### copyTo(IDrawingGuide[] array, int index) {#copyTo-com.aspose.slides.IDrawingGuide---int-}
```
public final void copyTo(IDrawingGuide[] array, int index)
```


تمام عناصر را از مجموعه به آرایهٔ مشخص شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | [IDrawingGuide\[\]](../../com.aspose.slides/idrawingguide) | آرایهٔ هدف. |
| index | int | اندیس شروع در آرایهٔ هدف. |