---
title: GetByteCount()
second_title: Referência da API Aspose.Slides para C++
description: Obtém o número de caracteres necessários para codificar um buffer de caracteres.
type: docs
weight: 27
url: /pt/system.text/icuencoding/getbytecount/
---
## ICUEncoding::GetByteCount(const char_t *, int) método

Obtém o número de caracteres necessários para codificar um buffer de caracteres.

```cpp
int System::Text::ICUEncoding::GetByteCount(const char_t *chars, int count) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chars | const char_t * | Buffer de caracteres. |
| count | int | [Buffer](../../../system/buffer/) tamanho. |

### Valor de Retorno

Tamanho de buffer necessário.

## ICUEncoding::GetByteCount(ArrayPtr\<char_t\>, int, int) método

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

## ICUEncoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) método

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

## ICUEncoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) método

RTTI.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

## ICUEncoding::GetByteCount(const String\&) método

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

## ICUEncoding::GetByteCount(ArrayPtr\<char_t\>) método

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

## ICUEncoding::GetByteCount(const char_t *, int) método

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ICUEncoding](../)
* Classe [String](../../../system/string/)
* Espaço de nomes [System::Text](../../)
* Biblioteca [Aspose.Slides](../../../)