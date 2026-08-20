---
title: AsMemory()
second_title: Aspose.Slides for C++ API Reference
description: Creates a read-only memory from a string.
type: docs
weight: 1
url: /system.memoryextensions/asmemory/
---
## System::MemoryExtensions::AsMemory(const System::String\&) function


Creates a read-only memory from a string.

```cpp
ReadOnlyMemory<char16_t> System::MemoryExtensions::AsMemory(const System::String &text)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| text | const [System::String](../../system/string/)\& | The source string. |

### Return Value

ReadOnlyMemory<char16_t> covering the specified portion of the string.
## Remarks



On C++ side this will be copy of string contents, not slice of existing string. 

## System::MemoryExtensions::AsMemory(const System::String\&, int32_t) function


Creates a read-only memory from a string slice.

```cpp
ReadOnlyMemory<char16_t> System::MemoryExtensions::AsMemory(const System::String &text, int32_t start)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| text | const [System::String](../../system/string/)\& | The source string. |
| start | **int32_t** | The starting index in the string. |

### Return Value

ReadOnlyMemory<char16_t> covering the specified portion of the string.

## System::MemoryExtensions::AsMemory(const System::String\&, int32_t, int32_t) function


Creates a read-only memory from a string slice.

```cpp
ReadOnlyMemory<char16_t> System::MemoryExtensions::AsMemory(const System::String &text, int32_t start, int32_t length)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| text | const [System::String](../../system/string/)\& | The source string. |
| start | **int32_t** | The starting index in the string. |
| length | **int32_t** | The length of the memory slice. |

### Return Value

ReadOnlyMemory<char16_t> covering the specified portion of the string.

## System::MemoryExtensions::AsMemory(const ArrayPtr\<T\>\&) function


Creates a mutable memory from an array.

```cpp
template<typename T> Memory<T> System::MemoryExtensions::AsMemory(const ArrayPtr<T> &array)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the array. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | The source array. |

### Return Value

Memory<T> wrapping the entire array.

## System::MemoryExtensions::AsMemory(const ArrayPtr\<T\>\&, int32_t) function


Creates a mutable memory from an array slice.

```cpp
template<typename T> Memory<T> System::MemoryExtensions::AsMemory(const ArrayPtr<T> &array, int32_t start)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the array. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | The source array. |
| start | **int32_t** | The starting index in the array. |

### Return Value

Memory<T> covering the specified portion of the array.

## System::MemoryExtensions::AsMemory(const ArrayPtr\<T\>\&, int32_t, int32_t) function


Creates a mutable memory from an array slice.

```cpp
template<typename T> Memory<T> System::MemoryExtensions::AsMemory(const ArrayPtr<T> &array, int32_t start, int32_t length)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the array. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | The source array. |
| start | **int32_t** | The starting index in the array. |
| length | **int32_t** | The length of the memory slice. |

### Return Value

Memory<T> covering the specified portion of the array.

## System::MemoryExtensions::AsMemory(const ArraySegment\<T\>\&) function


Creates a mutable memory from an array segment.

```cpp
template<typename T> Memory<T> System::MemoryExtensions::AsMemory(const ArraySegment<T> &segment)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the array. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| segment | const [ArraySegment](../../system/arraysegment/)\<T\>\& | The source array segment. |

### Return Value

Memory<T> covering the specified portion of the array.

## System::MemoryExtensions::AsMemory(const ArrayPtr\<T\>\&, const Range\&) function


Creates a mutable memory from a range within an array.

```cpp
template<typename T> Memory<T> System::MemoryExtensions::AsMemory(const ArrayPtr<T> &array, const Range &range)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the array. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | The source array. |
| range | const [Range](../../system/range/)\& | The range of elements to include in the memory. |

### Return Value

Memory<T> covering the specified portion of the array.

## See Also

* Typedef [ArrayPtr](../../system/arrayptr/)
* Class [ReadOnlyMemory](../../system/readonlymemory/)
* Class [String](../../system/string/)
* Class [Memory](../../system/memory/)
* Class [ArraySegment](../../system/arraysegment/)
* Class [Range](../../system/range/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)