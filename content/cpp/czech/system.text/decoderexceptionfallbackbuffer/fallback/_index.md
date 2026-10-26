---
title: Fallback()
second_title: Aspose.Slides pro C++ API Reference
description: Zpracovává selhání dekódování.
type: docs
weight: 27
url: /cs/system.text/decoderexceptionfallbackbuffer/fallback/
---
## DecoderExceptionFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) metoda


Handles decoding failure.

```cpp
virtual bool System::Text::DecoderExceptionFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) neznámých bytů; ignorováno. |
| index | int | Posun neznámých bytů; ignorováno. |

### Návratová hodnota

Nikdy ve skutečnosti nevrací, místo toho vyvolá výjimku.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [DecoderExceptionFallbackBuffer](../)
* Obor názvů [System::Text](../../)
* Knihovna [Aspose.Slides](../../../)