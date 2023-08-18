---
title: Fallback()
second_title: Aspose.Slides for C++ API Reference
description: Handles decoding failure.
type: docs
weight: 27
url: /system.text/decoderreplacementfallbackbuffer/fallback/
---
## DecoderReplacementFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) method


Handles decoding failure.

```cpp
virtual bool System::Text::DecoderReplacementFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) of unknown bytes; ignored. |
| index | int | Unknown bytes offset; ignored. |

### Return Value

True if replacement string is provided and is not empty, false otherwise.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [DecoderReplacementFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)