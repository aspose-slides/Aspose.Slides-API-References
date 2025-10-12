---
title: Contains()
second_title: Aspose.Slides for C++ API Reference
description: Checks if a character span contains another character span with specified comparison rules.
type: docs
weight: 53
url: /system.memoryextensions/contains/
---
## System::MemoryExtensions::Contains(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function


Checks if a character span contains another character span with specified comparison rules.

```cpp
bool System::MemoryExtensions::Contains(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The span to search in |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The span to search for |
| comparisonType | [StringComparison](../../system/stringcomparison/) | The type of string comparison to perform |

### Return Value

true if value is found in span, false otherwise

## System::MemoryExtensions::Contains(const ReadOnlySpan\<T\>\&, const T\&) function


Checks if a read-only span contains a specific value.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const ReadOnlySpan<T> &span, const T &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| value | const T\& | The value to search for |

### Return Value

true if value is found in span, false otherwise

## System::MemoryExtensions::Contains(const Span\<T\>\&, const T\&) function


Checks if a mutable span contains a specific value.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const Span<T> &span, const T &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The mutable span to search in |
| value | const T\& | The value to search for |

### Return Value

true if value is found in span, false otherwise

## See Also

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)