---
title: EqualityComparerAdapter
second_title: Aspose.Slides for C++ API 参考
description: "适配器使得可以在 STL 风格的集合和算法中使用 IEqualityComparer。若已设置，则使用 IEqualityComparer；若未设置，则使用 operator ==、Object::Equals 或 T::Equals，以可用者为准。"
type: docs
weight: 664
url: /zh/system.collections.generic/equalitycompareradapter/
---
## EqualityComparerAdapter 结构体

适配器使得在 STL 风格的集合和算法中使用 [IEqualityComparer](../iequalitycomparer/) 成为可能。如果已设置，则使用 [IEqualityComparer](../iequalitycomparer/)。如果未设置，则使用 operator ==、[Object::Equals](../../system/object/equals/) 或 T::Equals，以可用者为准。

```cpp
template<class T>class EqualityComparerAdapter
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 被比较的类型。 |

## 方法

| 方法 | 描述 |
| --- | --- |
|  [EqualityComparerAdapter](./equalitycompareradapter/)() | 创建不使用任何比较器的适配器。 |
|  [EqualityComparerAdapter](./equalitycompareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | 使用给定的比较器创建适配器。 |
| **bool** [operator()](./operator_call/)(const T\&, const T\&) const | 比较两个对象。 |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | 设置比较器。 |

## 另见

* 命名空间 [System::Collections::Generic](../)
* 库 [Aspose.Slides](../../)