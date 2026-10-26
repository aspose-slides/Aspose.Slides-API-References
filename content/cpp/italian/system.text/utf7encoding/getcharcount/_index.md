---
title: GetCharCount()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce il numero di caratteri necessari per decodificare un buffer di byte.
type: docs
weight: 79
url: /it/system.text/utf7encoding/getcharcount/
---
## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) metodo

Restituisce il numero di caratteri necessari per decodificare un buffer di byte.

```cpp
int System::Text::UTF7Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes to decode. |
| index | int | Slice beginning. |
| count | int | Slice size. |

### Valore restituito

Numero di caratteri.

## UTF7Encoding::GetCharCount(const uint8_t *, int) metodo

Restituisce il numero di caratteri necessari per decodificare un buffer di byte.

```cpp
int System::Text::UTF7Encoding::GetCharCount(const uint8_t *bytes, int count) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes to decode. |
| count | int | Bytes count. |

### Valore restituito

Numero di caratteri.

## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) metodo

Restituisce il numero di caratteri necessari per decodificare un buffer di byte.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes to decode. |
| index | int | Slice beginning. |
| count | int | Slice size. |

### Valore restituito

Numero di caratteri.

## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>) metodo

Restituisce il numero di caratteri necessari per decodificare un buffer di byte.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes to decode. |

### Valore restituito

Numero di caratteri.

## UTF7Encoding::GetCharCount(const uint8_t *, int) metodo

Restituisce il numero di caratteri necessari per decodificare un buffer di byte.

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes to decode. |
| count | int | Bytes count. |

### Valore restituito

Numero di caratteri.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [UTF7Encoding](../)
* Spazio dei nomi [System::Text](../../)
* Libreria [Aspose.Slides](../../../)