---
title: TabCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر مجموعه‌ای از برگه‌ها است.
type: docs
url: /fa/com.aspose.slides/tabcollection/
---
**ارث‌بری:**
java.lang.Object

**تمام اینترفیس‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ITabCollection](../../com.aspose.slides/itabcollection), com.aspose.slides.IDOMObject
```
public final class TabCollection implements ITabCollection, IDOMObject
```

نمایانگر مجموعه‌ای از برگه‌ها است.
## متدها

| متد | توضیح |
| --- | --- |
| [size()](#size--) | تعداد عناصری که واقعاً در مجموعه موجود هستند را بر می‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | عنصر موجود در اندیس مشخص‌شده را بر می‌گرداند. |
| [add(double position, int align)](#add-double-int-) | یک Tab را به مجموعه اضافه می‌کند. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | یک Tab را به مجموعه اضافه می‌کند. |
| [clear()](#clear--) | تمام عناصری را که در مجموعه هستند حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عنصر موجود در اندیس مشخص‌شده از مجموعه را حذف می‌کند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | تعیین می‌کند که آیا دو نمونه از TabsEx برابر هستند یا خیر. |
| [iterator()](#iterator--) | یک enumerator که از مجموعه می‌گذرد را بر می‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک java iterator برای کل مجموعه را بر می‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر مجموعه را به آرایهٔ مشخص‌شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را بر می‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده (ایمن در برابر رشته‌ها) است. |
| [getSyncRoot()](#getSyncRoot--) | یک ریشهٔ همگام‌سازی را بر می‌گرداند. |
### size() {#size--}
```
public final int size()
```

تعداد عناصری که واقعاً در مجموعه موجود هستند را بر می‌گرداند. فقط-خواندنی int.

**باز می‌گردد:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ITab get_Item(int index)
```

عنصر موجود در اندیس مشخص‌شده را بر می‌گرداند. فقط-خواندنی [Tab](../../com.aspose.slides/tab).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**باز می‌گردد:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public final ITab add(double position, int align)
```

یک Tab را به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| position | double |  |
| align | int |  |

**باز می‌گردد:**
[ITab](../../com.aspose.slides/itab) - برگه اضافه شده.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public final int add(ITab value)
```

یک Tab را به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | شیء Tab که در انتهای مجموعه اضافه می‌شود. |

**باز می‌گردد:**
int - اندیسی که برگه در آن اضافه شد.
### clear() {#clear--}
```
public final void clear()
```

تمام عناصری را که در مجموعه هستند حذف می‌کند.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

عنصر موجود در اندیس مشخص‌شده از مجموعه را حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر‌پایهٔ عنصری که باید حذف شود. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را بر می‌گرداند. فقط-خواندنی IDOMObject.

**باز می‌گردد:**
com.aspose.slides.IDOMObject
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

تعیین می‌کند که آیا دو نمونه از TabsEx برابر هستند یا خیر.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | TabsEx برای مقایسه با TabsEx فعلی. |

**باز می‌گردد:**
boolean - **true** اگر TabsEx مشخص‌شده با TabsEx فعلی برابر باشد؛ در غیر این صورت **false**.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iterator()
```

یک enumerator که از مجموعه می‌گذرد را بر می‌گرداند.

**باز می‌گردد:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - یک IGenericEnumerator که می‌تواند برای پیمایش مجموعه استفاده شود.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iteratorJava()
```

یک java iterator برای کل مجموعه را بر می‌گرداند.

**باز می‌گردد:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - یک java.util.Iterator برای کل مجموعه.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر مجموعه را به آرایهٔ مشخص‌شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایهٔ مقصد. |
| index | int | اندیس شروع در آرایهٔ مقصد. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را بر می‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده (ایمن در برابر رشته‌ها) است. فقط-خواندنی boolean.

**باز می‌گردد:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

یک ریشهٔ همگام‌سازی را بر می‌گرداند. فقط-خواندنی Object.

**باز می‌گردد:**
java.lang.Object