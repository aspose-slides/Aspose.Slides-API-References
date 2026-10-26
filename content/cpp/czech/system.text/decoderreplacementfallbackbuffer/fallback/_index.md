---
title: Fallback()
second_title: Aspose.Slides pro C++ API Reference
description: Zpracovává selhání dekódování.
type: docs
weight: 27
url: /cs/system.text/decoderreplacementfallbackbuffer/fallback/
---
## DecoderReplacementFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) metoda


Zpracovává selhání dekódování.

```cpp
virtual bool System::Text::DecoderReplacementFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) neznámých bajtů; ignorováno. |
| index | int | Posun neznámých bajtů; ignorováno. |

### Vrácená hodnota

True pokud je náhradní řetězec poskytnut a není prázdný, false jinak.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [DecoderReplacementFallbackBuffer](../)
* Jmenný prostor [System::Text](../../)
* Library [Aspose.Slides](../../../)