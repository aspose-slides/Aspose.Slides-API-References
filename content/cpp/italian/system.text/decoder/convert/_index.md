---
title: Convert()
second_title: Riferimento API Aspose.Slides per C++
description: Converte byte in caratteri.
type: docs
weight: 79
url: /it/system.text/decoder/convert/
---
## Decoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) metodo


Converte byte in caratteri.

```cpp
virtual void System::Text::Decoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
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
| flush | **bool** | Se true, pulisce lo stato interno del decoder dopo il calcolo. |
| bytesUsed | int\& | Riferimento a una variabile per memorizzare il conteggio dei byte letti. |
| charsUsed | int\& | Riferimento a una variabile per memorizzare il conteggio dei caratteri scritti. |
| completed | **bool**\& | Riferimento a una variabile da impostare a true se il buffer di input è stato esaurito e a false altrimenti. |

## Decoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) metodo


Converte byte in caratteri.

```cpp
virtual void System::Text::Decoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | const **uint8_t** * | Byte da decodificare. |
| byteCount | int | Dimensione del buffer di input. |
| chars | char_t * | Buffer di caratteri di destinazione. |
| charCount | int | Dimensione dell'array di destinazione. |
| flush | **bool** | Se true, pulisce lo stato interno del decoder dopo il calcolo. |
| bytesUsed | int\& | Riferimento a una variabile per memorizzare il conteggio dei byte letti. |
| charsUsed | int\& | Riferimento a una variabile per memorizzare il conteggio dei caratteri scritti. |
| completed | **bool**\& | Riferimento a una variabile da impostare a true se il buffer di input è stato esaurito e a false altrimenti. |

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Decoder](../)
* Spazio dei nomi [System::Text](../../)
* Libreria [Aspose.Slides](../../../)