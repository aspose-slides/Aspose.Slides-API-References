---
title: Fallback()
second_title: Aspose.Slides for C++ API Reference
description: Handles encoding failure.
type: docs
weight: 27
url: /cpp/system.text/encoderexceptionfallbackbuffer/fallback/
---
## EncoderExceptionFallbackBuffer::Fallback(char_t, int) method


Handles encoding failure.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknown, int index) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| charUnknown | char_t | Unknown characters; ignored. |
| index | int | Unknown characters offset; ignored. |

### Return Value

Never actually returns, throws instead.

## See Also

* Class [EncoderExceptionFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)
## EncoderExceptionFallbackBuffer::Fallback(char_t, char_t, int) method


Handles encoding failure.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| charUnknownHigh | char_t | High part of surrogate pair that triggered error. |
| charUnknownLow | char_t | Low part of surrogate pair that triggered error. |
| index | int | Unknown character offset; ignored. |

### Return Value

Never actually returns, throws instead.

## See Also

* Class [EncoderExceptionFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)
