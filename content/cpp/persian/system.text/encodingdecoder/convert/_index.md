---
title: Convert()
second_title: مرجع API Aspose.Slides برای C++
description: بایت‌ها را به کاراکترها تبدیل می‌کند.
type: docs
weight: 1
url: /fa/system.text/encodingdecoder/convert/
---
## EncodingDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int&, int&, bool&) متد

بایت‌ها را به کاراکترها تبدیل می‌کند.

```cpp
void System::Text::EncodingDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | const **uint8_t** * | بایت‌های برای رمزگشایی. |
| byteCount | int | اندازه بافر ورودی. |
| chars | char_t * | بافر کاراکتر مقصد. |
| charCount | int | اندازه آرایه مقصد. |
| flush | **bool** | اگر true باشد، وضعیت داخلی رمزگشای را پس از محاسبه پاک می‌کند. |
| bytesUsed | int& | مرجع به متغیری برای ذخیرهٔ تعداد بایت‌های خوانده‌شده. |
| charsUsed | int& | مرجع به متغیری برای ذخیرهٔ تعداد کاراکترهای نوشته‌شده. |
| completed | **bool**& | مرجع به متغیری که در صورت خالی شدن بافر ورودی به true تنظیم می‌شود و در غیر این صورت به false. |

## EncodingDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int&, int&, bool&) متد

بایت‌ها را به کاراکترها تبدیل می‌کند.

```cpp
void System::Text::EncodingDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | بایت‌های برای رمزگشایی. |
| byteIndex | int | مقدار افست بافر ورودی. |
| byteCount | int | اندازه بافر ورودی. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | بافر کاراکتر مقصد. |
| charIndex | int | افست آرایه مقصد. |
| charCount | int | اندازه آرایه مقصد. |
| flush | **bool** | اگر true باشد، وضعیت داخلی رمزگشای را پس از محاسبه پاک می‌کند. |
| bytesUsed | int& | مرجع به متغیری برای ذخیرهٔ تعداد بایت‌های خوانده‌شده. |
| charsUsed | int& | مرجع به متغیری برای ذخیرهٔ تعداد کاراکترهای نوشته‌شده. |
| completed | **bool**& | مرجع به متغیری که در صورت خالی شدن بافر ورودی به true تنظیم می‌شود و در غیر این صورت به false. |

## مراجع

* تعریف‌نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [EncodingDecoder](../)
* فضای نام [System::Text](../../)
* کتابخانه [Aspose.Slides](../../../)