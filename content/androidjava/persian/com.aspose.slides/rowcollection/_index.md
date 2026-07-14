---
title: RowCollection
second_title: مرجع API جاوا برای Aspose.Slides در اندروید
description: نمایش‌دهنده مجموعه ردیف‌های جدول.
type: docs
url: /fa/com.aspose.slides/rowcollection/
---
**وراثت:**  
java.lang.Object, com.aspose.slides.DomObject

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IRowCollection](../../com.aspose.slides/irowcollection)  
```
public final class RowCollection extends DomObject<Table> implements IRowCollection
```

نمایش‌دهنده مجموعه ردیف‌های جدول.
## متدها

| Method | Description |
| --- | --- |
| [size()](#size--) | تعداد ردیف‌هایی را که به‌طور واقعی در مجموعه موجود هستند، دریافت می‌کند. |
| [get_Item(int index)](#get-Item-int-) | ردیف را در ایندکس مشخص‌شده برمی‌گرداند. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | یک نسخه از ردیف الگوی مشخص‌شده را ایجاد می‌کند و آن را به انتهای جدول اضافه می‌نماید. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | یک نسخه از ردیف الگوی مشخص‌شده ایجاد می‌کند و آن را در موقعیت مشخص‌شده در جدول وارد می‌نماید. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | یک ردیف را در موقعیت مشخص‌شده از جدول حذف می‌کند. |
| [iterator()](#iterator--) | یک enumerator که از مجموعه عبور می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک java iterator برای کل مجموعه برمی‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر را از مجموعه به آرایه مشخص‌شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همگام‌سازی شده (thread-safe) است یا خیر. فقط قابل خواندن boolean. |
| [getSyncRoot()](#getSyncRoot--) | یک ریشه‌ی همگام‌سازی را برمی‌گرداند. فقط قابل خواندن Object. |
### size() {#size--}
```
public final int size()
```

تعداد ردیف‌هایی را که به‌طور واقعی در مجموعه موجود هستند، دریافت می‌کند. فقط قابل خواندن int.

**بازگشت:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final IRow get_Item(int index)
```

ردیف را در ایندکس مشخص‌شده برمی‌گرداند. فقط قابل خواندن [Row](../../com.aspose.slides/row).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public final IRow[] addClone(IRow templ, boolean withAttachedRows)
```

یک نسخه از ردیف الگوی مشخص‌شده را ایجاد می‌کند و آن را به انتهای جدول اضافه می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | ردیفی که به‌عنوان الگو استفاده می‌شود. |
| withAttachedRows | boolean | در صورت true تمام ردیف‌های پیوست‌شده به ردیف الگو نیز کپی می‌شوند. |

**بازگشت:**  
com.aspose.slides.IRow[] - ردیف‌های افزوده شده.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public final IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

یک نسخه از ردیف الگوی مشخص‌شده ایجاد می‌کند و آن را در موقعیت مشخص‌شده در جدول وارد می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص ردیف جدید. |
| templ | [IRow](../../com.aspose.slides/irow) | ردیفی که به‌عنوان الگو استفاده می‌شود. |
| withAttachedRows | boolean | در صورت true تمام ردیف‌های پیوست‌شده به ردیف الگو نیز کپی می‌شوند. |

**بازگشت:**  
com.aspose.slides.IRow[] - ردیف‌های درج‌شده.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstRowIndex, boolean withAttachedRows)
```

یک ردیف را در موقعیت مشخص‌شده از جدول حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| firstRowIndex | int | شاخص ردیف برای حذف. |
| withAttachedRows | boolean | در صورت true تمام ردیف‌های پیوست‌شده نیز حذف می‌شوند. |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iterator()
```

یک enumerator که از مجموعه عبور می‌کند را برمی‌گرداند.

**بازگشت:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - یک IGenericEnumerator که می‌تواند برای عبور از مجموعه استفاده شود.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iteratorJava()
```

یک java iterator برای کل مجموعه برمی‌گرداند.

**بازگشت:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - یک java.util.Iterator برای کل مجموعه.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر را از مجموعه به آرایه مشخص‌شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه مقصد. |
| index | int | شاخص شروع در آرایه مقصد. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همگام‌سازی شده (thread-safe) است یا خیر. فقط قابل خواندن boolean.

**بازگشت:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

یک ریشه‌ی همگام‌سازی را برمی‌گرداند. فقط قابل خواندن Object.

**بازگشت:**  
java.lang.Object