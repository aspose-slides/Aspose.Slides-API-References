---
title: SortedList()
second_title: Referencia de API de Aspose.Slides para C++
description: Construye una lista vacía.
type: docs
weight: 1
url: /es/system.collections.generic/sortedlist/sortedlist/
---
## SortedList::SortedList() constructor

Construye una lista vacía.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList()
```

## SortedList::SortedList(const SharedPtr\<IComparer\<TKey\>\>\&) constructor

Construye una lista vacía.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IComparer<TKey>> &comparer)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) para usar. |

## SortedList::SortedList(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) constructor

Constructor de copia.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../../dictionary/) para copiar datos de. |

## SortedList::SortedList(const map_t\&) constructor

Constructor de copia.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const map_t &map)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | Mapa del que copiar datos. |

## SortedList::SortedList(int) constructor

Construye una lista vacía.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(int capacity)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| capacity | int | Número de elementos a reservar. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [map_t](../map_t/)
* Clase [SortedList](../)
* Clase [IComparer](../../icomparer/)
* Clase [IDictionary](../../idictionary/)
* Espacio de nombres [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)