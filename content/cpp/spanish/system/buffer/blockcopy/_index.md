---
title: BlockCopy()
second_title: Referencia de la API de Aspose.Slides para C++
description: Copia un número especificado de bytes del búfer de origen al búfer de destino.
type: docs
weight: 1
url: /es/system/buffer/blockcopy/
---
## Buffer::BlockCopy(const uint8_t *, int, uint8_t *, int, int) método

Copia un número especificado de bytes del búfer de origen al búfer de destino.

```cpp
static void System::Buffer::BlockCopy(const uint8_t *src, int srcOffset, uint8_t *dst, int dstOffset, int count)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | const **uint8_t** * | Puntero al búfer de origen |
| srcOffset | int | Un desplazamiento de bytes en el búfer de origen donde comienza la copia |
| dst | **uint8_t** * | Puntero al búfer de destino |
| dstOffset | int | Un desplazamiento de bytes en el búfer de destino donde comenzar a insertar datos |
| count | int | El número de bytes a copiar |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) método

Interpreta dos matrices tipadas especificadas como matrices crudas de bytes y copia datos de una a otra.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TSrc | El tipo de los elementos de la matriz de origen |
| TDst | El tipo de los elementos de la matriz de destino |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | La matriz de origen |
| srcOffset | int | Un desplazamiento de bytes en la matriz de origen donde comienza la copia |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | La matriz de destino |
| dstOffset | int | Un desplazamiento de bytes en la matriz de destino donde comenzar a insertar datos |
| count | int | El número de bytes a copiar |

## Buffer::BlockCopy(const SharedPtr\<ArrayBase\>\&, int, const SharedPtr\<ArrayBase\>\&, int, int) método

Interpreta dos matrices especificadas como matrices crudas de bytes y copia datos de una a otra.

```cpp
static void System::Buffer::BlockCopy(const SharedPtr<ArrayBase> &src, int srcOffset, const SharedPtr<ArrayBase> &dst, int dstOffset, int count)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | La matriz de origen |
| srcOffset | int | Un desplazamiento de bytes en la matriz de origen donde comienza la copia |
| dst | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | La matriz de destino |
| dstOffset | int | Un desplazamiento de bytes en la matriz de destino donde comenzar a insertar datos |
| count | int | El número de bytes a copiar |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) método

Interpreta dos matrices tipadas especificadas como matrices crudas de bytes y copia datos de una a otra.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TSrc | El tipo de los elementos de la vista de matriz de origen |
| TDst | El tipo de los elementos de la vista de matriz de destino |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | La vista de matriz de origen |
| srcOffset | int | Un desplazamiento de bytes en la vista de matriz de origen donde comienza la copia |
| dst | const System::Details::ArrayView\<TDst\>\& | La vista de matriz de destino |
| dstOffset | int | Un desplazamiento de bytes en la vista de matriz de destino donde comenzar a insertar datos |
| count | int | El número de bytes a copiar |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) método

Interpreta dos matrices tipadas especificadas como matrices crudas de bytes y copia datos de una a otra.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TSrc | El tipo de los elementos de la matriz de origen |
| TDst | El tipo de los elementos de la vista de matriz de destino |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | La matriz de origen |
| srcOffset | int | Un desplazamiento de bytes en la matriz de origen donde comienza la copia |
| dst | const System::Details::ArrayView\<TDst\>\& | La vista de matriz de destino |
| dstOffset | int | Un desplazamiento de bytes en la vista de matriz de destino donde comenzar a insertar datos |
| count | int | El número de bytes a copiar |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) método

Interpreta dos matrices tipadas especificadas como matrices crudas de bytes y copia datos de una a otra.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TSrc | El tipo de los elementos de la vista de matriz de origen |
| TDst | El tipo de los elementos de la matriz de destino |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | La vista de matriz de origen |
| srcOffset | int | Un desplazamiento de bytes en la vista de matriz de origen donde comienza la copia |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | La matriz de destino |
| dstOffset | int | Un desplazamiento de bytes en la matriz de destino donde comenzar a insertar datos |
| count | int | El número de bytes a copiar |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) método

Interpreta dos matrices tipadas especificadas como matrices crudas de bytes y copia datos de una a otra.

```cpp
template<typename TSrc,std::size_t,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TSrc | El tipo de los elementos de la pila de origen |
| NS | El tamaño de la pila de origen |
| TDst | El tipo de los elementos de la pila de destino |
| ND | El tamaño de la pila de destino |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | La pila de origen |
| srcOffset | int | Un desplazamiento de bytes en la pila de origen donde comienza la copia |
| dst | const System::Details::StackArray\<TDst, ND\>\& | La pila de destino |
| dstOffset | int | Un desplazamiento de bytes en la pila de destino donde comenzar a insertar datos |
| count | int | El número de bytes a copiar |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) método

Interpreta dos matrices tipadas especificadas como matrices crudas de bytes y copia datos de una a otra.

```cpp
template<typename TSrc,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TSrc | El tipo de los elementos de la matriz de origen |
| TDst | El tipo de los elementos de la pila de destino |
| ND | El tamaño de la pila de destino |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | La matriz de origen |
| srcOffset | int | Un desplazamiento de bytes en la matriz de origen donde comienza la copia |
| dst | const System::Details::StackArray\<TDst, ND\>\& | La pila de destino |
| dstOffset | int | Un desplazamiento de bytes en la pila de destino donde comenzar a insertar datos |
| count | int | El número de bytes a copiar |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) método

Interpreta dos matrices tipadas especificadas como matrices crudas de bytes y copia datos de una a otra.

```cpp
template<typename TSrc,std::size_t,typename TDst> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TSrc | El tipo de los elementos de la pila de origen |
| NS | El tamaño de la pila de origen |
| TDst | El tipo de los elementos de la matriz de destino |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | La pila de origen |
| srcOffset | int | Un desplazamiento de bytes en la pila de origen donde comienza la copia |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | La matriz de destino |
| dstOffset | int | Un desplazamiento de bytes en la matriz de destino donde comenzar a insertar datos |
| count | int | El número de bytes a copiar |

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Clase [Buffer](../)
* Clase [Array](../../array/)
* Clase [ArrayBase](../../arraybase/)
* Espacio de nombres [System](../../)
* Library [Aspose.Slides](../../../)