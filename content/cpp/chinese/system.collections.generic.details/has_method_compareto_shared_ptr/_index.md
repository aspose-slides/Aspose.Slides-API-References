---
title: has_method_compareto_shared_ptr
second_title: Aspose.Slides C++ API 参考
description: "检查指定类型中是否存在 CompareTo(SharedPtr<T>) 方法。如果存在，则继承 std::true_type；否则继承 std::false_type。可用于 std::enable_if。"
type: docs
weight: 183
url: /zh/system.collections.generic.details/has_method_compareto_shared_ptr/
---
## has_method_compareto_shared_ptr struct


检查在指定类型中是否存在 CompareTo(SharedPtr<T>) 方法。若存在，则继承 std::true_type，否则继承 std::false_type。可用于 std::enable_if.

```cpp
template<typename T,typename Sfinae>class has_method_compareto_shared_ptr : public std::false_type
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 要检查是否存在 Equals 方法的类型。 |
| Sfinae | 用于使 SFINAE 工作的形式模板参数。 |

## 另请参阅

* 命名空间 [System::Collections::Generic::Details](../)
* 库 [Aspose.Slides](../../)