---
title: Nullable
second_title: Aspose.Slides C++ API 参考
description: 前向声明。
type: docs
weight: 1093
url: /zh/system/nullable/
---
## 可空类

Forward declaration.

```cpp
template<typename T>class Nullable
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 被 [Nullable](./) 类扩展的底层值类型 |

## 方法

| 方法 | 描述 |
| --- | --- |
| std::enable_if\<[IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [Equals](./equals/)(const T1\&) const | 确定当前对象表示的值是否等于指定的 [Nullable](./) 对象表示的值。 |
| **bool** [get_HasValue](./get_hasvalue/)() const | 确定当前对象是否表示任何值。 |
| T [get_Value](./get_value/)() const | 返回当前对象表示的值的副本。 |
| int [GetHashCode](./gethashcode/)() const | 返回当前对象的哈希码。 |
| T [GetValueOrDefault](./getvalueordefault/)(T) | 返回当前对象表示的值；如果当前对象表示的值为 null，则返回指定的值。 |
| T [GetValueOrDefault](./getvalueordefault/)() |  |
| **bool** [IsNull](./isnull/)() const | 确定当前对象是否表示 null 值。 |
|  [Nullable](./nullable/)() | 构造一个表示 null 值的实例。 |
|  [Nullable](./nullable/)(std::nullptr_t) | 构造一个表示 null 的实例。 |
|  [Nullable](./nullable/)(const T1\&) | 构造 [Nullable](./) 类的实例，该实例表示指定的值（如有必要）转换为底层类型 T 的值。 |
|  [Nullable](./nullable/)(const [Nullable](./)\<T1\>\&) | 构造一个实例，该实例表示由指定的 [Nullable](./) 对象表示的值。指定的可空对象可能表示的值类型与构造实例的底层类型不同，此时该值将转换为 T 类型的值。 |
| **bool** [NullableBoolHelper](./nullableboolhelper/)(const T1\&, const std::function\<**bool**()>\&, **bool**) const | 帮助函数，用于检查此对象和 **other** 是否都是非 null，并在满足时调用 lambda。用于实现。 |
|  [operator const T &](./operator_const_t__and/)() const | 返回对当前对象表示的值的常量引用。 |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | 确定当前对象表示的值是否非 null。 |
| std::enable_if\<![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const T1\&) const | 确定当前对象表示的值是否不等于指定的值。 |
| **bool** [operator!=](./operator_not_equal/)(const [Nullable](./)\<T1\>\&) const | 确定当前对象表示的值是否不等于指定的 [Nullable](./) 对象表示的值。 |
| std::enable_if<\[Nullable](./)\<T\>\>::type [operator&=](./operator_and_equal/)(**bool**) | 对当前对象表示的值应用 [operator&=()](./operator_and_equal/)，使用指定的值作为右侧参数。 |
| [Nullable](./)\<T\> [operator+](./operator_plus/)(std::nullptr_t) const | 返回一个默认构造的 Nullable<T> 类实例。 |
| auto [operator+](./operator_plus/)(const T1\&) const | 对可空和值类型的值求和。 |
| auto [operator+](./operator_plus/)(const [Nullable](./)\<T1\>\&) const | 对可空值求和。 |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(std::nullptr_t) | 重置当前对象，使其表示 null 值。 |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator+=](./operator_plus_equal/)(const T1\&) | 对当前对象表示的值应用 [operator+=()](./operator_plus_equal/)，使用指定的值作为右侧参数。 |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(const [Nullable](./)\<T1\>\&) | 对当前对象表示的值应用 [operator+=()](./operator_plus_equal/)，使用指定的 [Nullable](./) 对象表示的值作为右侧参数。 |
| [Nullable](./)\<T\> [operator-](./operator_minus/)(T1) const | 减去可空值和空指针值。 |
| auto [operator-](./operator_minus/)(const T1\&) const | 对可空值和非可空值进行减法。 |
| auto [operator-](./operator_minus/)(const [Nullable](./)\<T1\>\&) const | 对可空值进行减法。 |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(T1) | 返回表示 null 值的 [Nullable](./) 类实例。 |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator-=](./operator_minus_equal/)(const T1\&) | 对当前对象表示的值应用 [operator-=()](./operator_minus_equal/)，使用指定的值作为右侧参数。 |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(const [Nullable](./)\<T1\>\&) | 对当前对象表示的值应用 [operator-=()](./operator_minus_equal/)，使用指定的 [Nullable](./) 对象表示的值作为右侧参数。 |
| **bool** [operator<](./operator_less/)(std::nullptr_t) const | 始终返回 false。 |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<](./operator_less/)(const T1\&) const | 通过对这些值应用 [operator<()](./operator_less/)，确定当前对象表示的值是否小于指定的值。 |
| **bool** [operator<](./operator_less/)(const [Nullable](./)\<T1\>\&) const | 通过对这些值应用 [operator<()](./operator_less/)，确定当前对象表示的值是否小于指定的 [Nullable](./) 对象表示的值。 |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const | 始终返回 false。 |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<=](./operator_less_equal/)(const T1\&) const | 通过对这些值应用 [operator<=()](./operator_less_equal/)，确定当前对象表示的值是否小于或等于指定的值。 |
| **bool** [operator<=](./operator_less_equal/)(const [Nullable](./)\<T1\>\&) const | 通过对这些值应用 [operator<=()](./operator_less_equal/)，确定当前对象表示的值是否小于或等于指定的 [Nullable](./) 对象表示的值。 |
| [Nullable](./)\<T\> [operator=](./operator_equal/)(std::nullptr_t) | 将 null 赋给当前对象。 |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value\&&\!std::is_null_pointer\<T1\>::value, [Nullable](./)\<T\>\&\>::type [operator=](./operator_equal/)(const T1\&) | 将对象当前表示的值替换为指定的值。 |
| [Nullable](./)\<T\>\& [operator=](./operator_equal/)(const [Nullable](./)\<T1\>\&) | 将对象当前表示的值替换为指定的值。 |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | 确定当前对象表示的值是否为 null。 |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const T1\&) const | 确定当前对象表示的值是否等于指定的值。 |
| **bool** [operator==](./operator_equal_equal/)(const [Nullable](./)\<T1\>\&) const | 确定当前对象表示的值是否等于指定的 [Nullable](./) 对象表示的值。 |
| **bool** [operator>](./operator_greater/)(std::nullptr_t) const | 始终返回 false。 |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>](./operator_greater/)(const T1\&) const | 通过对这些值应用 [operator>()](./operator_greater/)，确定当前对象表示的值是否大于指定的值。 |
| **bool** [operator>](./operator_greater/)(const [Nullable](./)\<T1\>\&) const | 通过对这些值应用 [operator>()](./operator_greater/)，确定当前对象表示的值是否大于指定的 [Nullable](./) 对象表示的值。 |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const | 始终返回 false。 |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>=](./operator_greater_equal/)(const T1\&) const | 通过对这些值应用 [operator>=()](./operator_greater_equal/)，确定当前对象表示的值是否大于或等于指定对象表示的值。 |
| **bool** [operator>=](./operator_greater_equal/)(const [Nullable](./)\<T1\>\&) const | 通过对这些值应用 [operator>=()](./operator_greater_equal/)，确定当前对象表示的值是否大于或等于指定的 [Nullable](./) 对象表示的值。 |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator|=](./operator_or_equal/)(**bool**) | 对当前对象表示的值应用 [operator|=()](./operator_or_equal/)，使用指定的值作为右侧参数。 |
| void [reset](./reset/)() | 将当前表示的值设为 null。 |
| void [set_Value](./set_value/)(const T\&) | 为可空对象设置新值。 |
| [String](../string/) [ToString](./tostring/)() const | 将当前对象表示的值转换为字符串。 |

## 类型别名

| 类型别名 | 描述 |
| --- | --- |
| [ValueType](./valuetype/) | 此类表示的值类型的别名。 |

## 注意

表示可以赋值为 null 的指定类型的值。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 [System::SmartPtr](../smartptr/) 类来管理此类型的对象。

## 另见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)