---
title: InsertClone()
second_title: مرجع API Aspose.Slides برای C++
description: یک کپی از ردیف قالب مشخص شده ایجاد می‌کند و آن را در موقعیت تعیین شده در یک جدول درج می‌نماید.
type: docs
weight: 27
url: /fa/aspose.slides/irowcollection/insertclone/
---
## IRowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) متد

یک کپی از ردیف قالب مشخص شده ایجاد می‌کند و آن را در موقعیت تعیین شده در یک جدول درج می‌نماید.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | شاخص یک ردیف جدید. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) که به عنوان قالب استفاده می‌شود. |
| withAttachedRows | **bool** | True برای کپی کردن تمام ردیف‌های پیوست‌شده به ردیف قالب نیز. |

### مقدار برگشتی

ردیف‌های درج‌شده.

## موارد مرتبط

* تعریف‌نوع [ArrayPtr](../../../system/arrayptr/)
* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IRow](../../irow/)
* کلاس [IRowCollection](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)