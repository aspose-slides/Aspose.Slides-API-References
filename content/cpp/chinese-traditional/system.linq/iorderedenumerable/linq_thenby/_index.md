---
title: LINQ_ThenBy()
second_title: Aspose.Slides for C++ API 參考
description: 根據鍵以升序對序列中的元素執行後續排序。
type: docs
weight: 27
url: /zh-hant/system.linq/iorderedenumerable/linq_thenby/
---
## IOrderedEnumerable::LINQ_ThenBy(const Func\<T, Key\>\&) 方法

對序列中的元素進行後續排序，根據鍵以升序排列。

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<T>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<T, Key> &keySelector)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| Key | keySelector 回傳的鍵的類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| keySelector | const [Func](../../../system/func/)\<T, Key\>\& | 從每個元素中提取鍵的函式。 |

### 回傳值

[System::Linq::IOrderedEnumerable](../) 其元素根據鍵進行排序。

## IOrderedEnumerable::LINQ_ThenBy(const Func\<Source, Key\>\&) 方法

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<Source>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<Source, Key> &keySelector)
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IOrderedEnumerable](../)
* 類別 [Func](../../../system/func/)
* 命名空間 [System::Linq](../../)
* 函式庫 [Aspose.Slides](../../../)