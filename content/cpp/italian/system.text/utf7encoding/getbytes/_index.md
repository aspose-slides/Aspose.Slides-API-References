---
title: GetBytes()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottiene i byte risultanti dalla codifica di un buffer di caratteri.
type: docs
weight: 66
url: /it/system.text/utf7encoding/getbytes/
---
## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) metodo

Ottiene i byte risultanti dalla codifica di un buffer di caratteri.

```cpp
int System::Text::UTF7Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Caratteri da codificare. |
| char_index | int | Inizio della sezione di caratteri. |
| char_count | int | Numero di caratteri da convertire. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) per inserire i caratteri. |
| byte_index | int | Offset del buffer di output. |

### Valore di ritorno

Numero di byte scritti.

## UTF7Encoding::GetBytes(const char_t *, int, uint8_t *, int) metodo

Ottiene i byte risultanti dalla codifica di un buffer di caratteri.

```cpp
int System::Text::UTF7Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chars | const char_t * | Caratteri da codificare. |
| char_count | int | Numero di caratteri da convertire. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) per inserire i caratteri. |
| byte_count | int | Dimensione del buffer di output. |

### Valore di ritorno

Numero di byte scritti.

## UTF7Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) metodo

Ottiene i byte risultanti dalla codifica di un buffer di caratteri.

```cpp
int System::Text::UTF7Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) da codificare. |
| char_index | int | Inizio della sezione di caratteri. |
| char_count | int | Numero di caratteri da convertire. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) per inserire i caratteri. |
| byte_index | int | Offset del buffer di output. |

### Valore di ritorno

Numero di byte scritti.

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) metodo

Ottiene i byte risultanti dalla codifica di un buffer di caratteri.

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Caratteri da codificare. |
| char_index | int | Inizio della sezione di caratteri. |
| char_count | int | Numero di caratteri da convertire. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) per inserire i caratteri. |
| byte_index | int | Offset del buffer di output. |

### Valore di ritorno

Numero di byte scritti.

## UTF7Encoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) metodo

Ottiene i byte risultanti dalla codifica di un buffer di caratteri.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Caratteri da codificare. |
| char_index | int | Inizio della sezione di caratteri. |
| char_count | int | Numero di caratteri da convertire. |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) per inserire i caratteri. |
| byte_index | int | Offset del buffer di output. |

### Valore di ritorno

Numero di byte scritti.

## UTF7Encoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) metodo

Ottiene i byte risultanti dalla codifica di un buffer di caratteri.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | Caratteri da codificare. |
| char_index | int | Inizio della sezione di caratteri. |
| char_count | int | Numero di caratteri da convertire. |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) per inserire i caratteri. |
| byte_index | int | Offset del buffer di output. |

### Valore di ritorno

Numero di byte scritti.

## UTF7Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) metodo

Ottiene i byte risultanti dalla codifica di un buffer di caratteri.

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) da codificare. |
| char_index | int | Inizio della sezione di caratteri. |
| char_count | int | Numero di caratteri da convertire. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) per inserire i caratteri. |
| byte_index | int | Offset del buffer di output. |

### Valore di ritorno

Numero di byte scritti.

## UTF7Encoding::GetBytes(const String\&) metodo

Ottiene i byte risultanti dalla codifica di un buffer di caratteri.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) da codificare. |

### Valore di ritorno

[Buffer](../../../system/buffer/) che contiene la rappresentazione dei caratteri codificati.

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int) metodo

Ottiene i byte risultanti dalla codifica di un buffer di caratteri.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Caratteri da codificare. |
| index | int | Inizio della sezione di caratteri. |
| count | int | Numero di caratteri da convertire. |

### Valore di ritorno

[Buffer](../../../system/buffer/) che contiene la rappresentazione dei caratteri codificati.

## UTF7Encoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) metodo

Ottiene i byte risultanti dalla codifica di un buffer di caratteri.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | Caratteri da codificare. |
| index | int | Inizio della sezione di caratteri. |
| count | int | Numero di caratteri da convertire. |

### Valore di ritorno

[Buffer](../../../system/buffer/) che contiene la rappresentazione dei caratteri codificati.

## UTF7Encoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) metodo

Ottiene i byte risultanti dalla codifica di un buffer di caratteri.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Caratteri da codificare. |
| index | int | Inizio della sezione di caratteri. |
| count | int | Numero di caratteri da convertire. |

### Valore di ritorno

[Buffer](../../../system/buffer/) che contiene la rappresentazione dei caratteri codificati.

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>) metodo

Ottiene i byte risultanti dalla codifica di un buffer di caratteri.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Caratteri da codificare. |

### Valore di ritorno

[Buffer](../../../system/buffer/) che contiene la rappresentazione dei caratteri codificati.

## UTF7Encoding::GetBytes(const char_t *, int, uint8_t *, int) metodo

Ottiene i byte risultanti dalla codifica di un buffer di caratteri.

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chars | const char_t * | Caratteri da codificare. |
| char_count | int | Numero di caratteri da convertire. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) per inserire i caratteri. |
| byte_count | int | Dimensione del buffer di output. |

### Valore di ritorno

Numero di byte scritti.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [UTF7Encoding](../)
* Classe [String](../../../system/string/)
* Spazio dei nomi [System::Text](../../)
* Library [Aspose.Slides](../../../)