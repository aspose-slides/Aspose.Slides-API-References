---
title: ExtraColorSchemeCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر یک مجموعه از طرح‌های رنگی اضافی است.
type: docs
url: /fa/com.aspose.slides/extracolorschemecollection/
---
**وراثت:**  
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection), com.aspose.slides.IDOMObject  
```
public class ExtraColorSchemeCollection implements IExtraColorSchemeCollection, IDOMObject
```

نمایش‌دهنده یک مجموعه از طرح‌های رنگی اضافی است.

## متدها

| متد | توضیح |
| --- | --- |
| [size()](#size--) | تعداد عناصری در مجموعه را بر می‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | طرح رنگی را با اندیس بر می‌گرداند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iterator()](#iterator--) | یک شمارشگر که در مجموعه پیمایش می‌کند را بر می‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه را بر می‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر مجموعه را به آرایه مشخص شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را بر می‌گرداند که نشان می‌دهد دسترسی به ArrayList همگام‌سازی شده (امن در برابر نخ) است. |
| [getSyncRoot()](#getSyncRoot--) | یک شیء که می‌تواند برای همگام‌سازی دسترسی به مجموعه استفاده شود را بر می‌گرداند. |

### size() {#size--}
```
public final int size()
```

تعداد عناصری در مجموعه را بر می‌گرداند. فقط‌خواندنی int.

**باز می‌گرداند:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IExtraColorScheme get_Item(int index)
```

طرح رنگی را با اندیس بر می‌گرداند. فقط‌خواندنی [ExtraColorScheme](../../com.aspose.slides/extracolorscheme).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**باز می‌گرداند:**  
[IExtraColorScheme](../../com.aspose.slides/iextracolorscheme)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent\_Immediate را بر می‌گرداند. فقط‌خواندنی IDOMObject.

**باز می‌گرداند:**  
com.aspose.slides.IDOMObject

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iterator()
```

یک شمارشگر که در مجموعه پیمایش می‌کند را بر می‌گرداند.

**باز می‌گرداند:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - یک IGenericEnumerator که می‌تواند برای پیمایش در مجموعه استفاده شود.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iteratorJava()
```

یک iterator جاوا برای کل مجموعه را بر می‌گرداند.

**باز می‌گرداند:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - یک java.util.Iterator برای کل مجموعه.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر مجموعه را به آرایه مشخص شده کپی می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه هدف. |
| index | int | اندیس شروع در آرایه. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را بر می‌گرداند که نشان می‌دهد دسترسی به ArrayList همگام‌سازی شده (امن در برابر نخ) است. فقط‌خواندنی boolean.

**باز می‌گرداند:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

یک شیء که می‌تواند برای همگام‌سازی دسترسی به مجموعه استفاده شود را بر می‌گرداند. فقط‌خواندنی Object.

یک ریشه‌ی همگام‌سازی را بر می‌گرداند. فقط‌خواندنی Object.

**باز می‌گرداند:**  
java.lang.Object