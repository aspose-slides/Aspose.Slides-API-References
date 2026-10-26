---
title: CommonPrefixLength()
second_title: Referencia de API de Aspose.Slides para C++
description: Encuentra la longitud del prefijo común entre dos spans.
type: docs
weight: 27
url: /es/system.memoryextensions/commonprefixlength/
---
## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) función


Encuentra la longitud del prefijo común entre dos spans.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en los spans |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El primer span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El segundo span |

### Valor de retorno

El número de elementos coincidentes al principio de ambos spans

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) función


Encuentra la longitud del prefijo común entre un span mutable y un span de solo lectura.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en los spans |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | El span mutable |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span de solo lectura |

### Valor de retorno

El número de elementos coincidentes al principio de ambos spans

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&) función


Encuentra la longitud del prefijo común entre dos spans mutables.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en los spans |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | El primer span mutable |
| other | const [Span](../../system/span/)\<T\>\& | El segundo span mutable |

### Valor de retorno

El número de elementos coincidentes al principio de ambos spans

## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) función


Encuentra la longitud del prefijo común entre dos spans usando un comparador de igualdad personalizado.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en los spans |
| TEqualityComparer | El tipo del comparador de igualdad |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El primer span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El segundo span |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | El comparador de igualdad a usar para la comparación de elementos |

### Valor de retorno

El número de elementos coincidentes al principio de ambos spans

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) función


Encuentra la longitud del prefijo común entre un span mutable y un span de solo lectura usando un comparador de igualdad personalizado.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en los spans |
| TEqualityComparer | El tipo del comparador de igualdad |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | El span mutable |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span de solo lectura |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | El comparador de igualdad a usar para la comparación de elementos |

### Valor de retorno

El número de elementos coincidentes al principio de ambos spans

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) función


Encuentra la longitud del prefijo común entre dos spans mutables usando un comparador de igualdad personalizado.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en los spans |
| TEqualityComparer | El tipo del comparador de igualdad |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | El primer span mutable |
| other | const [Span](../../system/span/)\<T\>\& | El segundo span mutable |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | El comparador de igualdad a usar para la comparación de elementos |

### Valor de retorno

El número de elementos coincidentes al principio de ambos spans

## Ver también

* Typedef [SharedPtr](../../system/sharedptr/)
* Clase [ReadOnlySpan](../../system/readonlyspan/)
* Clase [Span](../../system/span/)
* Espacio de nombres [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)