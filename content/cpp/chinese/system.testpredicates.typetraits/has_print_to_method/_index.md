---
title: has_print_to_method
second_title: Aspose.Slides C++ API 参考
description: "检查接受给定类型作为第一个参数的 PrintTo 函数是否存在重载。如果存在重载，则继承 std::true_type，否则继承 std::false_type。"
type: docs
weight: 27
url: /zh/system.testpredicates.typetraits/has_print_to_method/
---
## has_print_to_method 结构体

检查是否存在接受给定类型作为第一个参数的 PrintTo 函数的重载。如果存在重载，则继承 std::true_type，否则继承 std::false_type。

```cpp
template<typename T,typename Enable>class has_print_to_method : public std::false_type
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 要检查的类型。 |
| Enable | 用于 SFINAE 工作的形式参数。 |

## 另请参见

* 命名空间 [System::TestPredicates::TypeTraits](../)
* 库 [Aspose.Slides](../../)