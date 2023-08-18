---
title: CopyTo()
second_title: Aspose.Slides for C++ API Reference
description: Copies list elements into existing array elements.
type: docs
weight: 209
url: /system.collections.generic/list/copyto/
---
## List::CopyTo(System::ArrayPtr\<T\>, int) method


Copies list elements into existing array elements.

```cpp
void System::Collections::Generic::List<T>::CopyTo(System::ArrayPtr<T> array, int arrayIndex) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<T\> | Destination array. |
| arrayIndex | int | Destination array starting index. |

## List::CopyTo(const System::ArrayPtr\<T\>\&) method


Copies all elements into existing array elements.

```cpp
void System::Collections::Generic::List<T>::CopyTo(const System::ArrayPtr<T> &array)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) to copy elements into. |

## List::CopyTo(int, const System::ArrayPtr\<T\>\&, int, int) method


Copies elements starting from the specified index into existing array elements.

```cpp
void System::Collections::Generic::List<T>::CopyTo(int index, const System::ArrayPtr<T> &array, int arrayIndex, int count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | int | A 0-based index of the element in the list represented by the current object to start copying from |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) to copy elements into. |
| arrayIndex | int | Beginning position in desitnation array. |
| count | int | Number of elements to copy. |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)