---
title: LINQ_Count()
second_title: Aspose.Slides for C++ API 參考
description: 返回序列中元素的數量（透過直接計數計算）。
type: docs
weight: 118
url: /zh-hant/system.collections.generic/ienumerable/linq_count/
---
## IEnumerable::LINQ_Count() 方法


返回序列中元素的數量（透過直接計數計算）。

```cpp
int System::Collections::Generic::IEnumerable<T>::LINQ_Count()
```


### 返回值

序列中元素的數量。

## IEnumerable::LINQ_Count(const Func\<T, bool\>\&) 方法


返回符合指定條件的序列中元素的數量。

```cpp
int System::Collections::Generic::IEnumerable<T>::LINQ_Count(const Func<T, bool> &predicate)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| predicate | const [Func](../../../system/func/)\<T, **bool**\>\& | 用於測試每個元素是否符合條件的函式。 |

### 返回值

符合指定條件的序列中元素的數量。

## 另請參閱

* 類別 [IEnumerable](../)
* 類別 [Func](../../../system/func/)
* 命名空間 [System::Collections::Generic](../../)
* 函式庫 [Aspose.Slides](../../../)