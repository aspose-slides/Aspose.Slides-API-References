---
title: InsertionSort()
second_title: Aspose.Slides C++ API 參考
description: 對鍵值對執行插入排序。
type: docs
weight: 66
url: /zh-hant/system.memoryextensions.details/insertionsort/
---
## System::MemoryExtensions::Details::InsertionSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) 函式

對鍵值對執行插入排序。

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::InsertionSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| TKey | 鍵的類型 |
| TValue | 值的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | 要排序的鍵跨度 |
| values | [Span](../../system/span/)\<TValue\>\& | 要排序的值跨度 |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) 用於鍵的函式 |

## 另見

* 類別 [Span](../../system/span/)
* 命名空間 [System::MemoryExtensions::Details](../)
* 函式庫 [Aspose.Slides](../../)