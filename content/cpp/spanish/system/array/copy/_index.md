---
title: Copy()
second_title: Referencia de API de Aspose.Slides para C++
description: Copia el número especificado de elementos de la matriz de origen a la matriz de destino.
type: docs
weight: 729
url: /es/system/array/copy/
---
## Array::Copy(const ArrayPtr\<SrcType\>\&, const ArrayPtr\<DstType\>\&, int64_t) método


Copia el número especificado de elementos de la matriz de origen a la matriz de destino.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Matriz de origen |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Matriz de destino |
| count | **int64_t** | El número de elementos a copiar |

## Array::Copy(System::Details::ArrayView\<SrcType\>, const ArrayPtr\<DstType\>\&, int64_t) método


Copia el número especificado de elementos de la vista de matriz de origen a la matriz de destino.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Vista de matriz de origen |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Matriz de destino |
| count | **int64_t** | El número de elementos a copiar |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::ArrayView\<DstType\>, int64_t) método


Copia el número especificado de elementos de la matriz de origen a la vista de matriz de destino.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Matriz de origen |
| dstArray | System::Details::ArrayView\<DstType\> | Vista de matriz de destino |
| count | **int64_t** | El número de elementos a copiar |

## Array::Copy(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, int64_t) método


Copia el número especificado de elementos de la vista de matriz de origen a la vista de matriz de destino.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Vista de matriz de origen |
| dstArray | System::Details::ArrayView\<DstType\> | Vista de matriz de destino |
| count | **int64_t** | El número de elementos a copiar |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, const ArrayPtr\<DstType\>\&, int64_t) método


Copia el número especificado de elementos de la matriz en pila de origen a la matriz de destino.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Matriz en pila de origen |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Matriz de destino |
| count | **int64_t** | El número de elementos a copiar |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, int64_t) método


Copia el número especificado de elementos de la matriz de origen a la matriz en pila de destino.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::StackArray<DstType, N> &dstArray, int64_t count)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Matriz de origen |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Matriz en pila de destino |
| count | **int64_t** | El número de elementos a copiar |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, int64_t) método


Copia el número especificado de elementos de la matriz en pila de origen a la matriz en pila de destino.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, System::Details::StackArray<DstType, ND> &dstArray, int64_t count)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Matriz en pila de origen |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Matriz en pila de destino |
| count | **int64_t** | El número de elementos a copiar |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) método


Copia un número especificado de elementos de la matriz de origen a partir del índice especificado a la posición especificada en la matriz de destino.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| SrcType | Tipo de elementos en la matriz de origen |
| DstType | Tipo de elementos en la matriz de destino |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Matriz de origen |
| srcIndex | **int64_t** | [Index](../../index/) en la matriz de origen que designa el comienzo del rango de elementos a copiar |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Matriz de destino |
| dstIndex | **int64_t** | [Index](../../index/) en la matriz de destino donde comenzar a insertar los elementos copiados |
| count | **int64_t** | El número de elementos a copiar |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) método


Copia un número especificado de elementos de la vista de matriz de origen a partir del índice especificado a la posición especificada en la matriz de destino.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| SrcType | Tipo de elementos en la vista de matriz de origen |
| DstType | Tipo de elementos en la matriz de destino |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Vista de matriz de origen |
| srcIndex | **int64_t** | [Index](../../index/) en la vista de matriz de origen que designa el comienzo del rango de elementos a copiar |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Matriz de destino |
| dstIndex | **int64_t** | [Index](../../index/) en la matriz de destino donde comenzar a insertar los elementos copiados |
| count | **int64_t** | El número de elementos a copiar |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) método


