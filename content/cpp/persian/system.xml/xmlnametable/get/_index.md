---
title: Get()
second_title: مرجع API Aspose.Slides برای C++
description: زمانی که در یک کلاس مشتق شده بازنویسی می‌شود، رشتهٔ اتمی‌شده‌ای را بر می‌گرداند که شامل همان کاراکترهای بازهٔ مشخص‌شده در آرایهٔ داده‌شده است.
type: docs
weight: 1
url: /fa/system.xml/xmlnametable/get/
---
## XmlNameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) متد

هنگامی که در یک کلاس مشتق شده بازنویسی می‌شود، رشتهٔ اتمی‌شده‌ای را بر می‌گرداند که شامل همان کاراکترهای بازهٔ تعیین‌شده در آرایهٔ داده‌شده است.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | آرایهٔ کاراکتری که شامل نام برای جستجو است. |
| offset | **int32_t** | شاخص صفر مبنا در آرایه که اولین کاراکتر نام را تعیین می‌کند. |
| length | **int32_t** | تعداد کاراکترهای موجود در نام. |

### مقدار بازگشت

رشتهٔ اتمی‌شده یا **nullptr** اگر رشته قبلاً اتمی‌نشده باشد. اگر **length** صفر باشد، [String::Empty](../../../system/string/empty/) برگردانده می‌شود.

## XmlNameTable::Get(const String\&) متد

هنگامی که در یک کلاس مشتق شده بازنویسی می‌شود، رشتهٔ اتمی‌شده‌ای را بر می‌گرداند که دارای همان مقدار رشتهٔ مشخص شده است.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const String &array)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | نام برای جستجو. |

### مقدار بازگشت

رشتهٔ اتمی‌شده یا **nullptr** اگر رشته قبلاً اتمی‌نشده باشد.

## مراجع

* تعریف‌نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [String](../../../system/string/)
* کلاس [XmlNameTable](../)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)