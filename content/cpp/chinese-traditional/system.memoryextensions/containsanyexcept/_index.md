---
title: ContainsAnyExcept()
second_title: Aspose.Slides for C++ API 參考
description: 檢查唯讀 span 是否包含除三個指定值之外的任何元素。
type: docs
weight: 66
url: /zh-hant/system.memoryextensions/containsanyexcept/
---
## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) 函式

檢查唯讀 span 是否包含除三個指定值之外的任何元素。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```


### 模板參數

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| value0 | const T\& | The first value to exclude |
| value1 | const T\& | The second value to exclude |
| value2 | const T\& | The third value to exclude |

### 返回值

若找到任何不同於指定值的元素則返回 true，否則返回 false

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) 函式

檢查可變 span 是否包含除三個指定值之外的任何元素。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```


### 模板參數

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The mutable span to search in |
| value0 | const T\& | The first value to exclude |
| value1 | const T\& | The second value to exclude |
| value2 | const T\& | The third value to exclude |

### 返回值

若找到任何不同於指定值的元素則返回 true，否則返回 false

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) 函式

檢查唯讀 span 是否包含除兩個指定值之外的任何元素。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```


### 模板參數

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| value0 | const T\& | The first value to exclude |
| value1 | const T\& | The second value to exclude |

### 返回值

若找到任何不同於指定值的元素則返回 true，否則返回 false

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&) 函式

檢查可變 span 是否包含除兩個指定值之外的任何元素。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```


### 模板參數

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The mutable span to search in |
| value0 | const T\& | The first value to exclude |
| value1 | const T\& | The second value to exclude |

### 返回值

若找到任何不同於指定值的元素則返回 true，否則返回 false

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) 函式

檢查唯讀 span 是否包含除指定值之外的任何元素。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```


### 模板參數

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| value | const T\& | The value to exclude |

### 返回值

若找到任何不同於指定值的元素則返回 true，否則返回 false

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&) 函式

檢查可變 span 是否包含除指定值之外的任何元素。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value)
```


### 模板參數

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The mutable span to search in |
| value | const T\& | The value to exclude |

### 返回值

若找到任何不同於指定值的元素則返回 true，否則返回 false

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 函式

檢查唯讀 span 是否包含除另一個 span 中的值之外的任何元素。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```


### 模板參數

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span of values to exclude |

### 返回值

若找到任何不在 values 中的元素則返回 true，否則返回 false

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 函式

檢查可變 span 是否包含除唯讀 span 中的值之外的任何元素。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```


### 模板參數

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The mutable span to search in |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The read-only span of values to exclude |

### 返回值

若找到任何不在 values 中的元素則返回 true，否則返回 false

## 另請參閱

* 類別 [ReadOnlySpan](../../system/readonlyspan/)
* 類別 [Span](../../system/span/)
* 命名空間 [System::MemoryExtensions](../)
* 函式庫 [Aspose.Slides](../../)