Copia un número especificado de elementos de la matriz de origen a partir del índice especificado a la posición especificada en la vista de matriz de destino.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| SrcType | Tipo de elementos en la matriz de origen |
| DstType | Tipo de elementos en la vista de matriz de destino |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Matriz de origen |
| srcIndex | **int64_t** | [Index](../../index/) en la matriz de origen que designa el comienzo del rango de elementos a copiar |
| dstArray | System::Details::ArrayView\<DstType\> | Vista de matriz de destino |
| dstIndex | **int64_t** | [Index](../../index/) en la vista de matriz de destino donde comenzar a insertar los elementos copiados |
| count | **int64_t** | El número de elementos a copiar |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) método


Copia un número especificado de elementos de la vista de matriz de origen a partir del índice especificado a la posición especificada en la vista de matriz de destino.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| SrcType | Tipo de elementos en la vista de matriz de origen |
| DstType | Tipo de elementos en la vista de matriz de destino |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Vista de matriz de origen |
| srcIndex | **int64_t** | [Index](../../index/) en la vista de matriz de origen que designa el comienzo del rango de elementos a copiar |
| dstArray | System::Details::ArrayView\<DstType\> | Vista de matriz de destino |
| dstIndex | **int64_t** | [Index](../../index/) en la vista de matriz de destino donde comenzar a insertar los elementos copiados |
| count | **int64_t** | El número de elementos a copiar |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) método


Copia un número especificado de elementos de la matriz en pila de origen a partir del índice especificado a la posición especificada en la matriz de destino.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| SrcType | Tipo de elementos en la matriz en pila de origen |
| DstType | Tipo de elementos en la matriz de destino |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Matriz en pila de origen |
| srcIndex | **int64_t** | [Index](../../index/) en la matriz en pila de origen que designa el comienzo del rango de elementos a copiar |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Matriz de destino |
| dstIndex | **int64_t** | [Index](../../index/) en la matriz de destino donde comenzar a insertar los elementos copiados |
| count | **int64_t** | El número de elementos a copiar |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, N\>\&, int64_t, int64_t) método


Copia un número especificado de elementos de la matriz de origen a partir del índice especificado a la posición especificada en la matriz en pila de destino.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, N> &dstArray, int64_t dstIndex, int64_t count)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| SrcType | Tipo de elementos en la matriz de origen |
| DstType | Tipo de elementos en la matriz en pila de destino |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Matriz de origen |
| srcIndex | **int64_t** | [Index](../../index/) en la matriz de origen que designa el comienzo del rango de elementos a copiar |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Matriz en pila de destino |
| dstIndex | **int64_t** | [Index](../../index/) en la matriz en pila de destino donde comenzar a insertar los elementos copiados |
| count | **int64_t** | El número de elementos a copiar |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) método


Copia un número especificado de elementos de la matriz en pila de origen a partir del índice especificado a la posición especificada en la matriz en pila de destino.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| SrcType | Tipo de elementos en la matriz en pila de origen |
| DstType | Tipo de elementos en la matriz en pila de destino |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Matriz en pila de origen |
| srcIndex | **int64_t** | [Index](../../index/) en la matriz en pila de origen que designa el comienzo del rango de elementos a copiar |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Matriz en pila de destino |
| dstIndex | **int64_t** | [Index](../../index/) en la matriz en pila de destino donde comenzar a insertar los elementos copiados |
| count | **int64_t** | El número de elementos a copiar |

## Array::Copy(System::Details::ArrayView\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) método


Copia un número especificado de elementos de la vista de matriz de origen a partir del índice especificado a la posición especificada en la matriz en pila de destino.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| SrcType | Tipo de elementos en la vista de matriz de origen |
| DstType | Tipo de elementos en la matriz en pila de destino |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\>\& | Vista de matriz de origen |
| srcIndex | **int64_t** | [Index](../../index/) en la vista de matriz de origen que designa el comienzo del rango de elementos a copiar |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Matriz en pila de destino |
| dstIndex | **int64_t** | [Index](../../index/) en la matriz en pila de destino donde comenzar a insertar los elementos copiados |
| count | **int64_t** | El número de elementos a copiar |

## Véase también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)