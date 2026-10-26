---
title: GetByteCount()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce il numero di byte necessari per codificare un buffer.
type: docs
weight: 40
url: /it/system.text/icuencoder/getbytecount/
---
## ICUEncoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) metodo

Restituisce il numero di byte necessari per codificare un buffer.

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Caratteri da codificare. |
| index | int | [Buffer](../../../system/buffer/) scostamento. |
| count | int | Numero di caratteri da codificare. |
| flush | **bool** | Se true, pulisce lo stato interno dell'encoder dopo il calcolo. |

### Valore restituito

Numero di byte richiesti per codificare il buffer.

## ICUEncoder::GetByteCount(const char_t *, int, bool) metodo

Restituisce il numero di byte necessari per codificare un buffer.

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(const char_t *chars, int count, bool flush)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chars | const char_t * | Caratteri da codificare. |
| count | int | Numero di caratteri da codificare. |
| flush | **bool** | Se true, pulisce lo stato interno dell'encoder dopo il calcolo. |

### Valore restituito

Numero di byte richiesti per codificare il buffer.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)