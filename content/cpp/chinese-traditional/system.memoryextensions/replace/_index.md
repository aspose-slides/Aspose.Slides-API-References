---
title: Replace()
second_title: Aspose.Slides for C++ API 參考
description: 將 Span 中所有出現的值取代為新值。
type: docs
weight: 287
url: /zh-hant/system.memoryextensions/replace/
---
## System::MemoryExtensions::Replace(Span\<T\>\&, const T\&, const T\&) 函式


在 [Span](../../system/span/) 中將所有出現的值取代為新值。

```cpp
template<typename T> void System::MemoryExtensions::Replace(Span<T> &span, const T &oldValue, const T &newValue)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的型別 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | 要就地修改的 span |
| oldValue | const T\& | 要搜尋並取代的值 |
| newValue | const T\& | 用來取代 oldValue 的新值 |

## System::MemoryExtensions::Replace(const ReadOnlySpan\<T\>\&, Span\<T\>\&, const T\&, const T\&) 函式


將元素從來源複製到目標，並在複製過程中取代指定的值。

```cpp
template<typename T> void System::MemoryExtensions::Replace(const ReadOnlySpan<T> &source, Span<T> &destination, const T &oldValue, const T &newValue)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | spans 中元素的型別 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要從中複製的來源 [ReadOnlySpan](../../system/readonlyspan/) |
| destination | [Span](../../system/span/)\<T\>\& | 要複製到的目標 [Span](../../system/span/) |
| oldValue | const T\& | 在複製期間要搜尋並取代的值 |
| newValue | const T\& | 用來取代 oldValue 的新值 |

## 參見

* 類別 [Span](../../system/span/)
* 類別 [ReadOnlySpan](../../system/readonlyspan/)
* 命名空間 [System::MemoryExtensions](../)
* 函式庫 [Aspose.Slides](../../)