---
title: ContainsAnyInRange()
second_title: Referencia de la API de Aspose.Slides para C++
description: Comprueba si una span de solo lectura contiene algún elemento dentro del rango especificado.
type: docs
weight: 92
url: /es/system.memoryextensions/containsanyinrange/
---
## System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) función


Comprueba si una span de solo lectura contiene algún elemento dentro del rango especificado.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en la span (debe ser comparable) |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La span en la que buscar |
| lowInclusive | const T\& | El límite inferior (inclusivo) |
| highInclusive | const T\& | El límite superior (inclusivo) |

### Valor devuelto

true si se encuentra algún elemento dentro del rango, false en caso contrario

## System::MemoryExtensions::ContainsAnyInRange(const Span\<T\>\&, const T\&, const T\&) función


Comprueba si una span mutable contiene algún elemento dentro del rango especificado.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en la span (debe ser comparable) |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | La span mutable en la que buscar |
| lowInclusive | const T\& | El límite inferior (inclusivo) |
| highInclusive | const T\& | El límite superior (inclusivo) |

### Valor devuelto

true si se encuentra algún elemento dentro del rango, false en caso contrario

## Ver también

* Clase [ReadOnlySpan](../../system/readonlyspan/)
* Clase [Span](../../system/span/)
* Espacio de nombres [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)