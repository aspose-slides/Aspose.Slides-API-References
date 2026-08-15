---
title: ContainsAny()
second_title: Aspose.Slides for C++ API 參考
description: 檢查唯讀 span 是否包含任意兩個值。
type: docs
weight: 53
url: /zh-hant/system.memoryextensions/containsany/
---
## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) 函式

檢查唯讀 Span 是否包含任意兩個值。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### 範本參數

| 參數 | 描述 |
| --- | --- |
| T | Span 中元素的類型 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜尋的 Span |
| value0 | const T\& | 要搜尋的第一個值 |
| value1 | const T\& | 要搜尋的第二個值 |

### 返回值

如果在 span 中找到任意值則為 true，否則為 false

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) 函式

檢查唯讀 Span 是否包含任意三個值。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### 範本參數

| 參數 | 描述 |
| --- | --- |
| T | Span 中元素的類型 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜尋的 Span |
| value0 | const T\& | 要搜尋的第一個值 |
| value1 | const T\& | 要搜尋的第二個值 |
| value2 | const T\& | 要搜尋的第三個值 |

### 返回值

如果在 span 中找到任意值則為 true，否則為 false

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&) 函式

檢查可變 Span 是否包含任意兩個值。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1)
```

### 範本參數

| 參數 | 描述 |
| --- | --- |
| T | Span 中元素的類型 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜尋的可變 Span |
| value0 | const T\& | 要搜尋的第一個值 |
| value1 | const T\& | 要搜尋的第二個值 |

### 返回值

如果在 span 中找到任意值則為 true，否則為 false

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&, const T\&) 函式

檢查可變 Span 是否包含任意三個值。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### 範本參數

| 參數 | 描述 |
| --- | --- |
| T | Span 中元素的類型 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜尋的可變 Span |
| value0 | const T\& | 要搜尋的第一個值 |
| value1 | const T\& | 要搜尋的第二個值 |
| value2 | const T\& | 要搜尋的第三個值 |

### 返回值

如果在 span 中找到任意值則為 true，否則為 false

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 函式

檢查唯讀 Span 是否包含來自另一個 Span 的任意值。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### 範本參數

| 參數 | 描述 |
| --- | --- |
| T | Span 中元素的類型 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜尋的 Span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜尋的值的 Span |

### 返回值

如果在 span 中找到任意值則為 true，否則為 false

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 函式

檢查可變 Span 是否包含來自唯讀 Span 的任意值。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### 範本參數

| 參數 | 描述 |
| --- | --- |
| T | Span 中元素的類型 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜尋的可變 Span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜尋的唯讀值的 Span |

### 返回值

如果在 span 中找到任意值則為 true，否則為 false

## 另見

* 類別 [ReadOnlySpan](../../system/readonlyspan/)
* 類別 [Span](../../system/span/)
* 命名空間 [System::MemoryExtensions](../)
* 函式庫 [Aspose.Slides](../../)