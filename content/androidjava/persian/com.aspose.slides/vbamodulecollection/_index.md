---
title: VbaModuleCollection
second_title: مرجع API جاوا برای Aspose.Slides برای Android
description: نمایانگر یک مجموعه از ماژول‌های پروژه VBA.
type: docs
url: /fa/com.aspose.slides/vbamodulecollection/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
```
public final class VbaModuleCollection implements IVbaModuleCollection
```

نمایانگر یک مجموعه از ماژول‌های پروژه VBA است.
## متدها

| متد | توضیح |
| --- | --- |
| [size()](#size--) | تعداد عناصری که واقعاً در مجموعه موجود هستند را دریافت می‌کند. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | یک ماژول خالی جدید به پروژه VBA اضافه می‌کند. |
| [get_Item(int index)](#get-Item-int-) | عنصری را که در اندیس مشخص شده قرار دارد برمی‌گرداند. |
| [iterator()](#iterator--) | یک شمارنده را برمی‌گرداند که از طریق مجموعه پیمایش می‌کند. |
| [iteratorJava()](#iteratorJava--) | یک مرورگر جاوا را برای کل مجموعه برمی‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر را از مجموعه به آرایه مشخص شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همگام‌سازی شده (Thread-Safe) است یا نه. |
| [getSyncRoot()](#getSyncRoot--) | یک ریشه همگام‌سازی را برمی‌گرداند. |
### size() {#size--}
```
public final int size()
```

تعداد عناصری که واقعاً در مجموعه موجود هستند را دریافت می‌کند. فقط-خواندنی int.

**بازمی‌گرداند:**
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

یک ماژول خالی جدید به پروژه VBA اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام ماژول |

**بازمی‌گرداند:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - ماژول اضافه‌شده.
### get_Item(int index) {#get-Item-int-}
```
public final IVbaModule get_Item(int index)
```

عنصری را که در اندیس مشخص شده قرار دارد برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازمی‌گرداند:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iterator()
```

یک شمارنده را برمی‌گرداند که از طریق مجموعه پیمایش می‌کند.

**بازمی‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - یک IGenericEnumerator که می‌توان از آن برای پیمایش مجموعه استفاده کرد.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iteratorJava()
```

یک مرورگر جاوا را برای کل مجموعه برمی‌گرداند.

**بازمی‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - یک java.util.Iterator برای کل مجموعه.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر را از مجموعه به آرایه مشخص شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه هدف. |
| index | int | اندیس شروع در آرایه هدف. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همگام‌سازی شده (Thread-Safe) است یا نه. فقط-خواندنی boolean.

**بازمی‌گرداند:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

یک ریشه همگام‌سازی را برمی‌گرداند. فقط-خواندنی Object.

**بازمی‌گرداند:**
java.lang.Object