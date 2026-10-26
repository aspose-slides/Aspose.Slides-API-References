---
title: SortedList()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit une liste vide.
type: docs
weight: 1
url: /fr/system.collections.generic/sortedlist/sortedlist/
---
## SortedList::SortedList() constructeur

Construit une liste vide.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList()
```

## SortedList::SortedList(const SharedPtr\<IComparer\<TKey\>\>\&) constructeur

Construit une liste vide.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IComparer<TKey>> &comparer)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) à utiliser. |

## SortedList::SortedList(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) constructeur

Constructeur de copie.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../../dictionary/) pour copier les données depuis. |

## SortedList::SortedList(const map_t\&) constructeur

Constructeur de copie.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const map_t &map)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | Map à copier les données depuis. |

## SortedList::SortedList(int) constructeur

Construit une liste vide.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(int capacity)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| capacity | int | Nombre d'éléments à réserver. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [map_t](../map_t/)
* Class [SortedList](../)
* Class [IComparer](../../icomparer/)
* Class [IDictionary](../../idictionary/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)