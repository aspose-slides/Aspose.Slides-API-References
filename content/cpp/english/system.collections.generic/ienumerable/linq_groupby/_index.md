---
title: LINQ_GroupBy()
second_title: Aspose.Slides for C++ API Reference
description: Groups the elements of a sequence.
type: docs
weight: 287
url: /system.collections.generic/ienumerable/linq_groupby/
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

## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>, System::Func\<T, Element\>) method


Groups the elements of a sequence.

```cpp
template<typename Key,typename Element> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate, System::Func<T, Element> elementSelector)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Key | The type of the key returned by keyPredicate |
| Element | The type of the element returned by elementSelector |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | A function to extract the key for each element. |
| elementSelector | [System::Func](../../../system/func/)\<T, Element\> | A function to extract value key for each element. |

### Return Value

An [IEnumerable](../) that contains a sequence of objects and a key

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>) method




```cpp
template<typename Key> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Source>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate)
```

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>, System::Func\<Source, Element\>) method




```cpp
template<typename Key,typename Element> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate, System::Func<Source, Element> elementSelector)
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [IGrouping](../../../system.linq/igrouping/)
* Class [Func](../../../system/func/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)