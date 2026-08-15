---
title: Overlaps()
second_title: Aspose.Slides for C++ API 參考
description: 判斷兩個 ReadOnlySpan 是否在記憶體中重疊而不計算位移。
type: docs
weight: 274
url: /zh-hant/system.memoryextensions/overlaps/
---
## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 函式


判斷兩個 ReadOnlySpan 是否在記憶體中重疊而不計算位移。

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```


### 模板參數

| Parameter | Description |
| --- | --- |
| T |跨度中元素的類型 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要檢查重疊的第一個跨度 |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要檢查重疊的第二個跨度 |

### 返回值

true if the spans share any common memory locations, false otherwise

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 函式


判斷 [Span](../../system/span/) 與 [ReadOnlySpan](../../system/readonlyspan/) 是否在記憶體中重疊而不計算位移。

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### 模板參數

| Parameter | Description |
| --- | --- |
| T |跨度中元素的類型 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要檢查重疊的 [Span](../../system/span/) |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要檢查重疊的 [ReadOnlySpan](../../system/readonlyspan/) |

### 返回值

true if the spans share any common memory locations, false otherwise

## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) 函式


判斷兩個 ReadOnlySpan 是否在記憶體中重疊並計算位移。

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```


### 模板參數

| Parameter | Description |
| --- | --- |
| T |跨度中元素的類型 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要檢查重疊的第一個跨度 |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要檢查重疊的第二個跨度 |
| elementOffset | **int32_t**\& | 如果跨度重疊，接收跨度之間位移的輸出參數 |

### 返回值

true if the spans share any common memory locations, false otherwise

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) 函式


判斷 [Span](../../system/span/) 與 [ReadOnlySpan](../../system/readonlyspan/) 是否在記憶體中重疊並計算位移。

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```


### 模板參數

| Parameter | Description |
| --- | --- |
| T |跨度中元素的類型 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要檢查重疊的 [Span](../../system/span/) |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要檢查重疊的 [ReadOnlySpan](../../system/readonlyspan/) |
| elementOffset | **int32_t**\& | 如果跨度重疊，接收跨度之間位移的輸出參數 |

### 返回值

true if the spans share any common memory locations, false otherwise

## 另見

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)