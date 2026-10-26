---
title: TabCollection
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نماینده یک مجموعه از تب‌ها.
type: docs
url: /fa/com.aspose.slides/tabcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ITabCollection](../../com.aspose.slides/itabcollection), com.aspose.slides.IDOMObject
```
public final class TabCollection implements ITabCollection, IDOMObject
```

یک مجموعه از تب‌ها را نشان می‌دهد.
## متدها

| Method | Description |
| --- | --- |
| [size()](#size--) | تعداد عناصری را که به‌طور واقعی در مجموعه وجود دارند، برمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | عنصر موجود در ایندکس مشخص شده را برمی‌گرداند. |
| [add(double position, int align)](#add-double-int-) | یک Tab را به مجموعه اضافه می‌کند. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | یک Tab را به مجموعه اضافه می‌کند. |
| [clear()](#clear--) | تمام عناصر را از مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عنصر موجود در ایندکس مشخص شده از مجموعه را حذف می‌کند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | مشخص می‌کند آیا دو نمونه TabsEx برابرند یا خیر. |
| [iterator()](#iterator--) | یک شمارنده که از طریق مجموعه پیمایش می‌کند، برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه برمی‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر را از مجموعه به آرایهٔ مشخص شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | یک مقدار که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده (thread-safe) است، برمی‌گرداند. |
| [getSyncRoot()](#getSyncRoot--) | یک ریشهٔ همگام‌سازی را برمی‌گرداند. |
### size() {#size--}
```
public final int size()
```

تعداد عناصری را که به‌طور واقعی در مجموعه وجود دارند، برمی‌گرداند. فقط-خواندنی int.

**بازگشت:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ITab get_Item(int index)
```

عنصر موجود در ایندکس مشخص شده را برمی‌گرداند. فقط-خواندنی [Tab](../../com.aspose.slides/tab).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
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

**بازگشت:**
[ITab](../../com.aspose.slides/itab) - Tab اضافه شده.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public final int add(ITab value)
```

یک Tab را به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | شیء Tab که در انتهای مجموعه اضافه می‌شود. |

**بازگشت:**
int - ایندکس‌ایی که Tab در آن اضافه شد.
### clear() {#clear--}
```
public final void clear()
```

تمام عناصر را از مجموعه حذف می‌کند.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

عنصر موجود در ایندکس مشخص شده از مجموعه را حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-پایهٔ عنصری که باید حذف شود. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را برمی‌گرداند. فقط-خواندنی IDOMObject.

**بازگشت:**
com.aspose.slides.IDOMObject
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

مشخص می‌کند آیا دو نمونه TabsEx برابرند یا خیر.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | TabsEx برای مقایسه با TabsEx فعلی. |

**بازگشت:**
boolean - **درست** اگر TabsEx مشخص شده برابر با TabsEx فعلی باشد؛ در غیر این صورت، **نادرست**.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iterator()
```

یک شمارنده که از طریق مجموعه پیمایش می‌کند، برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iteratorJava()
```

یک iterator جاوا برای کل مجموعه برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر را از مجموعه به آرایهٔ مشخص شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایهٔ مقصد. |
| index | int | ایندکس شروع در آرایهٔ مقصد. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

یک مقدار که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده (thread-safe) است، برمی‌گرداند. فقط-خواندنی boolean.

**بازگشت:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

یک ریشهٔ همگام‌سازی را برمی‌گرداند. فقط-خواندنی Object.

**بازگشت:**
java.lang.Object