---
title: CopyTo()
second_title: Referencia de la API de Aspose.Slides para C++
description: Copia los elementos de la lista en los elementos de una matriz existente.
type: docs
weight: 209
url: /es/system.collections.generic/list/copyto/
---
## List::CopyTo(System::ArrayPtr\<T\>, int) method


Copia los elementos de la lista en los elementos de una matriz existente.

```cpp
void System::Collections::Generic::List<T>::CopyTo(System::ArrayPtr<T> array, int arrayIndex) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<T\> | Matriz de destino. |
| arrayIndex | int | Índice inicial de la matriz de destino. |

## List::CopyTo(const System::ArrayPtr\<T\>\&) method


Copia todos los elementos en los elementos de una matriz existente.

```cpp
void System::Collections::Generic::List<T>::CopyTo(const System::ArrayPtr<T> &array)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) para copiar los elementos. |

## List::CopyTo(int, const System::ArrayPtr\<T\>\&, int, int) method


Copia los elementos a partir del índice especificado en los elementos de una matriz existente.

```cpp
void System::Collections::Generic::List<T>::CopyTo(int index, const System::ArrayPtr<T> &array, int arrayIndex, int count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Un índice basado en cero del elemento en la lista representada por el objeto actual desde el cual comenzar a copiar |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) para copiar los elementos. |
| arrayIndex | int | Posición inicial en la matriz de destino. |
| count | int | Número de elementos a copiar. |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [List](../)
* Espacio de nombres [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)