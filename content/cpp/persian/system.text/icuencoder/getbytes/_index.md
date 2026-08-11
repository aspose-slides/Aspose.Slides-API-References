---
title: GetBytes()
second_title: مرجع API Aspose.Slides برای C++
description: بایت‌هایی را که در نتیجهٔ رمزگذاری یک بافر به دست می‌آیند دریافت می‌کند.
type: docs
weight: 53
url: /fa/system.text/icuencoder/getbytes/
---
## ICUEncoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) متد


بایت‌هایی را که در نتیجهٔ رمزگذاری یک بافر به دست می‌آیند، دریافت می‌کند.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | کاراکترهای قابل رمزگذاری. |
| charIndex | int | آفست آرایه منبع. |
| charCount | int | طول زیرآرایه منبع. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | بافر بایت مقصد. |
| byteIndex | int | آفست بافر مقصد. |
| flush | **bool** | اگر مقدار true باشد، پس از محاسبه وضعیت داخلی رمزگذار را پاک می‌کند. |

### مقدار بازگشت

تعداد بایت‌های نوشته شده.

## ICUEncoder::GetBytes(const char_t *, int, uint8_t *, int, bool) متد


بایت‌هایی را که در نتیجهٔ رمزگذاری یک بافر به دست می‌آیند، دریافت می‌کند.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | const char_t * | کاراکترهای قابل رمزگذاری. |
| charCount | int | طول آرایه منبع. |
| bytes | **uint8_t** * | بافر بایت مقصد. |
| byteCount | int | اندازه بافر مقصد. |
| flush | **bool** | اگر مقدار true باشد، پس از محاسبه وضعیت داخلی رمزگذار را پاک می‌کند. |

### مقدار بازگشت

تعداد بایت‌های نوشته شده.

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)