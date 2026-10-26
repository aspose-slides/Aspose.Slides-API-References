---
title: SequenceCompareTo()
second_title: Aspose.Slides for C++ API 參考文件
description: 按字典順序比較兩個 ReadOnlySpans。
type: docs
weight: 313
url: /zh-hant/system.memoryextensions/sequencecompareto/
---
## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

按字典順序比較兩個 ReadOnlySpans。

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 跨度中元素的類型 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 第一個要比較的 span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 第二個要比較的 span |

### 返回值

- 1 若 span < other，0 若 span == other，1 若 span > other

## System::MemoryExtensions::SequenceCompareTo(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

按字典順序比較 [Span](../../system/span/) 和 [ReadOnlySpan](../../system/readonlyspan/)。

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 跨度中元素的類型 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要比較的 [Span](../../system/span/) |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要比較的 [ReadOnlySpan](../../system/readonlyspan/) |

### 返回值

- 1 若 span < other，0 若 span == other，1 若 span > other

## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) function

按字典順序比較 [ReadOnlySpan](../../system/readonlyspan/) 和 [Span](../../system/span/)。

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const Span<T> &other)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 跨度中元素的類型 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要比較的 [ReadOnlySpan](../../system/readonlyspan/) |
| other | const [Span](../../system/span/)\<T\>\& | 要比較的 [Span](../../system/span/) |

### 返回值

- 1 若 span < other，0 若 span == other，1 若 span > other

## 參見

* 類別 [ReadOnlySpan](../../system/readonlyspan/)
* 類別 [Span](../../system/span/)
* 命名空間 [System::MemoryExtensions](../)
* 函式庫 [Aspose.Slides](../../)