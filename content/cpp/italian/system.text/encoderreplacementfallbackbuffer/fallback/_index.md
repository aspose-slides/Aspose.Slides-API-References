---
title: Fallback()
second_title: Aspose.Slides per C++ Riferimento API
description: Gestisce il fallimento della codifica.
type: docs
weight: 27
url: /it/system.text/encoderreplacementfallbackbuffer/fallback/
---
## EncoderReplacementFallbackBuffer::Fallback(char_t, int) metodo


Gestisce il fallimento della codifica.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknown, int index) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| charUnknown | char_t | Carattere sconosciuto; ignorato. |
| index | int | Posizione del carattere sconosciuto; ignorata. |

### Valore restituito

True se la stringa di sostituzione è fornita e non è vuota, false altrimenti.

## EncoderReplacementFallbackBuffer::Fallback(char_t, char_t, int) metodo


Gestisce il fallimento della codifica.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| charUnknownHigh | char_t | Parte alta della coppia surrogata che ha generato l'errore. |
| charUnknownLow | char_t | Parte bassa della coppia surrogata che ha generato l'errore. |
| index | int | Posizione del carattere sconosciuto; ignorata. |

### Valore restituito

True se la stringa di sostituzione è fornita e non è vuota, false altrimenti.

## Vedi anche

* Classe [EncoderReplacementFallbackBuffer](../)
* Spazio dei nomi [System::Text](../../)
* Libreria [Aspose.Slides](../../../)