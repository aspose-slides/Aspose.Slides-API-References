---
title: GetBytes()
second_title: مستندات API Aspose.Slides برای C++
description: بایت‌هایی که نتیجهٔ رمزگذاری یک بافر هستند را دریافت می‌کند.
type: docs
weight: 53
url: /fa/system.text/encoder/getbytes/
---
## Encoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) متد


بایت‌هایی که نتیجهٔ رمزگذاری یک بافر هستند را دریافت می‌کند.

```cpp
virtual int System::Text::Encoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | کاراکترهای قابل رمزگذاری. |
| charIndex | int | افست آرایه منبع. |
| charCount | int | طول زیرآرایه منبع. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | بافر بایت مقصد. |
| byteIndex | int | افست بافر مقصد. |
| flush | **bool** | اگر true باشد، پس از محاسبه وضعیت داخلی رمزگذار را پاک می‌کند. |

### مقدار بازگشت

تعداد بایت‌های نوشته‌شده.

## Encoder::GetBytes(const char_t *, int, uint8_t *, int, bool) متد


بایت‌هایی که نتیجهٔ رمزگذاری یک بافر هستند را دریافت می‌کند.

```cpp
virtual int System::Text::Encoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | const char_t * | کاراکترهای قابل رمزگذاری. |
| charCount | int | طول آرایه منبع. |
| bytes | **uint8_t** * | بافر بایت مقصد. |
| byteCount | int | اندازهٔ بافر مقصد. |
| flush | **bool** | اگر true باشد، پس از محاسبه وضعیت داخلی رمزگذار را پاک می‌کند. |

### مقدار بازگشت

تعداد بایت‌های نوشته‌شده.

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [Encoder](../)
* فضای نام [System::Text](../../)
* کتابخانه [Aspose.Slides](../../../)