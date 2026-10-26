---
title: has_method_compareto
second_title: Aspose.Slides for C++ API 参考
description: "检查指定类型中是否存在 CompareTo 方法。如果存在，继承 std::true_type，否则继承 std::false_type。可用于 std::enable_if。"
type: docs
weight: 170
url: /zh/system.collections.generic.details/has_method_compareto/
---
## has_method_compareto 结构体

检查指定类型是否存在 CompareTo 方法。如果存在，继承 std::true_type，否则继承 std::false_type。可用于 std::enable_if。

```cpp
template<typename T,typename Sfinae>class has_method_compareto : public std::false_type
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 要检查是否存在 Equals 方法的类型。 |
| Sfinae | 用于使 SFINAE 工作的形式模板参数。 |

## 另见

* 命名空间 [System::Collections::Generic::Details](../)
* 库 [Aspose.Slides](../../)