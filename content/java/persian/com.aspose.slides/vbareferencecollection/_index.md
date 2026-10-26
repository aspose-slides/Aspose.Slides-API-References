---
title: VbaReferenceCollection
second_title: Aspose.Slides برای مرجع API جاوا
description: نماینده‌ای برای مجموعه‌ای از مراجع پروژه VBA.
type: docs
url: /fa/com.aspose.slides/vbareferencecollection/
---
**ارث بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
```
public class VbaReferenceCollection implements IVbaReferenceCollection
```

نماینده‌ای برای مجموعه‌ای از مراجع پروژه VBA.

## متدها

| Method | Description |
| --- | --- |
| [size()](#size--) | تعداد عناصری که واقعاً در مجموعه موجود هستند را دریافت می‌کند. |
| [add(IVbaReference value)](#add-com.aspose.slides.IVbaReference-) | مرجع جدید را به مجموعه مراجع اضافه می‌کند. |
| [get_Item(int index)](#get-Item-int-) | عنصر را در ایندکس مشخص‌شده دریافت می‌کند. |
| [iterator()](#iterator--) | یک شمارشگر که در مجموعه پیمایش می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه برمی‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر را از مجموعه به آرایهٔ مشخص‌شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده (thread-safe) است. |
| [getSyncRoot()](#getSyncRoot--) | ریشهٔ همگام‌سازی را برمی‌گرداند. |

### size() {#size--}
```
public final int size()
```

تعداد عناصری که واقعاً در مجموعه موجود هستند را دریافت می‌کند. فقط خواندنی int.

**بازمی‌گرداند:**
int

### add(IVbaReference value) {#add-com.aspose.slides.IVbaReference-}
```
public final void add(IVbaReference value)
```

مرجع جدید را به مجموعه مراجع اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IVbaReference](../../com.aspose.slides/ivbareference) |  |

### get_Item(int index) {#get-Item-int-}
```
public final IVbaReference get_Item(int index)
```

عنصر را در ایندکس مشخص‌شده دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازمی‌گرداند:**
[IVbaReference](../../com.aspose.slides/ivbareference)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaReference> iterator()
```

یک شمارشگر که در مجموعه پیمایش می‌کند را برمی‌گرداند.

**بازمی‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaReference> - یک IGenericEnumerator که می‌تواند برای پیمایش در مجموعه استفاده شود.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaReference> iteratorJava()
```

یک iterator جاوا برای کل مجموعه برمی‌گرداند.

**بازمی‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaReference> - یک java.util.Iterator برای کل مجموعه.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر را از مجموعه به آرایهٔ مشخص‌شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایهٔ هدف. |
| index | int | ایندکس شروع در آرایهٔ هدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده (thread-safe) است. فقط خواندنی boolean.

**بازمی‌گرداند:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ریشهٔ همگام‌سازی را برمی‌گرداند. فقط خواندنی Object.

**بازمی‌گرداند:**
java.lang.Object