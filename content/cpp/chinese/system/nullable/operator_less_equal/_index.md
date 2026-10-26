---
title: operator<=()
second_title: Aspose.Slides for C++ API 参考
description: 始终返回 false。
type: docs
weight: 196
url: /zh/system/nullable/operator_less_equal/
---
## Nullable::operator<=(std::nullptr_t) const 方法

始终返回 false。

```cpp
bool System::Nullable<T>::operator<=(std::nullptr_t) const
```

## Nullable::operator<=(const T1\&) const 方法

确定当前对象表示的值是否小于或等于指定值，方法是对这些值应用 [operator<=()](./)。

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<=(const T1 &other) const
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

如果当前对象表示的值小于或等于指定值则返回 true，否则返回 false

## Nullable::operator<=(const Nullable\<T1\>\&) const 方法

确定当前对象表示的值是否小于或等于由指定的 [Nullable](../) 对象表示的值，方法是对这些值应用 [operator<=()](./)。

```cpp
template<typename T1> bool System::Nullable<T>::operator<=(const Nullable<T1> &other) const
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 要比较的 [Nullable](../) 对象的基础类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | 要比较的 [Nullable](../) 对象的常量引用 |

### 返回值

如果当前对象表示的值小于或等于指定的 [Nullable](../) 对象表示的值则返回 true，否则返回 false

## 另见

* 类 [Nullable](../)
* 结构体 [IsNullable](../../isnullable/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)