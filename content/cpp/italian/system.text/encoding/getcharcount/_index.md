---
title: GetCharCount()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce il numero di caratteri necessari per decodificare un buffer di byte.
type: docs
weight: 261
url: /it/system.text/encoding/getcharcount/
---
## Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) metodo

Restituisce il numero di caratteri necessari per decodificare un buffer di byte.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte da decodificare. |
| index | int | Inizio della sezione. |
| count | int | Dimensione della sezione. |

### Valore restituito

Numero di caratteri.

## Encoding::GetCharCount(ArrayPtr\<uint8_t\>) metodo

Restituisce il numero di caratteri necessari per decodificare un buffer di byte.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte da decodificare. |

### Valore restituito

Numero di caratteri.

## Encoding::GetCharCount(const uint8_t *, int) metodo

Restituisce il numero di caratteri necessari per decodificare un buffer di byte.

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | Byte da decodificare. |
| count | int | Numero di byte. |

### Valore restituito

Numero di caratteri.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Encoding](../)
* Spazio dei nomi [System::Text](../../)
* Libreria [Aspose.Slides](../../../)