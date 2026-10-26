---
title: Convert()
second_title: مرجع API Aspose.Slides برای C++
description: بایت‌ها را به کاراکترها تبدیل می‌کند.
type: docs
weight: 66
url: /fa/system.text/icudecoder/convert/
---
## ICUDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) method


بایت‌ها را به کاراکترها تبدیل می‌کند.

```cpp
virtual void System::Text::ICUDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```


### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | بایت‌های برای رمزگشایی. |
| byteIndex | int | آفست بافر ورودی. |
| byteCount | int | اندازهٔ بافر ورودی. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | بافر کاراکتر مقصد. |
| charIndex | int | آفست آرایهٔ مقصد. |
| charCount | int | اندازهٔ آرایهٔ مقصد. |
| flush | **bool** | اگر true باشد، وضعیت داخلی رمزگشای را پس از محاسبه پاک می‌کند. |
| bytesUsed | int\& | مرجع به متغیری برای ذخیرهٔ تعداد بایت‌های خوانده‌شده. |
| charsUsed | int\& | مرجع به متغیری برای ذخیرهٔ تعداد کاراکترهای نوشته‌شده. |
| completed | **bool**\& | مرجع به متغیری که اگر بافر ورودی تمام شده باشد به true تنظیم می‌شود و در غیر این صورت به false. |

## ICUDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) method


بایت‌ها را به کاراکترها تبدیل می‌کند.

```cpp
virtual void System::Text::ICUDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```


### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | بایت‌های برای رمزگشایی. |
| byteCount | int | اندازهٔ بافر ورودی. |
| chars | char_t * | بافر کاراکتر مقصد. |
| charCount | int | اندازهٔ آرایهٔ مقصد. |
| flush | **bool** | اگر true باشد، وضعیت داخلی رمزگشای را پس از محاسبه پاک می‌کند. |
| bytesUsed | int\& | مرجع به متغیری برای ذخیرهٔ تعداد بایت‌های خوانده‌شده. |
| charsUsed | int\& | مرجع به متغیری برای ذخیرهٔ تعداد کاراکترهای نوشته‌شده. |
| completed | **bool**\& | مرجع به متغیری که اگر بافر ورودی تمام شده باشد به true تنظیم می‌شود و در غیر این صورت به false. |

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)