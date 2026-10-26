---
title: LINQ_OrderByDescending()
second_title: Referencia de API de Aspose.Slides para C++
description: Ordena los elementos de una secuencia en orden descendente según los valores de clave seleccionados por keySelector.
type: docs
weight: 222
url: /es/system.collections.generic/ienumerable/linq_orderbydescending/
---
## IEnumerable::LINQ_OrderByDescending(const Func\<T, Key\>\&) method

Ordena los elementos de una secuencia en orden descendente según los valores de clave seleccionados por keySelector.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<T, Key> &keySelector)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| keySelector | Una función para extraer una clave de un elemento. |

### Valor devuelto

Un IOrderedEnumerable cuyos elementos están ordenados en orden descendente según la clave

## IEnumerable::LINQ_OrderByDescending(const Func\<Source, Key\>\&) method




```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<Source, Key> &keySelector)
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)