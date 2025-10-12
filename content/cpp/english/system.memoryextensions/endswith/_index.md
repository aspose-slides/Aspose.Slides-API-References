---
title: EndsWith()
second_title: Aspose.Slides for C++ API Reference
description: Determines if a ReadOnlySpan<char16_t> ends with the specified value using StringComparison.
type: docs
weight: 144
url: /system.memoryextensions/endswith/
---
## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function


Determines if a ReadOnlySpan<char16_t> ends with the specified value using StringComparison.

```cpp
bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The span to check |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The value to check for at the end of the span |
| comparisonType | [StringComparison](../../system/stringcomparison/) | The string comparison type to use |

### Return Value

true if the span ends with the value, false otherwise

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const T\&) function


Determines if a ReadOnlySpan<T> ends with a single value.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const T &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to check |
| value | const T\& | The value to check for at the end of the span |

### Return Value

true if the span ends with the value, false otherwise

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function


Determines if a ReadOnlySpan<T> ends with another ReadOnlySpan<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to check |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to check for at the end of the target span |

### Return Value

true if the span ends with the value span, false otherwise

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function


Determines if a Span<T> ends with a ReadOnlySpan<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to check |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to check for at the end of the target span |

### Return Value

true if the span ends with the value span, false otherwise

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) function


Determines if a ReadOnlySpan<T> ends with a Span<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to check |
| value | const [Span](../../system/span/)\<T\>\& | The span to check for at the end of the target span |

### Return Value

true if the span ends with the value span, false otherwise

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const Span\<T\>\&) function


Determines if a Span<T> ends with another Span<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const Span<T> &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to check |
| value | const [Span](../../system/span/)\<T\>\& | The span to check for at the end of the target span |

### Return Value

true if the span ends with the value span, false otherwise

## See Also

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)