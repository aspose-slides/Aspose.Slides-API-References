---
title: ColumnCollection
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایش‌دهنده مجموعه‌ای از ستون‌ها در یک جدول.
type: docs
url: /fa/com.aspose.slides/columncollection/
---
**ارث‌بری:**
java.lang.Object, com.aspose.slides.DomObject

**همه رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IColumnCollection](../../com.aspose.slides/icolumncollection)
```
public final class ColumnCollection extends DomObject<RowCollection> implements IColumnCollection
```

نمایشگر مجموعه‌ای از ستون‌ها در یک جدول.
## متدها

| متد | توضیح |
| --- | --- |
| [size()](#size--) | تعداد ستون‌ها در یک مجموعه را برمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | ستونی که در ایندکس مشخص شده است را برمی‌گرداند. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | یک نسخه از ردیف قالب مشخص‌شده ایجاد می‌کند و آن را در انتهای جدول درج می‌کند. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | یک نسخه از ستون قالب مشخص‌شده ایجاد می‌کند و آن را در موقعیت مشخص‌شده در جدول درج می‌کند. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | ستونی را که در موقعیت مشخص شده است از جدول حذف می‌کند. |
| [iterator()](#iterator--) | یک شمارنده برمی‌گرداند که بر مجموعه تکرار می‌کند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه برمی‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر مجموعه را به آرایهٔ مشخص‌شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده (Thread-safe) است. |
| [getSyncRoot()](#getSyncRoot--) | یک ریشهٔ همگام‌سازی را برمی‌گرداند. |
### size() {#size--}
```
public final int size()
```

تعداد ستون‌ها در یک مجموعه را برمی‌گرداند. فقط‌خواندنی int.

**بازگرداندن:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColumn get_Item(int index)
```

ستونی که در ایندکس مشخص شده است را برمی‌گرداند. فقط‌خواندنی [Column](../../com.aspose.slides/column).

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| index | int |  |

**بازگرداندن:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

یک نسخه از ردیف قالب مشخص‌شده ایجاد می‌کند و آن را در انتهای جدول درج می‌کند.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | ستونی که به عنوان قالب استفاده می‌شود. |
| withAttachedColumns | boolean | True برای کپی همچنین تمام ستون‌های پیوست‌شده به ردیف قالب. |

**بازگرداندن:**
com.aspose.slides.IColumn[] - ستون‌های اضافه‌شده.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

یک نسخه از ستون قالب مشخص‌شده ایجاد می‌کند و آن را در موقعیت مشخص‌شده در جدول درج می‌کند.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| index | int | ایندکس ستونی جدید. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | ستونی که به عنوان قالب استفاده می‌شود. |
| withAttachedColumns | boolean | True برای کپی همچنین تمام ستون‌های پیوست‌شده به ستون قالب. |

**بازگرداندن:**
com.aspose.slides.IColumn[] - ستون‌های درج‌شده.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

ستونی را که در موقعیت مشخص شده است از جدول حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| firstColumnIndex | int | ایندکس ستونی برای حذف. |
| withAttachedRows | boolean | True برای حذف همچنین تمام ستون‌های پیوست‌شده. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iterator()
```

یک شمارنده برمی‌گرداند که بر مجموعه تکرار می‌کند.

**بازگرداندن:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - یک IGenericEnumerator که می‌توان از آن برای تکرار در مجموعه استفاده کرد.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iteratorJava()
```

یک iterator جاوا برای کل مجموعه برمی‌گرداند.

**بازگرداندن:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - یک java.util.Iterator برای کل مجموعه.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر مجموعه را به آرایهٔ مشخص‌شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه مقصد. |
| index | int | ایندکس شروع در آرایه مقصد. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همگام‌سازی شده (Thread-safe) است. فقط‌خواندنی boolean.

**بازگرداندن:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

یک ریشهٔ همگام‌سازی را برمی‌گرداند. فقط‌خواندنی Object.

**بازگرداندن:**
java.lang.Object