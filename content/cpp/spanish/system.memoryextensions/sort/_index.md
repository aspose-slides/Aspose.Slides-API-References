---
title: Sort()
second_title: Referencia de API de Aspose.Slides para C++
description: Ordena un Span usando un comparador personalizado.
type: docs
weight: 339
url: /es/system.memoryextensions/sort/
---
## System::MemoryExtensions::Sort(const Span\<T\>\&, const SharedPtr\<TComparer\>\&) function


Ordena un [Span](../../system/span/) usando un comparador personalizado.

```cpp
template<typename T,typename TComparer> void System::MemoryExtensions::Sort(const Span<T> &span, const SharedPtr<TComparer> &comparer)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en el span |
| TComparer | El tipo del objeto comparador |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | El span a ordenar |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Puntero inteligente al objeto comparador para la comparación de elementos |

## System::MemoryExtensions::Sort(Span\<T\>\&) function


Ordena un [Span](../../system/span/) usando la comparación predeterminada.

```cpp
template<typename T> void System::MemoryExtensions::Sort(Span<T> &span)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en el span |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | El span a ordenar |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, const SharedPtr\<TComparer\>\&) function


Ordena pares clave-valor usando un comparador personalizado (claves y valores ordenados juntos)

```cpp
template<typename TKey,typename TValue,typename TComparer> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, const SharedPtr<TComparer> &comparer)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TKey | El tipo de claves |
| TValue | El tipo de valores |
| TComparer | El tipo del objeto comparador |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | El span de claves a ordenar |
| values | [Span](../../system/span/)\<TValue\>\& | El span de valores a ordenar (manteniendo la correspondencia con las claves) |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Puntero inteligente al objeto comparador para la comparación de claves |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, System::Comparison\<TKey\>) function


Ordena pares clave-valor usando un delegado de comparación.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, System::Comparison<TKey> comparer)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TKey | El tipo de claves |
| TValue | El tipo de valores |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | El span de claves a ordenar |
| values | [Span](../../system/span/)\<TValue\>\& | El span de valores a ordenar |
| comparer | [System::Comparison](../../system/comparison/)\<TKey\> | [Comparison](../../system/comparison/) delegado para la comparación de claves |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&) function


Ordena pares clave-valor usando la comparación predeterminada.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TKey | El tipo de claves |
| TValue | El tipo de valores |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | El span de claves a ordenar |
| values | [Span](../../system/span/)\<TValue\>\& | El span de valores a ordenar |

## Ver también

* Typedef [SharedPtr](../../system/sharedptr/)
* Clase [Span](../../system/span/)
* Clase [Comparison](../../system/comparison/)
* Espacio de nombres [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)