---
title: "System::TestPredicates::TypeTraits"
second_title: Aspose.Slides for C++ API 参考
description: 
type: docs
weight: 963
url: /zh/system.testpredicates.typetraits/
---
## 结构体

| 结构体 | 描述 |
| --- | --- |
| [has_data_method](./has_data_method/) | 检查类型是否拥有 data() 方法。如果有，则继承 std::true_type；否则继承 std::false_type。 |
| [has_data_method< System::Collections::BitArray, void >](./has_data_method_tmpl_system_collections_bitarray__void__end_tmpl/) | 针对 BitArray 类型的特化，提供在此不可访问的 boost 类型。 |
| [has_print_to_method](./has_print_to_method/) | 检查是否存在接受给定类型作为第一个参数的 PrintTo 函数重载。如果存在重载，则继承 std::true_type；否则继承 std::false_type。 |
| [IsCppContainer](./iscppcontainer/) | 检查特定类型是否为 STL 风格的容器。为此，检查是否存在 iterator 和 const_iterator 成员类型。如果两者都存在，则继承 std::true_type；否则继承 std::false_type。 |
| [IsEnumerable](./isenumerable/) | 检查类型是否具有 [System::Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/) 特化作为基类型。如果是，则将 value 成员设为 true；否则设为 false。 |
| [LargestFPType](./largestfptype/) | 提供最长浮点类型的别名。忽略非浮点类型。 |

## 类型别名

| 类型别名 | 描述 |
| --- | --- |
| [AreFPandArithmetic](./arefpandarithmetic/) | 检查 **T1** 为算术类型且 **T2** 为浮点类型，或反之。如果满足，则将 value 成员设为 true；否则设为 false。 |
| [AnyOfDecimal](./anyofdecimal/) | 检查至少有一个类型参数是 [System::Decimal](../system/decimal/)。如果是，则将 value 成员设为 true；否则设为 false。 |
| [IsArray](./isarray/) | 检查类型是否为 [System::Array](../system/array/) 的特化。如果是，则将 value 成员设为 true；否则设为 false。 |
| [IsList](./islist/) | 检查类型是否为 [System::Collections::Generic::List](../system.collections.generic/list/) 的特化。如果是，则将 value 成员设为 true；否则设为 false。 |
| [BothArrayOrList](./botharrayorlist/) | 检查两个类型参数是否都是数组或列表。如果是，则将 value 成员设为 true；否则设为 false。 |
| [BothEnumerable](./bothenumerable/) | 检查两个类型参数是否都是 IEnumerable。如果是，则将 value 成员设为 true；否则设为 false。 |