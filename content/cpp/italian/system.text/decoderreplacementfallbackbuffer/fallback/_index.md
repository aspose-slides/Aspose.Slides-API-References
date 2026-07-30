---
title: Fallback()
second_title: Riferimento API di Aspose.Slides per C++
description: Gestisce il fallimento della decodifica.
type: docs
weight: 27
url: /it/system.text/decoderreplacementfallbackbuffer/fallback/
---
## DecoderReplacementFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) method

Gestisce il fallimento della decodifica.

```cpp
virtual bool System::Text::DecoderReplacementFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) di byte sconosciuti; ignorato. |
| index | int | Offset dei byte sconosciuti; ignorato. |

### Valore di ritorno

True se la stringa di sostituzione è fornita e non è vuota, false altrimenti.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [DecoderReplacementFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)