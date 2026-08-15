---
title: BinarySearch()
second_title: Aspose.Slides for C++ API 參考
description: 在已排序的列表中搜尋項目。
type: docs
weight: 339
url: /zh-hant/system.collections.generic/list/binarysearch/
---
## List::BinarySearch(const T\&) const 方法

在已排序的列表中搜尋項目。

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | const T\& | 待查找的項目。 |

### 回傳值

[Index](../../../system/index/) 項目在已排序列表中的索引，或最近索引的補數。

## List::BinarySearch(const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const 方法

在已排序的列表中搜尋項目。

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | const T\& | 待查找的項目。 |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) 使用的比較器。 |

### 回傳值

[Index](../../../system/index/) 項目在已排序列表中的索引，或最近索引的補數。

## List::BinarySearch(int, int, const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const 方法

在已排序的列表中搜尋項目。

```cpp
int System::Collections::Generic::List<T>::BinarySearch(int index, int count, const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | [Range](../../../system/range/) 起始位置。 |
| count | int | [Range](../../../system/range/) 大小。 |
| item | const T\& | 待查找的項目。 |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) 使用的比較器。 |

### 回傳值

[Index](../../../system/index/) 項目在已排序列表中的索引，或最近索引的補數。

## 參見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [List](../)
* 類別 [IComparer](../../icomparer/)
* 命名空間 [System::Collections::Generic](../../)
* 函式庫 [Aspose.Slides](../../../)