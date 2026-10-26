---
title: IntroSort()
second_title: Aspose.Slides for C++ API 參考
description: 鍵值對的 introsort 演算法之內部實作。
type: docs
weight: 40
url: /zh-hant/system.memoryextensions.details/introsort/
---
## System::MemoryExtensions::Details::IntroSort(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) 函式

內部實作鍵值對的 introsort 演算法。

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::IntroSort(Span<TKey> &keys, Span<TValue> &values, int32_t depthLimit, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| TKey | 鍵的類型 |
| TValue | 值的類型 |

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | 要排序的鍵的 span |
| values | [Span](../../system/span/)\<TValue\>\& | 要排序的值的 span |
| depthLimit | **int32_t** | 切換至 heapsort 前的最大遞迴深度 |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) 鍵的函式 |

## 另請參閱

* 類別 [Span](../../system/span/)
* 命名空間 [System::MemoryExtensions::Details](../)
* 函式庫 [Aspose.Slides](../../)