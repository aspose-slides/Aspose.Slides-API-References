---
title: GetByteCount()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene el número de caracteres necesarios para codificar un búfer de caracteres.
type: docs
weight: 235
url: /es/system.text/encoding/getbytecount/
---
## Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) método

Obtiene el número de caracteres necesarios para codificar un búfer de caracteres.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Búfer de caracteres. |
| index | int | Inicio del segmento. |
| count | int | Tamaño del segmento. |

### Valor de retorno

Tamaño de búfer requerido.

## Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) método

Obtiene el número de caracteres necesarios para codificar un búfer de caracteres.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Búfer de caracteres. |
| index | int | Inicio del segmento. |
| count | int | Tamaño del segmento. |

### Valor de retorno

Tamaño de búfer requerido.

## Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) método

Obtiene el número de caracteres necesarios para codificar un búfer de caracteres.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Búfer de caracteres. |
| index | int | Inicio del segmento. |
| count | int | Tamaño del segmento. |

### Valor de retorno

Tamaño de búfer requerido.

## Encoding::GetByteCount(const String\&) método

Obtiene el número de caracteres necesarios para codificar una cadena.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) para codificar. |

### Valor de retorno

Tamaño de búfer requerido.

## Encoding::GetByteCount(ArrayPtr\<char_t\>) método

Obtiene el número de caracteres necesarios para codificar un búfer de caracteres.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Búfer de caracteres. |

### Valor de retorno

Tamaño de búfer requerido.

## Encoding::GetByteCount(const char_t *, int) método

Obtiene el número de caracteres necesarios para codificar un búfer de caracteres.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chars | const char_t * | Búfer de caracteres. |
| count | int | [Buffer](../../../system/buffer/) tamaño. |

### Valor de retorno

Tamaño de búfer requerido.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoding](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)