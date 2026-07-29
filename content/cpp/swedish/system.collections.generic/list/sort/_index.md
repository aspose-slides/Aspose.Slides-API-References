---
title: Sort()
second_title: Aspose.Slides för C++ API-referens
description: Sorterar element i listan.
type: docs
weight: 521
url: /sv/system.collections.generic/list/sort/
---
## List::Sort(const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) metod

Sorterar element i listan.

```cpp
void System::Collections::Generic::List<T>::Sort(const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| comparator | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | Komparator att använda. |

## List::Sort() metod

Sorterar element i listan med standardkomparator.

```cpp
void System::Collections::Generic::List<T>::Sort()
```

## List::Sort(int, int, SharedPtr\<System::Collections::Generic::IComparer\<T\>\>) metod

Sorterar element i en del av listan.

```cpp
void System::Collections::Generic::List<T>::Sort(int index, int count, SharedPtr<System::Collections::Generic::IComparer<T>> comparator)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Startindex för del. |
| count | int | Storlek på del. |
| comparator | [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\> | Komparator att använda. |

## List::Sort(Comparison\<T\>, bool) metod

Sorterar element i listan.

```cpp
void System::Collections::Generic::List<T>::Sort(Comparison<T> comparison, bool)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| comparison | [Comparison](../../../system/comparison/)\<T\> | [Comparison](../../../system/comparison/) att använda. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IComparer](../../icomparer/)
* Klass [List](../)
* Klass [Comparison](../../../system/comparison/)
* Namnrymd [System::Collections::Generic](../../)
* Bibliotek [Aspose.Slides](../../../)