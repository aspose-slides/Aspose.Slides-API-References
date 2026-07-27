---
title: LastIndexOfAny()
second_title: Referencia de la API de Aspose.Slides para C++
description: Busca la última aparición de cualquiera de los tres valores especificados dentro de un span.
type: docs
weight: 222
url: /es/system.memoryextensions/lastindexofany/
---
## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) function


Busca la última aparición de cualquiera de los tres valores especificados dentro de un span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```


### Parámetros de plantilla

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to search for |
| value1 | const T\& | The second value to search for |
| value2 | const T\& | The third value to search for |

### Valor devuelto

El índice basado en cero de la última aparición, o -1 si no se encuentra

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&, const T\&) function


Busca la última aparición de cualquiera de los tres valores especificados dentro de un span mutable.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```


### Parámetros de plantilla

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to search for |
| value1 | const T\& | The second value to search for |
| value2 | const T\& | The third value to search for |

### Valor devuelto

El índice basado en cero de la última aparición, o -1 si no se encuentra

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function


Busca la última aparición de cualquiera de los dos valores especificados dentro de un span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```


### Parámetros de plantilla

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to search for |
| value1 | const T\& | The second value to search for |

### Valor devuelto

El índice basado en cero de la última aparición, o -1 si no se encuentra

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&) function


Busca la última aparición de cualquiera de los dos valores especificados dentro de un span mutable.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1)
```


### Parámetros de plantilla

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to search for |
| value1 | const T\& | The second value to search for |

### Valor devuelto

El índice basado en cero de la última aparición, o -1 si no se encuentra

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function


Busca la última aparición de cualquier valor de una secuencia dentro de un span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```


### Parámetros de plantilla

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sequence of values to search for |

### Valor devuelto

El índice basado en cero de la última aparición, o -1 si no se encuentra

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function


Busca la última aparición de cualquier valor de una secuencia dentro de un span mutable.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```


### Parámetros de plantilla

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sequence of values to search for |

### Valor devuelto

El índice basado en cero de la última aparición, o -1 si no se encuentra

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const Span\<T\>\&) function


Busca la última aparición de cualquier valor de una secuencia mutable dentro de un span mutable.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const Span<T> &values)
```


### Parámetros de plantilla

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| values | const [Span](../../system/span/)\<T\>\& | The sequence of values to search for |

### Valor devuelto

El índice basado en cero de la última aparición, o -1 si no se encuentra

## Véase también

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)