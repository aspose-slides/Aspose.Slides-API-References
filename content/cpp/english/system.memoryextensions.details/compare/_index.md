---
title: Compare()
second_title: Aspose.Slides for C++ API Reference
description: Compares two smart pointers.
type: docs
weight: 1
url: /system.memoryextensions.details/compare/
---
## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const SharedPtr\<U\>\&) function


Compares two smart pointers.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const SharedPtr<U> &b)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Type of first smart pointer |
| U | Type of second smart pointer |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | First smart pointer |
| b | const [SharedPtr](../../system/sharedptr/)\<U\>\& | Second smart pointer |

### Return Value

[Comparison](../../system/comparison/) result (0 if equal, -1 if a < b, 1 if a > b)

## System::MemoryExtensions::Details::Compare(const T\&, const T\&) function


Compares two arithmetic values.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::Compare(const T &a, const T &b)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Arithmetic type |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| a | const T\& | First value |
| b | const T\& | Second value |

### Return Value

[Comparison](../../system/comparison/) result (0 if equal, -1 if a < b, 1 if a > b)

## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const U\&) function


Compares a smart pointer with a value.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const U &b)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Type pointed to by smart pointer |
| U | Type of value |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Smart pointer |
| b | const U\& | Value |

### Return Value

[Comparison](../../system/comparison/) result (0 if equal, -1 if a < b, 1 if a > b)

## See Also

* Typedef [SharedPtr](../../system/sharedptr/)
* Namespace [System::MemoryExtensions::Details](../)
* Library [Aspose.Slides](../../)