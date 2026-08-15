---
title: SequenceEqualImpl()
second_title: Aspose.Slides for C++ API 參考
description: 檢查兩個 span 從指定位置開始是否相等。
type: docs
weight: 27
url: /zh-hant/system.memoryextensions.details/sequenceequalimpl/
---
## System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan\<T\>\&, const int32_t, int32_t, const ReadOnlySpan\<T\>\&) 函式



檢查兩個 span 是否從指定位置開始相等。

```cpp
template<typename T> bool System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan<T> &first, const int32_t start, int32_t length, const ReadOnlySpan<T> &second)
```


### 模板參數

| Parameter | Description |
| --- | --- |
| T | span 中元素的類型 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 第一個 span |
| start | const **int32_t** | 第一個 span 的起始索引 |
| length | **int32_t** | 比較的元素數量 |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 第二個 span |

### 回傳值

如果指定的範圍相等則返回 true，否則返回 false

## 另請參閱

* 類別 [ReadOnlySpan](../../system/readonlyspan/)
* 命名空間 [System::MemoryExtensions::Details](../)
* 函式庫 [Aspose.Slides](../../)