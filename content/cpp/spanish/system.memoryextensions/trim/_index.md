---
title: Trim()
second_title: Referencia de API de Aspose.Slides para C++
description: Recorta el elemento especificado de ambos extremos de un span tipado.
type: docs
weight: 365
url: /es/system.memoryextensions/trim/
---
## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, T) función

Recorta el elemento especificado de ambos extremos de un span tipado.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, T trimElement)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span a recortar |
| trimElement | T | El elemento a recortar |

### Valor de retorno

Un nuevo span con el elemento especificado recortado de ambos extremos

## System::MemoryExtensions::Trim(Span\<T\>\&, T) función

Recorta el elemento especificado de ambos extremos de un span tipado mutable.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, T trimElement)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | El span mutable a recortar |
| trimElement | T | El elemento a recortar |

### Valor de retorno

Un nuevo span con el elemento especificado recortado de ambos extremos

## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) función

Recorta los elementos especificados de ambos extremos de un span tipado.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span a recortar |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Los elementos a recortar |

### Valor de retorno

Un nuevo span con los elementos especificados recortados de ambos extremos

## System::MemoryExtensions::Trim(Span\<T\>\&, const ReadOnlySpan\<T\>\&) función

Recorta los elementos especificados de ambos extremos de un span tipado mutable.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | El span mutable a recortar |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Los elementos a recortar |

### Valor de retorno

Un nuevo span con los elementos especificados recortados de ambos extremos

## System::MemoryExtensions::Trim(const ReadOnlySpan\<char16_t\>\&) función

Recorta los caracteres de espacio en blanco de ambos extremos de un span de caracteres.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::Trim(const ReadOnlySpan<char16_t> &span)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | El span de caracteres a recortar |

### Valor de retorno

Un nuevo span con los espacios en blanco recortados de ambos extremos

## System::MemoryExtensions::Trim(Span\<char16_t\>\&) función

Recorta los caracteres de espacio en blanco de ambos extremos de un span de caracteres mutable.

```cpp
Span<char16_t> System::MemoryExtensions::Trim(Span<char16_t> &span)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | El span mutable de caracteres a recortar |

### Valor de retorno

Un nuevo span con los espacios en blanco recortados de ambos extremos

## Ver también

* Clase [ReadOnlySpan](../../system/readonlyspan/)
* Clase [Span](../../system/span/)
* Espacio de nombres [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)