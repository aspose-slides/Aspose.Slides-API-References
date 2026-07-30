---
title: GetBytes()
second_title: Riferimento API Aspose.Slides per C++
description: Ottieni i byte risultanti dalla codifica di un buffer di caratteri.
type: docs
weight: 40
url: /it/system.text/icuencoding/getbytes/
---
## ICUEncoding::GetBytes(const char_t *, int, uint8_t *, int) method

Ottiene i byte risultanti dalla codifica di un buffer di caratteri.

```cpp
int System::Text::ICUEncoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Caratteri da codificare. |
| char_count | int | Numero di caratteri da convertire. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) per inserire i caratteri. |
| byte_count | int | Dimensione del buffer di output. |

### Return Value

Numero di byte scritti.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) method

Ottiene i byte risultanti dalla codifica di un buffer di caratteri.

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Caratteri da codificare. |
| char_index | int | Inizio della porzione di caratteri. |
| char_count | int | Numero di caratteri da convertire. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) per inserire i caratteri. |
| byte_index | int | Offset del buffer di output. |

### Return Value

Numero di byte scritti.

## ICUEncoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) method

Ottiene i byte risultanti dalla codifica di un buffer di caratteri.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Caratteri da codificare. |
| char_index | int | Inizio della porzione di caratteri. |
| char_count | int | Numero di caratteri da convertire. |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) per inserire i caratteri. |
| byte_index | int | Offset del buffer di output. |

### Return Value

Numero di byte scritti.

## ICUEncoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) method

Ottiene i byte risultanti dalla codifica di un buffer di caratteri.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | Caratteri da codificare. |
| char_index | int | Inizio della porzione di caratteri. |
| char_count | int | Numero di caratteri da convertire. |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) per inserire i caratteri. |
| byte_index | int | Offset del buffer di output. |

### Return Value

Numero di byte scritti.

## ICUEncoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) method

Ottiene i byte risultanti dalla codifica di un buffer di caratteri.

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) per codificare. |
| char_index | int | Inizio della porzione di caratteri. |
| char_count | int | Numero di caratteri da convertire. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) per inserire i caratteri. |
| byte_index | int | Offset del buffer di output. |

### Return Value

Numero di byte scritti.

## ICUEncoding::GetBytes(const String\&) method

Ottiene i byte risultanti dalla codifica di un buffer di caratteri.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) per codificare. |

### Return Value

[Buffer](../../../system/buffer/) che contiene la rappresentazione dei caratteri codificati.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>, int, int) method

Ottiene i byte risultanti dalla codifica di un buffer di caratteri.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Caratteri da codificare. |
| index | int | Inizio della porzione di caratteri. |
| count | int | Numero di caratteri da convertire. |

### Return Value

[Buffer](../../../system/buffer/) che contiene la rappresentazione dei caratteri codificati.

## ICUEncoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) method

Ottiene i byte risultanti dalla codifica di un buffer di caratteri.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | Caratteri da codificare. |
| index | int | Inizio della porzione di caratteri. |
| count | int | Numero di caratteri da convertire. |

### Return Value

[Buffer](../../../system/buffer/) che contiene la rappresentazione dei caratteri codificati.

## ICUEncoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) method

Ottiene i byte risultanti dalla codifica di un buffer di caratteri.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Caratteri da codificare. |
| index | int | Inizio della porzione di caratteri. |
| count | int | Numero di caratteri da convertire. |

### Return Value

[Buffer](../../../system/buffer/) che contiene la rappresentazione dei caratteri codificati.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>) method

Ottiene i byte risultanti dalla codifica di un buffer di caratteri.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Caratteri da codificare. |

### Return Value

[Buffer](../../../system/buffer/) che contiene la rappresentazione dei caratteri codificati.

## ICUEncoding::GetBytes(const char_t *, int, uint8_t *, int) method

Ottiene i byte risultanti dalla codifica di un buffer di caratteri.

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Caratteri da codificare. |
| char_count | int | Numero di caratteri da convertire. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) per inserire i caratteri. |
| byte_count | int | Dimensione del buffer di output. |

### Return Value

Numero di byte scritti.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ICUEncoding](../)
* Classe [String](../../../system/string/)
* Spazio dei nomi [System::Text](../../)
* Libreria [Aspose.Slides](../../../)