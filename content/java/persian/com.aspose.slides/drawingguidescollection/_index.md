---
title: DrawingGuidesCollection
second_title: Aspose.Slides برای Java مرجع API
description: نمایش‌دهندهٔ مجموعه‌ای از راهنمایی‌های قابل تنظیم برای رسم.
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

نشان‌دهندهٔ مجموعه‌ای از راهنمایی‌های قابل تنظیم برای رسم است.
## متدها

| متد | توضیحات |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | راهنمای رسم را بر حسب اندیس برمی‌گرداند. |
| [add(byte orientation, float position)](#add-byte-float-) | راهنمای رسم را به انتهای مجموعه اضافه می‌کند. |
| [removeAt(int index)](#removeAt-int-) | راهنمای رسم را در اندیس مشخص حذف می‌کند. |
| [clear()](#clear--) | تمام عناصر را از مجموعه حذف می‌کند. |
| [iterator()](#iterator--) | یک enumerator که از مجموعه عبور می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک java iterator برای کل مجموعه برمی‌گرداند. |
| [getCount()](#getCount--) | تعداد عناصر موجود در مجموعه را برمی‌گرداند. |
| [copyTo(IDrawingGuide[] array, int index)](#copyTo-com.aspose.slides.IDrawingGuide---int-) | تمام عناصر را از مجموعه به آرایهٔ مشخص‌شده کپی می‌کند. |

### get_Item(int index) {#get-Item-int-}
```
public final IDrawingGuide get_Item(int index)
```

راهنمای رسم را بر حسب اندیس برمی‌گرداند. فقط‌خواندنی [IDrawingGuide](../../com.aspose.slides/idrawingguide).

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

راهنمای رسم را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| orientation | byte | جهت‌گیری راهنمای رسم. |
| position | float | موقعیت راهنمای رسم بر حسب پوینت. |

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

یک enumerator که از مجموعه عبور می‌کند را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iteratorJava()
```

یک java iterator برای کل مجموعه برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - An java.util.Iterator for the entire collection.

### getCount() {#getCount--}
```
public final int getCount()
```

تعداد عناصر موجود در مجموعه را برمی‌گرداند. فقط‌خواندنی int.

**بازگشت:**
int

### copyTo(IDrawingGuide[] array, int index) {#copyTo-com.aspose.slides.IDrawingGuide---int-}
```
public final void copyTo(IDrawingGuide[] array, int index)
```

تمام عناصر را از مجموعه به آرایهٔ مشخص‌شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | [IDrawingGuide\[\]](../../com.aspose.slides/idrawingguide) | آرایه هدف. |
| index | int | اندیس شروع در آرایه هدف. |