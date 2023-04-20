---
title: Convert()
second_title: Aspose.Slides for C++ API Reference
description: Converts characters to bytes.
type: docs
weight: 1
url: /cpp/system.text/encodingencoder/convert/
---
## EncodingEncoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) method


Converts characters to bytes.

```cpp
virtual void System::Text::EncodingEncoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Characters to encode. |
| charCount | int | Input buffer size. |
| bytes | **uint8_t** * | Destination byte buffer. |
| byteCount | int | Destination array size. |
| flush | **bool** | If true, cleans internal encoder state after calculation. |
| charsUsed | int\& | Reference to variable to store count of characters read. |
| bytesUsed | int\& | Reference to variable to store count of bytes written. |
| completed | **bool**\& | Reference to variable to be set to true if input buffer was exhausted and to false otherwise. |

## EncodingEncoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) method


Converts characters to bytes.

```cpp
virtual void System::Text::EncodingEncoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Characters to encode. |
| charIndex | int | Input buffer offset. |
| charCount | int | Input buffer size. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Destination byte buffer. |
| byteIndex | int | Destination array offset. |
| byteCount | int | Destination array size. |
| flush | **bool** | If true, cleans internal encoder state after calculation. |
| charsUsed | int\& | Reference to variable to store count of characters read. |
| bytesUsed | int\& | Reference to variable to store count of bytes written. |
| completed | **bool**\& | Reference to variable to be set to true if input buffer was exhausted and to false otherwise. |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [EncodingEncoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)