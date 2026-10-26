---
title: FindIndex()
second_title: Aspose.Slides for C++ API 參考
description: 尋找符合特定謂詞的元素。
type: docs
weight: 404
url: /zh-hant/system.collections.generic/list/findindex/
---
## List::FindIndex(System::Predicate\<T\>) 方法


尋找符合特定謂詞的元素。

```cpp
int System::Collections::Generic::List<T>::FindIndex(System::Predicate<T> match)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| match | [System::Predicate](../../../system/predicate/)\<T\> | 用於檢查元素的 Predicate。 |

### 返回值

[Index](../../../system/index/) of matching element or -1 if not found.

## List::FindIndex(int, System::Predicate\<T\>) 方法


尋找符合特定謂詞的元素。

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, System::Predicate<T> match)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/) to start search from. |
| match | [System::Predicate](../../../system/predicate/)\<T\> | 用於檢查元素的 Predicate。 |

### 返回值

[Index](../../../system/index/) of matching element or -1 if not found.

## List::FindIndex(int, int, System::Predicate\<T\>) 方法


尋找符合特定謂詞的元素。

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, int count, System::Predicate<T> match)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/) to start search from. |
| count | int | 要檢查的元素數量。 |
| match | [System::Predicate](../../../system/predicate/)\<T\> | 用於檢查元素的 Predicate。 |

### 返回值

[Index](../../../system/index/) of matching element or -1 if not found.

## 另見

* Typedef [Predicate](../../../system/predicate/)
* 類別 [List](../)
* 命名空間 [System::Collections::Generic](../../)
* 函式庫 [Aspose.Slides](../../../)