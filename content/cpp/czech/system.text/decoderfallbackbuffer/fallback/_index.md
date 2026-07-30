---
title: Fallback()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Implementuje skutečný postup záložního řešení.
type: docs
weight: 14
url: /cs/system.text/decoderfallbackbuffer/fallback/
---
## DecoderFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) metoda

Implementuje skutečný postup záložního řešení.

```cpp
virtual bool System::Text::DecoderFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) bajtů včetně toho, který dekodér nedokáže dekódovat. |
| index | int | [Index](../../../system/index/) bajtu, který způsobil chybu. |

### Návratová hodnota

True, pokud buffer zpracovává neznámé bajty, false, pokud je ignoruje.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [DecoderFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)