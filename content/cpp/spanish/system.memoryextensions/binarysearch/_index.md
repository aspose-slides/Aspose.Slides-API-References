---
title: BinarySearch()
second_title: Referencia de API de Aspose.Slides para C++
description: Realiza una búsqueda binaria en un span ordenado.
type: docs
weight: 14
url: /es/system.memoryextensions/binarysearch/
---
## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const TComparable\&) función

Realiza una búsqueda binaria en un span ordenado.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const TComparable &comparable)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos en el span |
| TComparable | El tipo del valor comparable |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span ordenado en el que buscar |
| comparable | const TComparable\& | El valor a buscar |

### Valor de retorno

[Index](../../system/index/) del elemento encontrado, o el complemento bit a bit del punto de inserción si no se encuentra


## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) función

Realiza una búsqueda binaria en un span ordenado usando un comparador personalizado.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const T &value, const SharedPtr<TComparer> &comparerPtr)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos en el span |
| TComparer | El tipo del comparador |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | El span ordenado en el que buscar |
| value | const T\& | El valor a buscar |
| comparerPtr | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | El comparador a utilizar para las comparaciones |

### Valor de retorno

[Index](../../system/index/) del elemento encontrado, o el complemento bit a bit del punto de inserción si no se encuentra


## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const TComparable\&) función

Realiza una búsqueda binaria en un span ordenado mutable.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const TComparable &comparable)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos en el span |
| TComparable | El tipo del valor comparable |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | El span ordenado en el que buscar |
| comparable | const TComparable\& | El valor a buscar |

### Valor de retorno

[Index](../../system/index/) del elemento encontrado, o el complemento bit a bit del punto de inserción si no se encuentra


## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) función

Realiza una búsqueda binaria en un span ordenado mutable usando un comparador personalizado.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const T &value, const SharedPtr<TComparer> &comparer)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos en el span |
| TComparer | El tipo del comparador |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | El span ordenado en el que buscar |
| value | const T\& | El valor a buscar |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | El comparador a utilizar para las comparaciones |

### Valor de retorno

[Index](../../system/index/) del elemento encontrado, o el complemento bit a bit del punto de inserción si no se encuentra


## Ver también

* Typedef [SharedPtr](../../system/sharedptr/)
* Clase [ReadOnlySpan](../../system/readonlyspan/)
* Clase [Span](../../system/span/)
* Espacio de nombres [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)