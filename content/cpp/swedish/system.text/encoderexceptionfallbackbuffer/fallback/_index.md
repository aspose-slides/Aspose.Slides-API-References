---
title: Fallback()
second_title: Aspose.Slides för C++ API-referens
description: Hanterar kodningsfel.
type: docs
weight: 27
url: /sv/system.text/encoderexceptionfallbackbuffer/fallback/
---
## EncoderExceptionFallbackBuffer::Fallback(char_t, int) metod

Hanterar kodningsfel.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknown, int index) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| charUnknown | char_t | Okända tecken; ignoreras. |
| index | int | Offset för okända tecken; ignoreras. |

### Returvärde

Returnerar aldrig på riktigt, kastar i stället.

## EncoderExceptionFallbackBuffer::Fallback(char_t, char_t, int) metod

Hanterar kodningsfel.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| charUnknownHigh | char_t | Hög del av surrogate-par som orsakade felet. |
| charUnknownLow | char_t | Låg del av surrogate-par som orsakade felet. |
| index | int | Offset för okänt tecken; ignoreras. |

### Returvärde

Returnerar aldrig på riktigt, kastar i stället.

## Se även

* Klass [EncoderExceptionFallbackBuffer](../)
* Namnrymd [System::Text](../../)
* Bibliotek [Aspose.Slides](../../../)