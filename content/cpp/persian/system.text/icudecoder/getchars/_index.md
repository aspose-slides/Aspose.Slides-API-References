---
title: GetChars()
second_title: Aspose.Slides برای مرجع API C++
description: کاراکترهایی که از رمزگشایی یک بافر به دست می‌آیند، دریافت کنید.
type: docs
weight: 53
url: /fa/system.text/icudecoder/getchars/
---
## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) متد

کاراکترهایی را که از رمزگشایی یک بافر به دست می‌آیند، دریافت کنید.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes to decode. |
| byteIndex | int | Input buffer offset. |
| byteCount | int | Input buffer size. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Destination character buffer. |
| charIndex | int | Destination array offset. |

### مقدار بازگشت

Number of characters written.

## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) متد

کاراکترهایی را که از رمزگشایی یک بافر به دست می‌آیند، دریافت کنید.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes to decode. |
| byteIndex | int | Input buffer offset. |
| byteCount | int | Input buffer size. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Destination character buffer. |
| charIndex | int | Destination array offset. |
| flush | **bool** | If true, cleans internal decoder state after calculation. |

### مقدار بازگشت

Number of characters written.

## ICUDecoder::GetChars(const uint8_t *, int, char_t *, int, bool) متد

کاراکترهایی را که از رمزگشایی یک بافر به دست می‌آیند، دریافت کنید.

```cpp
virtual int System::Text::ICUDecoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes to decode. |
| byteCount | int | Input buffer size. |
| chars | char_t * | Destination character buffer. |
| charCount | int | Destination array size. |
| flush | **bool** | If true, cleans internal decoder state after calculation. |

### مقدار بازگشت

Number of characters written.

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)