---
title: BinarySearch()
second_title: Aspose.Slides voor C++ API-referentie
description: Zoekt naar een item in een gesorteerde lijst.
type: docs
weight: 339
url: /nl/system.collections.generic/list/binarysearch/
---
## List::BinarySearch(const T\&) const methode

Zoekt naar een item in een gesorteerde lijst.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item) const
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | const T\& | Item om te zoeken. |

### Retourwaarde

[Index](../../../system/index/) van het item in de gesorteerde lijst of complement van de dichtstbijzijnde index.

## List::BinarySearch(const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const methode

Zoekt naar een item in een gesorteerde lijst.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | const T\& | Item om te zoeken. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) te gebruiken. |

### Retourwaarde

[Index](../../../system/index/) van het item in de gesorteerde lijst of complement van de dichtstbijzijnde index.

## List::BinarySearch(int, int, const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const methode

Zoekt naar een item in een gesorteerde lijst.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(int index, int count, const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | [Range](../../../system/range/) begin. |
| count | int | [Range](../../../system/range/) grootte. |
| item | const T\& | Item om te zoeken. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) te gebruiken. |

### Retourwaarde

[Index](../../../system/index/) van het item in de gesorteerde lijst of complement van de dichtstbijzijnde index.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [List](../)
* Klasse [IComparer](../../icomparer/)
* Namespace [System::Collections::Generic](../../)
* Bibliotheek [Aspose.Slides](../../../)