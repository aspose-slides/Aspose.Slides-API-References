---
title: GetChars()
second_title: Riferimento API Aspose.Slides per C++
description: Ottiene i caratteri risultanti dalla decodifica di un buffer di byte.
type: docs
weight: 92
url: /it/system.text/utf7encoding/getchars/
---
## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) metodo

Ottiene i caratteri risultanti dalla decodifica di un buffer di byte.

```cpp
int System::Text::UTF7Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) per leggere i byte da. |
| byte_index | int | Offset del buffer di input. |
| byte_count | int | Dimensione del buffer di input. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) per inserire i caratteri in. |
| char_index | int | Offset del buffer di output. |

### Valore restituito

Numero di caratteri scritti.

## UTF7Encoding::GetChars(const uint8_t *, int, char_t *, int) metodo

Ottiene i caratteri risultanti dalla decodifica di un buffer di byte.

```cpp
int System::Text::UTF7Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) per leggere i byte da. |
| byte_count | int | Dimensione del buffer di input. |
| chars | char_t * | [Buffer](../../../system/buffer/) per inserire i caratteri in. |
| char_count | int | Dimensione del buffer di output. |

### Valore restituito

Numero di caratteri scritti.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) metodo

Ottiene i caratteri risultanti dalla decodifica di un buffer di byte.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) per leggere i byte da. |
| byte_index | int | Offset del buffer di input. |
| byte_count | int | Dimensione del buffer di input. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) per inserire i caratteri in. |
| char_index | int | Offset del buffer di output. |

### Valore restituito

Numero di caratteri scritti.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int) metodo

Ottiene i caratteri risultanti dalla decodifica di un buffer di byte.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) per leggere i byte da. |
| index | int | Offset del buffer di input. |
| count | int | Dimensione del buffer di input. |

### Valore restituito

[Buffer](../../../system/buffer/) di caratteri decodificati.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>) metodo

Ottiene i caratteri risultanti dalla decodifica di un buffer di byte.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) per leggere i byte da. |

### Valore restituito

[Buffer](../../../system/buffer/) di caratteri decodificati.

## UTF7Encoding::GetChars(const uint8_t *, int, char_t *, int) metodo

Ottiene i caratteri risultanti dalla decodifica di un buffer di byte.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) per leggere i byte da. |
| byte_count | int | Dimensione del buffer di input. |
| chars | char_t * | [Buffer](../../../system/buffer/) per inserire i caratteri in. |
| char_count | int | Dimensione del buffer di output. |

### Valore restituito

Numero di caratteri scritti.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)