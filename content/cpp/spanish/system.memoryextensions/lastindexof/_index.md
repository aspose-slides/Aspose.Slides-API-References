---
title: LastIndexOf()
second_title: Referencia API de Aspose.Slides para C++
description: Busca la última aparición de una secuencia dentro de un span.
type: docs
weight: 209
url: /es/system.memoryextensions/lastindexof/
---
## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) función

Busca la última aparición de una secuencia dentro de un span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span en el que buscar |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La secuencia que se busca |

### Valor de retorno

El índice basado en cero de la última aparición, o -1 si no se encuentra

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const T\&) función


Busca la última aparición de un solo valor dentro de un span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const T &value)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span en el que buscar |
| value | const T\& | El valor que se busca |

### Valor de retorno

El índice basado en cero de la última aparición, o -1 si no se encuentra

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) función


Busca la última aparición de una secuencia dentro de un span mutable.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | El span en el que buscar |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | La secuencia que se busca |

### Valor de retorno

El índice basado en cero de la última aparición, o -1 si no se encuentra

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const T\&) función


Busca la última aparición de un solo valor dentro de un span mutable.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const T &value)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | El span en el que buscar |
| value | const T\& | El valor que se busca |

### Valor de retorno

El índice basado en cero de la última aparición, o -1 si no se encuentra

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) función


Busca la última aparición de un valor dentro de un span usando la comparación de cadena especificada.

```cpp
int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | El span en el que buscar |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | El valor que se busca |
| comparisonType | [StringComparison](../../system/stringcomparison/) | El tipo de comparación de cadena a realizar |

### Valor de retorno

El índice basado en cero de la última aparición, o -1 si no se encuentra

## Ver también

* Enumeración [StringComparison](../../system/stringcomparison/)
* Clase [ReadOnlySpan](../../system/readonlyspan/)
* Clase [Span](../../system/span/)
* Espacio de nombres [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)