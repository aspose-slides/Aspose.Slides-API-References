---
title: BinarySearch()
second_title: Odwołanie do API Aspose.Slides dla C++
description: Wyszukuje element w posortowanej liście.
type: docs
weight: 339
url: /pl/system.collections.generic/list/binarysearch/
---
## List::BinarySearch(const T\&) const method

Wyszukuje element w posortowanej liście.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| item | const T\& | Element do wyszukania. |

### Wartość zwracana

[Index](../../../system/index/) of the item in sorted list or complement of closest index.

## List::BinarySearch(const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const method

Wyszukuje element w posortowanej liście.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| item | const T\& | Element do wyszukania. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) do użycia. |

### Wartość zwracana

[Index](../../../system/index/) of the item in sorted list or complement of closest index.

## List::BinarySearch(int, int, const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const method

Wyszukuje element w posortowanej liście.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(int index, int count, const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | [Range](../../../system/range/) początek. |
| count | int | [Range](../../../system/range/) rozmiar. |
| item | const T\& | Element do wyszukania. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) do użycia. |

### Wartość zwracana

[Index](../../../system/index/) of the item in sorted list or complement of closest index.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [List](../)
* Klasa [IComparer](../../icomparer/)
* Przestrzeń nazw [System::Collections::Generic](../../)
* Biblioteka [Aspose.Slides](../../../)