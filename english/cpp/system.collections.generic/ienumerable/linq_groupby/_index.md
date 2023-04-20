---
title: LINQ_GroupBy()
second_title: Aspose.Slides for C++ API Reference
description: Groups the elements of a sequence.
type: docs
weight: 248
url: /cpp/system.collections.generic/ienumerable/linq_groupby/
---
## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>) method


Groups the elements of a sequence.

```cpp
template<typename Key> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, T>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Key | The type of the key returned by keyPredicate |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | A function to extract the key for each element. |

### Return Value

An [IEnumerable](../) that contains a sequence of objects and a key

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>) method




```cpp
template<typename Key> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Source>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate)
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [IGrouping](../../../system.linq/igrouping/)
* Class [Func](../../../system/func/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)