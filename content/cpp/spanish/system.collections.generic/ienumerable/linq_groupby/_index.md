---
title: LINQ_GroupBy()
second_title: Referencia de la API de Aspose.Slides para C++
description: Agrupa los elementos de una secuencia.
type: docs
weight: 287
url: /es/system.collections.generic/ienumerable/linq_groupby/
---
## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>) método

Agrupa los elementos de una secuencia.

```cpp
template<typename Key> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, T>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Key | El tipo de la clave devuelta por keyPredicate |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | Una función para extraer la clave de cada elemento. |

### Valor devuelto

Un [IEnumerable](../) que contiene una secuencia de objetos y una clave

## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>, System::Func\<T, Element\>) método

Agrupa los elementos de una secuencia.

```cpp
template<typename Key,typename Element> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate, System::Func<T, Element> elementSelector)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Key | El tipo de la clave devuelta por keyPredicate |
| Element | El tipo del elemento devuelto por elementSelector |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | Una función para extraer la clave de cada elemento. |
| elementSelector | [System::Func](../../../system/func/)\<T, Element\> | Una función para extraer valor clave de cada elemento. |

### Valor devuelto

Un [IEnumerable](../) que contiene una secuencia de objetos y una clave

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>) método




```cpp
template<typename Key> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Source>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate)
```

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>, System::Func\<Source, Element\>) método




```cpp
template<typename Key,typename Element> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate, System::Func<Source, Element> elementSelector)
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IEnumerable](../)
* Clase [IGrouping](../../../system.linq/igrouping/)
* Clase [Func](../../../system/func/)
* Espacio de nombres [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)