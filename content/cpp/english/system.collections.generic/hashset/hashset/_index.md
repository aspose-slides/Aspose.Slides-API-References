---
title: HashSet()
second_title: Aspose.Slides for C++ API Reference
description: Creates empty set.
type: docs
weight: 1
url: /system.collections.generic/hashset/hashset/
---
## HashSet::HashSet() constructor


Creates empty set.

```cpp
System::Collections::Generic::HashSet<T>::HashSet()
```

## HashSet::HashSet(int) constructor


Creates empty set with specified capacity.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(int capacity)
```

## HashSet::HashSet(const SharedPtr\<IEqualityComparer\<T\>\>\&) constructor


Creates empty set that uses the specified equality comparer.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEqualityComparer<T>> &comparer)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<T\>\>\& | Comparer object to associate with hashset. |

## HashSet::HashSet(const SharedPtr\<IEnumerable\<T\>\>\&) constructor


Creates hashset based on enumerable values.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEnumerable<T>> &items)
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HashSet](../)
* Class [IEqualityComparer](../../iequalitycomparer/)
* Class [IEnumerable](../../ienumerable/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)