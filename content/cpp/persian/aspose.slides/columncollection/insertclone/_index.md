---
title: InsertClone()
second_title: مرجع API Aspose.Slides برای C++
description: یک کپی از ستون قالب مشخص شده ایجاد می‌کند و آن را در موقعیت تعیین شده در جدول وارد می‌سازد.
type: docs
weight: 66
url: /fa/aspose.slides/columncollection/insertclone/
---
## ColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) method

یک کپی از ستون قالب مشخص شده ایجاد می‌کند و آن را در موقعیت تعیین‌شده در جدول وارد می‌سازد.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | اندیس یک ستون جدید. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) که به عنوان قالب استفاده می‌شود. |
| withAttachedColumns | **bool** | True برای این‌که تمام ستون‌های ضمیمه به ستون قالب نیز کپی شوند. |

### مقدار بازگشتی

ستون‌های وارد شده.

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IColumn](../../icolumn/)
* Class [ColumnCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)