---
title: EndsWith()
second_title: Aspose.Slides for C++ API 參考
description: 判斷 ReadOnlySpan<T> 是否以單一值結尾。
type: docs
weight: 131
url: /zh-hant/system.memoryextensions/endswith/
---
## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const T\&) 函式


判斷 ReadOnlySpan<T> 是否以單一值結尾。

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const T &value)
```


### 範本參數

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to check |
| value | const T\& | The value to check for at the end of the span |

### 返回值

true if the span ends with the value, false otherwise

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 函式


判斷 ReadOnlySpan<T> 是否以另一個 ReadOnlySpan<T> 結尾。

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### 範本參數

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to check |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to check for at the end of the target span |

### 返回值

true if the span ends with the value span, false otherwise

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 函式


判斷 Span<T> 是否以 ReadOnlySpan<T> 結尾。

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### 範本參數

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to check |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to check for at the end of the target span |

### 返回值

true if the span ends with the value span, false otherwise

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) 函式


判斷 ReadOnlySpan<T> 是否以 Span<T> 結尾。

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```


### 範本參數

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to check |
| value | const [Span](../../system/span/)\<T\>\& | The span to check for at the end of the target span |

### 返回值

true if the span ends with the value span, false otherwise

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const Span\<T\>\&) 函式


判斷 Span<T> 是否以另一個 Span<T> 結尾。

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const Span<T> &value)
```


### 範本參數

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to check |
| value | const [Span](../../system/span/)\<T\>\& | The span to check for at the end of the target span |

### 返回值

true if the span ends with the value span, false otherwise

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) 函式


判斷 ReadOnlySpan<char16_t> 是否使用 StringComparison 以指定值結尾。

```cpp
bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The span to check |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The value to check for at the end of the span |
| comparisonType | [StringComparison](../../system/stringcomparison/) | The string comparison type to use |

### 返回值

true if the span ends with the value, false otherwise

## 另請參閱

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)