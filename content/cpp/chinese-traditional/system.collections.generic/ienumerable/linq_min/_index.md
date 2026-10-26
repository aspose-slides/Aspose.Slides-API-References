---
title: LINQ_Min()
second_title: Aspose.Slides for C++ API 參考文件
description: 對泛型序列的每個元素呼叫轉換函式，並回傳最小的結果值。
type: docs
weight: 339
url: /zh-hant/system.collections.generic/ienumerable/linq_min/
---
## IEnumerable::LINQ_Min(const Func\<T, ResultType\>\&) 方法

對泛型序列的每個元素呼叫轉換函式，並回傳最小的結果值。

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<T, ResultType> &selector)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| ResultType | selector 回傳值的類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | 要套用於每個元素的轉換函式。 |

### 回傳值

序列中的最小值。

## IEnumerable::LINQ_Min(const Func\<Source, ResultType\>\&) 方法

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<Source, ResultType> &selector)
```

## 相關參考

* 類別 [Func](../../../system/func/)
* 類別 [IEnumerable](../)
* 命名空間 [System::Collections::Generic](../../)
* 函式庫 [Aspose.Slides](../../../)