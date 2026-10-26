---
title: operator>()
second_title: Aspose.Slides C++ API 参考
description: 始终返回 false。
type: docs
weight: 157
url: /zh/system/nullable/operator_greater/
---
## Nullable::operator>(std::nullptr_t) const 方法

始终返回 false。

```cpp
bool System::Nullable<T>::operator>(std::nullptr_t) const
```

## Nullable::operator>(const T1\&) const 方法

确定当前对象表示的值在对这些值应用 [operator>()](./) 后是否大于指定的值。

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>(const T1 &other) const
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 要比较的值的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | const T1\& | 要比较的值的常量引用 |

### 返回值

如果当前对象表示的值大于指定的值，则为 true；否则为 false

## Nullable::operator>(const Nullable\<T1\>\&) const 方法

确定当前对象表示的值在对这些值应用 [operator>()](./) 后是否大于指定的 [Nullable](../) 对象表示的值。

```cpp
template<typename T1> bool System::Nullable<T>::operator>(const Nullable<T1> &other) const
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 要比较的 [Nullable](../) 对象的底层类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | 要比较的 [Nullable](../) 对象的常量引用 |

### 返回值

如果当前对象表示的值大于指定的 [Nullable](../) 对象表示的值，则为 true；否则为 false

## 参见

* 类 [Nullable](../)
* 结构体 [IsNullable](../../isnullable/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)