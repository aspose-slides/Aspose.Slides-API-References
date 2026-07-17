---
title: EqualityComparerHashAdapter()
second_title: Aspose.Slides C++ API 参考
description: 创建不使用比较器的适配器。
type: docs
weight: 1
url: /zh/system.collections.generic/equalitycomparerhashadapter/equalitycomparerhashadapter/
---
## EqualityComparerHashAdapter::EqualityComparerHashAdapter() 构造函数


创建不使用比较器的适配器。

```cpp
System::Collections::Generic::EqualityComparerHashAdapter<T>::EqualityComparerHashAdapter()
```

## EqualityComparerHashAdapter::EqualityComparerHashAdapter(const SharedPtr\<IEqualityComparer\<T\>\>\&) 构造函数


创建使用给定比较器的适配器。

```cpp
System::Collections::Generic::EqualityComparerHashAdapter<T>::EqualityComparerHashAdapter(const SharedPtr<IEqualityComparer<T>> &comparator)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| comparator | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<T\>\>\& | 要使用的比较器。 |

## 参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IEqualityComparer](../../iequalitycomparer/)
* Struct [EqualityComparerHashAdapter](../)
* 命名空间 [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)