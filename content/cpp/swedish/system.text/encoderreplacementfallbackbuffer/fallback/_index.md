---
title: Fallback()
second_title: Aspose.Slides för C++ API-referens
description: Hanterar kodningsfel.
type: docs
weight: 27
url: /sv/system.text/encoderreplacementfallbackbuffer/fallback/
---
## EncoderReplacementFallbackBuffer::Fallback(char_t, int) metod


Hanterar kodningsfel.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknown, int index) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| charUnknown | char_t | Okänt tecken; ignoreras. |
| index | int | Okänd teckenposition; ignoreras. |

### Returvärde

Sant om ersättningssträngen tillhandahålls och inte är tom, falskt annars.

## EncoderReplacementFallbackBuffer::Fallback(char_t, char_t, int) metod


Hanterar kodningsfel.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| charUnknownHigh | char_t | Hög del av surrogatpar som orsakade felet. |
| charUnknownLow | char_t | Låg del av surrogatpar som orsakade felet. |
| index | int | Okänd teckenposition; ignoreras. |

### Returvärde

Sant om ersättningssträngen tillhandahålls och inte är tom, falskt annars.

## Se också

* Klass [EncoderReplacementFallbackBuffer](../)
* Namnrymd [System::Text](../../)
* Bibliotek [Aspose.Slides](../../../)