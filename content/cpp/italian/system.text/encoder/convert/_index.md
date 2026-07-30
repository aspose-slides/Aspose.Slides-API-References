---
title: Convert()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte i caratteri in byte.
type: docs
weight: 79
url: /it/system.text/encoder/convert/
---
## Encoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) method

Converte i caratteri in byte.

```cpp
virtual void System::Text::Encoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Caratteri da codificare. |
| charIndex | int | Offset del buffer di input. |
| charCount | int | Dimensione del buffer di input. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer di byte di destinazione. |
| byteIndex | int | Offset dell'array di destinazione. |
| byteCount | int | Dimensione dell'array di destinazione. |
| flush | **bool** | Se true, pulisce lo stato interno del codificatore dopo il calcolo. |
| charsUsed | int\& | Riferimento a una variabile per memorizzare il numero di caratteri letti. |
| bytesUsed | int\& | Riferimento a una variabile per memorizzare il numero di byte scritti. |
| completed | **bool**\& | Riferimento a una variabile da impostare a true se il buffer di input è stato esaurito e a false altrimenti. |

## Encoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) method

Converte i caratteri in byte.

```cpp
virtual void System::Text::Encoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Caratteri da codificare. |
| charCount | int | Dimensione del buffer di input. |
| bytes | **uint8_t** * | Buffer di byte di destinazione. |
| byteCount | int | Dimensione dell'array di destinazione. |
| flush | **bool** | Se true, pulisce lo stato interno del codificatore dopo il calcolo. |
| charsUsed | int\& | Riferimento a una variabile per memorizzare il numero di caratteri letti. |
| bytesUsed | int\& | Riferimento a una variabile per memorizzare il numero di byte scritti. |
| completed | **bool**\& | Riferimento a una variabile da impostare a true se il buffer di input è stato esaurito e a false altrimenti. |

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)