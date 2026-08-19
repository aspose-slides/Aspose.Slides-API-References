---
title: RowCollection
second_title: مرجع API Aspose.Slides برای Java
description: نمایش مجموعه ردیف‌های جدول.
type: docs
url: /fa/com.aspose.slides/rowcollection/
---
**ارث‌بری:**
java.lang.Object, com.aspose.slides.DomObject

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IRowCollection](../../com.aspose.slides/irowcollection)
```
public final class RowCollection extends DomObject<Table> implements IRowCollection
```

نمایش مجموعه ردیف جدول.
## متدها

| متد | توضیح |
| --- | --- |
| [size()](#size--) | تعداد ردیف‌های واقعاً موجود در مجموعه را دریافت می‌کند. |
| [get_Item(int index)](#get-Item-int-) | ردیف مربوط به اندیس مشخص شده را برمی‌گرداند. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | یک نسخهٔ کپی از ردیف الگوی مشخص شده ایجاد می‌کند و آن را در انتهای جدول وارد می‌نماید. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | یک نسخهٔ کپی از ردیف الگوی مشخص شده ایجاد می‌کند و آن را در موقعیت مشخص شده در جدول وارد می‌نماید. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | یک ردیف را در موقعیت مشخص شده از جدول حذف می‌کند. |
| [iterator()](#iterator--) | یک شمارش‌گر که از مجموعه عبور می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک مرورگر جاوا برای کل مجموعه را برمی‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر مجموعه را به آرایهٔ مشخص شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همزمان (thread-safe) است یا نه. |
| [getSyncRoot()](#getSyncRoot--) | یک ریشهٔ همزمانی را برمی‌گرداند. |
### size() {#size--}
```
public final int size()
```


تعداد ردیف‌های واقعاً موجود در مجموعه را دریافت می‌کند. فقط خواندنی int.

**بازگشت:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IRow get_Item(int index)
```


ردیف مربوط به اندیس مشخص شده را برمی‌گرداند. فقط خواندنی [Row](../../com.aspose.slides/row).

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


یک نسخهٔ کپی از ردیف الگوی مشخص شده ایجاد می‌کند و آن را در انتهای جدول وارد می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | ردیفی که به‌عنوان الگو استفاده می‌شود. |
| withAttachedRows | boolean | True برای کپی همچنین تمام ردیف‌های ضمیمه شده به ردیف الگو. |

**بازگشت:**
com.aspose.slides.IRRow[] - ردیف‌های افزوده.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public final IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```


یک نسخهٔ کپی از ردیف الگوی مشخص شده ایجاد می‌کند و آن را در موقعیت مشخص شده در جدول وارد می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس ردیف جدید. |
| templ | [IRow](../../com.aspose.slides/irow) | ردیفی که به‌عنوان الگو استفاده می‌شود. |
| withAttachedRows | boolean | True برای کپی همچنین تمام ردیف‌های ضمیمه شده به ردیف الگو. |

**بازگشت:**
com.aspose.slides.IRRow[] - ردیف‌های درج‌شده.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstRowIndex, boolean withAttachedRows)
```


یک ردیف را در موقعیت مشخص شده از جدول حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| firstRowIndex | int | اندیس ردیفی که باید حذف شود. |
| withAttachedRows | boolean | True برای حذف همچنین تمام ردیف‌های پیوست. |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iterator()
```


یک شمارش‌گر که از مجموعه عبور می‌کند را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRRow> - یک IGenericEnumerator که می‌توان برای عبور از مجموعه استفاده کرد.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iteratorJava()
```


یک مرورگر جاوا برای کل مجموعه را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRRow> - یک java.util.Iterator برای کل مجموعه.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


تمام عناصر مجموعه را به آرایهٔ مشخص شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایهٔ مقصد. |
| index | int | اندیس شروع در آرایهٔ مقصد. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


مقداری برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همزمان (thread-safe) است یا نه. فقط خواندنی boolean.

**بازگشت:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


یک ریشهٔ همزمانی را برمی‌گرداند. فقط خواندنی Object.

**بازگشت:**
java.lang.Object