---
title: Fallback()
second_title: Riferimento API di Aspose.Slides per C++
description: Gestisce il fallimento della codifica.
type: docs
weight: 27
url: /it/system.text/encoderexceptionfallbackbuffer/fallback/
---
## EncoderExceptionFallbackBuffer::Fallback(char_t, int) metodo

Gestisce il fallimento della codifica.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknown, int index) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| charUnknown | char_t | Caratteri sconosciuti; ignorati. |
| index | int | Offset dei caratteri sconosciuti; ignorato. |

### Valore restituito

Non restituisce mai, lancia invece un'eccezione.

## EncoderExceptionFallbackBuffer::Fallback(char_t, char_t, int) metodo

Gestisce il fallimento della codifica.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| charUnknownHigh | char_t | Parte alta della coppia surrogate che ha provocato l'errore. |
| charUnknownLow | char_t | Parte bassa della coppia surrogate che ha provocato l'errore. |
| index | int | Offset del carattere sconosciuto; ignorato. |

### Valore restituito

Non restituisce mai, lancia invece un'eccezione.

## Vedi anche

* Classe [EncoderExceptionFallbackBuffer](../)
* Spazio dei nomi [System::Text](../../)
* Libreria [Aspose.Slides](../../../)