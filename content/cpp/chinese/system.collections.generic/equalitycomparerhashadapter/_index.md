---
title: EqualityComparerHashAdapter
second_title: Aspose.Slides C++ API 参考
description: 用于使用 IEqualityComparer 进行散列的适配器。如果已设置比较器对象，则使用它；否则，使用通过 DictionaryHashSelector 结构体选择的可用散列方法。
type: docs
weight: 677
url: /zh/system.collections.generic/equalitycomparerhashadapter/
---
## EqualityComparerHashAdapter 结构体

适配器用于使用 [IEqualityComparer](../iequalitycomparer/) 进行散列。若已设置比较器对象，则使用它；否则，使用通过 [DictionaryHashSelector](../dictionaryhashselector/) 结构体选择的可用散列方法。

```cpp
template<typename T>class EqualityComparerHashAdapter
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Hashed | type. |
## 方法

| 方法 | 描述 |
| --- | --- |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)() | 创建不使用比较器的适配器。 |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | 创建使用给定比较器的适配器。 |
| std::size_t [operator()](./operator_call/)(const T\&) const | 计算散列值。 |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | 设置要使用的比较器。 |

## 另见

* 命名空间 [System::Collections::Generic](../)
* 库 [Aspose.Slides](../../)