---
title: LastIndexOf()
second_title: Aspose.Slides for C++ API 參考文件
description: 在跨度中搜尋序列的最後一次出現。
type: docs
weight: 209
url: /zh-hant/system.memoryextensions/lastindexof/
---
## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 函式

在跨度中搜尋序列的最後一次出現。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的型別 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜尋的 span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜尋的序列 |

### 返回值

最後一次出現的零基索引，若未找到則為 -1

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const T\&) 函式

在跨度中搜尋單一值的最後一次出現。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const T &value)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的型別 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜尋的 span |
| value | const T\& | 要搜尋的值 |

### 返回值

最後一次出現的零基索引，若未找到則為 -1

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 函式

在可變跨度中搜尋序列的最後一次出現。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的型別 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜尋的 span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜尋的序列 |

### 返回值

最後一次出現的零基索引，若未找到則為 -1

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const T\&) 函式

在可變跨度中搜尋單一值的最後一次出現。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const T &value)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的型別 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜尋的 span |
| value | const T\& | 要搜尋的值 |

### 返回值

最後一次出現的零基索引，若未找到則為 -1

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) 函式

使用指定的字串比較方式，在跨度中搜尋值的最後一次出現。

```cpp
int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要搜尋的 span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要搜尋的值 |
| comparisonType | [StringComparison](../../system/stringcomparison/) | 要執行的字串比較類型 |

### 返回值

最後一次出現的零基索引，若未找到則為 -1

## 另請參閱

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)