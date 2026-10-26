---
title: BinarySearch()
second_title: Referencia de la API de Aspose.Slides para C++
description: Realiza una búsqueda binaria en el arreglo ordenado.
type: docs
weight: 612
url: /es/system/array/binarysearch/
---
## Array::BinarySearch(System::ArrayPtr\<T\>, const T\&) método

Realiza una búsqueda binaria en el arreglo ordenado.

```cpp
static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const T &item)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | Arreglo ordenado en el que se realiza la búsqueda |
| item | const T\& | Un elemento a buscar |

### Valor de retorno

[Index](../../index/) del elemento buscado si se encuentra, de lo contrario, un entero negativo que es el complemento a nivel de bits del índice del siguiente elemento mayor que el elemento buscado o, si no hay un elemento mayor, el complemento a nivel de bits del número de elementos en el arreglo.

## Array::BinarySearch(System::ArrayPtr\<T\>, const Y\&, const SharedPtr\<Collections::Generic::IComparer\<Z\>\>\&) método

NO IMPLEMENTADO.

```cpp
template<typename Y,typename Z> static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const Y &item, const SharedPtr<Collections::Generic::IComparer<Z>> &comparer)
```

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Clase [Array](../)
* Clase [IComparer](../../../system.collections.generic/icomparer/)
* Espacio de nombres [System](../../)
* Library [Aspose.Slides](../../../)