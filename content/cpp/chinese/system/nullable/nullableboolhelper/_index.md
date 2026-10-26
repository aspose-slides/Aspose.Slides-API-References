---
title: NullableBoolHelper()
second_title: Aspose.Slides for C++ API 参考文档
description: 帮助函数，用于检查此对象和 other 是否均为非空，并在满足条件时调用 lambda。用于 implementation.s.
type: docs
weight: 105
url: /zh/system/nullable/nullableboolhelper/
---
## Nullable::NullableBoolHelper(const T1\&, const std::function\<bool()>\&, bool) const method

帮助函数，用于检查此对象和 **other** 是否均为非空，并在满足条件时调用 lambda。用于 implementation.s.

```cpp
template<typename T1> bool System::Nullable<T>::NullableBoolHelper(const T1 &other, const std::function<bool()> &f, bool default_if_both_are_null=false) const
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 其他可空类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | const T1\& | 用于比较的其他可空值。 |
| f | const std::function\<**bool**()>\& | 如果 **this** 和 **other** 均为非空时调用的 Lambda。 |
| default_if_both_are_null | **bool** | 如果两个值均为 null 时的返回值。 |

### 返回值

如果 **this** 或 **other** 任一为 null，则返回 false；如果两者均为 null，则返回 **default_if_both_are_null**；如果两者均非 null，则返回 **f** 调用的结果。

## 另见

* 类 [Nullable](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)