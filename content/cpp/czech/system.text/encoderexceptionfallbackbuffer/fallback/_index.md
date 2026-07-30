---
title: Fallback()
second_title: Aspose.Slides pro C++ API Reference
description: Zpracovává selhání kódování.
type: docs
weight: 27
url: /cs/system.text/encoderexceptionfallbackbuffer/fallback/
---
## EncoderExceptionFallbackBuffer::Fallback(char_t, int) metoda


Zpracovává selhání kódování.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknown, int index) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| charUnknown | char_t | Neznámé znaky; ignorováno. |
| index | int | Posun neznámých znaků; ignorováno. |

### Návratová hodnota

Nikdy ve skutečnosti nevrací, místo toho vyhodí výjimku.

## EncoderExceptionFallbackBuffer::Fallback(char_t, char_t, int) metoda


Zpracovává selhání kódování.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| charUnknownHigh | char_t | Vysoká část surrogátního páru, která vyvolala chybu. |
| charUnknownLow | char_t | Nízká část surrogátního páru, která vyvolala chybu. |
| index | int | Posun neznámého znaku; ignorováno. |

### Návratová hodnota

Nikdy ve skutečnosti nevrací, místo toho vyhodí výjimku.

## Viz také

* třída [EncoderExceptionFallbackBuffer](../)
* jmenný prostor [System::Text](../../)
* knihovna [Aspose.Slides](../../../)