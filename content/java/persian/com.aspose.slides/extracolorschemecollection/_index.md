---
title: ExtraColorSchemeCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر مجموعه‌ای از طرح‌های رنگی اضافی است.
type: docs
url: /fa/com.aspose.slides/extracolorschemecollection/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection), com.aspose.slides.IDOMObject
```
public class ExtraColorSchemeCollection implements IExtraColorSchemeCollection, IDOMObject
```

نمایانگر مجموعه‌ای از طرح‌های رنگی اضافی است.

## متدها

| Method | Description |
| --- | --- |
| [size()](#size--) | تعداد عناصری را در مجموعه برمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | یک طرح رنگی را بر اساس شاخص برمی‌گرداند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iterator()](#iterator--) | یک شمارنده را برمی‌گرداند که از طریق مجموعه پیمایش می‌کند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا را برای کل مجموعه برمی‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر مجموعه را در آرایهٔ مشخص شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به ArrayList همگام‌سازی شده است (ایمن در مقابل threading). |
| [getSyncRoot()](#getSyncRoot--) | یک شیء را برمی‌گرداند که می‌توان برای همگام‌سازی دسترسی به مجموعه استفاده کرد. |

### size() {#size--}
```
public final int size()
```

تعداد عناصری را در مجموعه برمی‌گرداند. فقط-خواندنی int.

**بازگشت:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IExtraColorScheme get_Item(int index)
```

یک طرح رنگی را بر اساس شاخص برمی‌گرداند. فقط-خواندنی [ExtraColorScheme](../../com.aspose.slides/extracolorscheme).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IExtraColorScheme](../../com.aspose.slides/iextracolorscheme)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را برمی‌گرداند. فقط-خواندنی IDOMObject.

**بازگشت:**
com.aspose.slides.IDOMObject

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iterator()
```

یک شمارنده را برمی‌گرداند که از طریق مجموعه پیمایش می‌کند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iteratorJava()
```

یک iterator جاوا را برای کل مجموعه برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - An java.util.Iterator for the entire collection.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر مجموعه را در آرایهٔ مشخص شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایهٔ هدف. |
| index | int | شاخص شروع در آرایه. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به ArrayList همگام‌سازی شده است (ایمن در مقابل threading). فقط-خواندنی boolean.

**بازگشت:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

یک شیء را برمی‌گرداند که می‌توان برای همگام‌سازی دسترسی به مجموعه استفاده کرد. فقط-خواندنی Object.

ریشهٔ همگام‌سازی را برمی‌گرداند. فقط-خواندنی Object.

**بازگشت:**
java.lang.Object