---
title: LastIndexOfAnyInRange()
second_title: Referencia de API de Aspose.Slides para C++
description: Encuentra la última aparición de cualquier elemento dentro del rango especificado en un span.
type: docs
weight: 261
url: /es/system.memoryextensions/lastindexofanyinrange/
---
## System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) función

Encuentra la última aparición de cualquier elemento dentro del rango especificado en un span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span en el que buscar |
| lowInclusive | const T\& | El límite inferior del rango (inclusivo) |
| highInclusive | const T\& | El límite superior del rango (inclusivo) |

### Valor de retorno

El índice basado en cero del último elemento dentro del rango, o -1 si no se encuentra

## System::MemoryExtensions::LastIndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) función

Encuentra la última aparición de cualquier elemento dentro del rango especificado en un span mutable.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | El span en el que buscar |
| lowInclusive | const T\& | El límite inferior del rango (inclusivo) |
| highInclusive | const T\& | El límite superior del rango (inclusivo) |

### Valor de retorno

El índice basado en cero del último elemento dentro del rango, o -1 si no se encuentra

## Ver también

* Clase [ReadOnlySpan](../../system/readonlyspan/)
* Clase [Span](../../system/span/)
* Espacio de nombres [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)