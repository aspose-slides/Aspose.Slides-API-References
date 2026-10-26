---
title: GetByteCount()
second_title: Referência da API Aspose.Slides para C++
description: Obtém o número de caracteres necessários para codificar um buffer de caracteres.
type: docs
weight: 235
url: /pt/system.text/encoding/getbytecount/
---
## Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) método


Obtém o número de caracteres necessários para codificar um buffer de caracteres.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Buffer de caracteres. |
| index | int | Início da fatia. |
| count | int | Tamanho da fatia. |

### Valor de Retorno

Tamanho de buffer necessário.

## Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) método


Obtém o número de caracteres necessários para codificar um buffer de caracteres.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Buffer de caracteres. |
| index | int | Início da fatia. |
| count | int | Tamanho da fatia. |

### Valor de Retorno

Tamanho de buffer necessário.

## Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) método


Obtém o número de caracteres necessários para codificar um buffer de caracteres.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Buffer de caracteres. |
| index | int | Início da fatia. |
| count | int | Tamanho da fatia. |

### Valor de Retorno

Tamanho de buffer necessário.

## Encoding::GetByteCount(const String\&) método


Obtém o número de caracteres necessários para codificar uma string.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) para codificar. |

### Valor de Retorno

Tamanho de buffer necessário.

## Encoding::GetByteCount(ArrayPtr\<char_t\>) método


Obtém o número de caracteres necessários para codificar um buffer de caracteres.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Buffer de caracteres. |

### Valor de Retorno

Tamanho de buffer necessário.

## Encoding::GetByteCount(const char_t *, int) método


Obtém o número de caracteres necessários para codificar um buffer de caracteres.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chars | const char_t * | Buffer de caracteres. |
| count | int | [Buffer](../../../system/buffer/) tamanho. |

### Valor de Retorno

Tamanho de buffer necessário.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Encoding](../)
* Classe [String](../../../system/string/)
* Namespace [System::Text](../../)
* Biblioteca [Aspose.Slides](../../../)