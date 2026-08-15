---
title: LastIndexOfImpl()
second_title: Aspose.Slides for C++ API 參考
description: 在 span 中尋找值的最後索引。
type: docs
weight: 14
url: /zh-hant/system.memoryextensions.details/lastindexofimpl/
---
## System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan\<T\>\&, int32_t, const T\&) function

在 span 中查找值的最後索引。

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan<T> &searchSpace, int32_t length, const T &value)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| searchSpace | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [Span](../../system/span/) 用於搜尋 |
| length | **int32_t** | 搜尋範圍的長度 |
| value | const T\& | 要尋找的值 |

### 返回值

值的最後索引，若未找到則返回 -1

## 另請參閱

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Namespace [System::MemoryExtensions::Details](../)
* Library [Aspose.Slides](../../)