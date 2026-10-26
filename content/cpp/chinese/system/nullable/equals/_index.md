---
title: Equals()
second_title: Aspose.Slides for C++ API 参考
description: 确定当前对象表示的值是否等于指定的 Nullable 对象表示的值。
type: docs
weight: 131
url: /zh/system/nullable/equals/
---
## Nullable::Equals(const T1\&) const 方法

确定当前对象表示的值是否等于指定的 [Nullable](../) 对象表示的值。

```cpp
template<typename T1> std::enable_if<IsNullable<T1>::value, bool>::type System::Nullable<T>::Equals(const T1 &other) const
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 用于比较的 [Nullable](../) 对象的基础类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | const T1\& | 用于比较的 [Nullable](../) 对象的常量引用 |

### 返回值

如果当前对象表示的值等于指定的 [Nullable](../) 对象表示的值，则为 true；否则为 false

## 另见

* 类 [Nullable](../)
* 结构体 [IsNullable](../../isnullable/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)