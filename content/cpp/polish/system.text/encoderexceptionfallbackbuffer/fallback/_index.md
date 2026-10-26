---
title: Fallback()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Obsługuje błąd kodowania.
type: docs
weight: 27
url: /pl/system.text/encoderexceptionfallbackbuffer/fallback/
---
## EncoderExceptionFallbackBuffer::Fallback(char_t, int) metoda

Obsługuje błąd kodowania.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknown, int index) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| charUnknown | char_t | Nieznane znaki; ignorowane. |
| index | int | Offset nieznanych znaków; ignorowany. |

### Wartość zwracana

W rzeczywistości nigdy nie zwraca, zamiast tego zgłasza wyjątek.

## EncoderExceptionFallbackBuffer::Fallback(char_t, char_t, int) metoda

Obsługuje błąd kodowania.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| charUnknownHigh | char_t | Wysoka część pary zastępczej, która spowodowała błąd. |
| charUnknownLow | char_t | Niska część pary zastępczej, która spowodowała błąd. |
| index | int | Offset nieznanego znaku; ignorowany. |

### Wartość zwracana

W rzeczywistości nigdy nie zwraca, zamiast tego zgłasza wyjątek.

## Zobacz także

* Klasa [EncoderExceptionFallbackBuffer](../)
* Przestrzeń nazw [System::Text](../../)
* Biblioteka [Aspose.Slides](../../../)