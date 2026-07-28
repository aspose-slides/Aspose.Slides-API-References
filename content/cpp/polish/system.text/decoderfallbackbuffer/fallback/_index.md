---
title: Fallback()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Implementuje rzeczywistą procedurę awaryjną.
type: docs
weight: 14
url: /pl/system.text/decoderfallbackbuffer/fallback/
---
## DecoderFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) metoda

Implementuje rzeczywistą procedurę awaryjną.

```cpp
virtual bool System::Text::DecoderFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) bajtów, w tym tego, którego dekoder nie potrafi zdekodować. |
| index | int | [Index](../../../system/index/) indeks bajtu, który spowodował błąd. |

### Wartość zwracana

True jeśli bufor przetwarza nieznane bajty, false jeśli je ignoruje.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [DecoderFallbackBuffer](../)
* Przestrzeń nazw [System::Text](../../)
* Biblioteka [Aspose.Slides](../../../)