---
title: HeapSort()
second_title: Aspose.Slides for C++ API 參考
description: 對鍵值對執行堆積排序。
type: docs
weight: 79
url: /zh-hant/system.memoryextensions.details/heapsort/
---
## System::MemoryExtensions::Details::HeapSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) 函式


對鍵值對執行堆積排序。

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::HeapSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```


### 範本參數

| 參數 | 說明 |
| --- | --- |
| TKey | 鍵的類型 |
| TValue | 值的類型 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | 要排序的鍵的 span |
| values | [Span](../../system/span/)\<TValue\>\& | 要排序的值的 span |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) 鍵的比較函式 |

## 另請參閱

* 類別 [Span](../../system/span/)
* 命名空間 [System::MemoryExtensions::Details](../)
* 函式庫 [Aspose.Slides](../../)