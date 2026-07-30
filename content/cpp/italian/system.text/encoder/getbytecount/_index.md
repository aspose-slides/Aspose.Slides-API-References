---
title: GetByteCount()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce il numero di byte necessari per codificare un buffer.
type: docs
weight: 40
url: /it/system.text/encoder/getbytecount/
---
## Encoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) metodo


Restituisce il numero di byte necessari per codificare un buffer.

```cpp
virtual int System::Text::Encoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Caratteri da codificare. |
| index | int | [Buffer](../../../system/buffer/) offset. |
| count | int | Numero di caratteri da codificare. |
| flush | **bool** | Se true, pulisce lo stato interno del codificatore dopo il calcolo. |

### Valore di ritorno

Numero di byte richiesti per codificare il buffer.

## Encoder::GetByteCount(const char_t *, int, bool) metodo


Restituisce il numero di byte necessari per codificare un buffer.

```cpp
virtual int System::Text::Encoder::GetByteCount(const char_t *chars, int count, bool flush)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chars | const char_t * | Caratteri da codificare. |
| count | int | Numero di caratteri da codificare. |
| flush | **bool** | Se true, pulisce lo stato interno del codificatore dopo il calcolo. |

### Valore di ritorno

Numero di byte richiesti per codificare il buffer.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Encoder](../)
* Spazio dei nomi [System::Text](../../)
* Libreria [Aspose.Slides](../../../)