---
title: SortedSet()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un conjunto vacío.
type: docs
weight: 1
url: /es/system.collections.generic/sortedset/sortedset/
---
## SortedSet::SortedSet() constructor

Crea un conjunto vacío.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet()
```

## SortedSet::SortedSet(int) constructor

Crea un conjunto vacío con la capacidad especificada.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(int capacity)
```

## SortedSet::SortedSet(const SharedPtr\<IComparer\<T\>\>\&) constructor

Crea un conjunto vacío que utiliza el comparador de igualdad especificado.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IComparer<T>> &comparer)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) objeto para asociar con [SortedSet](../). |

## SortedSet::SortedSet(const SharedPtr\<IEnumerable\<T\>\>\&) constructor

Crea [SortedSet](../) basándose en valores enumerables.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IEnumerable<T>> &items)
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [SortedSet](../)
* Clase [IComparer](../../icomparer/)
* Clase [IEnumerable](../../ienumerable/)
* Espacio de nombres [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)