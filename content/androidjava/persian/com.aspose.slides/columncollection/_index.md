---
title: ColumnCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر مجموعه‌ای از ستون‌ها در یک جدول.
type: docs
url: /fa/com.aspose.slides/columncollection/
---
**Inheritance:**  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
[com.aspose.slides.IColumnCollection](../../com.aspose.slides/icolumncollection)  
```
public final class ColumnCollection extends DomObject<RowCollection> implements IColumnCollection
```

نمایانگر مجموعه‌ای از ستون‌ها در یک جدول است.
## متدها

| متد | توضیح |
| --- | --- |
| [size()](#size--) | تعداد ستون‌ها در یک مجموعه را بر می‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | ستون را در ایندکس مشخص شده بر می‌گرداند. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | یک کپی از ردیف قالب مشخص‌شده را ایجاد می‌کند و آن را در انتهای جدول می‌گذارد. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | یک کپی از ستون قالب مشخص‌شده را ایجاد می‌کند و آن را در موقعیت تعیین‌شده در جدول وارد می‌نماید. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | ستونی را در موقعیت مشخص‌شده از جدول حذف می‌کند. |
| [iterator()](#iterator--) | یک شمارنده بر می‌گرداند که در مجموعه پیمایش می‌کند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه بر می‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر را از مجموعه به آرایه مشخص‌شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را بر می‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده (Thread-Safe) است. |
| [getSyncRoot()](#getSyncRoot--) | ریشه همگام‌سازی را بر می‌گرداند. |
### size() {#size--}
```
public final int size()
```

تعداد ستون‌ها در یک مجموعه را بر می‌گرداند. فقط‌خواندنی int.

**بازگشت:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final IColumn get_Item(int index)
```

ستون را در ایندکس مشخص‌شده بر می‌گرداند. فقط‌خواندنی [Column](../../com.aspose.slides/column).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**  
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

یک کپی از ردیف قالب مشخص‌شده را ایجاد می‌کند و آن را در انتهای جدول می‌گذارد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | ستونی که به‌عنوان قالب استفاده می‌شود. |
| withAttachedColumns | boolean | true برای کپی کردن تمام ستون‌های پیوست‌شده به ردیف قالب. |

**بازگشت:**  
com.aspose.slides.IColumn[] - ستون‌های اضافه‌شده.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

یک کپی از ستون قالب مشخص‌شده را ایجاد می‌کند و آن را در موقعیت تعیین‌شده در جدول وارد می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس ستون جدید. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | ستونی که به‌عنوان قالب استفاده می‌شود. |
| withAttachedColumns | boolean | true برای کپی کردن تمام ستون‌های پیوست‌شده به ستون قالب. |

**بازگشت:**  
com.aspose.slides.IColumn[] - ستون‌های واردشده.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

ستونی را در موقعیت مشخص‌شده از جدول حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| firstColumnIndex | int | ایندکس ستونی که حذف می‌شود. |
| withAttachedRows | boolean | true برای حذف تمام ستون‌های پیوست‌شده. |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iterator()
```

یک شمارنده بر می‌گرداند که در مجموعه پیمایش می‌کند.

**بازگشت:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - IGenericEnumeratorی که می‌تواند برای پیمایش مجموعه استفاده شود.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iteratorJava()
```

یک iterator جاوا برای کل مجموعه بر می‌گرداند.

**بازگشت:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - java.util.Iterator برای کل مجموعه.
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

مقداری را بر می‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده (Thread-Safe) است. فقط‌خواندنی boolean.

**بازگشت:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ریشه همگام‌سازی را بر می‌گرداند. فقط‌خواندنی Object.

**بازگشت:**  
java.lang.Object