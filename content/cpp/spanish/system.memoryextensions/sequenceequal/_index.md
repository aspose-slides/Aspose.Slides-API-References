---
title: SequenceEqual()
second_title: Referencia de API de Aspose.Slides para C++
description: Determina si dos ReadOnlySpans contienen elementos idénticos en el mismo orden.
type: docs
weight: 326
url: /es/system.memoryextensions/sequenceequal/
---
## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) función

Determina si dos ReadOnlySpans contienen elementos idénticos en el mismo orden.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &first, const ReadOnlySpan<T> &second)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en los spans |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El primer span a comparar |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El segundo span a comparar |

### Valor devuelto

true si los spans tienen la misma longitud y todos los elementos son iguales, false de lo contrario

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) función

Determina si un [Span](../../system/span/) y [ReadOnlySpan](../../system/readonlyspan/) contienen elementos idénticos en el mismo orden.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en los spans |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | El [Span](../../system/span/) a comparar |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El [ReadOnlySpan](../../system/readonlyspan/) a comparar |

### Valor devuelto

true si los spans tienen la misma longitud y todos los elementos son iguales, false de lo contrario

## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) función

Determina si dos ReadOnlySpans contienen elementos iguales usando un comparador personalizado.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en los spans |
| TComparer | El tipo del objeto comparador |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El primer span a comparar |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El segundo span a comparar |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Puntero inteligente al objeto comparer para la comparación de elementos |

### Valor devuelto

true si los spans tienen la misma longitud y el comparer considera todos los elementos iguales, false de lo contrario

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) función

Determina si un [Span](../../system/span/) y [ReadOnlySpan](../../system/readonlyspan/) contienen elementos iguales usando un comparador personalizado.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en los spans |
| TComparer | El tipo del objeto comparador |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | El [Span](../../system/span/) a comparar |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El [ReadOnlySpan](../../system/readonlyspan/) a comparar |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Puntero inteligente al objeto comparer para la comparación de elementos |

### Valor devuelto

true si los spans tienen la misma longitud y el comparer considera todos los elementos iguales, false de lo contrario

## Ver también

* Typedef [SharedPtr](../../system/sharedptr/)
* Clase [ReadOnlySpan](../../system/readonlyspan/)
* Clase [Span](../../system/span/)
* Espacio de nombres [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)