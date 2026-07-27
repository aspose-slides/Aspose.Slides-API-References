---
title: Count()
second_title: Referencia de API de Aspose.Slides para C++
description: Cuenta las apariciones de un valor en un span de solo lectura.
type: docs
weight: 118
url: /es/system.memoryextensions/count/
---
## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const T\&) función

Cuenta las apariciones de un valor en un span de solo lectura.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const T &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | The type of elements in the span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span en el que buscar |
| value | const T\& | El valor a contar |

### Valor devuelto

El número de veces que el valor aparece en el span

## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) función

Cuenta las apariciones de un span dentro de otro span de solo lectura.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | The type of elements in the spans |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span en el que buscar |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span del que contar las apariciones |

### Valor devuelto

El número de veces que el valor aparece en el span

## System::MemoryExtensions::Count(const Span\<T\>\&, const T\&) función

Cuenta las apariciones de un único valor en un Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const T &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | The type of elements in the span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | El span en el que buscar |
| value | const T\& | El valor del que contar las apariciones |

### Valor devuelto

El número de apariciones del valor en el span

## System::MemoryExtensions::Count(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) función

Cuenta las apariciones de un ReadOnlySpan<T> en un Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | The type of elements in the spans |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | El span en el que buscar |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span que contiene los valores de los que contar las apariciones |

### Valor devuelto

El número de apariciones del span de valores en el span de destino

## Véase también

* Clase [ReadOnlySpan](../../system/readonlyspan/)
* Clase [Span](../../system/span/)
* Espacio de nombres [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)