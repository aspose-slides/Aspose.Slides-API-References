---
title: FindIndex()
second_title: Aspose.Slides for C++ API Reference
description: Looks for element adhering to specific predicate.
type: docs
weight: 404
url: /system.collections.generic/list/findindex/
---
## List::FindIndex(System::Predicate\<T\>) method


Looks for element adhering to specific predicate.

```cpp
int System::Collections::Generic::List<T>::FindIndex(System::Predicate<T> match)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Predicate to check elements with. |

### Return Value

Index of matching element or -1 if not found.

## List::FindIndex(int, System::Predicate\<T\>) method


Looks for element adhering to specific predicate.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, System::Predicate<T> match)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | Index to start search from. |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Predicate to check elements with. |

### Return Value

Index of matching element or -1 if not found.

## List::FindIndex(int, int, System::Predicate\<T\>) method


Looks for element adhering to specific predicate.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, int count, System::Predicate<T> match)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | Index to start search from. |
| count | int | Number of elements to look through. |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Predicate to check elements with. |

### Return Value

Index of matching element or -1 if not found.

## See Also

* Typedef [Predicate](../../../system/predicate/)
* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)