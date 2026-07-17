---
title: EqualityComparerAdapter()
second_title: Aspose.Slides C++ API 参考
description: 创建不使用任何比较器的适配器。
type: docs
weight: 1
url: /zh/system.collections.generic/equalitycompareradapter/equalitycompareradapter/
---
## EqualityComparerAdapter::EqualityComparerAdapter() 构造函数

创建不使用任何比较器的适配器。

```cpp
System::Collections::Generic::EqualityComparerAdapter<T>::EqualityComparerAdapter()
```

## EqualityComparerAdapter::EqualityComparerAdapter(const SharedPtr\<IEqualityComparer\<T\>\>\&) 构造函数

使用给定的比较器创建适配器。

```cpp
System::Collections::Generic::EqualityComparerAdapter<T>::EqualityComparerAdapter(const SharedPtr<IEqualityComparer<T>> &comparator)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| comparator | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<T\>\>\& | 要使用的比较器。 |

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IEqualityComparer](../../iequalitycomparer/)
* 结构体 [EqualityComparerAdapter](../)
* 命名空间 [System::Collections::Generic](../../)
* 库 [Aspose.Slides](../../../)