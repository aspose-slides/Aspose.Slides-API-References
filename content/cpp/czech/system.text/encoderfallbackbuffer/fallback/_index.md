---
title: Fallback()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Implementuje skutečnou proceduru náhrady.
type: docs
weight: 14
url: /cs/system.text/encoderfallbackbuffer/fallback/
---
## EncoderFallbackBuffer::Fallback(char_t, int) metoda


Implementuje skutečnou proceduru náhrady.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknown, int index)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| charUnknown | char_t | Enkóder znaků selže při kódování. |
| index | int | [Index](../../../system/index/) znaku, který vyvolal chybu. |

### Návratová hodnota

True pokud buffer zpracovává neznámé znaky, false pokud je ignoruje.

## EncoderFallbackBuffer::Fallback(char_t, char_t, int) metoda


Implementuje skutečnou proceduru náhrady.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| charUnknownHigh | char_t | Vysoká část páru náhradních znaků, která vyvolala chybu. |
| charUnknownLow | char_t | Nízká část páru náhradních znaků, která vyvolala chybu. |
| index | int | [Index](../../../system/index/) znaku, který vyvolal chybu. |

### Návratová hodnota

True pokud buffer zpracovává neznámé znaky, false pokud je ignoruje.

## Viz také

* Třída [EncoderFallbackBuffer](../)
* Jmenný prostor [System::Text](../../)
* Knihovna [Aspose.Slides](../../../)