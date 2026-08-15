---
title: LINQ_Max()
second_title: Aspose.Slides for C++ API 參考文件
description: 對通用序列的每個元素呼叫轉換函式，並返回最大的結果值。
type: docs
weight: 352
url: /zh-hant/system.collections.generic/ienumerable/linq_max/
---
## IEnumerable::LINQ_Max(const Func\<T, ResultType\>\&) 方法

對通用序列的每個元素呼叫轉換函式，並返回最大的結果值。

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<T, ResultType> &selector)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| ResultType | selector 回傳之值的類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | 套用於每個元素的轉換函式。 |

### 返回值

序列中的最大值。

## IEnumerable::LINQ_Max(const Func\<Source, ResultType\>\&) 方法

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<Source, ResultType> &selector)
```

## 另請參閱

* 類別 [Func](../../../system/func/)
* 類別 [IEnumerable](../)
* 命名空間 [System::Collections::Generic](../../)
* 程式庫 [Aspose.Slides](../../../)