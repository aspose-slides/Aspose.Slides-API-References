---
title: GetBytes()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottieni i byte risultanti dalla codifica di un buffer.
type: docs
weight: 53
url: /it/system.text/icuencoder/getbytes/
---
## ICUEncoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) metodo

Ottieni i byte che risultano dalla codifica di un buffer.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Caratteri da codificare. |
| charIndex | int | Offset dell'array di origine. |
| charCount | int | Lunghezza della sottoarray di origine. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer di byte di destinazione. |
| byteIndex | int | Offset del buffer di destinazione. |
| flush | **bool** | Se true, pulisce lo stato interno del codificatore dopo il calcolo. |

### Valore di ritorno

Numero di byte scritti.

## ICUEncoder::GetBytes(const char_t *, int, uint8_t *, int, bool) metodo

Ottieni i byte che risultano dalla codifica di un buffer.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chars | const char_t * | Caratteri da codificare. |
| charCount | int | Lunghezza dell'array di origine. |
| bytes | **uint8_t** * | Buffer di byte di destinazione. |
| byteCount | int | Dimensione del buffer di destinazione. |
| flush | **bool** | Se true, pulisce lo stato interno del codificatore dopo il calcolo. |

### Valore di ritorno

Numero di byte scritti.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ICUEncoder](../)
* Spazio dei nomi [System::Text](../../)
* Libreria [Aspose.Slides](../../../)