---
title: Fallback()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Obsługuje błąd dekodowania.
type: docs
weight: 27
url: /pl/system.text/decoderexceptionfallbackbuffer/fallback/
---
## DecoderExceptionFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) method

Obsługuje błąd dekodowania.

```cpp
virtual bool System::Text::DecoderExceptionFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) nieznanych bajtów; ignorowane. |
| index | int | Przesunięcie nieznanych bajtów; ignorowane. |

### Wartość zwracana

Nigdy faktycznie nie zwraca, zamiast tego wyrzuca wyjątek.

## Zobacz także

* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Klasa [DecoderExceptionFallbackBuffer](../)
* Przestrzeń nazw [System::Text](../../)
* Biblioteka [Aspose.Slides](../../../)