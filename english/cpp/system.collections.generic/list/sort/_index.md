---
title: Sort()
second_title: Aspose.Slides for C++ API Reference
description: Sorts elements in the list.
type: docs
weight: 521
url: /cpp/system.collections.generic/list/sort/
---
## List::Sort(const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\&) method


Sorts elements in the list.

```cpp
void System::Collections::Generic::List<T>::Sort(const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| comparator | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | Comparator to use. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComparer](../../icomparer/)
* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)
## List::Sort() method


Sorts elements in the list using default comparator.

```cpp
void System::Collections::Generic::List<T>::Sort()
```

## See Also

* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)
## List::Sort(int, int, [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>) method


Sorts elements in the list slice.

```cpp
void System::Collections::Generic::List<T>::Sort(int index, int count, SharedPtr<System::Collections::Generic::IComparer<T>> comparator)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Slice beginning index. |
| count | int | Slice size. |
| comparator | [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\> | Comparator to use. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComparer](../../icomparer/)
* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)
## List::Sort([Comparison](../../../system/comparison/)\<T\>, **bool**) method


Sorts elements in the list.

```cpp
void System::Collections::Generic::List<T>::Sort(Comparison<T> comparison, bool)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| comparison | [Comparison](../../../system/comparison/)\<T\> | [Comparison](../../../system/comparison/) to use. |

## See Also

* Class [Comparison](../../../system/comparison/)
* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)
