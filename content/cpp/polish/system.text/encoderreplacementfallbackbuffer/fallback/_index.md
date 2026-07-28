---
title: Fallback()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Obsługuje błąd kodowania.
type: docs
weight: 27
url: /pl/system.text/encoderreplacementfallbackbuffer/fallback/
---
## EncoderReplacementFallbackBuffer::Fallback(char_t, int) metoda


Obsługuje błąd kodowania.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknown, int index) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| charUnknown | char_t | Nieznany znak; ignorowany. |
| index | int | Pozycja nieznanego znaku; ignorowana. |

### Wartość zwracana

prawda, jeśli podano ciąg zastępczy i nie jest pusty, w przeciwnym razie fałsz.

## EncoderReplacementFallbackBuffer::Fallback(char_t, char_t, int) metoda


Obsługuje błąd kodowania.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| charUnknownHigh | char_t | Wysoka część pary zastępczej, która spowodowała błąd. |
| charUnknownLow | char_t | Niska część pary zastępczej, która spowodowała błąd. |
| index | int | Pozycja nieznanego znaku; ignorowana. |

### Wartość zwracana

prawda, jeśli podano ciąg zastępczy i nie jest pusty, w przeciwnym razie fałsz.

## Zobacz także

* Klasa [EncoderReplacementFallbackBuffer](../)
* Przestrzeń nazw [System::Text](../../)
* Biblioteka [Aspose.Slides](../../../)