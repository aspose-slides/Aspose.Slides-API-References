---
title: GetChars()
second_title: مرجع API Aspose.Slides برای C++
description: کاراکترهای حاصل از رمزگشایی یک بافر را بر می‌گرداند.
type: docs
weight: 53
url: /fa/system.text/decoder/getchars/
---
## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) متد

کاراکترهای حاصل از رمزگشایی یک بافر را بر می‌گرداند.

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | بایت‌های قابل رمزگشایی. |
| byteIndex | int | افست بافر ورودی. |
| byteCount | int | اندازه بافر ورودی. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | بافر کاراکتر مقصد. |
| charIndex | int | افست آرایه مقصد. |

### مقدار بازگشت

تعداد کاراکترهای نوشته شده.

## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) متد

کاراکترهای حاصل از رمزگشایی یک بافر را بر می‌گرداند.

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | بایت‌های قابل رمزگشایی. |
| byteIndex | int | افست بافر ورودی. |
| byteCount | int | اندازه بافر ورودی. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | بافر کاراکتر مقصد. |
| charIndex | int | افست آرایه مقصد. |
| flush | **bool** | اگر مقدار true باشد، پس از محاسبه وضعیت داخلی دیکودر را پاک می‌کند. |

### مقدار بازگشت

تعداد کاراکترهای نوشته شده.

## Decoder::GetChars(const uint8_t *, int, char_t *, int, bool) متد

کاراکترهای حاصل از رمزگشایی یک بافر را بر می‌گرداند.

```cpp
virtual int System::Text::Decoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | بایت‌های قابل رمزگشایی. |
| byteCount | int | اندازه بافر ورودی. |
| chars | char_t * | بافر کاراکتر مقصد. |
| charCount | int | اندازه آرایه مقصد. |
| flush | **bool** | اگر مقدار true باشد، پس از محاسبه وضعیت داخلی دیکودر را پاک می‌کند. |

### مقدار بازگشت

تعداد کاراکترهای نوشته شده.

## مراجع

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [Decoder](../)
* فضای نام [System::Text](../../)
* کتابخانه [Aspose.Slides](../../../)