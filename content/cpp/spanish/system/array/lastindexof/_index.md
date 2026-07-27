---
title: LastIndexOf()
second_title: Referencia de API de Aspose.Slides para C++
description: Determina el índice de la última aparición del elemento especificado en un rango de elementos del arreglo especificado por el índice de inicio y el número de elementos en el rango.
type: docs
weight: 703
url: /es/system/array/lastindexof/
---
## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) método

Determina el índice de la última aparición del elemento especificado en un rango de elementos del arreglo especificado por el índice de inicio y el número de elementos en el rango.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| ArrayType | Tipo de elementos en el arreglo de destino |
| ValueType | Tipo del elemento a buscar en el arreglo |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) para buscar el elemento especificado en |
| value | const [ValueType](../valuetype/)\& | Índice del elemento que se debe determinar |
| startIndex | int | [Index](../../index/) en el que se inicia la búsqueda |
| count | int | Número de elementos del rango en el que buscar |

### Valor devuelto

[Index](../../index/) de la última aparición del elemento especificado si se encuentra, de lo contrario -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) método

Determina el índice de la última aparición del elemento especificado en el arreglo a partir del índice especificado.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value, int startIndex)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| ArrayType | Tipo de elementos en el arreglo de destino |
| ValueType | Tipo del elemento a buscar en el arreglo |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) para buscar el elemento especificado en |
| value | const [ValueType](../valuetype/)\& | Índice del elemento que se debe determinar |
| startIndex | int | [Index](../../index/) en el que se inicia la búsqueda |

### Valor devuelto

[Index](../../index/) de la última aparición del elemento especificado si se encuentra, de lo contrario -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) método

Determina el índice de la última aparición del elemento especificado en el arreglo.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| ArrayType | Tipo de elementos en el arreglo de destino |
| ValueType | Tipo del elemento a buscar en el arreglo |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) para buscar el elemento especificado en |
| value | const [ValueType](../valuetype/)\& | Índice del elemento que se debe determinar |

### Valor devuelto

[Index](../../index/) de la última aparición del elemento especificado si se encuentra, de lo contrario -1

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Clase [Array](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)