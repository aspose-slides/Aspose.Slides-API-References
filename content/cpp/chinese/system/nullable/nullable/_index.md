---
title: Nullable()
second_title: Aspose.Slides C++ API 参考
description: 构造一个表示空值的实例。
type: docs
weight: 1
url: /zh/system/nullable/nullable/
---
## Nullable::Nullable() 构造函数


构造一个表示空值的实例。

```cpp
System::Nullable<T>::Nullable()
```

## Nullable::Nullable(std::nullptr_t) 构造函数


构造一个表示空的实例。

```cpp
System::Nullable<T>::Nullable(std::nullptr_t)
```

## Nullable::Nullable(const T1\&) 构造函数


构造一个 [Nullable](../) 类的实例，该实例表示指定的值（如有必要）转换为底层类型 T 的值。

```cpp
template<typename T1> System::Nullable<T>::Nullable(const T1 &value)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 指定值的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const T1\& | 对值的常量引用，该值将由新构造的 [Nullable](../) 对象表示 |

## Nullable::Nullable(const Nullable\<T1\>\&) 构造函数


构造一个实例，该实例表示由指定的 [Nullable](../) 对象表示的值。指定的可空对象可能表示的值类型不同于构造实例的底层类型，在这种情况下，表示的值会转换为 T 类型的值。

```cpp
template<typename T1> System::Nullable<T>::Nullable(const Nullable<T1> &value)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 指定的 [Nullable](../) 对象所表示的值的类型 |

## 另请参见

* 类 [Nullable](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)