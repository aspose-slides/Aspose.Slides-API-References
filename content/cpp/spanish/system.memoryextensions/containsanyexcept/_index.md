---
title: ContainsAnyExcept()
second_title: Referencia de API de Aspose.Slides para C++
description: Comprueba si un span de solo lectura contiene algún elemento distinto de los tres valores especificados.
type: docs
weight: 66
url: /es/system.memoryextensions/containsanyexcept/
---
## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) función

Comprueba si un span de solo lectura contiene algún elemento distinto de los tres valores especificados.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span en el que buscar |
| value0 | const T\& | El primer valor a excluir |
| value1 | const T\& | El segundo valor a excluir |
| value2 | const T\& | El tercer valor a excluir |

### Valor devuelto

true si se encuentra algún elemento distinto de los valores especificados, false de lo contrario

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) función

Comprueba si un span mutable contiene algún elemento distinto de los tres valores especificados.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | El span mutable en el que buscar |
| value0 | const T\& | El primer valor a excluir |
| value1 | const T\& | El segundo valor a excluir |
| value2 | const T\& | El tercer valor a excluir |

### Valor devuelto

true si se encuentra algún elemento distinto de los valores especificados, false de lo contrario

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) función

Comprueba si un span de solo lectura contiene algún elemento distinto de los dos valores especificados.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span en el que buscar |
| value0 | const T\& | El primer valor a excluir |
| value1 | const T\& | El segundo valor a excluir |

### Valor devuelto

true si se encuentra algún elemento distinto de los valores especificados, false de lo contrario

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&) función

Comprueba si un span mutable contiene algún elemento distinto de los dos valores especificados.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | El span mutable en el que buscar |
| value0 | const T\& | El primer valor a excluir |
| value1 | const T\& | El segundo valor a excluir |

### Valor devuelto

true si se encuentra algún elemento distinto de los valores especificados, false de lo contrario

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) función

Comprueba si un span de solo lectura contiene algún elemento distinto de un valor especificado.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span en el que buscar |
| value | const T\& | El valor a excluir |

### Valor devuelto

true si se encuentra algún elemento distinto del valor especificado, false de lo contrario

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&) función

Comprueba si un span mutable contiene algún elemento distinto de un valor especificado.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | El span mutable en el que buscar |
| value | const T\& | El valor a excluir |

### Valor devuelto

true si se encuentra algún elemento distinto del valor especificado, false de lo contrario

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) función

Comprueba si un span de solo lectura contiene algún elemento distinto de los que están en otro span.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en los spans |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span en el que buscar |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span de valores a excluir |

### Valor devuelto

true si se encuentra algún elemento que no esté en values, false de lo contrario

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) función

Comprueba si un span mutable contiene algún elemento distinto de los que están en un span de solo lectura.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en los spans |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | El span mutable en el que buscar |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span de solo lectura de valores a excluir |

### Valor devuelto

true si se encuentra algún elemento que no esté en values, false de lo contrario

## Ver también

* Clase [ReadOnlySpan](../../system/readonlyspan/)
* Clase [Span](../../system/span/)
* Espacio de nombres [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)