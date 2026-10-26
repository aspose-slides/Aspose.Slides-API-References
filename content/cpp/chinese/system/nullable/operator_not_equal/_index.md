---
title: operator!=()
second_title: Aspose.Slides C++ API 参考
description: 确定当前对象表示的值是否非 null。
type: docs
weight: 144
url: /zh/system/nullable/operator_not_equal/
---
## Nullable::operator!=(std::nullptr_t) const 方法

确定当前对象表示的值是否非 null。

```cpp
bool System::Nullable<T>::operator!=(std::nullptr_t) const
```

### 返回值

如果当前对象表示的值不是 null，则为 True，否则为 false

## Nullable::operator!=(const T1\&) const 方法

确定当前对象表示的值是否不等于指定的值。

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator!=(const T1 &other) const
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

如果当前对象表示的值不等于指定的值，则为 True，否则为 false

## Nullable::operator!=(const Nullable\<T1\>\&) const 方法

确定当前对象表示的值是否不等于指定 [Nullable](../) 对象表示的值。

```cpp
template<typename T1> bool System::Nullable<T>::operator!=(const Nullable<T1> &other) const
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

如果当前对象表示的值不等于指定 [Nullable](../) 对象表示的值，则为 True，否则为 false

## 另见

* 类 [Nullable](../)
* 结构体 [IsNullable](../../isnullable/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)