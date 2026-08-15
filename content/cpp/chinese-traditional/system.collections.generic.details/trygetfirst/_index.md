---
title: TryGetFirst()
second_title: Aspose.Slides for C++ API 參考文件
description: 嘗試取得集合的第一個元素。
type: docs
weight: 248
url: /zh-hant/system.collections.generic.details/trygetfirst/
---
## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, bool\&) 函式


嘗試取得集合的第一個元素。

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, bool &found)
```


### 模板參數

| Parameter | Description |
| --- | --- |
| T | 集合元素的類型。 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | 要取得元素的集合。 |
| found | **bool**\& | 輸出參數。當集合包含任何元素時返回 true，否則返回 false。 |

### 返回值

返回集合的第一個元素。當集合為空時，將返回該類型的預設值。

## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, const Func\<T, bool\>\&, bool\&) 函式


嘗試取得集合中符合謂詞函式的第一個元素。

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, const Func<T, bool> &predicate, bool &found)
```


### 模板參數

| Parameter | Description |
| --- | --- |
| T | 集合元素的類型。 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | 要取得元素的集合。 |
| predicate | const [Func](../../system/func/)\<T, **bool**\>\& | 謂詞函式。 |
| found | **bool**\& | 輸出參數。當集合包含任何元素時返回 true，否則返回 false。 |

### 返回值

返回集合的第一個元素。當找不到符合指定謂詞函式的元素時，將返回該類型的預設值。

## 另請參閱

* 類別 [IEnumerable](../../system.collections.generic/ienumerable/)
* 類別 [Func](../../system/func/)
* 命名空間 [System::Collections::Generic::Details](../)
* 函式庫 [Aspose.Slides](../../)