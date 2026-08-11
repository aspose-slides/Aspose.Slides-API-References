---
title: InsertClone()
second_title: Aspose.Slides برای C++ مرجع API
description: یک کپی از ردیف الگوی مشخص شده ایجاد می‌کند و آن را در موقعیت مشخص شده در یک جدول اضافه می‌نماید.
type: docs
weight: 66
url: /fa/aspose.slides/rowcollection/insertclone/
---
## RowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) متد

یک نسخه از ردیف الگو مشخص شده ایجاد می‌کند و آن را در موقعیت مشخص شده در یک جدول اضافه می‌کند.

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows) override
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس یک ردیف جدید. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) که به عنوان الگو استفاده می‌شود. |
| withAttachedRows | **bool** | True برای کپی کردن همچنین تمام ردیف‌های پیوست شده به ردیف الگو. |

### مقدار بازگشتی

ردیف‌های درج شده.

## موارد مرتبط

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IRow](../../irow/)
* کلاس [RowCollection](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)