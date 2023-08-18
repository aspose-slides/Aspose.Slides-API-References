---
title: IndexOf()
second_title: Aspose.Slides for C++ API Reference
description: Determines the index of the first occurrence of the specified item in the array.
type: docs
weight: 131
url: /system/array/indexof/
---
## Array::IndexOf(const T\&) const method


Determines the index of the first occurrence of the specified item in the array.

```cpp
virtual int System::Array<T>::IndexOf(const T &item) const override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| item | const T\& | Item index of which is to be determined |

### Return Value

Index of the first occurrence of the specified item if the item is found, otherwise -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) method


Determines the index of the first occurrence of specified item in the array.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| ArrayType | Type of elements in the target array |
| ValueType | type of the item to search for in the array |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) to search the specified item in |
| value | const [ValueType](../valuetype/)\& | Item index of which is to be determined |

### Return Value

Index of the first occurrence specified item if the item is found, otherwise -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) method


Determines the index of the first occurrence of the specified item in the array starting from the specified index.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| ArrayType | Type of elements in the target array |
| ValueType | type of the item to search for in the array |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) to search the specified item in |
| value | const [ValueType](../valuetype/)\& | Item index of which is to be determined |
| startIndex | int | Index at which the search is started |

### Return Value

Index of the first occurrence of the specified item if the item is found, otherwise -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) method


Determines the index of the first occurrence of the specified item in a range of items of the array specified by the start index and the number of elements in the range.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| ArrayType | Type of elements in the target array |
| ValueType | type of the item to search for in the array |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) to search the specified item in |
| value | const [ValueType](../valuetype/)\& | Item index of which is to be determined |
| startIndex | int | Index at which the search is started |
| count | int | Number of elements of the range to search in |

### Return Value

Index of the first occurrence of the specified item if the item is found, otherwise -1

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)