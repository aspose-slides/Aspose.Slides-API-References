---
title: Convert()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte i caratteri in byte.
type: docs
weight: 1
url: /it/system.text/encodingencoder/convert/
---
## EncodingEncoder::Convert(const char_t *, int, uint8_t *, int, bool, int&, int&, bool&) metodo

Converte i caratteri in byte.

```cpp
virtual void System::Text::EncodingEncoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chars | const char_t * | Caratteri da codificare. |
| charCount | int | Dimensione del buffer di input. |
| bytes | **uint8_t** * | Buffer di byte di destinazione. |
| byteCount | int | Dimensione dell'array di destinazione. |
| flush | **bool** | Se true, pulisce lo stato interno dell'encoder dopo il calcolo. |
| charsUsed | int& | Riferimento a una variabile per memorizzare il conteggio dei caratteri letti. |
| bytesUsed | int& | Riferimento a una variabile per memorizzare il conteggio dei byte scritti. |
| completed | **bool**& | Riferimento a una variabile da impostare a true se il buffer di input è stato esaurito e a false altrimenti. |

## EncodingEncoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int&, int&, bool&) metodo

Converte i caratteri in byte.

```cpp
virtual void System::Text::EncodingEncoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Caratteri da codificare. |
| charIndex | int | Offset del buffer di input. |
| charCount | int | Dimensione del buffer di input. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer di byte di destinazione. |
| byteIndex | int | Offset dell'array di destinazione. |
| byteCount | int | Dimensione dell'array di destinazione. |
| flush | **bool** | Se true, pulisce lo stato interno dell'encoder dopo il calcolo. |
| charsUsed | int& | Riferimento a una variabile per memorizzare il conteggio dei caratteri letti. |
| bytesUsed | int& | Riferimento a una variabile per memorizzare il conteggio dei byte scritti. |
| completed | **bool**& | Riferimento a una variabile da impostare a true se il buffer di input è stato esaurito e a false altrimenti. |

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [EncodingEncoder](../)
* Spazio dei nomi [System::Text](../../)
* Libreria [Aspose.Slides](../../../)