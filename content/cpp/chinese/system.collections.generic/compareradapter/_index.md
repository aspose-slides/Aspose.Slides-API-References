---
title: ComparerAdapter
second_title: Aspose.Slides for C++ API 参考
description: 适配器用于在 STL 环境中使用 IComparer。如果已设置 IComparer 则使用它；否则使用 operator <（如果可用），如果不可用则返回 false。
type: docs
weight: 638
url: /zh/system.collections.generic/compareradapter/
---
## ComparerAdapter struct

适配器用于在 STL 环境中使用 [IComparer](../icomparer/)。如果已设置 [IComparer](../icomparer/) 则使用它；否则使用 operator <（如果可用），如果不可用则返回 false。

```cpp
template<class T>class ComparerAdapter
```

### 模板参数

| Parameter | Description |
| --- | --- |
| T | Type being compared. |

## 方法

| Method | Description |
| --- | --- |
|  [ComparerAdapter](./compareradapter/)() | 构造没有任何比较器可用的适配器。 |
|  [ComparerAdapter](./compareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | 构造适配器。 |
| std::enable_if\<detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) 针对具有 operator < 的类型的函数。 |
| std::enable_if<\!detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) 针对没有 operator < 的类型的函数。 |
| void [set_Comparator](./set_comparator/)(const [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<T\>\>\&) | 设置比较器对象。 |

## 另请参见

* 命名空间 [System::Collections::Generic](../)
* 库 [Aspose.Slides](../../)