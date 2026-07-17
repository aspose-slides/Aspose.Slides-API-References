---
title: Enum
second_title: Aspose.Slides C++ API 参考
description: 提供对枚举类型值执行某些操作的方法。这是一个没有实例服务的静态类型。无论何种方式都不应创建其实例。
type: docs
weight: 1561
url: /zh/system/enum/
---
## 枚举结构体

提供对枚举类型值执行某些操作的方法。这是一个没有实例服务的静态类型。无论何种方式都不应创建其实例。

```cpp
template<class E,class Guard>class Enum
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| E | 类处理的枚举值的枚举类型 |
| Guard | 服务类型参数，其目的是确保 **E** 为可枚举类型 |

## 方法

| 方法 | 描述 |
| --- | --- |
| static int [Compare](./compare/)(E, T) | 对指定枚举常量的值执行算术比较。 |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetDescription](./getdescription/)(T) | 返回具有指定值的枚举常量的名称。 |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetName](./getname/)(T) | 返回具有指定值的枚举常量的名称。 |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() | 返回包含枚举 **E** 所有成员名称的数组。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() | 返回枚举的底层类型。 |
| static [ArrayPtr](../arrayptr/)\<E\> [GetValues](./getvalues/)() | 返回包含枚举 **E** 所有成员的数组。 |
| static **bool** [HasFlag](./hasflag/)(E, E) | 确定在指定枚举值的位数组表示中是否设置了指定的位。 |
| static **bool** [IsDefined](./isdefined/)(E) | 确定指定值是否是枚举类型 **E** 的成员。 |
| static std::enable_if\<std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, **bool**\>::type [IsDefined](./isdefined/)(T) | 确定指定值是否是枚举类型 **T** 的成员。 |
| static **bool** [IsDefined](./isdefined/)(const [String](../string/)\&) | 确定具有指定名称的值是否在枚举 **E** 的成员中。 |
| static E [Parse](./parse/)(const [String](../string/)\&, **bool**) | 将指定的字符串转换为等效的枚举常量。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, E\&) | 尝试将指定的字符串转换为等效的枚举常量。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**, E\&) | 尝试将指定的字符串转换为等效的枚举常量。 |

## 类型别名

| 类型别名 | 描述 |
| --- | --- |
| [UnderlyingType](./underlyingtype/) | 枚举底层类型的别名。 |

## 另请参见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)