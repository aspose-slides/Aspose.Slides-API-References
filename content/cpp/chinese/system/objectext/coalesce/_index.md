---
title: Coalesce()
second_title: Aspose.Slides C++ API 参考
description: 对非可空类型的 '??' 运算符的实现
type: docs
weight: 170
url: /zh/system/objectext/coalesce/
---
## ObjectExt::Coalesce(T0, T1) 方法

对非可空类型的'??'运算符的实现。

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::Coalesce(T0 value, T1 func)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T0 | LHS 值类型。 |
| T1 | 封装 RHS 表达式的 lambda 类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | T0 | LHS 值。 |
| func | T1 | RHS 表达式。 |

### 返回值

如果 LHS 值不为 null，则返回 LHS；否则计算 RHS 表达式并返回结果。

## ObjectExt::Coalesce(System::Nullable\<T0\>, T1) 方法

对可空类型的'??'运算符的实现。

```cpp
template<typename T0,typename T1> static T0 System::ObjectExt::Coalesce(System::Nullable<T0> value, T1 func)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T0 | LHS 值类型。 |
| T1 | 封装 RHS 表达式的 lambda 类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [System::Nullable](../../nullable/)\<T0\> | LHS 值。 |
| func | T1 | RHS 表达式。 |

### 返回值

如果 LHS 值不为 null，则返回 LHS；否则计算 RHS 表达式并返回结果。

## 另见

* 类 [ObjectExt](../)
* 类 [Nullable](../../nullable/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)