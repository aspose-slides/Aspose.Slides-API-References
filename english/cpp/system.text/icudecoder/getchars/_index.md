---
title: GetChars()
second_title: Aspose.Slides for C++ API Reference
description: Get the characters that result from decoding a buffer.
type: docs
weight: 53
url: /cpp/system.text/icudecoder/getchars/
---
## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) method


Get the characters that result from decoding a buffer.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes to decode. |
| byteIndex | int | Input buffer offset. |
| byteCount | int | Input buffer size. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Destination character buffer. |
| charIndex | int | Destination array offset. |

### Return Value

Number of characters written.

## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) method


Get the characters that result from decoding a buffer.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes to decode. |
| byteIndex | int | Input buffer offset. |
| byteCount | int | Input buffer size. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Destination character buffer. |
| charIndex | int | Destination array offset. |
| flush | **bool** | If true, cleans internal decoder state after calculation. |

### Return Value

Number of characters written.

## ICUDecoder::GetChars(const uint8_t *, int, char_t *, int, bool) method


Get the characters that result from decoding a buffer.

```cpp
virtual int System::Text::ICUDecoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes to decode. |
| byteCount | int | Input buffer size. |
| chars | char_t * | Destination character buffer. |
| charCount | int | Destination array size. |
| flush | **bool** | If true, cleans internal decoder state after calculation. |

### Return Value

Number of characters written.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)