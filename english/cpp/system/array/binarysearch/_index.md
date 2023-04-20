---
title: BinarySearch()
second_title: Aspose.Slides for C++ API Reference
description: Performs binary search in the sorted array.
type: docs
weight: 586
url: /cpp/system/array/binarysearch/
---
## Array::BinarySearch(System::ArrayPtr\<T\>, const T\&) method


Performs binary search in the sorted array.

```cpp
static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const T &item)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | Sorted array to perform search in |
| item | const T\& | An item to search for |

### Return Value

Index of the searched item if one is found, otherwise, a negative integer that is the bitwise complement of the index of the next item greater than searched item or, if there is no greater item, the bitwise complement of the number of elements in the array.

## Array::BinarySearch(System::ArrayPtr\<T\>, const Y\&, const SharedPtr\<Collections::Generic::IComparer\<Z\>\>\&) method


NOT IMPLEMENTED.

```cpp
template<typename Y,typename Z> static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const Y &item, const SharedPtr<Collections::Generic::IComparer<Z>> &comparer)
```


## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Array](../)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)