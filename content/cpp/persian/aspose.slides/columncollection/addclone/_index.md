---
title: AddClone()
second_title: Aspose.Slides برای مرجع API C++
description: یک نسخهٔ کپی از سطر قالب مشخص‌شده را ایجاد می‌کند و آن را در پایین جدول قرار می‌دهد.
type: docs
weight: 53
url: /fa/aspose.slides/columncollection/addclone/
---
## ColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) متد

یک کپی از ردیف قالب مشخص‌شده ایجاد می‌کند و آن را در پایین جدول اضافه می‌نماید.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) که به عنوان قالب استفاده می‌شود. |
| withAttachedColumns | **bool** | True برای کپی کردن همچنین تمام ستون‌های پیوست‌شده به سطر قالب. |

### مقدار بازگشت

ستون‌های اضافه‌شده.

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IColumn](../../icolumn/)
* Class [ColumnCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)