---
title: HashSet()
second_title: Referencia de la API de Aspose.Slides para C++
description: Información RTTI.
type: docs
weight: 1
url: /es/system.collections.generic/hashset/hashset/
---
## HashSet::HashSet() constructor


RTTI information.

```cpp
System::Collections::Generic::HashSet<T>::HashSet()
```

## Observaciones


Crea un conjunto vacío. 
## HashSet::HashSet(int) constructor


Crea un conjunto vacío con la capacidad especificada.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(int capacity)
```

## HashSet::HashSet(const SharedPtr\<IEqualityComparer\<T\>\>\&) constructor


Crea un conjunto vacío que utiliza el comparador de igualdad especificado.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEqualityComparer<T>> &comparer)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<T\>\>\& | [Comparer](../../comparer/) objeto para asociar con hashset. |

## HashSet::HashSet(const SharedPtr\<IEnumerable\<T\>\>\&) constructor


Crea un hashset basado en valores enumerables.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEnumerable<T>> &items)
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [HashSet](../)
* Clase [IEqualityComparer](../../iequalitycomparer/)
* Clase [IEnumerable](../../ienumerable/)
* Espacio de nombres [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)