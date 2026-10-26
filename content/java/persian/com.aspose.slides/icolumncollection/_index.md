---
title: IColumnCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایش‌دهنده مجموعه‌ای از ستون‌ها در یک جدول.
type: docs
url: /fa/com.aspose.slides/icolumncollection/
---
**تمام اینترفیس‌های پیاده‌سازی شده:**
com.aspose.slides.IGenericCollection
```
public interface IColumnCollection extends IGenericCollection<IColumn>
```

نمایش‌دهندهٔ مجموعه‌ای از ستون‌ها در یک جدول.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ستون را در ایندکس مشخص شده برمی‌گرداند. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | یک کپی از ردیف قالب مشخص شده ایجاد می‌کند و آن را در انتهای جدول وارد می‌کند. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | یک کپی از ستون قالب مشخص شده ایجاد می‌کند و آن را در موقعیت مشخص شده در یک جدول وارد می‌کند. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | ستونی را در موقعیت مشخص شده از جدول حذف می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColumn get_Item(int index)
```

ستون را در ایندکس مشخص شده برمی‌گرداند. فقط‌خواندنی [IColumn](../../com.aspose.slides/icolumn).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

یک کپی از ردیف قالب مشخص شده ایجاد می‌کند و آن را در انتهای جدول وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | ستونی که به عنوان قالب استفاده می‌شود. |
| withAttachedColumns | boolean | True برای کپی کردن تمام ستون‌های پیوست به ردیف قالب. |

**بازگشت:**
com.aspose.slides.IColumn[] - ستون‌های اضافه شده.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

یک کپی از ستون قالب مشخص شده ایجاد می‌کند و آن را در موقعیت مشخص شده در یک جدول وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس یک ستون جدید. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | ستونی که به عنوان قالب استفاده می‌شود. |
| withAttachedColumns | boolean | True برای کپی کردن تمام ستون‌های پیوست به ستون قالب. |

**بازگشت:**
com.aspose.slides.IColumn[] - ستون‌های وارد شده.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

ستونی را در موقعیت مشخص شده از جدول حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| firstColumnIndex | int | اندیس یک ستون برای حذف. |
| withAttachedRows | boolean | True برای حذف تمام ستون‌های پیوست نیز. |