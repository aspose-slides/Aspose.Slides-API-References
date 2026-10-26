---
title: IndexOfAny()
second_title: Aspose.Slides for C++ API 參考
description: 在 ReadOnlySpan<T> 中尋找任意兩個指定值的第一個出現索引
type: docs
weight: 157
url: /zh-hant/system.memoryextensions/indexofany/
---
## System::MemoryExtensions::IndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

在 ReadOnlySpan<T> 中尋找任意兩個指定值的第一個出現索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜尋的 span |
| value0 | const T\& | 第一個要搜尋的值 |
| value1 | const T\& | 第二個要搜尋的值 |

### 傳回值

第一次出現的零基索引，若未找到則返回 -1

## System::MemoryExtensions::IndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) function

在 ReadOnlySpan<T> 中尋找任意三個指定值的第一個出現索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜尋的 span |
| value0 | const T\& | 第一個要搜尋的值 |
| value1 | const T\& | 第二個要搜尋的值 |
| value2 | const T\& | 第三個要搜尋的值 |

### 傳回值

第一次出現的零基索引，若未找到則返回 -1

## System::MemoryExtensions::IndexOfAny(const Span\<T\>\&, const T\&, const T\&) function

在 Span<T> 中尋找任意兩個指定值的第一個出現索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const Span<T> &span, const T &value0, const T &value1)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜尋的 span |
| value0 | const T\& | 第一個要搜尋的值 |
| value1 | const T\& | 第二個要搜尋的值 |

### 傳回值

第一次出現的零基索引，若未找到則返回 -1

## System::MemoryExtensions::IndexOfAny(const Span\<T\>\&, const T\&, const T\&, const T\&) function

在 Span<T> 中尋找任意三個指定值的第一個出現索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜尋的 span |
| value0 | const T\& | 第一個要搜尋的值 |
| value1 | const T\& | 第二個要搜尋的值 |
| value2 | const T\& | 第三個要搜尋的值 |

### 傳回值

第一次出現的零基索引，若未找到則返回 -1

## System::MemoryExtensions::IndexOfAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

在另一個 ReadOnlySpan<T> 中尋找 span 中任意值的第一個出現索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜尋的 span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 包含要搜尋值的 span |

### 傳回值

第一次出現的零基索引，若未找到則返回 -1

## System::MemoryExtensions::IndexOfAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

在 Span<T> 中尋找 span 中任意值的第一個出現索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜尋的 span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 包含要搜尋值的 span |

### 傳回值

第一次出現的零基索引，若未找到則返回 -1

## 另見

* 類別 [ReadOnlySpan](../../system/readonlyspan/)
* 類別 [Span](../../system/span/)
* 命名空間 [System::MemoryExtensions](../)
* 程式庫 [Aspose.Slides](../../)