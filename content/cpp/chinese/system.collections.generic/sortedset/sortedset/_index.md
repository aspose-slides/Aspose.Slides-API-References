---
title: SortedSet()
second_title: Aspose.Slides for C++ API 参考
description: 创建空集合。
type: docs
weight: 1
url: /zh/system.collections.generic/sortedset/sortedset/
---
## SortedSet::SortedSet() 构造函数

创建空集合。

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet()
```

## SortedSet::SortedSet(int) 构造函数

创建具有指定容量的空集合。

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(int capacity)
```

## SortedSet::SortedSet(const SharedPtr\<IComparer\<T\>\>\&) 构造函数

创建使用指定相等比较器的空集合。

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IComparer<T>> &comparer)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) 对象，用于与 [SortedSet](../) 关联。 |

## SortedSet::SortedSet(const SharedPtr\<IEnumerable\<T\>\>\&) 构造函数

基于可枚举值创建 [SortedSet](../)。

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IEnumerable<T>> &items)
```

## 另见

* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类 [SortedSet](../)
* 类 [IComparer](../../icomparer/)
* 类 [IEnumerable](../../ienumerable/)
* 命名空间 [System::Collections::Generic](../../)
* 库 [Aspose.Slides](../../../)