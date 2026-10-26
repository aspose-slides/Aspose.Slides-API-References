---
title: GetBytes()
second_title: Referência da API Aspose.Slides para C++
description: Obtém os bytes resultantes da codificação de um buffer de caracteres.
type: docs
weight: 248
url: /pt/system.text/encoding/getbytes/
---
## Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) método


Obtém os bytes resultantes da codificação de um buffer de caracteres.

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```


### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Caracteres a codificar. |
| char_index | int | Início da fatia de caracteres. |
| char_count | int | Número de caracteres a converter. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) para onde colocar os caracteres. |
| byte_index | int | Deslocamento do buffer de saída. |

### Return Value

Número de bytes escritos.

## Encoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) método


Obtém os bytes resultantes da codificação de um buffer de caracteres.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```


### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Caracteres a codificar. |
| char_index | int | Início da fatia de caracteres. |
| char_count | int | Número de caracteres a converter. |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) para onde colocar os caracteres. |
| byte_index | int | Deslocamento do buffer de saída. |

### Return Value

Número de bytes escritos.

## Encoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) método


Obtém os bytes resultantes da codificação de um buffer de caracteres.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```


### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | Caracteres a codificar. |
| char_index | int | Início da fatia de caracteres. |
| char_count | int | Número de caracteres a converter. |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) para onde colocar os caracteres. |
| byte_index | int | Deslocamento do buffer de saída. |

### Return Value

Número de bytes escritos.

## Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) método


Obtém os bytes resultantes da codificação de um buffer de caracteres.

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```


### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) para codificar. |
| char_index | int | Início da fatia de caracteres. |
| char_count | int | Número de caracteres a converter. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) para onde colocar os caracteres. |
| byte_index | int | Deslocamento do buffer de saída. |

### Return Value

Número de bytes escritos.

## Encoding::GetBytes(const String\&) método


Obtém os bytes resultantes da codificação de um buffer de caracteres.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```


### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) para codificar. |

### Return Value

[Buffer](../../../system/buffer/) que contém a representação dos caracteres sendo codificados.

## Encoding::GetBytes(ArrayPtr\<char_t\>, int, int) método


Obtém os bytes resultantes da codificação de um buffer de caracteres.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```


### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Caracteres a codificar. |
| index | int | Início da fatia de caracteres. |
| count | int | Número de caracteres a converter. |

### Return Value

[Buffer](../../../system/buffer/) que contém a representação dos caracteres sendo codificados.

## Encoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) método


Obtém os bytes resultantes da codificação de um buffer de caracteres.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```


### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | Caracteres a codificar. |
| index | int | Início da fatia de caracteres. |
| count | int | Número de caracteres a converter. |

### Return Value

[Buffer](../../../system/buffer/) que contém a representação dos caracteres sendo codificados.

## Encoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) método


Obtém os bytes resultantes da codificação de um buffer de caracteres.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```


### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Caracteres a codificar. |
| index | int | Início da fatia de caracteres. |
| count | int | Número de caracteres a converter. |

### Return Value

[Buffer](../../../system/buffer/) que contém a representação dos caracteres sendo codificados.

## Encoding::GetBytes(ArrayPtr\<char_t\>) método


Obtém os bytes resultantes da codificação de um buffer de caracteres.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```


### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Caracteres a codificar. |

### Return Value

[Buffer](../../../system/buffer/) que contém a representação dos caracteres sendo codificados.

## Encoding::GetBytes(const char_t *, int, uint8_t *, int) método


Obtém os bytes resultantes da codificação de um buffer de caracteres.

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```


### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chars | const char_t * | Caracteres a codificar. |
| char_count | int | Número de caracteres a converter. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) para onde colocar os caracteres. |
| byte_count | int | Tamanho do buffer de saída. |

### Return Value

Número de bytes escritos.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoding](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)