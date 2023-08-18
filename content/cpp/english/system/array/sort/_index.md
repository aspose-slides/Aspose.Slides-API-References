---
title: Sort()
second_title: Aspose.Slides for C++ API Reference
description: Sorts elements in the specified array using default comparer.
type: docs
weight: 703
url: /system/array/sort/
---
## Array::Sort(const ArrayPtr\<Type\>\&) method


Sorts elements in the specified array using default comparer.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Targed array |

## Array::Sort(const ArrayPtr\<Type\>\&, int, int) method


Sorts a range of elements in the specified array using default comparer.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, int startIndex, int count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Targed array |
| startIndex | int | The index designating the beginning of the range of elements to sort |
| count | int | The size of the range of elements to sort |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) method


Sorts elements in the specified array using specified comparer.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Targed array |
| comparator | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<T\>\>\& | IComparer<T> object used to compare elements of the array |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<Y\>\>\&) method


NOT IMPLEMENTED.

```cpp
template<typename Type,typename Y> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<Y>> &comparator)
```


## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&) method


Sorts two arrays one containing keys and the other - corresponding items, based on the values of array containing keys, elements of which are compared using operator<.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TKey | The type of the elements in the **keys** array |
| TValue | the type of the elements in the **items** array |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) that contains key values |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) that contains items that are mapped to the key values in **keys** array |

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&, int, int) method


Sorts two arrays one containing keys and the other - corresponding items, based on the values of array containing keys, elements of which are compared using default comparer.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items, int index, int length)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TKey | The type of the elements in the **keys** array |
| TValue | the type of the elements in the **items** array |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) that contains key values |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) that contains items that are mapped to the key values in **keys** array |
| index | int | The index designating the beginning of the range to sort |
| length | int | The number of elements in the range to sort |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [Type](../../object/type/)
* Class [Array](../)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)