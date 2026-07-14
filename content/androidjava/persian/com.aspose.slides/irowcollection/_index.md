---
title: IRowCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش‌دهنده مجموعه سطرهای جدول.
type: docs
url: /fa/com.aspose.slides/irowcollection/
---
**تمام رابط‌های پیاده‌سازی شده:**
com.aspose.slides.IGenericCollection
```
public interface IRowCollection extends IGenericCollection<IRow>
```

نمایش‌دهنده مجموعه سطرهای جدول.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصری را در اندیس مشخص‌شده دریافت می‌کند. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | یک کپی از سطر الگوی مشخص‌شده ایجاد کرده و در پایین جدول اضافه می‌کند. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | یک کپی از سطر الگوی مشخص‌شده ایجاد کرده و در موقعیت مشخص‌شده در جدول قرار می‌دهد. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | سطری را در موقعیت مشخص‌شده از جدول حذف می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```

عنصری را در اندیس مشخص‌شده دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**برگرداندن:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] addClone(IRow templ, boolean withAttachedRows)
```

یک کپی از سطر الگوی مشخص‌شده ایجاد کرده و در پایین جدول اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | سطری که به عنوان الگو استفاده می‌شود. |
| withAttachedRows | boolean | برای کپی کردن همچنین تمام سطرهای پیوست به سطر الگو مقدار True باشد. |

**برگرداندن:**
com.aspose.slides.IRow[] - سطرهای اضافه‌شده.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

یک کپی از سطر الگوی مشخص‌شده ایجاد کرده و در موقعیت مشخص‌شده در جدول قرار می‌دهد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس سطر جدید. |
| templ | [IRow](../../com.aspose.slides/irow) | سطری که به عنوان الگو استفاده می‌شود. |
| withAttachedRows | boolean | برای کپی کردن همچنین تمام سطرهای پیوست به سطر الگو مقدار True باشد. |

**برگرداندن:**
com.aspose.slides.IRow[] - سطرهای واردشده.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```

سطر را در موقعیت مشخص‌شده از جدول حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| firstRowIndex | int | اندیس سطری که حذف می‌شود. |
| withAttachedRows | boolean | برای حذف همچنین تمام سطرهای پیوست مقدار True باشد. |