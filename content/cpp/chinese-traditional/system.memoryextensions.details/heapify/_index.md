---
title: Heapify()
second_title: Aspose.Slides for C++ API 參考
description: 維持鍵值對的堆積屬性。
type: docs
weight: 92
url: /zh-hant/system.memoryextensions.details/heapify/
---
## System::MemoryExtensions::Details::Heapify(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) 函式

維持鍵值對的堆積屬性。

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::Heapify(Span<TKey> &keys, Span<TValue> &values, int32_t n, int32_t i, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| TKey | 鍵的型別 |
| TValue | 值的型別 |

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | 堆積中鍵的 span |
| values | [Span](../../system/span/)\<TValue\>\& | 堆積中值的 span |
| n | **int32_t** | 堆積的大小 |
| i | **int32_t** | [Index](../../system/index/) 要進行 heapify 的起始位置 |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) 用於鍵的比較函式 |

## 另請參見

* 類別 [Span](../../system/span/)
* 命名空間 [System::MemoryExtensions::Details](../)
* 函式庫 [Aspose.Slides](../../)