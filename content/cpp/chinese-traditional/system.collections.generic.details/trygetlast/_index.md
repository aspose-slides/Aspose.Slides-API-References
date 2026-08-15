---
title: TryGetLast()
second_title: Aspose.Slides for C++ API 參考
description: 嘗試取得集合的最後一個元素。
type: docs
weight: 261
url: /zh-hant/system.collections.generic.details/trygetlast/
---
## System::Collections::Generic::Details::TryGetLast(IEnumerable\<T\>\&, bool\&) 函式


嘗試取得集合的最後一個元素。

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetLast(IEnumerable<T> &enumerable, bool &found)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | The type of the collection elements. |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | 要從中取得元素的集合。 |
| found | **bool**\& | 輸出參數。當集合包含任何元素時返回 true，否則返回 false。 |

### 傳回值

傳回集合的最後一個元素。當集合為空時，傳回該類型的預設值。

## 另請參閱

* 類別 [IEnumerable](../../system.collections.generic/ienumerable/)
* 命名空間 [System::Collections::Generic::Details](../)
* 函式庫 [Aspose.Slides](../../)