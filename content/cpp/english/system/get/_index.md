---
title: Get()
second_title: Aspose.Slides for C++ API Reference
description: Function to get N-th element of tuple given. Overload for base object.
type: docs
weight: 2406
url: /system/get/
---
## System::Get(const SharedPtr\<Object\>\&) function


Function to get N-th element of tuple given. Overload for base object.

```cpp
template<std::size_t> auto System::Get(const SharedPtr<Object> &object)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| N | element index. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | object to inspect. |

### Return Value

value of N-th tuple element casted to object.

## System::Get(const T\&) function


Function to get N-th element of tuple given. Overload for objects with Deconstruct method.

```cpp
template<std::size_t,typename T> auto System::Get(const T &object)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| N | element index. |
| T | type of inspected object. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| object | const T\& | object to inspect. |

### Return Value

value of N-th tuple element.

## System::Get(const SharedPtr\<T\>\&) function


Function to get N-th element of tuple given. Overload for shared pointers.

```cpp
template<std::size_t,typename T> auto System::Get(const SharedPtr<T> &pointer)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| N | element index. |
| T | type of inspected object. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | object to inspect. |

### Return Value

value of N-th tuple element.

## System::Get(T\&, const Index\&) function


Implementation for collection[index] expressions.

```cpp
template<typename T> auto & System::Get(T &collection, const Index &index)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Collection type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| collection | T\& | Collection object. |
| index | const [Index](../index/)\& | Element index of type [System.Index](../index/). |

### Return Value

Collection element at the calculated offset.

## System::Get(T\&, const Range\&) function


Returns a slice of the specified collection defined by the provided range.

```cpp
template<typename T> auto System::Get(T &collection, const Range &range)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| collection | T\& | The collection to slice. |
| range | const [Range](../range/)\& | The range specifying the slice boundaries. |

### Return Value

A view or slice of the collection from the computed start offset and length.

## System::Get(const ValueTuple\<Args...\>\&) function


Gets N-th element of value tuple.

```cpp
template<std::size_t,typename...> auto System::Get(const ValueTuple<Args...> &tuple)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| N | element index. |
| Args | tuple elements. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| tuple | const [ValueTuple](../valuetuple/)\<Args...\>\& | tuple to get element from. |

### Return Value

value of N-th tuple element.

## See Also

* Typedef [SharedPtr](../sharedptr/)
* Class [Object](../object/)
* Class [Index](../index/)
* Class [Range](../range/)
* Class [ValueTuple](../valuetuple/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)