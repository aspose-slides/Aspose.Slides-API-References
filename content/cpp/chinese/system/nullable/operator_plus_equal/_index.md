---
title: operator+=()
second_title: Aspose.Slides for C++ API 参考
description: 将当前对象重置，使其表示空值。
type: docs
weight: 235
url: /zh/system/nullable/operator_plus_equal/
---
## Nullable::operator+=(std::nullptr_t) 方法


将当前对象重置，使其表示空值。

```cpp
Nullable<T> System::Nullable<T>::operator+=(std::nullptr_t)
```


### 返回值

自身的副本

## Nullable::operator+=(const T1\&) 方法


使用指定值作为右侧参数，将 [operator+=()](./) 应用于当前对象表示的值。

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator+=(const T1 &other)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 用于 [operator+=()](./) 的右侧值的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | const T1\& | 对当前对象表示的值应用的 [operator+=()](./) 使用的右侧值的常量引用。 |

### 返回值

对自身的引用

## Nullable::operator+=(const Nullable\<T1\>\&) 方法


使用指定的 [Nullable](../) 对象表示的值作为右侧参数，将 [operator+=()](./) 应用于当前对象表示的值。

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator+=(const Nullable<T1> &other)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | [operator+=()](./) 的右侧参数使用的、由 [Nullable](../) 对象表示的值的底层类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | 对当前对象表示的值应用的 [operator+=()](./) 使用的右侧参数的常量引用，即由 [Nullable](../) 对象表示的值。 |

### 返回值

对自身的引用

## 另请参见

* 类 [Nullable](../)
* 结构体 [IsNullable](../../isnullable/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)