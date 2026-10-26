---
title: Sort()
second_title: Aspose.Slides for C++ API 參考
description: 對列表中的元素進行排序。
type: docs
weight: 521
url: /zh-hant/system.collections.generic/list/sort/
---
## List::Sort(const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) 方法

對列表中的元素進行排序。

```cpp
void System::Collections::Generic::List<T>::Sort(const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| comparator | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | 要使用的比較器。 |

## List::Sort() 方法

使用預設比較器對列表中的元素進行排序。

```cpp
void System::Collections::Generic::List<T>::Sort()
```

## List::Sort(int, int, SharedPtr\<System::Collections::Generic::IComparer\<T\>\>) 方法

對列表切片中的元素進行排序。

```cpp
void System::Collections::Generic::List<T>::Sort(int index, int count, SharedPtr<System::Collections::Generic::IComparer<T>> comparator)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 切片起始索引。 |
| count | int | 切片大小。 |
| comparator | [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\> | 要使用的比較器。 |

## List::Sort(Comparison\<T\>, bool) 方法

對列表中的元素進行排序。

```cpp
void System::Collections::Generic::List<T>::Sort(Comparison<T> comparison, bool)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| comparison | [Comparison](../../../system/comparison/)\<T\> | 要使用的[Comparison](../../../system/comparison/)。 |

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IComparer](../../icomparer/)
* 類別 [List](../)
* 類別 [Comparison](../../../system/comparison/)
* 命名空間 [System::Collections::Generic](../../)
* 函式庫 [Aspose.Slides](../../../)