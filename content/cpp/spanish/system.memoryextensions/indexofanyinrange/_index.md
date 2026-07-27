---
title: IndexOfAnyInRange()
second_title: Referencia de la API de Aspose.Slides para C++
description: Encuentra el índice del primer elemento que está dentro del rango especificado en un ReadOnlySpan<T>
type: docs
weight: 196
url: /es/system.memoryextensions/indexofanyinrange/
---
## System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) función

Encuentra el índice del primer elemento que está dentro del rango especificado en un ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span en el que buscar |
| lowInclusive | const T\& | El límite inferior del rango (inclusive) |
| highInclusive | const T\& | El límite superior del rango (inclusive) |

### Valor devuelto

El índice basado en cero del primer elemento dentro del rango, o -1 si no se encuentra

## System::MemoryExtensions::IndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) función

Encuentra el índice del primer elemento que está dentro del rango especificado en un Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | El span en el que buscar |
| lowInclusive | const T\& | El límite inferior del rango (inclusive) |
| highInclusive | const T\& | El límite superior del rango (inclusive) |

### Valor devuelto

El índice basado en cero del primer elemento dentro del rango, o -1 si no se encuentra

## Ver también

* Clase [ReadOnlySpan](../../system/readonlyspan/)
* Clase [Span](../../system/span/)
* Espacio de nombres [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)