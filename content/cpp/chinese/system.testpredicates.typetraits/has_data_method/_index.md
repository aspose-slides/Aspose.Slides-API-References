---
title: has_data_method
second_title: Aspose.Slides C++ API 参考
description: "检查类型是否具有 data() 方法。如果有，继承 std::true_type，否则继承 std::false_type。"
type: docs
weight: 1
url: /zh/system.testpredicates.typetraits/has_data_method/
---
## has_data_method 结构体

检查类型是否具有 data() 方法。如果有，则继承 std::true_type，否则继承 std::false_type。

```cpp
template<typename T,typename Enable>class has_data_method : public std::false_type
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 要检查的类型。 |
| Enable | 用于使 SFINAE 生效的形式参数。 |

## 另见

* 命名空间 [System::TestPredicates::TypeTraits](../)
* 库 [Aspose.Slides](../../)