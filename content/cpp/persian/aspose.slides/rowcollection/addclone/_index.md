---
title: AddClone()
second_title: مرجع API Aspose.Slides برای C++
description: یک کپی از ردیف قالب مشخص شده را ایجاد می‌کند و آن را در انتهای جدول درج می‌گذارد.
type: docs
weight: 53
url: /fa/aspose.slides/rowcollection/addclone/
---
## RowCollection::AddClone(System::SharedPtr\<IRow\>, bool) متد

یک کپی از ردیف قالب مشخص شده را ایجاد می‌کند و آن را در انتهای جدول درج می‌گذارد.

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) که به عنوان قالب استفاده می‌شود. |
| withAttachedRows | **bool** | True برای کپی‌کردن تمام ردیف‌های پیوست‌شده به ردیف قالب نیز. |

### مقدار بازگشتی

سطرهای اضافه‌شده.

## مراجع

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IRow](../../irow/)
* کلاس [RowCollection](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)