---
title: IColumnCollection
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نماینده مجموعه‌ای از ستون‌ها در یک جدول.
type: docs
url: /fa/com.aspose.slides/icolumncollection/
---
**تمام واسط‌های پیاده‌سازی شده:**
com.aspose.slides.IGenericCollection
```
public interface IColumnCollection extends IGenericCollection<IColumn>
```

نمایش‌دهنده مجموعه‌ای از ستون‌ها در یک جدول.
## روش‌ها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ستونی را که در اندیس مشخص شده است بر می‌گرداند. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | یک کپی از سطر قالب مشخص‌شده ایجاد می‌کند و آن را در انتهای جدول وارد می‌نماید. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | یک کپی از ستون قالب مشخص‌شده ایجاد می‌کند و آن را در موقعیت مشخص‌شده در جدول وارد می‌نماید. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | ستونی را که در موقعیت مشخص شده است از جدول حذف می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColumn get_Item(int index)
```

ستونی را که در اندیس مشخص شده است بر می‌گرداند. فقط خواندنی [IColumn](../../com.aspose.slides/icolumn).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بر می‌گرداند:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

یک کپی از سطر قالب مشخص‌شده ایجاد می‌کند و آن را در انتهای جدول وارد می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | ستونی که به عنوان قالب استفاده می‌شود. |
| withAttachedColumns | boolean | درست برای کپی کردن تمام ستون‌های متصل به سطر قالب. |

**بر می‌گرداند:**
com.aspose.slides.IColumn[] - ستون‌های اضافه شده.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

یک کپی از ستون قالب مشخص‌شده ایجاد می‌کند و آن را در موقعیت مشخص‌شده در جدول وارد می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس ستون جدید. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | ستونی که به عنوان قالب استفاده می‌شود. |
| withAttachedColumns | boolean | درست برای کپی کردن تمام ستون‌های متصل به ستون قالب. |

**بر می‌گرداند:**
com.aspose.slides.IColumn[] - ستون‌های وارد شده.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

ستونی را که در موقعیت مشخص شده است از جدول حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| firstColumnIndex | int | اندیس ستونی که باید حذف شود. |
| withAttachedRows | boolean | درست برای حذف تمام ستون‌های متصل. |