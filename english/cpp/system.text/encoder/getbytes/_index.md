---
title: GetBytes()
second_title: Aspose.Slides for C++ API Reference
description: Get the bytes that result from encoding a buffer.
type: docs
weight: 53
url: /cpp/system.text/encoder/getbytes/
---
## Encoder::GetBytes([ArrayPtr](../../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>, int, **bool**) method


Get the bytes that result from encoding a buffer.

```cpp
virtual int System::Text::Encoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Characters to encode. |
| charIndex | int | Source array offset. |
| charCount | int | Source subarray length. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Destination byte buffer. |
| byteIndex | int | Destination buffer offset. |
| flush | **bool** | If true, cleans internal encoder state after calculation. |

### Return Value

Number of bytes written.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)
## Encoder::GetBytes(const char_t *, int, **uint8_t** *, int, **bool**) method


Get the bytes that result from encoding a buffer.

```cpp
virtual int System::Text::Encoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Characters to encode. |
| charCount | int | Source array length. |
| bytes | **uint8_t** * | Destination byte buffer. |
| byteCount | int | Destination buffer size. |
| flush | **bool** | If true, cleans internal encoder state after calculation. |

### Return Value

Number of bytes written.

## See Also

* Class [Encoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)
