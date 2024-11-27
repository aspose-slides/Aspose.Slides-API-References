---
title: SortedList()
second_title: Aspose.Slides for C++ API Reference
description: Constructs empty list.
type: docs
weight: 1
url: /system.collections.generic/sortedlist/sortedlist/
---
## SortedList::SortedList() constructor


Constructs empty list.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList()
```

## SortedList::SortedList(const SharedPtr\<IComparer\<TKey\>\>\&) constructor


Constructs empty list.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IComparer<TKey>> &comparer)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) to use. |

## SortedList::SortedList(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) constructor


Copy constructor.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IDictionary<TKey, TValue>> &src)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../../dictionary/) to copy data from. |

## SortedList::SortedList(const map_t\&) constructor


Copy constructor.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const map_t &map)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | Map tp copy data from. |

## SortedList::SortedList(int) constructor


Constructs empty list.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(int capacity)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| capacity | int | Number of elements to reserve. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [map_t](../map_t/)
* Class [SortedList](../)
* Class [IComparer](../../icomparer/)
* Class [IDictionary](../../idictionary/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)