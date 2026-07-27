---
title: GetByteCount()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtenga el número de caracteres necesarios para codificar un búfer de caracteres.
type: docs
weight: 27
url: /es/system.text/icuencoding/getbytecount/
---
## ICUEncoding::GetByteCount(const char_t *, int) método

Obtiene el número de caracteres necesarios para codificar un búfer de caracteres.

```cpp
int System::Text::ICUEncoding::GetByteCount(const char_t *chars, int count) override
```

### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chars | const char_t * | Búfer de caracteres. |
| count | int | [Buffer](../../../system/buffer/) tamaño. |

### Valor devuelto

Tamaño de búfer requerido.

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

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [ICUEncoding](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::Text](../../)
* Biblioteca [Aspose.Slides](../../../)