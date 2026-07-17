---
title: operator==()
second_title: Aspose.Slides for C++ API 参考
description: 确定当前对象所表示的值是否为 null。
type: docs
weight: 118
url: /zh/system/nullable/operator_equal_equal/
---
## Nullable::operator==(std::nullptr_t) const 方法

Determines if the value represented by the current object is null.

```cpp
bool System::Nullable<T>::operator==(std::nullptr_t) const
```

### 返回值

如果当前对象所表示的值为 null，则返回 true；否则返回 false。

## Nullable::operator==(const T1\&) const 方法

Determines if the value represented by the current object is equal to the specified value.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator==(const T1 &other) const
```

### 模板参数

| Parameter | Description |
| --- | --- |
| T1 | 用于比较的值的类型 |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | 用于比较的值的常量引用 |

### 返回值

如果当前对象所表示的值等于指定的值，则返回 true；否则返回 false。

## Nullable::operator==(const Nullable\<T1\>\&) const 方法

Determines if the value represented by the current object is equal to the value represented by the specified [Nullable](../) object.

```cpp
template<typename T1> bool System::Nullable<T>::operator==(const Nullable<T1> &other) const
```

### 模板参数

| Parameter | Description |
| --- | --- |
| T1 | 用于比较的 [Nullable](../) 对象的底层类型 |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | 用于比较的 [Nullable](../) 对象的常量引用 |

### 返回值

如果当前对象所表示的值等于指定的 [Nullable](../) 对象所表示的值，则返回 true；否则返回 false。

## 另见

* 类 [Nullable](../)
* 结构体 [IsNullable](../../isnullable/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)