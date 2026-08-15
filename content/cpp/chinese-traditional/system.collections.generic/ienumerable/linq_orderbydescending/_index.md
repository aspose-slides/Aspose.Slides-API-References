---
title: LINQ_OrderByDescending()
second_title: Aspose.Slides for C++ API 參考
description: 根據 keySelector 所選取的鍵值，將序列的元素以遞減順序排序。
type: docs
weight: 222
url: /zh-hant/system.collections.generic/ienumerable/linq_orderbydescending/
---
## IEnumerable::LINQ_OrderByDescending(const Func\<T, Key\>\&) 方法

依據 keySelector 所選取的鍵值，將序列的元素以遞減順序排序。

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<T, Key> &keySelector)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| keySelector | 從元素中擷取鍵的函式。 |

### 傳回值

一個 IOrderedEnumerable，其元素會依鍵值的遞減順序排序。

## IEnumerable::LINQ_OrderByDescending(const Func\<Source, Key\>\&) 方法

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<Source, Key> &keySelector)
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* 類別 [Func](../../../system/func/)
* 類別 [IEnumerable](../)
* 命名空間 [System::Collections::Generic](../../)
* 函式庫 [Aspose.Slides](../../../)