---
title: LINQ_OrderBy()
second_title: Referencia de API de Aspose.Slides para C++
description: Ordena los elementos de una secuencia en orden ascendente según los valores de clave seleccionados por keySelector.
type: docs
weight: 209
url: /es/system.collections.generic/ienumerable/linq_orderby/
---
## IEnumerable::LINQ_OrderBy(const Func\<T, Key\>\&) método


Ordena los elementos de una secuencia en orden ascendente según los valores de clave seleccionados por keySelector.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<T, Key> &keySelector)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| keySelector | Una función para extraer una clave de un elemento. |

### Valor devuelto

Un IOrderedEnumerable cuyos elementos están ordenados según una clave

## IEnumerable::LINQ_OrderBy(const Func\<Source, Key\>\&) método




```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<Source, Key> &keySelector)
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Clase [Func](../../../system/func/)
* Clase [IEnumerable](../)
* Espacio de nombres [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)