---
title: BinarySearch()
second_title: Aspose.Slides pro C++ API Reference
description: Hledá položku ve seřazeném seznamu.
type: docs
weight: 339
url: /cs/system.collections.generic/list/binarysearch/
---
## List::BinarySearch(const T\&) const metoda

Hledá položku ve seřazeném seznamu.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| item | const T\& | Položka k hledání. |

### Návratová hodnota

[Index](../../../system/index/) položky v seřazeném seznamu nebo doplněk nejbližšího indexu.

## List::BinarySearch(const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const metoda


Hledá položku ve seřazeném seznamu.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| item | const T\& | Položka k hledání. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) k použití. |

### Návratová hodnota

[Index](../../../system/index/) položky v seřazeném seznamu nebo doplněk nejbližšího indexu.

## List::BinarySearch(int, int, const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const metoda


Hledá položku ve seřazeném seznamu.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(int index, int count, const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | [Range](../../../system/range/) začátek. |
| count | int | [Range](../../../system/range/) velikost. |
| item | const T\& | Položka k hledání. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) k použití. |

### Návratová hodnota

[Index](../../../system/index/) položky v seřazeném seznamu nebo doplněk nejbližšího indexu.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../)
* Class [IComparer](../../icomparer/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)