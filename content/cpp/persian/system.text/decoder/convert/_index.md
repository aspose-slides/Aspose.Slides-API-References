---
title: Convert()
second_title: Aspose.Slides برای C++ مستندات API
description: بایت‌ها را به کاراکترها تبدیل می‌کند.
type: docs
weight: 79
url: /fa/system.text/decoder/convert/
---
## Decoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) method

بایت‌ها را به کاراکترها تبدیل می‌کند.

```cpp
virtual void System::Text::Decoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | بایت‌های برای رمزگشایی. |
| byteIndex | int | آفست بافر ورودی. |
| byteCount | int | اندازه بافر ورودی. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | بافر کاراکتر مقصد. |
| charIndex | int | آفست آرایه مقصد. |
| charCount | int | اندازه آرایه مقصد. |
| flush | **bool** | اگر true باشد، وضعیت داخلی decoder را پس از محاسبه پاک می‌کند. |
| bytesUsed | int\& | مرجع به متغیر برای ذخیره‌سازی شمارش بایت‌های خوانده‌شده. |
| charsUsed | int\& | مرجع به متغیر برای ذخیره‌سازی شمارش کاراکترهای نوشته‌شده. |
| completed | **bool**\& | مرجع به متغیر که در صورت تخلیه بفر ورودی به true تنظیم می‌شود و در غیر این صورت به false. |

## Decoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) method

بایت‌ها را به کاراکترها تبدیل می‌کند.

```cpp
virtual void System::Text::Decoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | const **uint8_t** * | بایت‌های برای رمزگشایی. |
| byteCount | int | اندازه بافر ورودی. |
| chars | char_t * | بافر کاراکتر مقصد. |
| charCount | int | اندازه آرایه مقصد. |
| flush | **bool** | اگر true باشد، وضعیت داخلی decoder را پس از محاسبه پاک می‌کند. |
| bytesUsed | int\& | مرجع به متغیر برای ذخیره‌سازی شمارش بایت‌های خوانده‌شده. |
| charsUsed | int\& | مرجع به متغیر برای ذخیره‌سازی شمارش کاراکترهای نوشته‌شده. |
| completed | **bool**\& | مرجع به متغیر که در صورت تخلیه بفر ورودی به true تنظیم می‌شود و در غیر این صورت به false. |

## موارد مرتبط

* تعریف‌نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [Decoder](../)
* فضای‌نام [System::Text](../../)
* کتابخانه [Aspose.Slides](../../../)