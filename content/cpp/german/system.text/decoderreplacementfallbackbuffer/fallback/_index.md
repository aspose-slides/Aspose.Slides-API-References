---
title: Fallback()
second_title: Aspose.Slides für C++ API Referenz
description: Behandelt Dekodierungsfehler.
type: docs
weight: 27
url: /de/system.text/decoderreplacementfallbackbuffer/fallback/
---
## DecoderReplacementFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) Methode

Behandelt Dekodierungsfehler.

```cpp
virtual bool System::Text::DecoderReplacementFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) von unbekannten Bytes; ignoriert. |
| index | int | Offset unbekannter Bytes; ignoriert. |

### Rückgabewert

True, wenn ein Ersatzstring bereitgestellt wird und nicht leer ist, sonst false.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [DecoderReplacementFallbackBuffer](../)
* Namensraum [System::Text](../../)
* Bibliothek [Aspose.Slides](../../../)