---
title: LINQ_ThenBy()
second_title: Aspose.Slides for C++ API Reference
description: Performs a subsequent ordering of the elements in a sequence in ascending order according to a key.
type: docs
weight: 27
url: /system.linq/iorderedenumerable/linq_thenby/
---
## IOrderedEnumerable::LINQ_ThenBy(const Func\<T, Key\>\&) method


Performs a subsequent ordering of the elements in a sequence in ascending order according to a key.

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<T>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<T, Key> &keySelector)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Key | The type of the key returned by keySelector. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| keySelector | const [Func](../../../system/func/)\<T, Key\>\& | A function to extract a key from each element. |

### Return Value

[System::Linq::IOrderedEnumerable](../) whose elements are sorted according to a key.

## IOrderedEnumerable::LINQ_ThenBy(const Func\<Source, Key\>\&) method




```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<Source>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<Source, Key> &keySelector)
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOrderedEnumerable](../)
* Class [Func](../../../system/func/)
* Namespace [System::Linq](../../)
* Library [Aspose.Slides](../../../)