---
title: operator&=()
second_title: Aspose.Slides for C++ API 参考
description: 对当前对象表示的值应用 operator&=()，使用指定的值作为右侧参数。
type: docs
weight: 274
url: /zh/system/nullable/operator_and_equal/
---
## Nullable::operator&=(bool) 方法

对当前对象表示的值应用 [operator&=()](./)，使用指定的值作为右侧参数。

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator&=(bool other)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 使 SFINAE 工作的模板参数。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | **bool** | 布尔值，用作应用于当前对象表示的值的 [operator&=()](./) 的右侧值。 |

### 返回值

对自身的引用。

## 另见

* 类 [Nullable](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)