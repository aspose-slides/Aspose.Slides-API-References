---
title: SwapIfGreaterWithValues()
second_title: Aspose.Slides for C++ API 參考
description: 如果滿足比較條件，則交換鍵值對。
type: docs
weight: 53
url: /zh-hant/system.memoryextensions.details/swapifgreaterwithvalues/
---
## System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>, int32_t, int32_t) function

如果滿足比較條件，則交換鍵值對。

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer, int32_t i, int32_t j)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| TKey | 鍵的類型 |
| TValue | 值的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | 鍵的跨度 |
| values | [Span](../../system/span/)\<TValue\>\& | 值的跨度 |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) 函式用於鍵 |
| i | **int32_t** | 第一個比較索引 |
| j | **int32_t** | 第二個比較索引 |

## 另請參閱

* 類別 [Span](../../system/span/)
* 命名空間 [System::MemoryExtensions::Details](../)
* 函式庫 [Aspose.Slides](../../)