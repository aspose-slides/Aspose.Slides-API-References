---
title: Fallback()
second_title: Aspose.Slides for C++ API Reference
description: Implements actual fallback procedure.
type: docs
weight: 14
url: /cpp/system.text/decoderfallbackbuffer/fallback/
---
## DecoderFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) method


Implements actual fallback procedure.

```cpp
virtual bool System::Text::DecoderFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) of bytes including the one decoder fails to decode. |
| index | int | Index of byte that triggered error. |

### Return Value

True if buffer processes unknown bytes, false if it ignores them.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [DecoderFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)