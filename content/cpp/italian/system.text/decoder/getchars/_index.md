---
title: GetChars()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottiene i caratteri risultanti dalla decodifica di un buffer.
type: docs
weight: 53
url: /it/system.text/decoder/getchars/
---
## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) metodo

Ottiene i caratteri risultanti dalla decodifica di un buffer.

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte da decodificare. |
| byteIndex | int | Offset del buffer di input. |
| byteCount | int | Dimensione del buffer di input. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Buffer di caratteri di destinazione. |
| charIndex | int | Offset dell'array di destinazione. |

### Valore di ritorno

Numero di caratteri scritti.

## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) metodo

Ottiene i caratteri risultanti dalla decodifica di un buffer.

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte da decodificare. |
| byteIndex | int | Offset del buffer di input. |
| byteCount | int | Dimensione del buffer di input. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Buffer di caratteri di destinazione. |
| charIndex | int | Offset dell'array di destinazione. |
| flush | **bool** | Se vero, pulisce lo stato interno del decoder dopo il calcolo. |

### Valore di ritorno

Numero di caratteri scritti.

## Decoder::GetChars(const uint8_t *, int, char_t *, int, bool) metodo

Ottiene i caratteri risultanti dalla decodifica di un buffer.

```cpp
virtual int System::Text::Decoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | const **uint8_t** * | Byte da decodificare. |
| byteCount | int | Dimensione del buffer di input. |
| chars | char_t * | Buffer di caratteri di destinazione. |
| charCount | int | Dimensione dell'array di destinazione. |
| flush | **bool** | Se vero, pulisce lo stato interno del decoder dopo il calcolo. |

### Valore di ritorno

Numero di caratteri scritti.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Decoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)