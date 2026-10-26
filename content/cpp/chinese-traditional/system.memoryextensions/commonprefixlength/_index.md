---
title: CommonPrefixLength()
second_title: Aspose.Slides for C++ API 參考
description: 找出兩個 Span 之間共同前置字元的長度。
type: docs
weight: 27
url: /zh-hant/system.memoryextensions/commonprefixlength/
---
## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 函式

找出兩個 Span 之間共同前置字元的長度。

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | Span 中元素的型別 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 第一個 Span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 第二個 Span |

### 傳回值

兩個 Span 開頭相符元素的數量

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 函式

找出可變 Span 與唯讀 Span 之間共同前置字元的長度。

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | Span 中元素的型別 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 可變 Span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 唯讀 Span |

### 傳回值

兩個 Span 開頭相符元素的數量

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&) 函式

找出兩個可變 Span 之間共同前置字元的長度。

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | Span 中元素的型別 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 第一個可變 Span |
| other | const [Span](../../system/span/)\<T\>\& | 第二個可變 Span |

### 傳回值

兩個 Span 開頭相符元素的數量

## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) 函式

使用自訂等值比較器找出兩個 Span 之間共同前置字元的長度。

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | Span 中元素的型別 |
| TEqualityComparer | 等值比較器的型別 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 第一個 Span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 第二個 Span |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | 用於元素比較的等值比較器 |

### 傳回值

兩個 Span 開頭相符元素的數量

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) 函式

使用自訂等值比較器找出可變 Span 與唯讀 Span 之間共同前置字元的長度。

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | Span 中元素的型別 |
| TEqualityComparer | 等值比較器的型別 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 可變 Span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 唯讀 Span |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | 用於元素比較的等值比較器 |

### 傳回值

兩個 Span 開頭相符元素的數量

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) 函式

使用自訂等值比較器找出兩個可變 Span 之間共同前置字元的長度。

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | Span 中元素的型別 |
| TEqualityComparer | 等值比較器的型別 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 第一個可變 Span |
| other | const [Span](../../system/span/)\<T\>\& | 第二個可變 Span |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | 用於元素比較的等值比較器 |

### 傳回值

兩個 Span 開頭相符元素的數量

## 另請參見

* 型別別名 [SharedPtr](../../system/sharedptr/)
* 類別 [ReadOnlySpan](../../system/readonlyspan/)
* 類別 [Span](../../system/span/)
* 命名空間 [System::MemoryExtensions](../)
* 函式庫 [Aspose.Slides](../../)