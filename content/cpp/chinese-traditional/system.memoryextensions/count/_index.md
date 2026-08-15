---
title: Count()
second_title: Aspose.Slides for C++ API 參考
description: 計算只讀 span 中某個值的出現次數。
type: docs
weight: 118
url: /zh-hant/system.memoryextensions/count/
---
## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const T\&) 函式

計算只讀 Span 中值的出現次數。

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const T &value)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | Span 中元素的類型 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜尋的 Span |
| value | const T\& | 要計數的值 |

### 傳回值

值在 Span 中出現的次數

## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 函式

計算只讀 Span 中另一個只讀 Span 出現的次數。

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | 這些 Span 中元素的類型 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜尋的 Span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要計算其出現次數的 Span |

### 傳回值

Span 在 Span 中出現的次數

## System::MemoryExtensions::Count(const Span\<T\>\&, const T\&) 函式

計算 Span<T> 中單一值的出現次數。

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const T &value)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | Span 中元素的類型 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜尋的 Span |
| value | const T\& | 要計數的值 |

### 傳回值

值在 Span 中出現的次數

## System::MemoryExtensions::Count(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 函式

計算只讀 Span<T> 在 Span<T> 中的出現次數。

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | 這些 Span 中元素的類型 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜尋的 Span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 包含要計數之值的 Span |

### 傳回值

目標 Span 中該值 Span 出現的次數

## 另請參閱

* 類別 [ReadOnlySpan](../../system/readonlyspan/)
* 類別 [Span](../../system/span/)
* 名稱空間 [System::MemoryExtensions](../)
* 函式庫 [Aspose.Slides](../../)