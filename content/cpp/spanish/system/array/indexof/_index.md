---
title: IndexOf()
second_title: Referencia de la API de Aspose.Slides para C++
description: Determina el índice de la primera aparición del elemento especificado en el array.
type: docs
weight: 131
url: /es/system/array/indexof/
---
## Array::IndexOf(const T\&) const método

Determina el índice de la primera aparición del elemento especificado en el array.

```cpp
virtual int System::Array<T>::IndexOf(const T &item) const override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | const T\& | Índice del elemento que se debe determinar |

### Valor de retorno

[Index](../../index/) de la primera aparición del elemento especificado si se encuentra el elemento, de lo contrario -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) método

Determina el índice de la primera aparición del elemento especificado en el array.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| ArrayType | Tipo de los elementos en el array objetivo |
| ValueType | tipo del elemento a buscar en el array |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) para buscar el elemento especificado en |
| value | const [ValueType](../valuetype/)\& | Índice del elemento que se debe determinar |

### Valor de retorno

[Index](../../index/) de la primera aparición del elemento especificado si se encuentra el elemento, de lo contrario -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) método

Determina el índice de la primera aparición del elemento especificado en el array a partir del índice especificado.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| ArrayType | Tipo de los elementos en el array objetivo |
| ValueType | tipo del elemento a buscar en el array |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) para buscar el elemento especificado en |
| value | const [ValueType](../valuetype/)\& | Índice del elemento que se debe determinar |
| startIndex | int | [Index](../../index/) en el que se inicia la búsqueda |

### Valor de retorno

[Index](../../index/) de la primera aparición del elemento especificado si se encuentra el elemento, de lo contrario -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) método

Determina el índice de la primera aparición del elemento especificado en un rango de elementos del array definido por el índice de inicio y el número de elementos en el rango.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| ArrayType | Tipo de los elementos en el array objetivo |
| ValueType | tipo del elemento a buscar en el array |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) para buscar el elemento especificado en |
| value | const [ValueType](../valuetype/)\& | Índice del elemento que se debe determinar |
| startIndex | int | [Index](../../index/) en el que se inicia la búsqueda |
| count | int | Número de elementos del rango en el que buscar |

### Valor de retorno

[Index](../../index/) de la primera aparición del elemento especificado si se encuentra el elemento, de lo contrario -1

## Véase también

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)