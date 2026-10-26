---
title: BinarySearch()
second_title: Referencia de API de Aspose.Slides para C++
description: Busca el elemento en una lista ordenada.
type: docs
weight: 339
url: /es/system.collections.generic/list/binarysearch/
---
## List::BinarySearch(const T\&) const método

Busca el elemento en una lista ordenada.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | const T\& | Elemento a buscar. |

### Valor devuelto

[Index](../../../system/index/) del elemento en la lista ordenada o el complemento del índice más cercano.

## List::BinarySearch(const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const método

Busca el elemento en una lista ordenada.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | const T\& | Elemento a buscar. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) para usar. |

### Valor devuelto

[Index](../../../system/index/) del elemento en la lista ordenada o el complemento del índice más cercano.

## List::BinarySearch(int, int, const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const método

Busca el elemento en una lista ordenada.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(int index, int count, const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | [Range](../../../system/range/) del inicio. |
| count | int | [Range](../../../system/range/) tamaño. |
| item | const T\& | Elemento a buscar. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) para usar. |

### Valor devuelto

[Index](../../../system/index/) del elemento en la lista ordenada o el complemento del índice más cercano.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [List](../)
* Clase [IComparer](../../icomparer/)
* Espacio de nombres [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)