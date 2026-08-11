---
title: Add()
second_title: Aspose.Slides برای C++ مرجع API
description: هنگامی که در یک کلاس مشتق شده بازنویسی می‌شود، رشتهٔ مشخص‌شده را اتمی‌سازی می‌کند و به XmlNameTable اضافه می‌دارد.
type: docs
weight: 14
url: /fa/system.xml/xmlnametable/add/
---
## XmlNameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) متد


هنگامی که در یک کلاس مشتق شده بازنویسی می‌شود، رشتهٔ مشخص شده را اتمی‌سازی کرده و به [XmlNameTable](../) اضافه می‌کند.

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | آرایهٔ کاراکتری که شامل نام برای افزودن است. |
| offset | **int32_t** | شاخص صفر-پایه در آرایه که اولین کاراکتر نام را تعیین می‌کند. |
| length | **int32_t** | تعداد کاراکترهای نام. |

### مقدار بازگشت

رشتهٔ اتمی‌سازی‌شدهٔ جدید یا رشتهٔ موجود در صورتی که از قبل وجود داشته باشد. اگر طول صفر باشد، [String::Empty](../../../system/string/empty/) برگردانده می‌شود.

## XmlNameTable::Add(const String\&) متد


هنگامی که در یک کلاس مشتق شده بازنویسی می‌شود، رشتهٔ مشخص شده را اتمی‌سازی کرده و به [XmlNameTable](../) اضافه می‌کند.

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const String &array)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | نام برای افزودن. |

### مقدار بازگشت

رشتهٔ اتمی‌سازی‌شدهٔ جدید یا رشتهٔ موجود در صورتی که از قبل وجود داشته باشد.

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [String](../../../system/string/)
* کلاس [XmlNameTable](../)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)