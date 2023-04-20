---
title: GetCharCount()
second_title: Aspose.Slides for C++ API Reference
description: Get the number of characters needed to decode a byte buffer.
type: docs
weight: 261
url: /cpp/system.text/encoding/getcharcount/
---
## Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) method


Get the number of characters needed to decode a byte buffer.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes to decode. |
| index | int | Slice beginning. |
| count | int | Slice size. |

### Return Value

Number of characters.

## Encoding::GetCharCount(ArrayPtr\<uint8_t\>) method


Get the number of characters needed to decode a byte buffer.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes to decode. |

### Return Value

Number of characters.

## Encoding::GetCharCount(const uint8_t *, int) method


Get the number of characters needed to decode a byte buffer.

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes to decode. |
| count | int | Bytes count. |

### Return Value

Number of characters.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)