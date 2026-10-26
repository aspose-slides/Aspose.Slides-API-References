---
title: IndexOf()
second_title: Aspose.Slides for C++ API 參考
description: 在另一個 ReadOnlySpan<T> 中尋找 ReadOnlySpan<T> 值的索引
type: docs
weight: 144
url: /zh-hant/system.memoryextensions/indexof/
---
## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 函式


在另一個 ReadOnlySpan<T> 中尋找 ReadOnlySpan<T> 值的索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | 跨度中元素的類型 |

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜尋的跨度 |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜尋的跨度 |

### 回傳值

第一個出現的位置的零基索引，若找不到則返回 -1

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const T\&) 函式


在 ReadOnlySpan<T> 中尋找單一值的索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const T &value)
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | 跨度中元素的類型 |

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜尋的跨度 |
| value | const T\& | 要搜尋的值 |

### 回傳值

第一個出現的位置的零基索引，若找不到則返回 -1

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 函式


在 Span<T> 中尋找 ReadOnlySpan<T> 值的索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | 跨度中元素的類型 |

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜尋的跨度 |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜尋的跨度 |

### 回傳值

第一個出現的位置的零基索引，若找不到則返回 -1

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const T\&) 函式


在 Span<T> 中尋找單一值的索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const T &value)
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | 跨度中元素的類型 |

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜尋的跨度 |
| value | const T\& | 要搜尋的值 |

### 回傳值

第一個出現的位置的零基索引，若找不到則返回 -1

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) 函式


在 ReadOnlySpan<char16_t> 中以 StringComparison 尋找 ReadOnlySpan<char16_t> 值的索引

```cpp
int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要搜尋的跨度 |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要搜尋的值 |
| comparisonType | [StringComparison](../../system/stringcomparison/) | 要使用的字串比較類型 |

### 回傳值

第一個出現的位置的零基索引，若找不到則返回 -1

## 另請參閱

* 列舉 [StringComparison](../../system/stringcomparison/)
* 類別 [ReadOnlySpan](../../system/readonlyspan/)
* 類別 [Span](../../system/span/)
* 命名空間 [System::MemoryExtensions](../)
* 函式庫 [Aspose.Slides](../../)