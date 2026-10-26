---
title: ObjectType
second_title: Aspose.Slides for C++ API 参考
description: 提供实现对象类型获取器的静态方法。这是一个没有实例服务的静态类型。您永远不应以任何方式创建其实例。
type: docs
weight: 1145
url: /zh/system/objecttype/
---
## ObjectType 类

提供实现对象类型获取器的静态方法。这是一个没有实例服务的静态类型。您永远不应以任何方式创建其实例。

```cpp
class ObjectType
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | 实现 typeof() 翻译。针对智能指针的重载。 |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | 实现 typeof() 翻译。针对结构体的重载。 |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | 实现 typeof() 翻译。针对异常的重载。 |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | 实现 typeof() 翻译。针对原始类型的重载。 |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | 实现 typeof() 翻译。针对 [Nullable](../nullable/) 类型的重载。 |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | 实现 typeof() 翻译。针对原始类型的重载。 |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | 实现 typeof() 翻译。针对枚举类型的重载。 |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | 实现 typeof() 翻译。针对结构体和指针的重载。 |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | 实现 typeof() 翻译。针对 [Nullable](../nullable/) 的重载。 |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | 实现 typeof() 翻译。针对 MutlicastDelegate 的重载。 |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | 实现 typeof() 翻译。针对结构体和指针的重载。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)(const [String](../string/)\&) | 实现 typeof() 翻译。针对字符串类型的重载。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | 实现 typeof() 翻译。针对 **uint8_t** 的重载。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | 实现 typeof() 翻译。针对 **uint8_t** 的重载。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | 实现 typeof() 翻译。针对 **uint8_t** 的重载。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | 实现 typeof() 翻译。针对 **uint8_t** 的重载。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | 实现 typeof() 翻译。针对 **uint8_t** 的重载。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | 实现 typeof() 翻译。针对 **uint8_t** 的重载。 |

## 另请参见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)