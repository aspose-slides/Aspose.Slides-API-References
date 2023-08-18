---
title: LINQ_OrderByDescending()
second_title: Aspose.Slides for C++ API Reference
description: Sorts the elements of a sequence in descending order according to the key values selected by keySelector.
type: docs
weight: 196
url: /system.collections.generic/ienumerable/linq_orderbydescending/
---
## IEnumerable::LINQ_OrderByDescending(const Func\<T, Key\>\&) method


Sorts the elements of a sequence in descending order according to the key values selected by keySelector.

```cpp
template<typename Key> SharedPtr<IEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<T, Key> &keySelector)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| keySelector | A function to extract a key from an element. |

### Return Value

An [IEnumerable](../) whose elements are sorted to the descending order of the key

## IEnumerable::LINQ_OrderByDescending(const Func\<Source, Key\>\&) method




```cpp
template<typename Key> SharedPtr<IEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<Source, Key> &keySelector)
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [Func](../../../system/func/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)