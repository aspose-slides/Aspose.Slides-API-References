---
title: IRowCollection
second_title: مرجع API Aspose.Slides برای Java
description: نمایانگر مجموعه سطرهای جدول است.
type: docs
url: /fa/com.aspose.slides/irowcollection/
---
**همه رابط‌های پیاده‌سازی‌شده:**
com.aspose.slides.IGenericCollection
```
public interface IRowCollection extends IGenericCollection<IRow>
```

نمایانگر مجموعه سطرهای جدول است.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Creates a copy of the specified template row and inserts it at the bottom of a table. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Creates a copy of the specified template row and insert it at the specified position in a table. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Removes a row at the specified position from a table. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```


عنصر موردنظر را در ایندکس مشخص‌شده برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] addClone(IRow templ, boolean withAttachedRows)
```


یک نسخه از سطر قالب مشخص‌شده ایجاد می‌کند و آن را در انتهای جدول وارد می‌سازد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | سطری که به عنوان قالب استفاده می‌شود. |
| withAttachedRows | boolean | در صورتی‌که true باشد، تمام سطرهای پیوست‌شده به سطر قالب نیز کپی می‌شوند. |

**بازگشت:**
com.aspose.slides.IRow[] - سطرهای اضافه‌شده.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```


یک نسخه از سطر قالب مشخص‌شده ایجاد می‌کند و آن را در موقعیت مشخص‌شده در جدول وارد می‌سازد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس سطر جدید. |
| templ | [IRow](../../com.aspose.slides/irow) | سطری که به عنوان قالب استفاده می‌شود. |
| withAttachedRows | boolean | در صورتی‌که true باشد، تمام سطرهای پیوست‌شده به سطر قالب نیز کپی می‌شوند. |

**بازگشت:**
com.aspose.slides.IRow[] - سطرهای وارد‌شده.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```


سطر را در موقعیت مشخص‌شده از جدول حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| firstRowIndex | int | ایندکس سطر برای حذف. |
| withAttachedRows | boolean | در صورتی‌که true باشد، تمام سطرهای پیوست‌شده نیز حذف می‌شوند. |