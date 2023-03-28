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

## See Also

* Class [Dictionary](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)
## Dictionary::Dictionary(const [map_t](../map_t/)\&) constructor


Copies data from map.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const map_t &map)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | Map to copy data from. |

## See Also

* Typedef [map_t](../map_t/)
* Class [Dictionary](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)
## Dictionary::Dictionary(int) constructor


Overload which corresponds to creating pre-allocated dictionary; does no allocation, actually.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| capacity | int | Capacity to allocate; ignored. |

## See Also

* Class [Dictionary](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)
## Dictionary::Dictionary(const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\&) constructor


Copy constructor.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../) to copy data from. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../idictionary/)
* Class [Dictionary](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)
## Dictionary::Dictionary(const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\&, const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\&) constructor


Copy constructor.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | Source dictionary. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | Comparer object to use. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../idictionary/)
* Class [IEqualityComparer](../../iequalitycomparer/)
* Class [Dictionary](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)
## Dictionary::Dictionary(const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\&) constructor


Creates empty dictionary.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IEqualityComparer<TKey>> &comparer)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | Comparer to use. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEqualityComparer](../../iequalitycomparer/)
* Class [Dictionary](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)
## Dictionary::Dictionary(int, const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\&) constructor


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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEqualityComparer](../../iequalitycomparer/)
* Class [Dictionary](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)
