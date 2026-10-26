---
title: Convert()
second_title: Aspose.Slides برای C++ مرجع API
description: کاراکترها را به بایت تبدیل می‌کند.
type: docs
weight: 1
url: /fa/system.text/encodingencoder/convert/
---
## EncodingEncoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) متد


کاراکترها را به بایت تبدیل می‌کند.

```cpp
virtual void System::Text::EncodingEncoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | const char_t * | کاراکترها برای رمزنگاری. |
| charCount | int | اندازه بافر ورودی. |
| bytes | **uint8_t** * | بافر بایت مقصد. |
| byteCount | int | اندازه آرایه مقصد. |
| flush | **bool** | اگر true باشد، وضعیت داخلی انکودر را پس از محاسبه پاک می‌کند. |
| charsUsed | int\& | مرجع به متغیری برای ذخیره تعداد کاراکترهای خوانده‌شده. |
| bytesUsed | int\& | مرجع به متغیری برای ذخیره تعداد بایت‌های نوشته‌شده. |
| completed | **bool**\& | مرجع به متغیری که اگر بافر ورودی تمام شد به true تنظیم می‌شود و در غیر اینصورت به false. |

## EncodingEncoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) متد


کاراکترها را به بایت تبدیل می‌کند.

```cpp
virtual void System::Text::EncodingEncoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | کاراکترها برای رمزنگاری. |
| charIndex | int | جایگاه بافر ورودی. |
| charCount | int | اندازه بافر ورودی. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | بافر بایت مقصد. |
| byteIndex | int | جایگاه آرایه مقصد. |
| byteCount | int | اندازه آرایه مقصد. |
| flush | **bool** | اگر true باشد، وضعیت داخلی انکودر را پس از محاسبه پاک می‌کند. |
| charsUsed | int\& | مرجع به متغیری برای ذخیره تعداد کاراکترهای خوانده‌شده. |
| bytesUsed | int\& | مرجع به متغیری برای ذخیره تعداد بایت‌های نوشته‌شده. |
| completed | **bool**\& | مرجع به متغیری که اگر بافر ورودی تمام شد به true تنظیم می‌شود و در غیر اینصورت به false. |

## مراجع

* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [EncodingEncoder](../)
* فضای‌نام [System::Text](../../)
* Library [Aspose.Slides](../../../)