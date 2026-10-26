---
title: Sort()
second_title: Aspose.Slides for C++ API 参考
description: 对指定数组中的元素进行排序，使用默认比较器。
type: docs
weight: 742
url: /zh/system/array/sort/
---
## Array::Sort(const ArrayPtr\<Type\>\&) 方法

对指定数组中的元素进行排序，使用默认比较器。

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | 目标数组 |

## Array::Sort(const ArrayPtr\<Type\>\&, int, int) 方法

对指定数组中一定范围的元素进行排序，使用默认比较器。

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, int startIndex, int count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | 目标数组 |
| startIndex | int | 指定排序范围起始位置的索引 |
| count | int | 要排序的元素范围的大小 |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) 方法

使用指定的比较器对指定数组中的元素进行排序。

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | 目标数组 |
| comparator | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<T\>\>\& | 用于比较数组元素的 IComparer<T> 对象 |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<Y\>\>\&) 方法

未实现。

```cpp
template<typename Type,typename Y> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<Y>> &comparator)
```

## Array::Sort(const ArrayPtr\<Type\>\&, const System::Comparison\<T\>\&) 方法

使用指定的比较函数对指定数组中的元素进行排序。

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const System::Comparison<T> &comparison)
```

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&) 方法

对两个数组进行排序，一个包含键，另一个包含对应的项，基于键数组的值进行排序，键数组的元素使用 operator< 进行比较。

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| TKey | **keys** 数组中元素的类型 |
| TValue | **items** 数组中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) 包含键值 |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) 包含映射到 **keys** 数组中键值的项 |

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&, int, int) 方法

对两个数组进行排序，一个包含键，另一个包含对应的项，基于键数组的值进行排序，键数组的元素使用默认比较器进行比较。

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items, int index, int length)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| TKey | **keys** 数组中元素的类型 |
| TValue | **items** 数组中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) 包含键值 |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) 包含映射到 **keys** 数组中键值的项 |
| index | int | 指定要排序的范围起始位置的索引 |
| length | int | 要排序的范围内的元素数量 |

## 另请参见

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [Type](../../object/type/)
* Class [Array](../)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [Comparison](../../comparison/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)