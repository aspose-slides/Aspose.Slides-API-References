---
title: Convert()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte byte in caratteri.
type: docs
weight: 66
url: /it/system.text/icudecoder/convert/
---
## ICUDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) metodo

Converte byte in caratteri.

```cpp
virtual void System::Text::ICUDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte da decodificare. |
| byteIndex | int | Offset del buffer di input. |
| byteCount | int | Dimensione del buffer di input. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Buffer di caratteri di destinazione. |
| charIndex | int | Offset dell'array di destinazione. |
| charCount | int | Dimensione dell'array di destinazione. |
| flush | **bool** | Se true, pulisce lo stato interno del decodificatore dopo il calcolo. |
| bytesUsed | int\& | Riferimento a una variabile per memorizzare il conteggio dei byte letti. |
| charsUsed | int\& | Riferimento a una variabile per memorizzare il conteggio dei caratteri scritti. |
| completed | **bool**\& | Riferimento a una variabile da impostare a true se il buffer di input è stato esaurito e a false altrimenti. |

## ICUDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) metodo

Converte byte in caratteri.

```cpp
virtual void System::Text::ICUDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | const **uint8_t** * | Byte da decodificare. |
| byteCount | int | Dimensione del buffer di input. |
| chars | char_t * | Buffer di caratteri di destinazione. |
| charCount | int | Dimensione dell'array di destinazione. |
| flush | **bool** | Se true, pulisce lo stato interno del decodificatore dopo il calcolo. |
| bytesUsed | int\& | Riferimento a una variabile per memorizzare il conteggio dei byte letti. |
| charsUsed | int\& | Riferimento a una variabile per memorizzare il conteggio dei caratteri scritti. |
| completed | **bool**\& | Riferimento a una variabile da impostare a true se il buffer di input è stato esaurito e a false altrimenti. |

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ICUDecoder](../)
* Namespace [System::Text](../../)
* Libreria [Aspose.Slides](../../../)