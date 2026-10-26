---
title: Fallback()
second_title: Aspose.Slides für C++ API-Referenz
description: Implementiert das tatsächliche Rückfallverfahren.
type: docs
weight: 14
url: /de/system.text/decoderfallbackbuffer/fallback/
---
## DecoderFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) Methode

Implementiert das tatsächliche Rückfallverfahren.

```cpp
virtual bool System::Text::DecoderFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) von Bytes einschließlich des Bytes, das der Decoder nicht dekodieren kann. |
| index | int | [Index](../../../system/index/) des Bytes, das den Fehler ausgelöst hat. |

### Rückgabewert

True, wenn der Puffer unbekannte Bytes verarbeitet, false, wenn er sie ignoriert.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [DecoderFallbackBuffer](../)
* Namensraum [System::Text](../../)
* Bibliothek [Aspose.Slides](../../../)