---
title: AddClone()
second_title: مرجع API Aspose.Slides برای C++
description: یک نسخه از ردیف قالب مشخص ایجاد می‌کند و آن را در انتهای جدول وارد می‌سازد.
type: docs
weight: 14
url: /fa/aspose.slides/icolumncollection/addclone/
---
## IColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) متد

یک نسخه از ردیف قالب مشخص ایجاد می‌کند و آن را در انتهای جدول وارد می‌سد.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) که به عنوان قالب استفاده می‌شود. |
| withAttachedColumns | **bool** | True برای کپی همچنین تمام ستون‌های پیوست شده به ردیف قالب. |

### مقدار بازگشت

ستون‌های اضافه شده.

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IColumn](../../icolumn/)
* Class [IColumnCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)