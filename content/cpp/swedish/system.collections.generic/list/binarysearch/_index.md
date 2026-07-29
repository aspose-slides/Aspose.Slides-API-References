---
title: BinarySearch()
second_title: Aspose.Slides för C++ API-referens
description: Söker efter element i en sorterad lista.
type: docs
weight: 339
url: /sv/system.collections.generic/list/binarysearch/
---
## List::BinarySearch(const T\&) const metod

Söker efter element i en sorterad lista.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | const T\& | Element att söka efter. |

### Returvärde

[Index](../../../system/index/) of the item in sorted list or complement of closest index.

## List::BinarySearch(const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const metod

Söker efter element i en sorterad lista.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | const T\& | Element att söka efter. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) att använda. |

### Returvärde

[Index](../../../system/index/) of the item in sorted list or complement of closest index.

## List::BinarySearch(int, int, const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const metod

Söker efter element i en sorterad lista.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(int index, int count, const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | [Range](../../../system/range/) början. |
| count | int | [Range](../../../system/range/) storlek. |
| item | const T\& | Element att söka efter. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) att använda. |

### Returvärde

[Index](../../../system/index/) of the item in sorted list or complement of closest index.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [List](../)
* Klass [IComparer](../../icomparer/)
* Namnrymd [System::Collections::Generic](../../)
* Bibliotek [Aspose.Slides](../../../)