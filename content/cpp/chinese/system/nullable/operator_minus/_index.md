---
title: operator-()
second_title: Aspose.Slides for C++ API 参考
description: 对可空值和空指针值执行减法。
type: docs
weight: 222
url: /zh/system/nullable/operator_minus/
---
## Nullable::operator-(T1) const 方法

对可空值和空指针值执行减法。

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-(T1) const
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 右操作数类型，应为nullptr_t。 |

### 返回值

空的[Nullable](../)对象。

## Nullable::operator-(const T1\&) const 方法

对可空值和非可空值执行减法。

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator-(const T1 &other) const -> Nullable<decltype(get_Value() - other)>
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 右操作数类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | const T1\& | 要减去的值。 |

### 返回值

减法结果。

## Nullable::operator-(const Nullable\<T1\>\&) const 方法

对可空值执行减法。

```cpp
template<typename T1> auto System::Nullable<T>::operator-(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value() - other.get_Value())>
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 右操作数类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | 要减去的值。 |

### 返回值

减法结果。

## 另见

* 类 [Nullable](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)