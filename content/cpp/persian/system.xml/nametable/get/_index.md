---
title: Get()
second_title: Aspose.Slides برای C++ مرجع API
description: رشتهٔ اتمیزه‌شده با مقدار مشخص‌ شده را برمی‌گرداند.
type: docs
weight: 27
url: /fa/system.xml/nametable/get/
---
## NameTable::Get(const String\&) متد

رشتهٔ اتمیزه‌شده با مقدار مشخص‌شده را باز می‌گرداند.

```cpp
const String & System::Xml::NameTable::Get(const String &value) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | نامی که باید یافت شود. |

### مقدار بازگشت

رشتهٔ اتمیزه‌شده یا **nullptr** اگر رشتهٔ قبلاً اتمیزه نشده باشد.

## NameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) متد

رشتهٔ اتمیزه‌شده‌ای را باز می‌گرداند که شامل همان کاراکترها به‌عنوان بازهٔ مشخص‌شده‌ای از کاراکترها در آرایهٔ داده شده است.

```cpp
const String & System::Xml::NameTable::Get(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | آرایهٔ کاراکتری که شامل نام برای جستجو است. |
| start | **int32_t** | اندیس صفر-مبنا در آرایه که اولین کاراکتر نام را مشخص می‌کند. |
| len | **int32_t** | تعداد کاراکترهای نام. |

### مقدار بازگشت

رشتهٔ اتمیزه‌شده یا **nullptr** اگر رشتهٔ قبلاً اتمیزه نشده باشد. اگر **len** صفر باشد، [String::Empty](../../../system/string/empty/) بازگردانده می‌شود.

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [NameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)