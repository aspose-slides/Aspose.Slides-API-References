---
title: GetCharCount()
second_title: Aspose.Slides for C++ API Reference
description: Gets the number of characters needed to decode a buffer.
type: docs
weight: 40
url: /system.text/decoder/getcharcount/
---
## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) method


Gets the number of characters needed to decode a buffer.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes to decode. |
| index | int | [Buffer](../../../system/buffer/) offset. |
| count | int | Number of bytes to decode. |

### Return Value

Number of characters required to decode the buffer.

## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) method


Gets the number of characters needed to decode a buffer.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes to decode. |
| index | int | [Buffer](../../../system/buffer/) offset. |
| count | int | Number of bytes to decode. |
| flush | **bool** | If true, cleans internal decoder state after calculation. |

### Return Value

Number of characters required to decode the buffer.

## Decoder::GetCharCount(const uint8_t *, int, bool) method


Gets the number of characters needed to decode a buffer.

```cpp
virtual int System::Text::Decoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes to decode. |
| count | int | Number of bytes to decode. |
| flush | **bool** | If true, cleans internal decoder state after calculation. |

### Return Value

Number of characters required to decode the buffer.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Decoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)