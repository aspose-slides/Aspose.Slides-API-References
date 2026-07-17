---
title: operator-=()
second_title: Aspose.Slides C++ API 参考
description: 返回表示空值的 Nullable 类实例。
type: docs
weight: 248
url: /zh/system/nullable/operator_minus_equal/
---
## Nullable::operator-=(T1) 方法

返回 [Nullable](../) 类的实例，表示空值。

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-=(T1)
```

## Nullable::operator-=(const T1\&) 方法

将 [operator-=()](./) 应用于当前对象所表示的值，使用指定的值作为右侧参数。

```cpp
template<typename T1,typename> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator-=(const T1 &other)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 用于 [operator-=()](./) 的右侧值的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | const T1\& | 对当前对象所表示的值应用 [operator-=()](./) 时，作为右侧值使用的值的常量引用。 |

### 返回值

对自身的引用

## Nullable::operator-=(const Nullable\<T1\>\&) 方法

将 [operator-=()](./) 应用于当前对象所表示的值，使用指定 [Nullable](../) 对象所表示的值作为右侧参数。

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator-=(const Nullable<T1> &other)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 用作 [operator-=()](./) 的右侧参数的 [Nullable](../) 对象所表示的值的基础类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | 对当前对象所表示的值应用 [operator-=()](./) 时，作为右侧参数使用的 [Nullable](../) 对象的常量引用。 |

### 返回值

对自身的引用

## 参见

* 类 [Nullable](../)
* 结构体 [IsNullable](../../isnullable/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)