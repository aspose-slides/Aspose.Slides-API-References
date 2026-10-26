---
title: InsertClone()
second_title: مرجع API Aspose.Slides برای C++
description: یک کپی از ستون قالب مشخص‌شده ایجاد می‌کند و آن را در موقعیت مشخص‌شده در یک جدول درج می‌کند.
type: docs
weight: 27
url: /fa/aspose.slides/icolumncollection/insertclone/
---
## IColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) متد

Creates a copy of the specified template column and insert it at the specified position in a table.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس یک ستون جدید. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) که به عنوان الگو استفاده می‌شود. |
| withAttachedColumns | **bool** | True برای کپی کردن همچنین تمام ستون‌های پیوست شده به ستون الگو. |

### مقدار بازگشتی

ستون‌های درج‌شده.

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IColumn](../../icolumn/)
* کلاس [IColumnCollection](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)