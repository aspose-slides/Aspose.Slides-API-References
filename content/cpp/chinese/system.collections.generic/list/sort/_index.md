---
title: Sort()
second_title: Aspose.Slides for C++ API 参考
description: 对列表中的元素进行排序。
type: docs
weight: 521
url: /zh/system.collections.generic/list/sort/
---
## List::Sort(const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) method

对列表中的元素进行排序。

```cpp
void System::Collections::Generic::List<T>::Sort(const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| comparator | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | 要使用的比较器。 |

## List::Sort() method

使用默认比较器对列表中的元素进行排序。

```cpp
void System::Collections::Generic::List<T>::Sort()
```

## List::Sort(int, int, SharedPtr\<System::Collections::Generic::IComparer\<T\>\>) method

对列表切片中的元素进行排序。

```cpp
void System::Collections::Generic::List<T>::Sort(int index, int count, SharedPtr<System::Collections::Generic::IComparer<T>> comparator)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 切片的起始索引。 |
| count | int | 切片大小。 |
| comparator | [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\> | 要使用的比较器。 |

## List::Sort(Comparison\<T\>, bool) method

对列表中的元素进行排序。

```cpp
void System::Collections::Generic::List<T>::Sort(Comparison<T> comparison, bool)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| comparison | [Comparison](../../../system/comparison/)\<T\> | [Comparison](../../../system/comparison/) 要使用。 |

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IComparer](../../icomparer/)
* 类 [List](../)
* 类 [Comparison](../../../system/comparison/)
* 命名空间 [System::Collections::Generic](../../)
* 库 [Aspose.Slides](../../../)