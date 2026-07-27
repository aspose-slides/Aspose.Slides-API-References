---
title: LastIndexOfAnyExceptInRange()
second_title: Referencia de API de Aspose.Slides para C++
description: Busca la última ocurrencia de cualquier elemento fuera del rango especificado dentro de un span.
type: docs
weight: 248
url: /es/system.memoryextensions/lastindexofanyexceptinrange/
---
## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) función

Busca la última ocurrencia de cualquier elemento fuera del rango especificado dentro de un span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
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

El índice basado en cero del último elemento fuera del rango, o -1 si no se encuentra

## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) función

Busca la última ocurrencia de cualquier elemento fuera del rango especificado dentro de un span mutable.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
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

El índice basado en cero del último elemento fuera del rango, o -1 si no se encuentra

## Ver también

* Clase [ReadOnlySpan](../../system/readonlyspan/)
* Clase [Span](../../system/span/)
* Espacio de nombres [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)