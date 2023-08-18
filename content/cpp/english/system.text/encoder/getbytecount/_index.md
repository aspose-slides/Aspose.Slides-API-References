---
title: GetByteCount()
second_title: Aspose.Slides for C++ API Reference
description: Gets the number of bytes needed to encode a buffer.
type: docs
weight: 40
url: /system.text/encoder/getbytecount/
---
## Encoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) method


Gets the number of bytes needed to encode a buffer.

```cpp
virtual int System::Text::Encoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Characters to encode. |
| index | int | [Buffer](../../../system/buffer/) offset. |
| count | int | Number of characters to encode. |
| flush | **bool** | If true, cleans internal encoder state after calculation. |

### Return Value

Number of bytes required to encode the buffer.

## Encoder::GetByteCount(const char_t *, int, bool) method


Gets the number of bytes needed to encode a buffer.

```cpp
virtual int System::Text::Encoder::GetByteCount(const char_t *chars, int count, bool flush)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Characters to encode. |
| count | int | Number of characters to encode. |
| flush | **bool** | If true, cleans internal encoder state after calculation. |

### Return Value

Number of bytes required to encode the buffer.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)