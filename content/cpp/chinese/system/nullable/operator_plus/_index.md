---
title: operator+()
second_title: Aspose.Slides C++ API 参考
description: 返回 Nullable<T> 类的默认构造实例。
type: docs
weight: 209
url: /zh/system/nullable/operator_plus/
---
## Nullable::operator+(std::nullptr_t) const 方法


返回 Nullable<T> 类的默认构造实例。

```cpp
Nullable<T> System::Nullable<T>::operator+(std::nullptr_t) const
```

## Nullable::operator+(const T1\&) const 方法


对可空值和非可空值求和。

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator+(const T1 &other) const -> Nullable<decltype(get_Value()+other)>
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 右操作数类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | const T1\& | 要添加的值。 |

### 返回值

求和结果。

## Nullable::operator+(const Nullable\<T1\>\&) const 方法


对可空值求和。

```cpp
template<typename T1> auto System::Nullable<T>::operator+(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value()+other.get_Value())>
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 右操作数类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | 要添加的值。 |

### 返回值

求和结果。

## 另见

* 类 [Nullable](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)