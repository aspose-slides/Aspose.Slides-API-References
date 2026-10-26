---
title: ToBase64String()
second_title: مرجع API Aspose.Slides برای C++
description: Base-64 عناصر موجود در آرایه بایت مشخص‌شده را رمزگذاری می‌کند و داده‌های رمزگذاری‌شده را به صورت یک رشته برمی‌گرداند.
type: docs
weight: 40
url: /fa/system/convert/tobase64string/
---
## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, bool) متد

Base-64 عناصر موجود در آرایه بایت مشخص شده را رمزگذاری می‌کند و دادهٔ رمزگذاری‌شده را به صورت یک رشته بازمی‌گرداند.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, bool insert_line_breaks=false)
```

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | آرایه بایت برای رمزگذاری |
| insert_line_breaks | **bool** | مشخص می‌کند آیا کاراکترهای شکست خط باید پس از هر ۷۶ کاراکتر Base-64 در رشته خروجی درج شوند یا خیر |

### مقدار بازگشت

رشته‌ای که نمایانگر رمزگذاری Base-64 آرایهٔ ورودی است

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, bool) متد

Base-64 محدوده‌ای از عناصر موجود در آرایه بایت مشخص شده را رمزگذاری می‌کند و دادهٔ رمزگذاری‌شده را به صورت یک رشته بازمی‌گرداند.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, bool insert_line_breaks=false)
```

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | آرایه بایت حاوی محدودهٔ عناصری که باید رمزگذاری شوند |
| offset_in | int | یک اندیس از یک عنصر در آرایهٔ ورودی که در آن محدودهٔ رمزگذاری آغاز می‌شود |
| length | int | طول محدودهٔ عناصری که باید رمزگذاری شوند |
| insert_line_breaks | **bool** | مشخص می‌کند آیا کاراکترهای شکست خط باید پس از هر ۷۶ کاراکتر Base-64 در رشته خروجی درج شوند یا خیر |

### مقدار بازگشت

رشته‌ای که نمایانگر رمزگذاری Base-64 محدودهٔ عناصر آرایهٔ ورودی است

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, Base64FormattingOptions) متد

Base-64 عناصر موجود در آرایه بایت مشخص شده را رمزگذاری می‌کند و دادهٔ رمزگذاری‌شده را به صورت یک رشته بازمی‌گرداند.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, Base64FormattingOptions options)
```

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | آرایه بایت برای رمزگذاری |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | گزینه‌های قالب‌بندی دادهٔ رمزگذاری Base-64 را مشخص می‌کند |

### مقدار بازگشت

رشته‌ای که نمایانگر رمزگذاری Base-64 آرایهٔ ورودی است

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, Base64FormattingOptions) متد

Base-64 محدوده‌ای از عناصر موجود در آرایه بایت مشخص شده را رمزگذاری می‌کند و دادهٔ رمزگذاری‌شده را به صورت یک رشته بازمی‌گرداند.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, Base64FormattingOptions options)
```

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | آرایه بایت حاوی محدودهٔ عناصری که باید رمزگذاری شوند |
| offset_in | int | یک اندیس از یک عنصر در آرایهٔ ورودی که در آن محدودهٔ رمزگذاری آغاز می‌شود |
| length | int | طول محدودهٔ عناصری که باید رمزگذاری شوند |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | گزینه‌های قالب‌بندی دادهٔ رمزگذاری Base-64 را مشخص می‌کند |

### مقدار بازگشت

رشته‌ای که نمایانگر رمزگذاری Base-64 محدودهٔ عناصر آرایهٔ ورودی است

## مراجع

* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../../string/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)