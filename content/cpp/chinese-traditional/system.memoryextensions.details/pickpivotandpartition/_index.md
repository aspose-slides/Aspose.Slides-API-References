---
title: PickPivotAndPartition()
second_title: Aspose.Slides for C++ API 參考文件
description: 選取基準點並將鍵值對分割以進行快速排序。
type: docs
weight: 105
url: /zh-hant/system.memoryextensions.details/pickpivotandpartition/
---
## System::MemoryExtensions::Details::PickPivotAndPartition(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) 函式

選取基準點並將鍵值對分割以進行快速排序。

```cpp
template<typename TKey,typename TValue> int32_t System::MemoryExtensions::Details::PickPivotAndPartition(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| TKey | The type of keys |
| TValue | The type of values |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | 要分割的鍵的跨度 |
| values | [Span](../../system/span/)\<TValue\>\& | 要分割的值的跨度 |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) 鍵的比較函式 |

### 傳回值

分割後的基準點索引

## 另請參閱

* 類別 [Span](../../system/span/)
* 命名空間 [System::MemoryExtensions::Details](../)
* 函式庫 [Aspose.Slides](../../)