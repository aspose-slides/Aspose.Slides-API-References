---
title: SortedSet()
second_title: Aspose.Slides pro C++ referenční příručku API
description: Vytvoří prázdnou množinu.
type: docs
weight: 1
url: /cs/system.collections.generic/sortedset/sortedset/
---
## SortedSet::SortedSet() konstruktor

Vytvoří prázdnou množinu.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet()
```

## SortedSet::SortedSet(int) konstruktor

Vytvoří prázdnou množinu se zadanou kapacitou.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(int capacity)
```

## SortedSet::SortedSet(const SharedPtr\<IComparer\<T\>\>\&) konstruktor

Vytvoří prázdnou množinu, která používá zadaný porovnávač rovnosti.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IComparer<T>> &comparer)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) objekt k přiřazení k [SortedSet](../). |

## SortedSet::SortedSet(const SharedPtr\<IEnumerable\<T\>\>\&) konstruktor

Vytvoří [SortedSet](../) na základě hodnot enumerable.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IEnumerable<T>> &items)
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SortedSet](../)
* Class [IComparer](../../icomparer/)
* Class [IEnumerable](../../ienumerable/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)