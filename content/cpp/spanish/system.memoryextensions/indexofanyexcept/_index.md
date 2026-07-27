---
title: IndexOfAnyExcept()
second_title: Referencia de la API de Aspose.Slides para C++
description: Encuentra el índice del primer elemento que no es igual al valor especificado en un ReadOnlySpan<T>
type: docs
weight: 170
url: /es/system.memoryextensions/indexofanyexcept/
---
## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) function

Encuentra el índice del primer elemento que no es igual al valor especificado en un ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span en el que buscar |
| value | const T\& | El valor a excluir de la búsqueda |

### Valor devuelto

El índice basado en cero del primer elemento que no coincide, o -1 si no se encuentra

## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

Encuentra el índice del primer elemento que no es igual a ninguno de los dos valores especificados en un ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span en el que buscar |
| value0 | const T\& | El primer valor a excluir de la búsqueda |
| value1 | const T\& | El segundo valor a excluir de la búsqueda |

### Valor devuelto

El índice basado en cero del primer elemento que no coincide, o -1 si no se encuentra

## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) function

Encuentra el índice del primer elemento que no es igual a ninguno de los tres valores especificados en un ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span en el que buscar |
| value0 | const T\& | El primer valor a excluir de la búsqueda |
| value1 | const T\& | El segundo valor a excluir de la búsqueda |
| value2 | const T\& | El tercer valor a excluir de la búsqueda |

### Valor devuelto

El índice basado en cero del primer elemento que no coincide, o -1 si no se encuentra

## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const T\&) function

Encuentra el índice del primer elemento que no es igual al valor especificado en un Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const T &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | El span en el que buscar |
| value | const T\& | El valor a excluir de la búsqueda |

### Valor devuelto

El índice basado en cero del primer elemento que no coincide, o -1 si no se encuentra

## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&) function

Encuentra el índice del primer elemento que no es igual a ninguno de los dos valores especificados en un Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | El span en el que buscar |
| value0 | const T\& | El primer valor a excluir de la búsqueda |
| value1 | const T\& | El segundo valor a excluir de la búsqueda |

### Valor devuelto

El índice basado en cero del primer elemento que no coincide, o -1 si no se encuentra

## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) function

Encuentra el índice del primer elemento que no es igual a ninguno de los tres valores especificados en un Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | El span en el que buscar |
| value0 | const T\& | El primer valor a excluir de la búsqueda |
| value1 | const T\& | El segundo valor a excluir de la búsqueda |
| value2 | const T\& | El tercer valor a excluir de la búsqueda |

### Valor devuelto

El índice basado en cero del primer elemento que no coincide, o -1 si no se encuentra

## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Encuentra el índice del primer elemento que no es igual a ningún valor en un span de valores.

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos en los spans |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span en el que buscar |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span que contiene los valores a excluir de la búsqueda |

### Valor devuelto

El índice basado en cero del primer elemento que no coincide, o -1 si no se encuentra

## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Encuentra el índice del primer elemento que no es igual a ningún valor en un span de valores en un Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos en los spans |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | El span en el que buscar |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span que contiene los valores a excluir de la búsqueda |

### Valor devuelto

El índice basado en cero del primer elemento que no coincide, o -1 si no se encuentra

## Ver también

* Clase [ReadOnlySpan](../../system/readonlyspan/)
* Clase [Span](../../system/span/)
* Espacio de nombres [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)