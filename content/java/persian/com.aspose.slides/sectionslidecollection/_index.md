---
title: SectionSlideCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: یک مجموعه از اسلایدها را در بخش نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/sectionslidecollection/
---
**Inheritance:**  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
[com.aspose.slides.ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)  
```
public final class SectionSlideCollection extends DomObject<Section> implements ISectionSlideCollection
```

نمایش یک مجموعه از اسلایدها در بخش.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصر را در ایندکس مشخص‌شده دریافت می‌کند. |
| [size()](#size--) | تعداد عنصرهای واقعاً موجود در مجموعه را دریافت می‌کند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | کل مجموعه را به آرایهٔ مشخص‌شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان‌دهنده این است که دسترسی به مجموعه همگام‌سازی شده (thread-safe) است. |
| [getSyncRoot()](#getSyncRoot--) | ریشهٔ همگام‌سازی را برمی‌گرداند. |
| [iterator()](#iterator--) | یک enumerator که در مجموعه پیمایش می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک java iterator برای کل مجموعه را برمی‌گرداند. |
### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

عنصر را در ایندکس مشخص‌شده دریافت می‌کند. فقط خواندنی [ISlide](../../com.aspose.slides/islide).

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

تعداد عنصرهای واقعاً موجود در مجموعه را دریافت می‌کند. فقط خواندنی int.

**بازگشت:**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

کل مجموعه را به آرایهٔ مشخص‌شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه هدف |
| index | int | ایندکس در آرایه هدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان‌دهنده این است که دسترسی به مجموعه همگام‌سازی شده (thread-safe) است. فقط خواندنی boolean.

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

یک enumerator که در مجموعه پیمایش می‌کند را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

یک java iterator برای کل مجموعه را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - An java.util.Iterator for the entire collection.