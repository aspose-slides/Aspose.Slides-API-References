---
title: SequenceCompareTo()
second_title: Referencia de API de Aspose.Slides para C++
description: Compara dos ReadOnlySpans lexicográficamente.
type: docs
weight: 313
url: /es/system.memoryextensions/sequencecompareto/
---
## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) función

Compara dos ReadOnlySpans lexicográficamente.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | The type of elements in the spans |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El primer span para comparar |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El segundo span para comparar |

### Valor de retorno

- 1 si span < other, 0 si span == other, 1 si span > other

## System::MemoryExtensions::SequenceCompareTo(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) función

Compara un [Span](../../system/span/) y [ReadOnlySpan](../../system/readonlyspan/) lexicográficamente.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | The type of elements in the spans |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | El [Span](../../system/span/) para comparar |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El [ReadOnlySpan](../../system/readonlyspan/) para comparar |

### Valor de retorno

- 1 si span < other, 0 si span == other, 1 si span > other

## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) función

Compara un [ReadOnlySpan](../../system/readonlyspan/) y [Span](../../system/span/) lexicográficamente.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const Span<T> &other)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | The type of elements in the spans |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El [ReadOnlySpan](../../system/readonlyspan/) para comparar |
| other | const [Span](../../system/span/)\<T\>\& | El [Span](../../system/span/) para comparar |

### Valor de retorno

- 1 si span < other, 0 si span == other, 1 si span > other

## Ver también

* Clase [ReadOnlySpan](../../system/readonlyspan/)
* Clase [Span](../../system/span/)
* Espacio de nombres [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)