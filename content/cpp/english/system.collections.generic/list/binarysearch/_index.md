---
title: BinarySearch()
second_title: Aspose.Slides for C++ API Reference
description: Looks for item in a sorted list.
type: docs
weight: 339
url: /system.collections.generic/list/binarysearch/
---
## List::BinarySearch(const T\&) const method


Looks for item in a sorted list.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| item | const T\& | Item to look for. |

### Return Value

Index of the item in sorted list or complement of closest index.

## List::BinarySearch(const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const method


Looks for item in a sorted list.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| item | const T\& | Item to look for. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | Comparer to use. |

### Return Value

Index of the item in sorted list or complement of closest index.

## List::BinarySearch(int, int, const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const method


Looks for item in a sorted list.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(int index, int count, const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Range beginning. |
| count | int | Range size. |
| item | const T\& | Item to look for. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | Comparer to use. |

### Return Value

Index of the item in sorted list or complement of closest index.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../)
* Class [IComparer](../../icomparer/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)