---
title: VbaModuleCollection
second_title: Aspose.Slides برای Java مرجع API
description: نمایانگر مجموعه‌ای از ماژول‌های پروژه VBA است.
type: docs
url: /fa/com.aspose.slides/vbamodulecollection/
---
**وراثت:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
```
public final class VbaModuleCollection implements IVbaModuleCollection
```

نمایانگر مجموعه‌ای از ماژول‌های پروژه VBA است.
## متدها

| متد | توضیح |
| --- | --- |
| [size()](#size--) | تعداد عناصری که واقعاً در مجموعه موجود هستند را دریافت می‌کند. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | یک ماژول جدید خالی به پروژه VBA اضافه می‌کند. |
| [get_Item(int index)](#get-Item-int-) | عنصری را که در ایندکس مشخص شده است دریافت می‌کند. |
| [iterator()](#iterator--) | یک enumerator که از طریق مجموعه می‌چرخد، برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک java iterator برای کل مجموعه برمی‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر را از مجموعه به آرایه مشخص‌شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همگام‌سازی شده است (ایمن برای رشته). |
| [getSyncRoot()](#getSyncRoot--) | ریشه‌ی همگام‌سازی را برمی‌گرداند. |
### size() {#size--}
```
public final int size()
```

تعداد عناصری که واقعاً در مجموعه موجود هستند را دریافت می‌کند. فقط-خواندنی int.

**بازگشت:**
int
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public final void remove(IVbaModule value)
```

اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | ماژولی که باید از مجموعه حذف شود. |
### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public final IVbaModule addEmptyModule(String name)
```

یک ماژول جدید خالی به پروژه VBA اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام ماژول |

**بازگشت:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - ماژول اضافه‌شده.
### get_Item(int index) {#get-Item-int-}
```
public final IVbaModule get_Item(int index)
```

عنصری را که در ایندکس مشخص شده است دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iterator()
```

یک enumerator که از طریق مجموعه می‌چرخد، برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iteratorJava()
```

یک java iterator برای کل مجموعه برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر را از مجموعه به آرایه مشخص‌شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه هدف. |
| index | int | ایندکس شروع در آرایه هدف. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همگام‌سازی شده است (ایمن برای رشته). فقط-خواندنی boolean.

**بازگشت:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ریشه‌ی همگام‌سازی را برمی‌گرداند. فقط-خواندنی Object.

**بازگشت:**
java.lang.Object