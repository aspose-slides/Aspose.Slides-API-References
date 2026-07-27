---
title: CopyTo()
second_title: Referencia de API de Aspose.Slides para C++
description: Copia todos los elementos del array actual al array de destino especificado. Los elementos se insertan en el array de destino comenzando en el índice especificado por el argumento arrayIndex.
type: docs
weight: 118
url: /es/system/array/copyto/
---
## Array::CopyTo(ArrayPtr\<T\>, int) método


Copia todos los elementos del array actual al array de destino especificado. Los elementos se insertan en el array de destino comenzando en el índice especificado por el argumento arrayIndex.

```cpp
virtual void System::Array<T>::CopyTo(ArrayPtr<T> arr, int arrayIndex) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | Array de destino |
| arrayIndex | int | [Index](../../index/) en el array de destino para comenzar a insertar los elementos copiados |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t) const método


Copia todos los elementos del array actual al array de destino especificado. Los elementos se insertan en el array de destino comenzando en el índice especificado por el argumento dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t dstIndex) const
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| DstType | Tipo de elementos en el array de destino |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Array de destino |
| dstIndex | **int64_t** | [Index](../../index/) en el array de destino para comenzar a insertar los elementos copiados |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t) const método


Copia todos los elementos del array actual a la vista de array de destino especificada. Los elementos se insertan en la vista de array de destino comenzando en el índice especificado por el argumento dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t dstIndex) const
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| DstType | Tipo de elementos en la vista de array de destino |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Vista de array de destino |
| dstIndex | **int64_t** | [Index](../../index/) en la vista de array de destino para comenzar a insertar los elementos copiados |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t, int64_t, int64_t) const método


Copia un número especificado de elementos del array actual comenzando en la posición especificada a un array de destino especificado. Los elementos se insertan en el array de destino comenzando en el índice especificado por el argumento dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| DstType | Tipo de elementos en el array de destino |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Array de destino |
| srcIndex | **int64_t** | [Index](../../index/) en el array de origen para comenzar a copiar los elementos |
| dstIndex | **int64_t** | [Index](../../index/) en el array de destino para comenzar a insertar los elementos copiados |
| count | **int64_t** | Número de elementos a copiar |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t, int64_t, int64_t) const método


Copia un número especificado de elementos del array actual comenzando en la posición especificada a una vista de array de destino especificada. Los elementos se insertan en la vista de array de destino comenzando en el índice especificado por el argumento dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| DstType | Tipo de elementos en la vista de array de destino |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Vista de array de destino |
| srcIndex | **int64_t** | [Index](../../index/) en el array de origen para comenzar a copiar los elementos |
| dstIndex | **int64_t** | [Index](../../index/) en la vista de array de destino para comenzar a insertar los elementos copiados |
| count | **int64_t** | Número de elementos a copiar |

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Clase [Array](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)