---
title: BinarySearch()
second_title: Aspose.Slides C++ API 参考
description: 在已排序的列表中查找项。
type: docs
weight: 339
url: /zh/system.collections.generic/list/binarysearch/
---
## List::BinarySearch(const T\&) const 方法

在已排序的列表中查找项。

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | const T\& | 要查找的项。 |

### 返回值

已排序列表中项的索引或最近索引的补数。

## List::BinarySearch(const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const 方法

在已排序的列表中查找项。

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | const T\& | 要查找的项。 |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | 要使用的[Comparer](../../comparer/)。 |

### 返回值

已排序列表中项的索引或最近索引的补数。

## List::BinarySearch(int, int, const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const 方法

在已排序的列表中查找项。

```cpp
int System::Collections::Generic::List<T>::BinarySearch(int index, int count, const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 范围起始。 |
| count | int | 范围大小。 |
| item | const T\& | 要查找的项。 |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | 要使用的[Comparer](../../comparer/)。 |

### 返回值

已排序列表中项的索引或最近索引的补数。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [List](../)
* 类 [IComparer](../../icomparer/)
* 命名空间 [System::Collections::Generic](../../)
* 库 [Aspose.Slides](../../../)