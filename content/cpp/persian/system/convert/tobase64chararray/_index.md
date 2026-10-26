---
title: ToBase64CharArray()
second_title: Aspose.Slides برای C++ مرجع API
description: Base-64 محدوده‌ای از عناصر را در آرایه بایت مشخص‌شده رمزگذاری می‌کند و داده‌های رمزگذاری‌شده را به‌صورت آرایه‌ای از کاراکترهای یونیکد ذخیره می‌نماید.
type: docs
weight: 27
url: /fa/system/convert/tobase64chararray/
---
## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char16_t\>\&, int, bool) متد

Base-64 محدوده‌ای از عناصر را در آرایه بایت مشخص‌شده رمزگذاری می‌کند و داده‌های رمزگذاری‌شده را به‌صورت آرایه‌ای از کاراکترهای یونیکد ذخیره می‌نماید.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char16_t> &out_array, int offset_out, bool insert_line_breaks=false)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | آرایه‌ای از بایت‌ها که شامل محدوده‌ای از عناصر برای رمزگذاری است |
| offset_in | int | نمایه‌ای از یک عنصر در آرایه ورودی که محدوده برای رمزگذاری از آنجا شروع می‌شود |
| length | int | طول محدوده‌ای از عناصر برای رمزگذاری |
| out_array | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | یک مرجع ثابت به آرایه خروجی که دادهٔ حاصل در آن قرار می‌گیرد |
| offset_out | int | نمایه‌ای در آرایه خروجی که از آنجا شروع به قرار دادن دادهٔ حاصل می‌شود |
| insert_line_breaks | **bool** | مشخص می‌کند آیا کاراکترهای شکست خط پس از هر ۷۶ کاراکتر base-64 در آرایه خروجی درج شوند |

### مقدار بازگشت

تعداد کاراکترهای نوشته‌شده در آرایه خروجی

## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char_t\>\&, int, Base64FormattingOptions) متد

Base-64 محدوده‌ای از عناصر را در آرایه بایت مشخص‌شده رمزگذاری می‌کند و داده‌های رمزگذاری‌شده را به‌صورت آرایه‌ای از کاراکترهای یونیکد ذخیره می‌نماید.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char_t> &out_array, int offset_out, Base64FormattingOptions options)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | آرایه‌ای از بایت‌ها که شامل محدوده‌ای از عناصر برای رمزگذاری است |
| offset_in | int | نمایه‌ای از یک عنصر در آرایه ورودی که محدوده برای رمزگذاری از آنجا شروع می‌شود |
| length | int | طول محدوده‌ای از عناصر برای رمزگذاری |
| out_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | یک مرجع ثابت به آرایه خروجی که دادهٔ حاصل در آن قرار می‌گیرد |
| offset_out | int | نمایه‌ای در آرایه خروجی که از آنجا شروع به قرار دادن دادهٔ حاصل می‌شود |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | گزینه‌های قالب‌بندی داده‌های رمزگذاری‌شدهٔ base-64 را مشخص می‌کند |

### مقدار بازگشت

تعداد کاراکترهای نوشته‌شده در آرایه خروجی

## همچنین ببینید

* enum [Base64FormattingOptions](../../base64formattingoptions/)
* typedef [ArrayPtr](../../arrayptr/)
* ساختار [Convert](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)