---
title: SectionSlideCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر مجموعه‌ای از اسلایدها در بخش است.
type: docs
url: /fa/com.aspose.slides/sectionslidecollection/
---
**ارث‌بری:**  
java.lang.Object, com.aspose.slides.DomObject

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)  
```
public final class SectionSlideCollection extends DomObject<Section> implements ISectionSlideCollection
```

نمایانگر مجموعه‌ای از اسلایدها در بخش است.

## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصر را در شاخص مشخص شده دریافت می‌کند. |
| [size()](#size--) | تعداد عناصری که واقعاً در مجموعه موجود هستند را دریافت می‌کند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | کل مجموعه را در آرایهٔ مشخص‌شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده (امنیت‌پذیر) است. |
| [getSyncRoot()](#getSyncRoot--) | ریشهٔ همگام‌سازی را برمی‌گرداند. |
| [iterator()](#iterator--) | یک شمارشگر که از طریق مجموعه تکرار می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه برمی‌گرداند. |
### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

عنصر را در شاخص مشخص شده دریافت می‌کند. فقط خواندنی [ISlide](../../com.aspose.slides/islide).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[ISlide](../../com.aspose.slides/islide)
### size() {#size--}
```
public final int size()
```

تعداد عناصری که واقعاً در مجموعه موجود هستند را دریافت می‌کند. فقط خواندنی int.

**بازگشت:**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

کل مجموعه را در آرایهٔ مشخص‌شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه هدف |
| index | int | شاخص در آرایه هدف. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده (امنیت‌پذیر) است. فقط خواندنی boolean.

**بازگشت:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ریشهٔ همگام‌سازی را برمی‌گرداند. فقط خواندنی Object.

**بازگشت:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

یک شمارشگر که از طریق مجموعه تکرار می‌کند را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - یک IGenericEnumerator که می‌تواند برای تکرار از طریق مجموعه استفاده شود.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

یک iterator جاوا برای کل مجموعه برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - یک java.util.Iterator برای کل مجموعه.