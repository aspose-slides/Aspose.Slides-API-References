---
title: AddClone()
second_title: Aspose.Slides برای مرجع API C++
description: یک نسخه از ردیف الگوی مشخص‌شده ایجاد می‌کند و آن را در پایین جدول درج می‌نماید.
type: docs
weight: 14
url: /fa/aspose.slides/irowcollection/addclone/
---
## IRowCollection::AddClone(System::SharedPtr\<IRow\>, bool) متد


یک نسخه از ردیف الگوی مشخص‌شده را ایجاد می‌کند و آن را در پایین جدول درج می‌نماید.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) که به عنوان الگو استفاده می‌شود. |
| withAttachedRows | **bool** | True برای کپی کردن همه ردیف‌های پیوست‌شده به ردیف الگو نیز. |

### مقدار بازگشتی

ردیف‌های اضافه شده.

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IRow](../../irow/)
* کلاس [IRowCollection](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)