---
title: Convert()
second_title: Aspose.Slides برای C++ مرجع API
description: کاراکترها را به بایت‌ها تبدیل می‌کند.
type: docs
weight: 66
url: /fa/system.text/icuencoder/convert/
---
## ICUEncoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) متد

کاراکترها را به بایت‌ها تبدیل می‌کند.

```cpp
virtual void System::Text::ICUEncoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | کاراکترها برای رمزگذاری. |
| charIndex | int | آفست بافر ورودی. |
| charCount | int | اندازه بافر ورودی. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | بافر بایتی مقصد. |
| byteIndex | int | آفست آرایه مقصد. |
| byteCount | int | اندازه آرایه مقصد. |
| flush | **bool** | اگر درست باشد، پس از محاسبه وضعیت داخلی انکودر را پاک می‌کند. |
| charsUsed | int\& | مرجع به متغیری برای ذخیره تعداد کاراکترهای خوانده شده. |
| bytesUsed | int\& | مرجع به متغیری برای ذخیره تعداد بایت‌های نوشته شده. |
| completed | **bool**\& | مرجع به متغیری که در صورت تمام شدن بافر ورودی به true تنظیم می‌شود و در غیر اینصورت به false. |

## ICUEncoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) متد

کاراکترها را به بایت‌ها تبدیل می‌کند.

```cpp
virtual void System::Text::ICUEncoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | const char_t * | کاراکترها برای رمزگذاری. |
| charCount | int | اندازه بافر ورودی. |
| bytes | **uint8_t** * | بافر بایتی مقصد. |
| byteCount | int | اندازه آرایه مقصد. |
| flush | **bool** | اگر درست باشد، پس از محاسبه وضعیت داخلی انکودر را پاک می‌کند. |
| charsUsed | int\& | مرجع به متغیری برای ذخیره تعداد کاراکترهای خوانده شده. |
| bytesUsed | int\& | مرجع به متغیری برای ذخیره تعداد بایت‌های نوشته شده. |
| completed | **bool**\& | مرجع به متغیری که در صورت تمام شدن بافر ورودی به true تنظیم می‌شود و در غیر اینصورت به false. |

## همچنین ببینید

* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [ICUEncoder](../)
* فضای نام [System::Text](../../)
* کتابخانه [Aspose.Slides](../../../)