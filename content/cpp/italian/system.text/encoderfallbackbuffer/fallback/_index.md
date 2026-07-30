---
title: Fallback()
second_title: Riferimento API di Aspose.Slides per C++
description: Implementa la procedura di fallback reale.
type: docs
weight: 14
url: /it/system.text/encoderfallbackbuffer/fallback/
---
## EncoderFallbackBuffer::Fallback(char_t, int) metodo

Implementa la procedura di fallback reale.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknown, int index)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| charUnknown | char_t | Il codificatore di caratteri non riesce a codificare. |
| index | int | [Index](../../../system/index/) del carattere che ha generato l'errore. |

### Valore di ritorno

True se il buffer elabora i caratteri sconosciuti, false se li ignora.

## EncoderFallbackBuffer::Fallback(char_t, char_t, int) metodo

Implementa la procedura di fallback reale.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| charUnknownHigh | char_t | Parte alta della coppia surrogata che ha generato l'errore. |
| charUnknownLow | char_t | Parte bassa della coppia surrogata che ha generato l'errore. |
| index | int | [Index](../../../system/index/) del carattere che ha generato l'errore. |

### Valore di ritorno

True se il buffer elabora i caratteri sconosciuti, false se li ignora.

## Vedi anche

* Classe [EncoderFallbackBuffer](../)
* Spazio dei nomi [System::Text](../../)
* Libreria [Aspose.Slides](../../../)