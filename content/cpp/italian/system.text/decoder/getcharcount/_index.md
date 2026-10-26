---
title: GetCharCount()
second_title: Aspose.Slides per C++ Riferimento API
description: Restituisce il numero di caratteri necessari per decodificare un buffer.
type: docs
weight: 40
url: /it/system.text/decoder/getcharcount/
---
## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) method


Restituisce il numero di caratteri necessari per decodificare un buffer.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte da decodificare. |
| index | int | [Buffer](../../../system/buffer/) offset. |
| count | int | Numero di byte da decodificare. |

### Valore di ritorno

Numero di caratteri richiesti per decodificare il buffer.

## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) method


Restituisce il numero di caratteri necessari per decodificare un buffer.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte da decodificare. |
| index | int | [Buffer](../../../system/buffer/) offset. |
| count | int | Numero di byte da decodificare. |
| flush | **bool** | Se true, pulisce lo stato interno del decodificatore dopo il calcolo. |

### Valore di ritorno

Numero di caratteri richiesti per decodificare il buffer.

## Decoder::GetCharCount(const uint8_t *, int, bool) method


Restituisce il numero di caratteri necessari per decodificare un buffer.

```cpp
virtual int System::Text::Decoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | const **uint8_t** * | Byte da decodificare. |
| count | int | Numero di byte da decodificare. |
| flush | **bool** | Se true, pulisce lo stato interno del decodificatore dopo il calcolo. |

### Valore di ritorno

Numero di caratteri richiesti per decodificare il buffer.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Decoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)