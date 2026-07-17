---
title: HashSet()
second_title: Aspose.Slides C++ API 参考
description: RTTI 信息。
type: docs
weight: 1
url: /zh/system.collections.generic/hashset/hashset/
---
## HashSet::HashSet() 构造函数

RTTI 信息。

```cpp
System::Collections::Generic::HashSet<T>::HashSet()
```

## 备注

创建空集合。

## HashSet::HashSet(int) 构造函数

创建具有指定容量的空集合。

```cpp
System::Collections::Generic::HashSet<T>::HashSet(int capacity)
```

## HashSet::HashSet(const SharedPtr\<IEqualityComparer\<T\>\>\&) 构造函数

创建使用指定相等比较器的空集合。

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEqualityComparer<T>> &comparer)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<T\>\>\& | [Comparer](../../comparer/) 对象用于关联 hashset。 |

## HashSet::HashSet(const SharedPtr\<IEnumerable\<T\>\>\&) 构造函数

根据可枚举值创建 hashset。

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEnumerable<T>> &items)
```

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [HashSet](../)
* 类 [IEqualityComparer](../../iequalitycomparer/)
* 类 [IEnumerable](../../ienumerable/)
* 命名空间 [System::Collections::Generic](../../)
* 库 [Aspose.Slides](../../../)