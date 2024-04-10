---
title: SortedSet()
second_title: Aspose.Slides for C++ API Reference
description: Creates empty set.
type: docs
weight: 1
url: /system.collections.generic/sortedset/sortedset/
---
## SortedSet::SortedSet() constructor


Creates empty set.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet()
```

## SortedSet::SortedSet(int) constructor


Creates empty set with specified capacity.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(int capacity)
```

## SortedSet::SortedSet(const SharedPtr\<IComparer\<T\>\>\&) constructor


Creates empty set that uses the specified equality comparer.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IComparer<T>> &comparer)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<T\>\>\& | Comparer object to associate with [SortedSet](../). |

## SortedSet::SortedSet(const SharedPtr\<IEnumerable\<T\>\>\&) constructor


Creates [SortedSet](../) based on enumerable values.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IEnumerable<T>> &items)
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SortedSet](../)
* Class [IComparer](../../icomparer/)
* Class [IEnumerable](../../ienumerable/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)