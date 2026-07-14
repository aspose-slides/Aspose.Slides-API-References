---
title: TextAnimationCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش‌دهنده مجموعه‌ای از انیمیشن‌های متنی.
type: docs
url: /fa/com.aspose.slides/textanimationcollection/
---
**وراثت:**  
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)
```
public class TextAnimationCollection implements ITextAnimationCollection
```

نمایش‌دهنده مجموعه‌ای از انیمیشن‌های متنی.

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [TextAnimationCollection()](#TextAnimationCollection--) |  |

## متدها

| متد | توضیح |
| --- | --- |
| [size()](#size--) | تعداد عناصر در مجموعه را برمی‌گرداند. |
| [add()](#add--) | انیمیشن متنی جدیدی را به مجموعه اضافه می‌کند. |
| [get_Item(int index)](#get-Item-int-) | عنصر را بر اساس اندیس برمی‌گرداند. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | تمام عناصر را برمی‌گرداند |
| [iterator()](#iterator--) | شمارنده‌ای را برمی‌گرداند که بر مجموعه تکرار می‌کند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه برمی‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر را از مجموعه به آرایه مشخص شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی‌شده (thread-safe) است. |
| [getSyncRoot()](#getSyncRoot--) | ریشه همگام‌سازی را برمی‌گرداند. |

### TextAnimationCollection() {#TextAnimationCollection--}
```
public TextAnimationCollection()
```

### size() {#size--}
```
public final int size()
```

تعداد عناصر در مجموعه را برمی‌گرداند. فقط‌خواندنی int.

**بازگشت:**  
int

### add() {#add--}
```
public final TextAnimation add()
```

انیمیشن متنی جدیدی را به مجموعه اضافه می‌کند.

**بازگشت:**  
[TextAnimation](../../com.aspose.slides/textanimation) - اضافه شد [TextAnimation](../../com.aspose.slides/textanimation)

### get_Item(int index) {#get-Item-int-}
```
public final ITextAnimation get_Item(int index)
```

عنصر را بر اساس اندیس برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**  
[ITextAnimation](../../com.aspose.slides/itextanimation)

### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public final ITextAnimation[] get_Item(IShape shape)
```

تمام عناصر را برمی‌گرداند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) برای حذف. |

**بازگشت:**  
com.aspose.slides.ITextAnimation[] - آرایه‌ای از [ITextAnimation](../../com.aspose.slides/itextanimation)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iterator()
```

یک شمارنده را برمی‌گرداند که می‌توان برای تکرار در مجموعه استفاده کرد.

**بازگشت:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - یک IGenericEnumerator که می‌توان برای تکرار در مجموعه استفاده کرد.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iteratorJava()
```

یک iterator جاوا برای کل مجموعه برمی‌گرداند.

**بازگشت:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - یک java.util.Iterator برای کل مجموعه.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر را از مجموعه به آرایه مشخص شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه برای پر کردن. |
| index | int | موقعیت آغازین در آرایه هدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی‌شده (thread-safe) است. فقط‌خواندنی boolean.

**بازگشت:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ریشه همگام‌سازی را برمی‌گرداند. فقط‌خواندنی Object.

**بازگشت:**  
java.lang.Object