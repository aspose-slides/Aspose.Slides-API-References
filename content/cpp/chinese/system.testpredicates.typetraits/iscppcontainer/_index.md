---
title: IsCppContainer
second_title: Aspose.Slides C++ API 参考
description: "检查特定类型是否为 STL 风格的容器。为此，会检查 iterator 和 const_iterator 成员类型是否存在。如果两者都存在，则继承 std::true_type，否则继承 std::false_type。"
type: docs
weight: 40
url: /zh/system.testpredicates.typetraits/iscppcontainer/
---
## IsCppContainer 结构体

检查特定类型是否为 STL 风格的容器。为此，检查 iterator 和 const_iterator 成员类型是否存在。如果两者都存在，则继承 std::true_type，否则继承 std::false_type。

```cpp
template<typename T,typename Enable>class IsCppContainer : public std::false_type
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 要检查的类型。 |
| Enable | 用于使 SFINAE 起作用的形式参数。 |

## 另见

* 命名空间 [System::TestPredicates::TypeTraits](../)
* 库 [Aspose.Slides](../../)