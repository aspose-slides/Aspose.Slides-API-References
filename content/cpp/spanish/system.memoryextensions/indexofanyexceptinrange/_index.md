---
title: IndexOfAnyExceptInRange()
second_title: Referencia de API de Aspose.Slides para C++
description: Encuentra el índice del primer elemento que está fuera del rango especificado en un ReadOnlySpan<T>
type: docs
weight: 183
url: /es/system.memoryextensions/indexofanyexceptinrange/
---
## System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function


Encuentra el índice del primer elemento que está fuera del rango especificado en un ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en la secuencia |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La secuencia en la que buscar |
| lowInclusive | const T\& | El límite inferior del rango (inclusive) |
| highInclusive | const T\& | El límite superior del rango (inclusive) |

### Valor devuelto

El índice basado en cero del primer elemento fuera del rango, o -1 si no se encuentra

## System::MemoryExtensions::IndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) function


Encuentra el índice del primer elemento que está fuera del rango especificado en un Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en la secuencia |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | La secuencia en la que buscar |
| lowInclusive | const T\& | El límite inferior del rango (inclusive) |
| highInclusive | const T\& | El límite superior del rango (inclusive) |

### Valor devuelto

El índice basado en cero del primer elemento fuera del rango, o -1 si no se encuentra

## Ver también

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)