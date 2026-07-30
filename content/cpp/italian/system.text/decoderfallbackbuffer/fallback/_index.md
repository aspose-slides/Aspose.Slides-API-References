---
title: Fallback()
second_title: Riferimento API di Aspose.Slides per C++
description: Implementa la procedura di fallback reale.
type: docs
weight: 14
url: /it/system.text/decoderfallbackbuffer/fallback/
---
## DecoderFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) metodo


Implementa la procedura di fallback reale.

```cpp
virtual bool System::Text::DecoderFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) di byte inclusi quello che il decoder non riesce a decodificare. |
| index | int | [Index](../../../system/index/) del byte che ha causato l'errore. |

### Valore di ritorno

True se il buffer elabora i byte sconosciuti, false se li ignora.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [DecoderFallbackBuffer](../)
* Spazio dei nomi [System::Text](../../)
* Library [Aspose.Slides](../../../)