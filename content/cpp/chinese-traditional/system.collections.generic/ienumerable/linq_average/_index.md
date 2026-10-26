---
title: LINQ_Average()
second_title: Aspose.Slides 用於 C++ 的 API 參考
description: 計算數值序列的平均值。
type: docs
weight: 365
url: /zh-hant/system.collections.generic/ienumerable/linq_average/
---
## IEnumerable::LINQ_Average() 方法


計算數值序列的平均值。

```cpp
Source System::Collections::Generic::IEnumerable<Source>::LINQ_Average()
```


### 回傳值

序列中值的平均值。

## IEnumerable::LINQ_Average(const Func\<T, ResultType\>\&) 方法


計算透過對輸入序列的每個元素呼叫轉換函式取得之值序列的平均值。

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<T, ResultType> &selector)
```


### 範本參數

| 參數 | 描述 |
| --- | --- |
| ResultType | selector 回傳的值的類型。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | 套用於每個元素的轉換函式。 |

### 回傳值

投影值的平均值。

## IEnumerable::LINQ_Average(const Func\<Source, ResultType\>\&) 方法




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<Source, ResultType> &selector)
```

## 另請參閱

* 類別 [IEnumerable](../)
* 類別 [Func](../../../system/func/)
* 命名空間 [System::Collections::Generic](../../)
* 程式庫 [Aspose.Slides](../../../)