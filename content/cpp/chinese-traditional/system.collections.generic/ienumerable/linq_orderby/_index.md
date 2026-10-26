---
title: LINQ_OrderBy()
second_title: Aspose.Slides for C++ API 參考
description: 依據 keySelector 選取的鍵值，將序列中的元素以升序排序。
type: docs
weight: 209
url: /zh-hant/system.collections.generic/ienumerable/linq_orderby/
---
## IEnumerable::LINQ_OrderBy(const Func\<T, Key\>\&) 方法


將序列的元素依據 keySelector 所選擇的鍵值以升序排列。

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<T, Key> &keySelector)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| keySelector | 用於從元素中提取鍵的函式。 |

### 返回值

一個 IOrderedEnumerable，其元素根據鍵進行排序

## IEnumerable::LINQ_OrderBy(const Func\<Source, Key\>\&) 方法




```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<Source, Key> &keySelector)
```

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* 類別 [Func](../../../system/func/)
* 類別 [IEnumerable](../)
* 命名空間 [System::Collections::Generic](../../)
* 函式庫 [Aspose.Slides](../../../)