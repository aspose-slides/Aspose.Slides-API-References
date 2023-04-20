---
title: Dictionary()
second_title: Aspose.Slides for C++ API Reference
description: Creates empty dictionary.
type: docs
weight: 1
url: /cpp/system.collections.generic/dictionary/dictionary/
---
## Dictionary::Dictionary() constructor


Creates empty dictionary.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary()
```

## Dictionary::Dictionary(const map_t\&) constructor


Copies data from map.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const map_t &map)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | Map to copy data from. |

## Dictionary::Dictionary(int) constructor


Overload which corresponds to creating pre-allocated dictionary; does no allocation, actually.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| capacity | int | Capacity to allocate; ignored. |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) constructor


Copy constructor.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../) to copy data from. |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) constructor


Copy constructor.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | Source dictionary. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | Comparer object to use. |

## Dictionary::Dictionary(const SharedPtr\<IEqualityComparer\<TKey\>\>\&) constructor


Creates empty dictionary.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IEqualityComparer<TKey>> &comparer)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | Comparer to use. |

## Dictionary::Dictionary(int, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) constructor


Creates empty dictionary.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| capacity | int | [Dictionary](../) capacity after creation; ignored. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | Comparer to use. |

## See Also

* Typedef [map_t](../map_t/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Dictionary](../)
* Class [IDictionary](../../idictionary/)
* Class [IEqualityComparer](../../iequalitycomparer/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)