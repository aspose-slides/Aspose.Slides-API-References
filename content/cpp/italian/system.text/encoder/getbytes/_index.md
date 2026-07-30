---
title: GetBytes()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottieni i byte risultanti dalla codifica di un buffer.
type: docs
weight: 53
url: /it/system.text/encoder/getbytes/
---
## Encoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) metodo

Ottieni i byte risultanti dalla codifica di un buffer.

```cpp
virtual int System::Text::Encoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Caratteri da codificare. |
| charIndex | int | Offset dell'array di origine. |
| charCount | int | Lunghezza del sottoarray di origine. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer di byte di destinazione. |
| byteIndex | int | Offset del buffer di destinazione. |
| flush | **bool** | Se true, pulisce lo stato interno del codificatore dopo il calcolo. |

### Valore restituito

Number of bytes written.

## Encoder::GetBytes(const char_t *, int, uint8_t *, int, bool) metodo

Ottieni i byte risultanti dalla codifica di un buffer.

```cpp
virtual int System::Text::Encoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Caratteri da codificare. |
| charCount | int | Lunghezza dell'array di origine. |
| bytes | **uint8_t** * | Buffer di byte di destinazione. |
| byteCount | int | Dimensione del buffer di destinazione. |
| flush | **bool** | Se true, pulisce lo stato interno del codificatore dopo il calcolo. |

### Valore restituito

Number of bytes written.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)