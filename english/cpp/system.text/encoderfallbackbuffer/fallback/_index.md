---
title: Fallback()
second_title: Aspose.Slides for C++ API Reference
description: Implements actual fallback procedure.
type: docs
weight: 14
url: /cpp/system.text/encoderfallbackbuffer/fallback/
---
## EncoderFallbackBuffer::Fallback(char_t, int) method


Implements actual fallback procedure.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknown, int index)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| charUnknown | char_t | Character encoder fails to encode. |
| index | int | Index of character that triggered error. |

### Return Value

True if buffer processes unknown characters, false if it ignores them.

## See Also

* Class [EncoderFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)
## EncoderFallbackBuffer::Fallback(char_t, char_t, int) method


Implements actual fallback procedure.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| charUnknownHigh | char_t | High part of surrogate pair that triggered error. |
| charUnknownLow | char_t | Low part of surrogate pair that triggered error. |
| index | int | Index of character that triggered error. |

### Return Value

True if buffer processes unknown characters, false if it ignores them.

## See Also

* Class [EncoderFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)
