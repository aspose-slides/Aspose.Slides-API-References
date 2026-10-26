---
title: Overlaps()
second_title: Referencia de la API de Aspose.Slides para C++
description: Determina si dos ReadOnlySpans se superponen en memoria sin calcular el desplazamiento.
type: docs
weight: 274
url: /es/system.memoryextensions/overlaps/
---
## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) función


Determina si dos ReadOnlySpans se superponen en memoria sin calcular el desplazamiento.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en los spans |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El primer span para comprobar la superposición |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El segundo span para comprobar la superposición |

### Valor devuelto

true if the spans share any common memory locations, false otherwise

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) función


Determina si un [Span](../../system/span/) y [ReadOnlySpan](../../system/readonlyspan/) se superponen en memoria sin calcular el desplazamiento.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en los spans |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | El [Span](../../system/span/) para comprobar la superposición |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El [ReadOnlySpan](../../system/readonlyspan/) para comprobar la superposición |

### Valor devuelto

true if the spans share any common memory locations, false otherwise

## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) función


Determina si dos ReadOnlySpans se superponen en memoria y calcula el desplazamiento.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en los spans |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El primer span para comprobar la superposición |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El segundo span para comprobar la superposición |
| elementOffset | **int32_t**\& | Parámetro de salida que recibe el desplazamiento entre spans si se superponen |

### Valor devuelto

true if the spans share any common memory locations, false otherwise

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) función


Determina si un [Span](../../system/span/) y [ReadOnlySpan](../../system/readonlyspan/) se superponen en memoria y calcula el desplazamiento.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en los spans |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | El [Span](../../system/span/) para comprobar la superposición |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El [ReadOnlySpan](../../system/readonlyspan/) para comprobar la superposición |
| elementOffset | **int32_t**\& | Parámetro de salida que recibe el desplazamiento entre spans si se superponen |

### Valor devuelto

true if the spans share any common memory locations, false otherwise

## Ver también

* Clase [ReadOnlySpan](../../system/readonlyspan/)
* Clase [Span](../../system/span/)
* Espacio de nombres [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)