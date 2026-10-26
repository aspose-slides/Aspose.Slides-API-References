---
title: SortedSet()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en tom uppsättning.
type: docs
weight: 1
url: /sv/system.collections.generic/sortedset/sortedset/
---
## SortedSet::SortedSet() konstruktor


Skapar en tom uppsättning.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet()
```

## SortedSet::SortedSet(int) konstruktor


Skapar en tom uppsättning med angiven kapacitet.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(int capacity)
```

## SortedSet::SortedSet(const SharedPtr\<IComparer\<T\>\>\&) konstruktor


Skapar en tom uppsättning som använder den angivna likhetsjämföraren.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IComparer<T>> &comparer)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) objekt att associera med [SortedSet](../). |

## SortedSet::SortedSet(const SharedPtr\<IEnumerable\<T\>\>\&) konstruktor


Skapar [SortedSet](../) baserat på uppräkningsvärden.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IEnumerable<T>> &items)
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [SortedSet](../)
* Klass [IComparer](../../icomparer/)
* Klass [IEnumerable](../../ienumerable/)
* Namnrymd [System::Collections::Generic](../../)
* Bibliotek [Aspose.Slides](../../../)