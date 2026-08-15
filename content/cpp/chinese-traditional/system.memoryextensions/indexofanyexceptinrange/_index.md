---
title: IndexOfAnyExceptInRange()
second_title: Aspose.Slides for C++ API 參考文件
description: 在 ReadOnlySpan<T> 中尋找第一個超出指定範圍的元素索引
type: docs
weight: 183
url: /zh-hant/system.memoryextensions/indexofanyexceptinrange/
---
## System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) 函式


尋找在 ReadOnlySpan<T> 中第一個超出指定範圍的元素索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```


### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | The type of elements in the span |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| lowInclusive | const T\& | The lower bound of the range (inclusive) |
| highInclusive | const T\& | The upper bound of the range (inclusive) |

### 回傳值

The zero-based index of the first element outside the range, or -1 if not found

## System::MemoryExtensions::IndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) 函式


尋找在 Span<T> 中第一個超出指定範圍的元素索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```


### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | The type of elements in the span |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search in |
| lowInclusive | const T\& | The lower bound of the range (inclusive) |
| highInclusive | const T\& | The upper bound of the range (inclusive) |

### 回傳值

The zero-based index of the first element outside the range, or -1 if not found

## 另請參閱

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)