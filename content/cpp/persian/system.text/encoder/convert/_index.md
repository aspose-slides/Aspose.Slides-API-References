---
title: Convert()
second_title: Aspose.Slides برای C++ مرجع API
description: کاراکترها را به بایت تبدیل می‌کند.
type: docs
weight: 79
url: /fa/system.text/encoder/convert/
---
## Encoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) متد


کاراکترها را به بایت تبدیل می‌کند.

```cpp
virtual void System::Text::Encoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | کاراکترهای قابل رمزگذاری. |
| charIndex | int | افست بافر ورودی. |
| charCount | int | اندازه بافر ورودی. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | بافر بایت مقصد. |
| byteIndex | int | افست آرایه مقصد. |
| byteCount | int | اندازه آرایه مقصد. |
| flush | **bool** | اگر true باشد، پس از محاسبه حالت داخلی رمزگذار را پاک می‌کند. |
| charsUsed | int\& | مرجع به متغیری که شمارش کاراکترهای خوانده‌شده را ذخیره می‌کند. |
| bytesUsed | int\& | مرجع به متغیری که شمارش بایت‌های نوشته‌شده را ذخیره می‌کند. |
| completed | **bool**\& | مرجع به متغیری که اگر بافر ورودی مصرف شد به true تنظیم می‌شود و در غیر این صورت به false. |

## Encoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) متد


کاراکترها را به بایت تبدیل می‌کند.

```cpp
virtual void System::Text::Encoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | const char_t * | کاراکترهای قابل رمزگذاری. |
| charCount | int | اندازه بافر ورودی. |
| bytes | **uint8_t** * | بافر بایت مقصد. |
| byteCount | int | اندازه آرایه مقصد. |
| flush | **bool** | اگر true باشد، پس از محاسبه حالت داخلی رمزگذار را پاک می‌کند. |
| charsUsed | int\& | مرجع به متغیری که شمارش کاراکترهای خوانده‌شده را ذخیره می‌کند. |
| bytesUsed | int\& | مرجع به متغیری که شمارش بایت‌های نوشته‌شده را ذخیره می‌کند. |
| completed | **bool**\& | مرجع به متغیری که اگر بافر ورودی مصرف شد به true تنظیم می‌شود و در غیر این صورت به false. |

## مراجع

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [Encoder](../)
* فضای نام [System::Text](../../)
* کتابخانه [Aspose.Slides](../../../)