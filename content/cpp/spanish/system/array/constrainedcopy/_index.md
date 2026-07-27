---
title: ConstrainedCopy()
second_title: Referencia de API de Aspose.Slides para C++
description: Copia un rango de elementos de un System.Array que comienza en la fuente especificada.
type: docs
weight: 716
url: /es/system/array/constrainedcopy/
---
## Array::ConstrainedCopy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) método


Copia un rango de elementos de un [System.Array](../) que comienza en la fuente especificada.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::ConstrainedCopy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
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

## Observaciones

IMPLEMENTACIÓN CRUDA TEMPORAL SIN NINGÚN DESHECHO!

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Clase [Array](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)