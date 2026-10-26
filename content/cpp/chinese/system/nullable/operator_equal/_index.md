---
title: operator=()
second_title: Aspose.Slides for C++ API 参考
description: 将 null 赋给当前对象。
type: docs
weight: 14
url: /zh/system/nullable/operator_equal/
---
## Nullable::operator=(std::nullptr_t) 方法

将 null 赋给当前对象。

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator=(std::nullptr_t)
```

### 返回值

[Nullable](../) 对象，表示空值。

## Nullable::operator=(const T1\&) 方法

用指定的值替换对象当前表示的值。

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value &&!std::is_null_pointer<T1>::value, Nullable<T> &>::type System::Nullable<T>::operator=(const T1 &x)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| The | 当前对象表示的新值的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | const T1\& | 当前对象表示的新值 |

### 返回值

对自身的引用

## Nullable::operator=(const Nullable\<T1\>\&) 方法

用指定的值替换对象当前表示的值。

```cpp
template<typename T1> Nullable<T> & System::Nullable<T>::operator=(const Nullable<T1> &x)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| The | 当前对象表示的新值的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | const [Nullable](../)\<T1\>\& | 当前对象表示的新值 |

### 返回值

对自身的引用

## 另请参阅

* 类 [Nullable](../)
* 结构体 [IsNullable](../../isnullable/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)