---
title: IndexOf()
second_title: Referencia de API de Aspose.Slides para C++
description: Busca el índice de un valor ReadOnlySpan<T> en otro ReadOnlySpan<T>
type: docs
weight: 144
url: /es/system.memoryextensions/indexof/
---
## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) función

Busca el índice de un valor ReadOnlySpan<T> en otro ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | The type of elements in the spans |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span en el que buscar |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span a buscar |

### Valor devuelto

El índice basado en cero de la primera ocurrencia, o -1 si no se encuentra

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const T\&) función

Busca el índice de un único valor en un ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const T &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | The type of elements in the span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span en el que buscar |
| value | const T\& | El valor a buscar |

### Valor devuelto

El índice basado en cero de la primera ocurrencia, o -1 si no se encuentra

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) función

Busca el índice de un valor ReadOnlySpan<T> en un Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | The type of elements in the spans |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | El span en el que buscar |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span a buscar |

### Valor devuelto

El índice basado en cero de la primera ocurrencia, o -1 si no se encuentra

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const T\&) función

Busca el índice de un único valor en un Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const T &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | The type of elements in the span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | El span en el que buscar |
| value | const T\& | El valor a buscar |

### Valor devuelto

El índice basado en cero de la primera ocurrencia, o -1 si no se encuentra

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) función

Busca el índice de un valor ReadOnlySpan<char16_t> en un ReadOnlySpan<char16_t> con StringComparison.

```cpp
int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | El span en el que buscar |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | El valor a buscar |
| comparisonType | [StringComparison](../../system/stringcomparison/) | El tipo de comparación de cadena a usar |

### Valor devuelto

El índice basado en cero de la primera ocurrencia, o -1 si no se encuentra

## Ver también

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)