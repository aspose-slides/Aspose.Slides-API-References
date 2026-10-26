---
title: ContainsAny()
second_title: Referencia de API de Aspose.Slides para C++
description: Verifica si un span de solo lectura contiene alguno de dos valores.
type: docs
weight: 53
url: /es/system.memoryextensions/containsany/
---
## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) función


Verifica si un span de solo lectura contiene alguno de dos valores.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span en el que buscar |
| value0 | const T\& | El primer valor a buscar |
| value1 | const T\& | El segundo valor a buscar |

### Valor devuelto

true si alguno de los valores se encuentra en el span, false en caso contrario

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) función


Verifica si un span de solo lectura contiene alguno de tres valores.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span en el que buscar |
| value0 | const T\& | El primer valor a buscar |
| value1 | const T\& | El segundo valor a buscar |
| value2 | const T\& | El tercer valor a buscar |

### Valor devuelto

true si alguno de los valores se encuentra en el span, false en caso contrario

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&) función


Verifica si un span mutable contiene alguno de dos valores.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | El span mutable en el que buscar |
| value0 | const T\& | El primer valor a buscar |
| value1 | const T\& | El segundo valor a buscar |

### Valor devuelto

true si alguno de los valores se encuentra en el span, false en caso contrario

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&, const T\&) función


Verifica si un span mutable contiene alguno de tres valores.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | El span mutable en el que buscar |
| value0 | const T\& | El primer valor a buscar |
| value1 | const T\& | El segundo valor a buscar |
| value2 | const T\& | El tercer valor a buscar |

### Valor devuelto

true si alguno de los valores se encuentra en el span, false en caso contrario

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) función


Verifica si un span de solo lectura contiene algún valor de otro span.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en los spans |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span en el que buscar |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span de valores a buscar |

### Valor devuelto

true si algún valor de values se encuentra en el span, false en caso contrario

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) función


Verifica si un span mutable contiene algún valor de un span de solo lectura.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en los spans |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | El span mutable en el que buscar |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span de solo lectura de valores a buscar |

### Valor devuelto

true si algún valor de values se encuentra en el span, false en caso contrario

## Ver también

* Clase [ReadOnlySpan](../../system/readonlyspan/)
* Clase [Span](../../system/span/)
* Espacio de nombres [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)