---
title: LastIndexOf()
second_title: Aspose.Slides for C++ API Reference
description: Determines the index of the last occurrence of the specified item in a range of items of the array specified by the start index and the number of elements in the range.
type: docs
weight: 677
url: /cpp/system/array/lastindexof/
---
## Array::LastIndexOf(const [ArrayPtr](../../arrayptr/)\<ArrayType\>\&, const [ValueType](../valuetype/)\&, int, int) method


Determines the index of the last occurrence of the specified item in a range of items of the array specified by the start index and the number of elements in the range.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
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

Index of the last occurrence of the specified item if the item is found, otherwise -1

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## Array::LastIndexOf(const [ArrayPtr](../../arrayptr/)\<ArrayType\>\&, const [ValueType](../valuetype/)\&, int) method


Determines the index of the last occurrence of the specified item in the array starting from the specified index.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value, int startIndex)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| ArrayType | Type of elements in the target array |
| ValueType | type of the item to search for in the array |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) to search the specified item in |
| value | const [ValueType](../valuetype/)\& | Item index of which is to be determined |
| startIndex | int | Index at which the search is started |

### Return Value

Index of the last occurrence of the specified item if the item is found, otherwise -1

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## Array::LastIndexOf(const [ArrayPtr](../../arrayptr/)\<ArrayType\>\&, const [ValueType](../valuetype/)\&) method


Determines the index of the last occurrence of the specified item in the array.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| ArrayType | Type of elements in the target array |
| ValueType | type of the item to search for in the array |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) to search the specified item in |
| value | const [ValueType](../valuetype/)\& | Item index of which is to be determined |

### Return Value

Index of the last occurrence of the specified item if the item is found, otherwise -1

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
