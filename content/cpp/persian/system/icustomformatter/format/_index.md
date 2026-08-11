---
title: Format()
second_title: مرجع API Aspose.Slides برای C++
description: یک نمایش متنی از مقداری که توسط شیء جاری نمایانده می‌شود با استفاده از قالب مشخص‌شده برمی‌گرداند.
type: docs
weight: 1
url: /fa/system/icustomformatter/format/
---
## ICustomFormatter::Format(System::String, System::SharedPtr\<System::Object\>, System::SharedPtr\<System::IFormatProvider\>) متد

یک نمایش متنی از مقداری که توسط شیء جاری نمایانده می‌شود با استفاده از قالب مشخص‌شده برمی‌گرداند.

```cpp
virtual System::String System::ICustomFormatter::Format(System::String format, System::SharedPtr<System::Object> arg, System::SharedPtr<System::IFormatProvider> formatProvider)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| format | [System::String](../../string/) | قالب رشته |
| arg | [System::SharedPtr](../../sharedptr/)\<[System::Object](../../object/)\> | شیئی که باید قالب‌بندی شود |
| formatProvider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | شیئی که اطلاعات قالب‌بندی را فراهم می‌کند |

### مقدار بازگشتی

نمایش متنی **arg** که بر اساس قالب مشخص‌شده توسط **format** و **formatProvider** قالب‌بندی شده است

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../sharedptr/)
* کلاس [String](../../string/)
* کلاس [Object](../../object/)
* کلاس [IFormatProvider](../../iformatprovider/)
* کلاس [ICustomFormatter](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)