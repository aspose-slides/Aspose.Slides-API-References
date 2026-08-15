---
title: LINQ_Select()
second_title: Aspose.Slides for C++ API 參考
description: 轉換序列中的元素。
type: docs
weight: 248
url: /zh-hant/system.collections.generic/ienumerable/linq_select/
---
## IEnumerable::LINQ_Select(const Func\<T, ResultType\>\&) 方法

將序列中的元素轉換。

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, ResultType> &selector)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| ResultType | **selector** 回傳值的類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | 轉換函式。 |

### 回傳值

一個 [IEnumerable](../)，其包含由 **selector** 函式回傳的元素。

## IEnumerable::LINQ_Select(const Func\<T, int32_t, ResultType\>\&) 方法

將序列中的每個元素轉換為新形式，並結合元素的索引。

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, int32_t, ResultType> &selector)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| ResultType | **selector** 回傳值的類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, **int32_t**, ResultType\>\& | 轉換函式。 |

### 回傳值

一個 [IEnumerable](../)，其包含由 **selector** 函式回傳的元素。

## IEnumerable::LINQ_Select(const Func\<Source, Result\>\&) 方法




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, Result> &selector)
```

## IEnumerable::LINQ_Select(const Func\<Source, int32_t, Result\>\&) 方法




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, int32_t, Result> &selector)
```

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IEnumerable](../)
* 類別 [Func](../../../system/func/)
* 命名空間 [System::Collections::Generic](../../)
* 函式庫 [Aspose.Slides](../../../)