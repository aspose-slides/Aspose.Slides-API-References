---
title: LINQ_OrderBy()
second_title: Aspose.Slides for C++ API Reference
description: Sorts the elements of a sequence in ascending order according to the key values selected by keySelector.
type: docs
weight: 209
url: /system.collections.generic/ienumerable/linq_orderby/
---
## IEnumerable::LINQ_OrderBy(const Func\<T, Key\>\&) method


Sorts the elements of a sequence in ascending order according to the key values selected by keySelector.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<T, Key> &keySelector)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| keySelector | A function to extract a key from an element. |

### Return Value

An IOrderedEnumerable whose elements are sorted according to a key

## IEnumerable::LINQ_OrderBy(const Func\<Source, Key\>\&) method




```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<Source, Key> &keySelector)
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)