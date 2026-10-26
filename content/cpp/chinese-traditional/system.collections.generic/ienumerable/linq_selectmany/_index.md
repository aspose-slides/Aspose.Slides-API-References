---
title: LINQ_SelectMany()
second_title: Aspose.Slides for C++ API 參考文件
description: 將序列中的每個元素投射，並將產生的序列合併為一個序列。
type: docs
weight: 300
url: /zh-hant/system.collections.generic/ienumerable/linq_selectmany/
---
## IEnumerable::LINQ_SelectMany(const Func\<T, SharedPtr\<IEnumerable\<ResultType\>\>\>\&) method

將序列中的每個元素投射，並將產生的序列合併為一個序列。

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<T, SharedPtr<IEnumerable<ResultType>>> &selector)
```

### 範本參數

| Parameter | Description |
| --- | --- |
| ResultType | 由 **selector** 回傳的值的類型。 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, [SharedPtr](../../../system/sharedptr/)\<[IEnumerable](../)\<ResultType\>\>\>\& | 轉換函式。 |

### 返回值

一個 [IEnumerable](../)，其中包含對輸入序列中每個元素呼叫一對多投影函式的結果。

## IEnumerable::LINQ_SelectMany(const Func\<Source, SharedPtr\<IEnumerable\<Result\>\>\>\&) method

```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<Source, SharedPtr<IEnumerable<Result>>> &selector)
```

## 另請參考

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IEnumerable](../)
* 類別 [Func](../../../system/func/)
* 命名空間 [System::Collections::Generic](../../)
* 函式庫 [Aspose.Slides](../../../)