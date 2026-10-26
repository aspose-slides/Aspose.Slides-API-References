---
title: SequenceEqual()
second_title: Aspose.Slides for C++ API 參考文件
description: 判斷兩個 ReadOnlySpans 是否包含相同順序的相同元素。
type: docs
weight: 326
url: /zh-hant/system.memoryextensions/sequenceequal/
---
## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 函式


判斷兩個 ReadOnlySpans 是否包含相同順序的相同元素。

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &first, const ReadOnlySpan<T> &second)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | spans 中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要比較的第一個 span |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要比較的第二個 span |

### 返回值

若 spans 具有相同長度且所有元素相等則回傳 true，否則回傳 false

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 函式


判斷 [Span](../../system/span/) 與 [ReadOnlySpan](../../system/readonlyspan/) 是否包含相同順序的相同元素。

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | spans 中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要比較的 [Span](../../system/span/) |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要比較的 [ReadOnlySpan](../../system/readonlyspan/) |

### 返回值

若 spans 具有相同長度且所有元素相等則回傳 true，否則回傳 false

## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) 函式


判斷兩個 ReadOnlySpans 是否使用自訂比較器來比較相等的元素。

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | spans 中元素的類型 |
| TComparer | 比較器物件的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要比較的第一個 span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要比較的第二個 span |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | 用於元素比較的 comparer 物件之智慧指標 |

### 返回值

若 spans 具有相同長度且 comparer 認為所有元素相等則回傳 true，否則回傳 false

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) 函式


判斷 [Span](../../system/span/) 與 [ReadOnlySpan](../../system/readonlyspan/) 是否使用自訂比較器來比較相等的元素。

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | spans 中元素的類型 |
| TComparer | 比較器物件的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要比較的 [Span](../../system/span/) |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要比較的 [ReadOnlySpan](../../system/readonlyspan/) |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | 用於元素比較的 comparer 物件之智慧指標 |

### 返回值

若 spans 具有相同長度且 comparer 認為所有元素相等則回傳 true，否則回傳 false

## 另請參閱

* 型別別名 [SharedPtr](../../system/sharedptr/)
* 類別 [ReadOnlySpan](../../system/readonlyspan/)
* 類別 [Span](../../system/span/)
* 命名空間 [System::MemoryExtensions](../)
* 函式庫 [Aspose.Slides](../../)