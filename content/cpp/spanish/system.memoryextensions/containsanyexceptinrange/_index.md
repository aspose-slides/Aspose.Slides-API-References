---
title: ContainsAnyExceptInRange()
second_title: Referencia de la API de Aspose.Slides para C++
description: Comprueba si un span de solo lectura contiene algún elemento fuera del rango especificado.
type: docs
weight: 79
url: /es/system.memoryextensions/containsanyexceptinrange/
---
## System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) función


Checks if a read-only span contains any element outside the specified range.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en el span (debe ser comparable) |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span para buscar en |
| lowInclusive | const T\& | El límite inferior (inclusivo) |
| highInclusive | const T\& | El límite superior (inclusivo) |

### Valor devuelto

true si se encuentra algún elemento fuera del rango, false en caso contrario

## System::MemoryExtensions::ContainsAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) función


Checks if a mutable span contains any element outside the specified range.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en el span (debe ser comparable) |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | El span mutable para buscar en |
| lowInclusive | const T\& | El límite inferior (inclusivo) |
| highInclusive | const T\& | El límite superior (inclusivo) |

### Valor devuelto

true si se encuentra algún elemento fuera del rango, false en caso contrario

## Ver también

* Clase [ReadOnlySpan](../../system/readonlyspan/)
* Clase [Span](../../system/span/)
* Espacio de nombres [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)